# Academic Blockchain Papers
A curated blockchain-related academic papers. All papers are sorted based on the conference name and published year. 


## Table of Listed Conferences
- [CRYPTO](#crypto)
- [EUROCRYPT](#eurocrypt)
- [USENIX Security](#usenix-security)
- [IEEE Security and Privacy(S&P)](#ieee-security-and-privacysp)
- [Network and Distributed System Security(NDSS)](#network-and-distributed-system-security-ndss)
- [ACM Symposium on Operating Systems Principles(SOSP)](#acm-symposium-on-operating-systems-principles-sosp)
- [ACM Symposium on Principles of Distributed Computing(PODC)](#acm-symposium-on-principles-of-distributed-computing-podc)
- [ACM Conference on Computer and Communications Security(CCS)](#acm-conference-on-computer-and-communications-security-ccs)
- [IEEE International Conference on Computer Communications(INFOCOM)](#ieee-international-conference-on-computer-communicationsinfocom)
- [IEEE International Conference on Distributed Computing Systems(ICDCS)](#ieee-international-conference-on-distributed-computing-systems-icdcs)
- [USENIX Symposium on Networked Systems Design and Implementation(NSDI)](#usenix-symposium-on-networked-systems-design-and-implementation-nsdi)
- [ACM Conference on Emerging Networking EXperiments and Technologies(CoNEXT)](#acm-conference-on-emerging-networking-experiments-and-technologies-conext)
- [Financial Cryptography(FC)](#financial-cryptography-fc) 
- [License](#license)

Key Words: System Design, Consensus(Proof-of-Work, Proof-of-Stake, Proof-of-X, BFT), Off-chain Design(Payment Networks, Sidechain), Crosschain, P2P Network, Privacy Issue, Security, Economics, Smart Contracts, Applications, Cryptograph. 


## CRYPTO
[Consensus-PoS] [The Bitcoin Backbone Protocol with Chains of Variable Difficulty](https://eprint.iacr.org/2016/1048). Juan A. Garay and Aggelos Kiayias and Nikos Leonardos. Crypto '17.

[Consensus-PoS] [Ouroboros Praos: An adaptively-secure, semi-synchronous proof-of-stake protocol](http://eprint.iacr.org/2017/573.pdf). Bernardo D, Gazi P, Kiayias A, Russell A. Crypto '17.

## EUROCRYPT
[Consensus-PoW] [The Bitcoin Backbone Protocol: Analysis and Applications](https://eprint.iacr.org/2014/765.pdf). Garay J, Kiayias A, Leonardos N. EUROCRYPT '15.

[Consensus-PoW] [Analysis of the Blockchain Protocol in Asynchronous Networks](https://eprint.iacr.org/2016/454.pdf). Pass R, Seeman L, shelat a. EUROCRYPT '17

[Consensus][Consensus through Herding](https://link.springer.com/content/pdf/10.1007%2F978-3-030-17653-2_24.pdf). T-H. Hubert Chan Rafael Pass Elaine Shi. EUROCRYPT '19. 

[PoS][Proof-of-Stake Protocols for Privacy-Aware Blockchains](https://link.springer.com/content/pdf/10.1007%2F978-3-030-17653-2_23.pdf). Chaya Ganesh Claudio Orlandi Daniel Tschudi. EUROCRYPT '19. 

[Payment Channel][Multi-Party Virtual State Channels](https://link.springer.com/content/pdf/10.1007%2F978-3-030-17653-2_21.pdf). Stefan Dziembowski Lisa Eckey Sebastian Faust Julia Hesse Kristina Hostáková. EUROCRYPT '19. 

[System Design][Aggregate Cash Systems: A Cryptographic Investigation of Mimblewimble](https://link.springer.com/content/pdf/10.1007%2F978-3-030-17653-2_22.pdf). Georg Fuchsbauer Michele Orrù Yannick Seurin. EUROCRYPT '19. 


## IEEE Security and Privacy（S&P）
[Privacy] [Zerocoin: Anonymous distributed e-cash from bitcoin](http://ieeexplore.ieee.org/iel7/6547086/6547088/06547123.pdf). Miers I, Garman C, Green M, Rubin AD. S&P '13.

[Consensus-PoW] [Permacoin: Repurposing bitcoin work for data preservation](http://ieeexplore.ieee.org/iel7/6954656/6956545/06956582.pdf). Miller A, Juels A, Shi E, Parno B, Katz J. Permacoin. S&P '14.

[Privacy] [Zerocash: Decentralized anonymous payments from bitcoin](http://ieeexplore.ieee.org/iel7/6954656/6956545/06956581.pdf). Sasson EB, Chiesa A, Garman C, Green M, Miers I, Tromer E, Virza M. S&P '14.

[Consensus-PoW-Mining][The Miner's Dilemma](https://arxiv.org/abs/1411.7099). Ittay Eyal. S&P '15

[General] [SoK: Research Perspectives and Challenges for Bitcoin and Cryptocurrencies](http://www.jbonneau.com/doc/BMCNKF15-IEEESP-bitcoin.pdf). Bonneau J, Miller A, Clark J, Narayanan A, Kroll JA, Felten EW. S&P '15

[Privacy] [Hawk: The Blockchain Model of Cryptography and Privacy-Preserving Smart Contracts](https://eprint.iacr.org/2015/675.pdf). Kosba A, Miller A, Shi E, Wen Z, Papamanthou C. S&P '16

[System] [OmniLedger: A Secure, Scale-Out, Decentralized Ledger via Sharding](). E. Kokoris-Kogias and P. Jovanovic and L. Gasser and N. Gailly and E. Syta and B. Ford. S&P '18

[Sidechain][Proof-of-Stake Sidechains](https://eprint.iacr.org/2018/1239.pdf). Peter Gaži, Aggelos Kiayias, Dionysis Zindros. IEEE S&P '19.  

[Payment Networks] [Perun: Virtual payment hubs over cryptocurrencies](https://eprint.iacr.org/2017/635.pdf) Dziembowski S, Eckey L, Faust S, Malinowski D. IEEE S&P '19.

[Consensus-PoW] [Lay Down the Common Metrics: Evaluating Proof-of-Work Consensus Protocols’ Security](https://www.esat.kuleuven.be/cosic/publications/article-3005.pdf) Ren Zhang, Bart Preneel. IEEE S&P '19.

[Consensus][Redactable Blockchain in the Permissionless Setting](https://arxiv.org/abs/1901.03206). Dominic Deuber, Bernardo Magri, Sri Aravinda Krishnan Thyagarajan. IEEE S&P '19.

[Consensus-Privacy][Ouroboros Crypsinous: Privacy-Preserving Proof-of-Stake](https://eprint.iacr.org/2018/1132). Thomas Kerber and Markulf Kohlweiss and Aggelos Kiayias and Vassilis Zikas. IEEE S&P '19.

[Scalaility][XCLAIM: Decentralized, Interoperable, Cryptocurrency-Backed Assets](https://eprint.iacr.org/2018/643.pdf). 
Alexei Zamyatin, Dominik Harz, Joshua Lind, Panayiotis Panayiotou, Arthur Gervais, William J. Knottenbelt. IEEE S&P '19. 

## USENIX Security
[Network] [Eclipse Attacks on Bitcoin's Peer-to-Peer Network](https://www.usenix.org/system/files/conference/usenixsecurity15/sec15-paper-heilman.pdf). Heilman E, Kendler A, Zohar A, Goldberg S. USENIX '15 Security Symposium.

[Consensus] [Enhancing Bitcoin Security and Performance with Strong Consistency via Collective Signing](https://www.usenix.org/system/files/conference/usenixsecurity16/sec16_paper_kokoris-kogias.pdf). Kogias EK, Jovanovic P, Gailly N, Khoffi I, Gasser L, Ford B. USENIX '16 Security Symposium.

[Mining][SmartPool: Practical Decentralized Pooled Mining](). Loi Luu,  Yaron Velner, Jason Teutsch, TrueBit Foundation; Prateek Saxena.USENIX '17 Security Symposium.

[Mining][REM: Resource-Efficient Mining for Blockchains](https://eprint.iacr.org/2017/179). Fan Zhang and Ittay Eyal and Robert Escriva and Ari Juels and Robbert van Renesse. USENIX '17 Security Symposium.

[Smart contract][teEther: Gnawing at Ethereum to Automatically Exploit Smart Contracts](https://www.usenix.org/system/files/conference/usenixsecurity18/sec18-krupp.pdf).Johannes Krupp and Christian Rossow. USENIX '18 Security Symposium.

[Anonymity Privacy][An Empirical Analysis of Anonymity in Zcash](https://www.usenix.org/system/files/conference/usenixsecurity18/sec18-kappos.pdf). George Kappos, Haaroon Yousaf, Mary Maller, and Sarah Meiklejohn. USENIX '18 Security Symposium.

[Smart contract][Arbitrum: Scalable, private smart contracts](https://www.usenix.org/system/files/conference/usenixsecurity18/sec18-kalodner.pdf). Harry Kalodner, Steven Goldfeder, Xiaoqi Chen, S. Matthew Weinberg,
and Edward W. Felten. USENIX '18 Security Symposium.

[Smart contract][FastKitten: Practical Smart Contracts on Bitcoin](). Poulami Das, Lisa Eckey, Tommaso Frassetto, David Gens, Kristina Hostáková, Patrick Jauernig, Sebastian Faust, and Ahmad-Reza Sadeghi. USENIX '18 Security Symposium.

[Transaction Analysis][Tracing Transactions Across Cryptocurrency Ledgers](). Haaroon Yousaf, George Kappos, and Sarah Meiklejohn. USENIX '19 Security Symposium.

[Consensus][StrongChain: Transparent and Collaborative Proof-of-Work Consensus](). Pawel Szalachowski, Daniël Reijsbergen, and Ivan Homoliak, Siwei Sun. USENIX '19 Security Symposium.

[Privacy][BITE: Bitcoin Lightweight Client Privacy using Trusted Execution](). Sinisa Matetic, Karl Wüst, Moritz Schneider, and Kari Kostiainen, Ghassan Karame, Srdjan Capkun. USENIX '19 Security Symposium.

[Smart Contract][FastKitten: Practical Smart Contracts on Bitcoin](). Poulami Das, Lisa Eckey, Tommaso Frassetto, David Gens, Kristina Hostáková, Patrick Jauernig, Sebastian Faust, and Ahmad-Reza Sadeghi. USENIX '19 Security Symposium.

## Network and Distributed System Security (NDSS) 
[Economic-Smart Contracts] ["Zeus": Analyzing Safety of Smart Contracts](http://wp.internetsociety.org/ndss/wp-content/uploads/sites/25/2018/02/ndss2018_09-1_Kalra_paper.pdf). Kalra S, Goel S, Dhawan M, Sharma S. NDSS '18.

[System Design][Chainspace: A Sharded Smart Contracts Platform](https://sheharbano.com/assets/publications/ndss2018-chainspace.pdf). Mustafa Al-Bassam, Alberto Sonnino, Shehar Bano, Dave Hrycyszyn, and George Danezis. NDSS '18.

[off-chain][Settling Payments Fast and Private: Efficient Decentralized Routing for Path-Based Transactions](https://www.ndss-symposium.org/wp-content/uploads/2018/02/ndss2018_09-3_Roos_paper.pdf). Stefanie Roos, Pedro Moreno-Sanchez, Aniket Kate, and Ian Goldberg. NDSS '18.

[Network][SABRE: Protecting Bitcoin against Routing Attacks](https://arxiv.org/pdf/1808.06254.pdf). Maria Apostolaki, Gian Marti, Jan Müller, and Laurent Vanbever. NDSS '19.

[Smart Contract][Seth: Protecting Existing Smart Contracts Against Re-Entrancy Attacks](https://arxiv.org/pdf/1812.05934.pdf). Michael Rodler, Wenting Li and Ghassan Karame, Lucas Davi. NDSS '19.

[Smart Contract][YODA: Enabling computationally intensive contracts on blockchains with Byzantine and Selfish nodes](https://arxiv.org/pdf/1811.03265.pdf). Sourav Das, Vinay Joseph Ribeiro, and Abhijeet Anand. NDSS '19.

[Cryptograph][Fine-Grained and Controlled Rewriting in Blockchains: Chameleon-Hashing Gone Attribute-Based](https://www.ndss-symposium.org/wp-content/uploads/2019/02/ndss2019_02A-3_Derler_paper.pdf). David Derler, Kai Samelin, Daniel Slamanig and Christoph Striecks. NDSS '19.

[off-Chain][Privacy-preserving Multi-hop Locks for Blockchain Scalability and Interoperability](https://www.ndss-symposium.org/wp-content/uploads/2019/02/ndss2019_09-4_Malavolta_paper.pdf). Giulio Malavolta, Pedro Moreno Sanchez, Clara Schneidewind and Matteo Maffei, Aniket Kate. NDSS '19.

## ACM Symposium on Operating Systems Principles (SOSP)
[Consensus] [Algorand: Scaling Byzantine Agreements for Cryptocurrencies](https://people.csail.mit.edu/nickolai/papers/gilad-algorand.pdf). Yossi Gilad, Rotem Hemo, Silvio Micali, Georgios Vlachos, Nickolai Zeldovich. SOSP'17

[Payment Networks] [Teechain: A Secure Payment Network with Asynchronous Blockchain Access](https://arxiv.org/pdf/1707.05454.pdf). Joshua Lind, Oded Naor, Ittay Eyal, Florian Kelbert, Peter Pietzuch, Emin Gun Sirer. SOSP'19

## ACM Symposium on Principles of Distributed Computing (PODC)
[Consensus-PoW] [FruitChains: A Fair Blockchain](https://eprint.iacr.org/2016/916.pdf).Rafael Pass, Elaine Shi. PODC'17

[Sidechain] [Atomic Cross-Chain Swaps](https://arxiv.org/abs/1801.09515). Maurice Herlihy. PODC'18

[Consessus] [Brief Announcement: Sustainable Blockchains through Proof of eXercise](https://haslab.uminho.pt/ashoker/files/pox-podc.pdf). Ali Shoker. PODC'18

[Consensus][The Consensus Number of a Cryptocurrency](https://arxiv.org/pdf/1906.05574.pdf). R. Guerraoui, P. Kuznetsov, M. Monti, M. Pavlovic, D. Seredinschi. PODC'19

[Consensus-BFT][Communication Complexity of Byzantine Agreement, Revisited](). I. Abraham, T. Chan, D. Dolev, K. Nayak, R. Pass, L. Ren, E. Shi. PODC'19

[Consensus-BFT][Exact Byzantine Consensus on Undirected Graphs under Local Broadcast Model](https://arxiv.org/pdf/1903.11677.pdf). M. Khan, S. Naqvi, N. Vaidya. PODC'19

[Consensus-BFT][Asymptotically Optimal Validated Asynchronous Byzantine Agreement](). I. Abraham, D. Malkhi, A. Spiegelman. PODC'19

[Consensus-BFT][HotStuff: BFT Consensus with Linearity and Responsiveness](https://www.cs.unc.edu/~reiter/papers/2019/PODC.pdf). M. Yin, I. Abraham, G. Gueta, D. Malkhi, M. Reiter. PODC'19

## ACM Conference on Computer and Communications Security (CCS)
[Consensus-PoW-Mining][Double-Spending Fast Payments in Bitcoin](https://www.eecis.udel.edu/~ruizhang/CISC859/S17/Paper/p9.pdf). Karame, Ghassan O. and Androulaki, Elli and Capkun, Srdjan. CCS '12.

[Privacy] [Deanonymisation of Clients in Bitcoin P2P Network](https://arxiv.org/pdf/1405.7418.pdf). Biryukov A, Khovratovich D, Pustogarov I. CCS '14.

[Privacy] [Provisions: Privacy-preserving proofs of solvency for Bitcoin exchanges](https://eprint.iacr.org/2015/1008.pdf). Dagher GG, Bünz B, Bonneau J, Clark J, Boneh D. CCS '15

[Economic][Demystifying incentives in the consensus computer](https://eprint.iacr.org/2015/702). Loi Luu, Jason Teutsch, Raghav Kulkarni and Prateek Saxena. CCS '15

[PoW-Network][Tampering with the Delivery of Blocks and Transactions in Bitcoin](https://eprint.iacr.org/2015/578.pdf).Gervais, Arthur and Ritzdorf, Hubert and Karame, Ghassan O. and Capkun, Srdjan. CCS '15

[Consensus-PoW-Mining][Non-outsourceable Scratch-Off Puzzles to Discourage Bitcoin Mining Coalitions](http://soc1024.ece.illinois.edu/nonoutsourceable_full.pdf). Andrew Miller, Elaine Shi, Ahmed Kosba, and Jonathan Katz. CCS '15

[System] [The Honey Badger of BFT Protocols](https://infoscience.epfl.ch/record/222858/files/199.pdf). Miller A, Xia Y, Croman K, Shi E, Song D. CCS '16.

[Smart Contracts] [Making Smart Contracts Smarter](https://www.comp.nus.edu.sg/~loiluu/papers/oyente.pdf). Luu L, Chu DH, Olickel H, Saxena P, Hobor A. CCS '16.

[Economic] [On the instability of Bitcoin without the block reward](http://www.cs.princeton.edu/~smattw/CKWN-CCS16.pdf). Carlsten M, Kalodner H, Weinberg SM, Narayanan A. CCS '16.

[Smart Contracts] [Town crier: An authenticated data feed for smart contracts](http://delivery.acm.org/10.1145/2980000/2978326/p270-zhang.pdf?ip=46.176.188.9&id=2978326&acc=OA&key=4D4702B0C3E38B35%2E4D4702B0C3E38B35%2E4D4702B0C3E38B35%2E594C525CFFA2AFAF&CFID=923932938&CFTOKEN=56121949&__acm__=1492299159_38039f3afa858f241818fdcf190e0200). Zhang F, Cecchetti E, Croman K, Juels A, Shi E. CCS '16.

[Privacy][On the Security and Performance of Proof of Work Blockchains](https://eprint.iacr.org/2016/555.pdf). Gervais A, Karame GO, Karl Wüst, Glykantzis V, Ritzdorf H, Capkun S. CCS '16.

[System][A Secure Sharding Protocol For Open Blockchains](https://www.comp.nus.edu.sg/~loiluu/papers/elastico.pdf). Loi Luu, Viswesh Narayanan, Chaodong Zheng, Kunal Baweja, Seth Gilbert, Prateek Saxena. CCS '16.

[Payment Networks] [Revive: Rebalancing Off-Blockchain Payment Networks](https://eprint.iacr.org/2017/823.pdf). Khalil, R., & Gervais, A. CCS '17.

[Payment Networks] [General State Channel Networks](https://eprint.iacr.org/2018/320.pdf) Dziembowski S, Faust S, Hostáková K. CCS '18.

[System Design] [FairSwap: How to fairly exchange digital goods](https://eprint.iacr.org/2018/740) Dziembowski S, Faust S, Eckey L. CCS '18.

[System] [RapidChain: Scaling Blockchain via Full Sharding](). Mahdi Zamani, Mahnush Movahedi, Mariana Raykova. CCS '18.

## IEEE International Conference on Computer Communications(INFOCOM)
[Network][Stochastic Models and Wide-Area Network Measurements for Blockchain Design and Analysis](https://www.researchgate.net/publication/321369565_Stochastic_Models_and_Wide-Area_Network_Measurements_for_Blockchain_Design_and_Analysis). Nikolaos Papadis, Sem Borst, Anwar Walid, Mohamed Grissa, Leandros Tassiulas. INFOCOM'18

[Transaction][Understanding ethereum via graph analysis](https://www4.comp.polyu.edu.hk/~csxluo/EthereumGraphAnalysis.pdf). Ting Chen,Yuxiao Zhu, Zihao Li, Jiachi Chen, Xiaoqi Li, Xiapu Luo, Xiaodong Lin, Xiaodong Lin. INFOCOM'18

[Security][Corking by Forking: Vulnerability Analysis of Blockchain](). Shengling Wang and Chenyu Wang, Qin Hu. INFOCOM'19

[Scalability][ACCEL: Accelerating the Bitcoin Blockchain for High-throughput, Low-latency Applications](). Adiseshu Hari, Murali Kodialam, T. V Lakshman. INFOCOM'19

[Application][A Blockchain based Witness Model for Trustworthy Cloud Service Level Agreement Enforcement](). Huan Zhou, Xue Ouyang,  Zhijie Ren, Jinshu Su, Cees de Laat and Zhiming Zhao. INFOCOM'19

## IEEE International Conference on Distributed Computing Systems (ICDCS)
[Application] [Transform Blockchain into Distributed Parallel Computing Architecture for Precision Medicine]().Zonyin Shae, Jeffrey J.P. Tsai. ICDCS'18

[Crosschain] [Towards A Novel Architecture for Enabling Interoperability Amongst Multiple Blockchains](). Hai Jin, Xiaohai Dai, and Jiang Xiao. ICDCS'18

[Consensus] [Short Paper][Towards Dependable, Scalable, and Pervasive Distributed Ledgers with Blockchains](). Zhang Kaiwen, Jacobsen Hans-Arno.ICDCS'18

[Privacy] [Short Paper][A Flexible Network Approach to Privacy of Blockchain Transactions](). David M¨odinger, Henning Kopp, Frank Kargl and Franz J. Hauck. ICDCS'18

[PoW][Selfish Mining in Ethereum](https://arxiv.org/abs/1901.04620) Jianyu Niu and Chen Feng. ICDCS'19

[Consensus][Trust Mends Blockchains: Living up to Expectations](http://kth.diva-portal.org/smash/get/diva2:1316199/FULLTEXT01.pdf). Leila Bahri and Sarunas Girdzijauskas. ICDCS'19

[Application][Hierarchical Edge-Cloud Computing for Mobile Blockchain Mining Game](https://pdfs.semanticscholar.org/cfe0/77c9b880c2a0dfb495448a068fdf1db07b6e.pdf). Suhan Jiang, Xinyi Li and Jie Wu. ICDCS'19

[Scalability][OptChain: Optimal Transactions Placement for Scalable Blockchain Sharding](). Lan Nguyen, Truc Nguyen, Thang Dinh and My Thai. ICDCS'19

[][Jidar: A Jigsaw-like Data Reduction Approach without Trust Assumptions for Bitcoin System](). Xiaohai Dai, Jiang Xiao, Wenhui Yang, Chaofan Wang and Hai Jin. ICDCS'19

[Scalability][ParBlockchain: Leveraging Transaction Parallelism in Permissioned Blockchain Systems](https://arxiv.org/pdf/1902.01457.pdf). Mohammad Javad Amiri, Divyakant Agrawal and Amr El Abbadi. ICDCS'19

[Application][Optimal Admission Control For Secondary Users using Blockchain Technology In Cognitive Radio Networks](). Wenlong Ni, Yuhong Zhang and Wei Li. ICDCS'19

[application][B-IoT: Blockchain Driven Internet of Things with Credit-Based Consensus Mechanism](). Junqin Huang, Linghe Kong, Guihai Chen, Long Chen, Kaishun Wu and Xue Liu. ICDCS'19

[Application][Resource Allocation and Consensus on Edge Blockchain in Pervasive Edge Computing Environments](). Yaodong Huang, Jiarui Zhang, Jun Duan, Bin Xiao, Fan Ye and Yuanyuan Yang. ICDCS'19

[Application][Xyreum: A High-Performance and Scalable Blockchain for IIoT Security and Privacy](). Abubakar Sadiq Sani, Dong Yuan, Wei Bao, Phee Lep Yeoh, Zhaoyang Dong, Branka Vucetic and Elisa Bertino. ICDCS'19

[Vision][AI Blockchain Platform for Trusting News](). Zonyin Shae and Jeffrey Tsai. ICDCS'19

[Vision][Dependable Public Ledger for Policy Compliance, a Blockchain Based Approach](). Zhou Wu, Andrew Williams and Debbie Perouli. ICDCS'19

[Vision][Please, do not decentralize the Internet with (permissionless) blockchains!](https://arxiv.org/pdf/1904.13093.pdf). Pedro Garcia Lopez, Alberto Montresor and Anwitaman Datta. ICDCS'19

## USENIX Symposium on Networked Systems Design and Implementation(NSDI)
[Consensus-PoW] [Bitcoin-NG: A Scalable Blockchain Protocol](https://www.usenix.org/system/files/conference/nsdi16/nsdi16-paper-eyal.pdf). Eyal I, Gencer AE, Sirer EG, Van Renesse R. NSDI ’16

[System][Monoxide: Scale Out Blockchain with Asynchronized Consensus Zones](https://www.usenix.org/system/files/nsdi19-wang-jiaping.pdf). Jiaping Wang, Hao Wang. NSDI'19

## ACM Conference on Emerging Networking EXperiments and Technologies(CoNEXT)
[Consensus-PoW] [On the Necessity of a Prescribed Block Validity Consensus: Analyzing Bitcoin Unlimited Mining Protocol](https://eprint.iacr.org/2017/686.pdf). Ren Zhang, Bart Preneel. CoNEXT '17

## Financial Cryptography (FC)
[Economic-PoW] [Majority Is Not Enough: Bitcoin Mining Is Vulnerable](https://arxiv.org/pdf/1311.0243). Eyal I, Sirer EG. FC '14.

[Consensus-PoW] [Secure High-Rate Transaction Processing in Bitcoin](http://www.cs.huji.ac.il/~avivz/pubs/15/btc_ghost_full.pdf). Sompolinsky Y, Zohar A. FC '15.

[ChainStructure][Inclusive Block Chain Protocols](https://fc15.ifca.ai/preproceedings/paper_101.pdf). Yoad Lewenberg, Yonatan Sompolinsky, Aviv Zohar. FC '15.

[Consensus] [Cryptocurrencies without Proof of Work](http://fc16.ifca.ai/bitcoin/papers/BGM16.pdf). Bentov I, Gabizon A, Mizrahi A. FC '16.

[Economic-PoW] [Optimal Selfish Mining Strategies in Bitcoin](http://fc16.ifca.ai/preproceedings/30_Sapirshtein.pdf). Sapirshtein A, Sompolinsky Y, Zohar A. FC '16.

[Consensus-PoS] [A Proof-of-Stake protocol for consensus on Bitcoin subchains](http://eprint.iacr.org/2017/417.pdf). Bartoletti M, Lande S, & Podda A S. FC '17.

[FC Accepted Paper Link:] [FC'15](https://fc15.ifca.ai/schedule.html), [FC'16](https://fc16.ifca.ai/program.html), [FC'17](https://fc17.ifca.ai/program.html), [FC'18](https://fc18.ifca.ai/program.html), [FC'19](https://fc19.ifca.ai/program.html).

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)


This list is released into the public domain.
