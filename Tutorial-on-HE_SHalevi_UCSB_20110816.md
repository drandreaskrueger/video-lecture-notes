
# Tutorial on Homomorphic Encryption 
Shai Halevi, IBM at CRYPTO 2011 in UC Santa Barbara 2011-08-16  

TOC of the video https://www.youtube.com/watch?v=jIWOR2bGC7c  
of this event http://www.iacr.org/conferences/crypto2011/program.shtml  
with the slides available at https://shaih.github.io/presentations.html (video has low quality, so better watch the 2011 slides PDF while listening).

### TOC part 1
N.B.: Have only partly understood it, and discovered the slides only near the end. So this might have actual errors in it, please correct - thanks. 

00:00 high-level view  
01:18 example  
02:17 organization of the tutorial  
02:55 notation, semantic security  
04:00 homomorphic  
05:25 compactness  
06:31 1978  
07:28 some existing schemes have homomorphisms  
09:28 (x,+) hom encr  
10:00 evaluate any function!  
10:28 Gentry 2009 blueprint: Step 1 error correcting codes, linear ECCs --> addit.. Step 2: lives inside ring --> muiltipl., low-degree polys. Step 3: Bootstraping: from few operations to any number of operations. Step 4: everything else.  
12:01 random looking codes  
13:08 how use ECCs  
14:08 example: integers mod p  
16:10 different input encoding & decryption  
18:20 additive homomorphism  
19:55 Step 2: Code lives in algebraic ring.  
22:32 example integers mod p. Hom. as long as noise < p/2  
24:15 summary until now ; ideal --> SHE somewhat h.e.  
25:30 instantiations  
26:15 matrix rings, LWE --> didn't work  
27:03 SWHE, noise increases  
28:06 bootstraping to handle higher degrees  
28:59 setup  
29:45 hope: low degree polynomial. encrypt secret key with its public key. assume circular security.  
30:38 decrease noise  
31:40 hom.computation inly applied to green ciphertexts  
32:00 mulitply 2 orange ciphertexts  
34:01 ... so that's bootstraping.  
34:13 Step 4 everything else.  
34:20 older cryptosystems cannot  
34:40 "squash", will not talk about it.  
35:57 Performance  
36:15 SWHE 1-10 seconds for single multiplication  
36:40 bootstraping is inherently inefficient  
37:40 (best implementation until 2011) pubkey 2GB, bootstraping 3-30 minutes for 1 gate  
38:45 blueprint done  
39:00 Chimeric H.E. = SWHE + MHE (multiplicative, e.g. Elgamal)  
42:00 can do without squashing & SSSP  

### TOC part 1
video https://www.youtube.com/watch?v=huLGjBpj3Os  
event, and slides - see above.  

00:00 Brakerski-Vaikuntanathan 2011b intro  
01:10 LWE Regev 2005  
03:20 as hard as some worst-case lattice problems in dim n  
03:50 used extensively in crypto  
04:10 [BV'11b] construction  
05:55 "close" = to space orthogonal to secret key vector  
06:45 get addit.homomorphic for free. But how to multiply? Tensor product?  
09:00 multiply more than once?  
...  
45:50 putting it all together  
...  
50:20 what we have so far  
50:37 security based on LWE: modulus, noise and depth  
51:40 variants & optimizations: e.g. bootstrapping, batching  
55:08 overhead reduction --> quasilinear  
55:50 current (2011) status of H.E. constructions  



### contributors
Please fork, edit/correct/extend, and pull request. Thanks.    

* https://github.com/drandreaskrueger


