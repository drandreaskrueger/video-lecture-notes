
# EEA Quorum - Demos - NY 10/2017
JPMorgan + Zcash presenting several Quorum Demos  
in EEA meeting (see our [EEA](https://gitlab.com/electronDLT/training-material/blob/master/EEA/EEA-readme.md), [Quorum WG](https://gitlab.com/electronDLT/training-material/blob/master/EEA/EEA-Quorum-WG.md)) in New York on 2017 Oct 20th.

TOC of [Youtube video](https://www.youtube.com/watch?v=u0VkRvMBIsY) by Enterprise Ethereum Alliance, Published on 30 Jan 2018 

#### TOC
Intro is probably using [these slides](https://github.com/jpmorganchase/quorum-docs/blob/master/Quorum_Architecture_20171016.pdf)

00:00 Amber Baldet & Patrick Nielsen; intro overview  
01:21 Amber: crash course intro  
03:40 Patrick: Architecture/Design - Constellation. Permissioned. Private transactions  
05:40 partnered with ZCash team, and why  
06:10 Z tokens, anything fungible enough can be transfered  

06:25 Jack Gavigan, ZCash  
06:40 how ZCash --> Quorum? Smart contract "Z-contracts", precompiled contracts  
07:25 shielded ZTokens  
08:00 use Constellation  
08:25 provide evidence that tx has taken place  
08:45 demo intro:   
--:-- USD & [ACME](https://en.wikipedia.org/wiki/Acme_Corporation) Z-contracts  
--:--  transparent vs shielded  
--:--  private trading contract  
--:--  state watchers, note trackers  
--:--  information for the public is reduced  

12:30 Sean: Live demo - left Alice, right Bob  
13:43 "seven nodes example" = ?  
14:20 make ztoken contract  
15:20 set up tracker  
15:40 shield some of the tokens == zero knowledge proof  
16:00 send tokens to Bob  
16:38 make *private* contract for token bid  
17:44 Bob's view: 
17:50 recreate 3 contracts via their ETH addresses  
19:00 run watcher utility 
19:35 create tracker, accept bid  
19:58 Alice is notified  
20:08 Alice: list shielded notes, and send some of them  
21:00 zero knowledge proof is generated - 41 seconds!  
21:33 Bob: shield some ACME tokens - ZKP 2 seconds  
21:58 Bon: submit settlement transaction - ZKP 
23:20 ZKPs same elliptic curves as in ZCash, take about 40 seconds  
24:00 applause  

24:10 Jack Gavigan  
24:30 most types of transactions can be implemented like this  
25:00 try it, open source, *not* production ready; adapt for, or tell us your use cases  
26:19 next steps: testnet, more use cases, efficiency, ...  



27:09 @TyLobban @dino_joel  - Istanbul PBFT  
27:46 QuorumChain vs Raft  
28:08 Quorum has configurable consensus model  
28:15 "QuorumChain" = voting & smartcontract based  
28:28 "Raft" e.g. used in [kubernetes](https://github.com/kubernetes/kubernetes/blob/master/vendor/github.com/coreos/etcd/raft/raft.go) - transaction finality  
--:-- ?  
30:00 Alex, Taiwan  
31:-- Istanbul PBFT - transaction finality, 33% fault tolerance  
32:20 on azure ~ 1000 tps  
32:40 test suite for malicious behaviour  
33:08 Joel, Quorum team    
33:30 quick demo: 4 nodes, 1 rogue actor; dockerized  
35:00 create transaction  
35:-- consensus even in presence of malicious actor  



36:04 Kieren James-Lubin, COO, BlockApps.net  
37:20 what was done?  
--:-- RDBMS integration  
--:-- pruning  
--:-- mgmt dashboard f setup & permissioning   
--:-- obscure recipient of tx  
40:10 RDBMS architecture: Blockapps tools --> [github](https://github.com/blockapps/quorum-rdbms-implementation)  
41:10 Governance Dashboard --> [github](https://github.com/blockapps/quorum-network-dashboard)  

42:15 Amber: closing remarks  
42:30 Quorum as general as Ethereum, decentralized or consortium  
42:46 does not use cryptocurrency  
43:15 three types of transactions: vanilla Ethereum, private smart contracts, ZSL contracts  



### contributors
Please fork, edit/correct/extend, and pull request. Thanks.    

* https://gitlab.com/andreaskrueger

