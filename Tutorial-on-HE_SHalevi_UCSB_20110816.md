
# Tutorial on Homomorphic Encryption 
Shai Halevi, IBM at CRYPTO 2011 in UC Santa Barbara 2011-08-16  

TOC of the video https://www.youtube.com/watch?v=jIWOR2bGC7c  
of this event http://www.iacr.org/conferences/crypto2011/program.shtml  
with the slides available at https://shaih.github.io/presentations.html (video has low quality, so do get the 2011 PDF slides while listening).

### TOC part 1
N.B.: Have not fully understood it, and discovered slides only near the end. So this might have actual errors in it, please correct. And extend anyways, and make more explicit. 

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

to be continued in part 2...

