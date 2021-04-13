# Academic Blockchain Papers
A curated blockchain-related academic papers. All papers are sorted based on the conference name and published year.
Welcome developers or researchers to add more published paper to this list. 

## Table of Listed Conferences
- [CRYPTO](#crypto)
- [EuroSys](#eurosys)
- [EUROCRYPT](#eurocrypt)
- [USENIX Security](#usenix-security)
- [IEEE Security and Privacy(S&P)](#sp)
- [ACM SIGMETRICS / IFIP Performance](#sigmetricperformance)
- [Network and Distributed System Security(NDSS)](#ndss)
- [International Conference on Software Engineering(ICSE)](#icse) 
- [ACM Symposium on Operating Systems Principles(SOSP)](#sosp)
- [International Conference on Very Large Data Bases(VLDB)](#vldb)
- [International Symposium on Reliable Distributed Systems(SRDS)](#srds)
- [ACM Symposium on Principles of Distributed Computing(PODC)](#podc)
- [ACM International Conference on Management of Data(SIGMOD)](#sigmod)
- [ACM Conference on Computer and Communications Security(CCS)](#ccs)
- [IEEE International Parallel & Distributed Processing Symposium(IPDPS)](#ipdps)
- [ACM Symposium on Parallelism in Algorithms and Architectures(SPAA)](#spaa)
- [IEEE International Conference on Computer Communications(INFOCOM)](#infocom)
- [IEEE International Conference on Distributed Computing Systems(ICDCS)](#icdcs)
- [USENIX Symposium on Networked Systems Design and Implementation(NSDI)](#nsdi)
- [USENIX Symposium on Operating Systems Design and Implementation(OSDI)](#osdi)
- [IEEE/IFIP International Conference on Dependable Systems and Networks(DSN)](#dsn)
- [ACM Conference on Emerging Networking EXperiments and Technologies(CoNEXT)](#conext)
- [ACM SIGPLAN Conference on Programming Language Design&Implementation(PLDI)](#pldi) 
- [Financial Cryptography(FC)](#fc) 
- [ACM Conference on Economics and Computation(EC)](#ec) 
- [License](#license)

Key Words: Topics: System Architecture, Consensus(Proof-of-X and BFT), Layer 2 (Off-chain, Payment Networks, Sidechain, Crosschain), Network, Smart Contracts, Application (Trasactions), Cryptograph, Storage (light client); Contents: privacy, security, economics (incentive).


## CRYPTO
[Consensus-PoW] [The Bitcoin Backbone Protocol with Chains of Variable Difficulty](https://eprint.iacr.org/2016/1048). Juan A. Garay and Aggelos Kiayias and Nikos Leonardos. Crypto '17.

[Consensus-PoS] [Ouroboros Praos: An adaptively-secure, semi-synchronous proof-of-stake protocol](http://eprint.iacr.org/2017/573.pdf). Bernardo D, Gazi P, Kiayias A, Russell A. Crypto '17.

[Consensus-BFT] [Order-Fairness for Byzantine Consensus](https://eprint.iacr.org/2020/269.pdf) Mahimna Kelkar,Fan Zhang,Ari Juels. Crypto '20.

## Eurosys
[System] [Hyperledger Fabric: A Distributed Operating System for Permissioned Blockchains](https://arxiv.org/pdf/1801.10228.pdf). Elli Androulaki, Artem Barger, Vita Bortnikov, Christian Cachin, Konstantinos Christidis, Angelo De Caro, David Enyeart, Christopher Ferris, Gennady Laventman, Yacov Manevich, Srinivasan Muralidharan, Chet Murthy, Binh Nguyen, Manish Sethi, Gari Singh, Keith Smith, Alessandro Sorniotti, Chrysoula Stathakopoulou, Marko Vukolić, Sharon Weed Cocco, Jason Yellick. EuroSys'18

[Random Beacons][Fully Distributed Verifiable Random Functions and their Application to Decentralised Random Beacons](). Monjur Alam, Frank Werner, Milos Prvulovic, Alenka Zajic and Baki Yilmaz, Niels Samwel, Daniel Genkin, Yuval Yarom.

## EUROCRYPT
[Consensus-PoW] [The Bitcoin Backbone Protocol: Analysis and Applications](https://eprint.iacr.org/2014/765.pdf). Garay J, Kiayias A, Leonardos N. EUROCRYPT '15.

[Consensus-PoW] [Analysis of the Blockchain Protocol in Asynchronous Networks](https://eprint.iacr.org/2016/454.pdf). Pass R, Seeman L, abhi shelat. EUROCRYPT '17

[Consensus][Thunderella: Blockchains with Optimistic Instant Confirmation](https://eprint.iacr.org/2017/913.pdf). Rafael Pass, Elaine Shi. EUROCRYPT '18.

[Consensus-PoS][Ouroboros Praos: An adaptively-secure, semi-synchronous proof-of-stake blockchain](https://eprint.iacr.org/2017/573.pdf). Bernardo David, Peter Gaži, Aggelos Kiayias, Alexander Russell. EUROCRYPT '18. 

[Consensus][Consensus through Herding](https://link.springer.com/content/pdf/10.1007%2F978-3-030-17653-2_24.pdf). T-H. Hubert Chan Rafael Pass Elaine Shi. EUROCRYPT '19. 

[Consensus-PoS][Proof-of-Stake Protocols for Privacy-Aware Blockchains](https://link.springer.com/content/pdf/10.1007%2F978-3-030-17653-2_23.pdf). Chaya Ganesh Claudio Orlandi Daniel Tschudi. EUROCRYPT '19. 

[Payment Channel][Multi-Party Virtual State Channels](https://link.springer.com/content/pdf/10.1007%2F978-3-030-17653-2_21.pdf). Stefan Dziembowski Lisa Eckey Sebastian Faust Julia Hesse Kristina Hostáková. EUROCRYPT '19. 

[Cryptography-Privacy][Aggregate Cash Systems: A Cryptographic Investigation of Mimblewimble](https://link.springer.com/content/pdf/10.1007%2F978-3-030-17653-2_22.pdf). Georg Fuchsbauer Michele Orrù Yannick Seurin. EUROCRYPT '19. 

## USENIX Security
[Network-security] [Eclipse Attacks on Bitcoin's Peer-to-Peer Network](https://www.usenix.org/system/files/conference/usenixsecurity15/sec15-paper-heilman.pdf). Heilman E, Kendler A, Zohar A, Goldberg S. USENIX '15 Security Symposium.

[Consensus-PoW] [Enhancing Bitcoin Security and Performance with Strong Consistency via Collective Signing](https://www.usenix.org/system/files/conference/usenixsecurity16/sec16_paper_kokoris-kogias.pdf). Kogias EK, Jovanovic P, Gailly N, Khoffi I, Gasser L, Ford B. USENIX '16 Security Symposium.

[Mining][SmartPool: Practical Decentralized Pooled Mining](https://www.usenix.org/system/files/conference/usenixsecurity17/sec17-luu.pdf). Loi Luu,  Yaron Velner, Jason Teutsch, TrueBit Foundation; Prateek Saxena.USENIX '17 Security Symposium.

[Mining][REM: Resource-Efficient Mining for Blockchains](https://eprint.iacr.org/2017/179). Fan Zhang and Ittay Eyal and Robert Escriva and Ari Juels and Robbert van Renesse. USENIX '17 Security Symposium.

[Smart contract][teEther: Gnawing at Ethereum to Automatically Exploit Smart Contracts](https://www.usenix.org/system/files/conference/usenixsecurity18/sec18-krupp.pdf).Johannes Krupp and Christian Rossow. USENIX '18 Security Symposium.

[Anonymity Privacy][An Empirical Analysis of Anonymity in Zcash](https://www.usenix.org/system/files/conference/usenixsecurity18/sec18-kappos.pdf). George Kappos, Haaroon Yousaf, Mary Maller, and Sarah Meiklejohn. USENIX '18 Security Symposium.

[Smart contract][Arbitrum: Scalable, private smart contracts](https://www.usenix.org/system/files/conference/usenixsecurity18/sec18-kalodner.pdf). Harry Kalodner, Steven Goldfeder, Xiaoqi Chen, S. Matthew Weinberg,
and Edward W. Felten. USENIX '18 Security Symposium.

[Smart contract][FastKitten: Practical Smart Contracts on Bitcoin](). Poulami Das, Lisa Eckey, Tommaso Frassetto, David Gens, Kristina Hostáková, Patrick Jauernig, Sebastian Faust, and Ahmad-Reza Sadeghi. USENIX '18 Security Symposium.

[Transaction Analysis][Tracing Transactions Across Cryptocurrency Ledgers](https://smeiklej.com/files/usenix19.pdf). Haaroon Yousaf, George Kappos, and Sarah Meiklejohn. USENIX '19 Security Symposium.

[Consensus][StrongChain: Transparent and Collaborative Proof-of-Work Consensus](https://arxiv.org/pdf/1905.09655.pdf). Pawel Szalachowski, Daniël Reijsbergen, and Ivan Homoliak, Siwei Sun. USENIX '19 Security Symposium.

[Privacy][BITE: Bitcoin Lightweight Client Privacy using Trusted Execution](https://www.usenix.org/system/files/sec19fall_matetic_prepub.pdf). Sinisa Matetic, Karl Wüst, Moritz Schneider, and Kari Kostiainen, Ghassan Karame, Srdjan Capkun. USENIX '19 Security Symposium.

[Smart Contract][FastKitten: Practical Smart Contracts on Bitcoin](https://www.usenix.org/system/files/sec19fall_das_prepub.pdf). Poulami Das, Lisa Eckey, Tommaso Frassetto, David Gens, Kristina Hostáková, Patrick Jauernig, Sebastian Faust, and Ahmad-Reza Sadeghi. USENIX '19 Security Symposium.

[Transaction Analysis][BlockSci: Design and applications of a blockchain analysis platform](https://www.usenix.org/conference/usenixsecurity20/presentation/kalodner). Harry Kalodner, Malte Möser, and Kevin Lee,Steven Goldfeder, Martin Plattner, Alishah Chator, Arvind Narayanan. USENIX '20 Security Symposium.

[SideChain][Remote Side-Channel Attacks on Anonymous Transaction](https://www.usenix.org/conference/usenixsecurity20/presentation/tramer#:~:text=These%20attacks%20enable%20an%20active,implementation%20of%20different%20system%20components.). Florian Tramer and Dan Boneh, Kenny Paterson. USENIX '20 Security Symposium.

[Smart Contract][ETHBMC: A Bounded Model Checker for Smart Contracts](https://www.usenix.org/conference/usenixsecurity20/presentation/frank). Joel Frank, Cornelius Aschermann, and Thorsten Holz. USENIX '20 Security Symposium.

[Smart Contract][TXSPECTOR: Uncovering Attacks in Ethereum from Transactions](https://www.usenix.org/conference/usenixsecurity20/presentation/zhang-mengya). Mengya Zhang, Xiaokuan Zhang, Yinqian Zhang, and Zhiqiang Lin. USENIX '20 Security Symposium.

[Smart Contract][An Ever-evolving Game: Evaluation of Real-world Attacks and Defenses in Ethereum Ecosystem](https://www.usenix.org/conference/usenixsecurity20/presentation/zhou-shunfan). Shunfan Zhou, Zhemin Yang, and Jie Xiang, Yinzhi Cao,Min Yang and Yuan Zhang. USENIX '20 Security Symposium.

[Smart Contract][EVMPatch: Timely and Automated Patching of Ethereum Smart Contracts](). Michael Rodler, Wenting Li and Ghassan O. Karame, Lucas Davi. USENIX '21 Security Symposium.

[Application][Evil Under the Sun: Understanding and Discovering Attacks on Ethereum Decentralized Applications](). Liya Su, Xinyue Shen, Xiangyu Du, Xiaojing Liao, XiaoFeng Wang, and Luyi Xing, Baoxu Liu. USENIX '21 Security Symposium.

[Smart Contract][Smart Contract Vulnerabilities: Vulnerable Does Not Imply Exploited]() Daniel Perez and Ben Livshits. USENIX '21 Security Symposium. 


## S&P
[Privacy] [Zerocoin: Anonymous distributed e-cash from bitcoin](http://ieeexplore.ieee.org/iel7/6547086/6547088/06547123.pdf). Miers I, Garman C, Green M, Rubin AD. S&P '13.

[Consensus-PoW] [Permacoin: Repurposing bitcoin work for data preservation](http://ieeexplore.ieee.org/iel7/6954656/6956545/06956582.pdf). Miller A, Juels A, Shi E, Parno B, Katz J. Permacoin. S&P '14.

[Privacy] [Zerocash: Decentralized anonymous payments from bitcoin](http://ieeexplore.ieee.org/iel7/6954656/6956545/06956581.pdf). Sasson EB, Chiesa A, Garman C, Green M, Miers I, Tromer E, Virza M. S&P '14.

[Consensus-PoW-Mining][The Miner's Dilemma](https://arxiv.org/abs/1411.7099). Ittay Eyal. S&P '15

[General] [SoK: Research Perspectives and Challenges for Bitcoin and Cryptocurrencies](http://www.jbonneau.com/doc/BMCNKF15-IEEESP-bitcoin.pdf). Bonneau J, Miller A, Clark J, Narayanan A, Kroll JA, Felten EW. S&P '15

[Privacy] [Hawk: The Blockchain Model of Cryptography and Privacy-Preserving Smart Contracts](https://eprint.iacr.org/2015/675.pdf). Kosba A, Miller A, Shi E, Wen Z, Papamanthou C. S&P '16

[System] [OmniLedger: A Secure, Scale-Out, Decentralized Ledger via Sharding](https://eprint.iacr.org/2017/406.pdf). E. Kokoris-Kogias and P. Jovanovic and L. Gasser and N. Gailly and E. Syta and B. Ford. S&P '18

[Sidechain][Proof-of-Stake Sidechains](https://eprint.iacr.org/2018/1239.pdf). Peter Gaži, Aggelos Kiayias, Dionysis Zindros. IEEE S&P '19.  

[Payment Networks] [Perun: Virtual payment hubs over cryptocurrencies](https://eprint.iacr.org/2017/635.pdf) Dziembowski S, Eckey L, Faust S, Malinowski D. IEEE S&P '19.

[Consensus-PoW] [Lay Down the Common Metrics: Evaluating Proof-of-Work Consensus Protocols’ Security](https://www.esat.kuleuven.be/cosic/publications/article-3005.pdf) Ren Zhang, Bart Preneel. IEEE S&P '19.

[Consensus][Redactable Blockchain in the Permissionless Setting](https://arxiv.org/abs/1901.03206). Dominic Deuber, Bernardo Magri, Sri Aravinda Krishnan Thyagarajan. IEEE S&P '19.

[Consensus-Privacy][Ouroboros Crypsinous: Privacy-Preserving Proof-of-Stake](https://eprint.iacr.org/2018/1132). Thomas Kerber and Markulf Kohlweiss and Aggelos Kiayias and Vassilis Zikas. IEEE S&P '19.

[Scalaility][XCLAIM: Decentralized, Interoperable, Cryptocurrency-Backed Assets](https://eprint.iacr.org/2018/643.pdf). 
Alexei Zamyatin, Dominik Harz, Joshua Lind, Panayiotis Panayiotou, Arthur Gervais, William J. Knottenbelt. IEEE S&P '19. 

[Consensus-PoW][OHIE: Blockchain Scaling Made Simple](https://arxiv.org/abs/1811.12628). Haifeng Yu, Ivica Nikolic, Ruomu Hou, and Prateek Saxena. IEEE S&P '20. 

[Smart Contract][VerX: Safety Verification of Smart Contracts](). Anton Permenev, Dimitar Dimitrov, Petar Tsankov, Dana Drachsler-Cohen, Martin Vechev. IEEE S&P '20. 

[Smart Contract][VeriSmart: A Highly Precise Safety Verifier for Ethereum Smart Contracts](). Sunbeom So, Myungho Lee, Jisu Park, Heejo Lee, Hakjoo Oh. IEEE S&P '20. 

[Smart Contract][Executable Operational Semantics of Solidity](https://arxiv.org/pdf/1804.01295.pdf). Jiao Jiao, Shuanglong Kan, Shang-Wei Lin, David Sanan, Yang Liu, Jun Sun. IEEE S&P '20. 

[Consensus][Sync HotStuff: Simple and Practical Synchronous State Machine Replication](). Ittai Abraham, Dahlia Malkhi, Kartik Nayak, Ling Ren, Maofan Yin. IEEE S&P '20. 

[Application][Flash Boys 2.0: Frontrunning in Decentralized Exchanges, Miner Extractable Value, and Consensus Instability](). Philip Daian, Steven Goldfeder, Tyler Kell, Yunqi Li, Xueyuan Zhao, Iddo Bentov, Lorenz Breidenbach, Ari Juels. IEEE S&P '20. 

[Application][FlyClient: Super-Light Clients for Cryptocurrencies](). Benedikt Bünz, Lucianna Kiffer, Loi Luu, Mahdi Zamani. IEEE S&P '20. 

[Exchange][High-Frequency Trading on Decentralized On-Chain Exchanges]() Liyi Zhou, Kaihua Qin, Christof Ferreira Torres, Duc V Le, Arthur Gervais, Tyler Crain, Christopher Natoli, Vincent Gramoli. IEEE S&P '21.  

[Payment][A2L: Anonymous Atomic Locks for Scalability in Payment Channel Hubs] Erkan Tairi, Pedro Moreno-Sanchez, Matteo Maffei. IEEE S&P '21. 

[Consensus][Ebb-and-Flow Protocols: A Resolution of the Availability-Finality Dilemma]() Joachim Neu, Ertem Nusret Tas, David Tse. IEEE S&P '21.  

[Sidechain][MAD-HTLC: Because HTLC is Crazy-Cheap to Attack]() Itay Tsabary, Matan Yechieli, Alex Manuskin, Ittay Eyal. IEEE S&P '21.  

[PoS][On the Anonymity Guarantees of Anonymous Proof-of-Stake Protocols]() Varun Madathil, Alessandra Scafuro, Kartik Nayak, Markulf Kohlweiss. IEEE S&P '21. 

[Defi][On the Just-In-Time Discovery of Profit-Generating Transactions in DeFi Protocols]() Liyi Zhou, Kaihua Qin, Antoine Cully, Benjamin Livshits, Arthur Gervais. IEEE S&P '21. 

[Smart contract][SGUARD: Smart Contracts Made Vulnerability-Free]() Long H. Pham, Jun Sun, Tai Duy Nguyen. IEEE S&P '21. 



## Sigmetric&Performance
[Network][Stability and Scalability of Blockchain Systems](). Aditya Gopalan, Abishek Sankararaman, Anwar Walid, Sriram Vishwanath. Sigmetric '20.

[Layer-2][Privacy-Utility Tradeoffs in Routing Cryptocurrency over Payment Channel Networks](). Weizhao Tang, Weina Wang, Giulia Fanti, Sewoong Oh. Sigmetric '20.

[Network][Understanding (Mis)Behavior on the EOSIO Blockchain](). Yuheng Huang, Haoyu Wang, Lei Wu, Gareth Tyson, Xiapu Luo, Run Zhang, Xuanzhe Liu, Gang Huang, Xuxian Jiang. Sigmetric '20.

[Incentive][Incentive Analysis of Bitcoin-NG, Revisited](https://arxiv.org/abs/2001.05082).Jianyu Niu, Ziyu Wang, Fangyu Gai and Chen Feng. Performance '20.

[Transactions][Tracking Counterfeit Cryptocurrency End-to-end]() Bingyu Gao, Haoyu Wang, Pengcheng Xia, Siwei Wu, Yajin Zhou, Xiapu Luo, Gareth Tyson. Sigmetric '21.

## NDSS
[Economic-Smart Contracts] ["Zeus": Analyzing Safety of Smart Contracts](http://wp.internetsociety.org/ndss/wp-content/uploads/sites/25/2018/02/ndss2018_09-1_Kalra_paper.pdf). Kalra S, Goel S, Dhawan M, Sharma S. NDSS '18.

[System Design][Chainspace: A Sharded Smart Contracts Platform](https://sheharbano.com/assets/publications/ndss2018-chainspace.pdf). Mustafa Al-Bassam, Alberto Sonnino, Shehar Bano, Dave Hrycyszyn, and George Danezis. NDSS '18.

[off-chain][Settling Payments Fast and Private: Efficient Decentralized Routing for Path-Based Transactions](https://www.ndss-symposium.org/wp-content/uploads/2018/02/ndss2018_09-3_Roos_paper.pdf). Stefanie Roos, Pedro Moreno-Sanchez, Aniket Kate, and Ian Goldberg. NDSS '18.

[Network][SABRE: Protecting Bitcoin against Routing Attacks](https://arxiv.org/pdf/1808.06254.pdf). Maria Apostolaki, Gian Marti, Jan Müller, and Laurent Vanbever. NDSS '19.

[Smart Contract][Seth: Protecting Existing Smart Contracts Against Re-Entrancy Attacks](https://arxiv.org/pdf/1812.05934.pdf). Michael Rodler, Wenting Li and Ghassan Karame, Lucas Davi. NDSS '19.

[Smart Contract][YODA: Enabling computationally intensive contracts on blockchains with Byzantine and Selfish nodes](https://arxiv.org/pdf/1811.03265.pdf). Sourav Das, Vinay Joseph Ribeiro, and Abhijeet Anand. NDSS '19.

[Cryptograph][Fine-Grained and Controlled Rewriting in Blockchains: Chameleon-Hashing Gone Attribute-Based](https://www.ndss-symposium.org/wp-content/uploads/2019/02/ndss2019_02A-3_Derler_paper.pdf). David Derler, Kai Samelin, Daniel Slamanig and Christoph Striecks. NDSS '19.

[off-Chain][Privacy-preserving Multi-hop Locks for Blockchain Scalability and Interoperability](https://www.ndss-symposium.org/wp-content/uploads/2019/02/ndss2019_09-4_Malavolta_paper.pdf). Giulio Malavolta, Pedro Moreno Sanchez, Clara Schneidewind and Matteo Maffei, Aniket Kate. NDSS '19.

[Consensus-PoW][Bobtail: Improved Blockchain Security with Low-Variance Mining](https://arxiv.org/pdf/1709.08750.pdf). George Bissias and Brian N. Levine. NDSS '20.

[Consensus-PoS][The Attack of the Clones Against Proof-of-Authority](https://arxiv.org/pdf/1902.10244.pdf). Parinya Ekparinya, Vincent Gramoli,Guillaume Jourjon. NDSS '20.

[Layer2][Snappy: Fast On-chain Payments with Practical Collaterals](https://arxiv.org/pdf/2001.01278.pdf) Vasilios Mavroudis,Karl Wüst, Aritra Dhar, Kari Kostiainen, and Srdjan Capkun. NDSS '20.

[Smart Contract][Broken Metre: Attacking Resource Metering in EVM](https://arxiv.org/pdf/1909.07220.pdf). Daniel Perez, and Benjamin Livshits. NDSS '20.

[Smart Contract][SODA: A Generic Online Detection Framework for Smart Contracts](https://www.ndss-symposium.org/wp-content/uploads/2020/02/24449-paper.pdf). Ting Chen, Rong Cao, Ting Li, Xiapu Luo, Guofei Gu, Yufei Zhang, Zhou Liao, Hang Zhu, Gang Chen,
Zheyuan He, Yuxing Tang, Xiaodong Lin, and Xiaosong Zhang. NDSS '20.

[Smart Contract][Bitcontracts: Supporting Smart Contracts in Legacy Blockchains](). Karl Wüst, Loris Diana, Kari Kostiainen, Ghassan Karame, Sinisa Matetic, Srdjan Capkun (ETH Zurich). NDSS '21.

[Mining Attack][SquirRL: Automating Attack Analysis on Blockchain Incentive Mechanisms with Deep Reinforcement Learning]().
Charlie Hou, Mingxun Zhou, Yan Ji and Phil Daian, Florian Tramèr, Giulia Fanti, Ari Juels. NDSS '21.

[Network Attack][As Strong As Its Weakest Link: How to Break Blockchain DApps at RPC Service](). Kai Li, Jiaqi Chen, Xianghong Liu, and Yuzhe Tang, XiaoFeng Wang, Xiapu Luo. NDSS '21.

[Consensus-PoS][ProPoS: A Probabilistic Proof-of-Stake Protocol](). Daniel Reijsbergen, Pawel Szalachowski, Junming Ke, Zengpeng Li, and Jianying Zhou. NDSS '21.


## ICSE
[Smart Contract] [Empirical Review of Automated Analysis Tools on 47,587 Ethereum Smart Contracts](https://arxiv.org/pdf/1910.10601.pdf). T Durieux, JF Ferreira, R Abreu, P Cruz. ICSE '2020

[Smart Contract] [sFuzz-An Efficient Adaptive Fuzzer for Solidity Smart Contracts](https://arxiv.org/pdf/2004.08563.pdf). TD Nguyen, LH Pham, J Sun, Y Lin, QT Minh. ICSE '2020

## SOSP
[Consensus] [Algorand: Scaling Byzantine Agreements for Cryptocurrencies](https://people.csail.mit.edu/nickolai/papers/gilad-algorand.pdf). Yossi Gilad, Rotem Hemo, Silvio Micali, Georgios Vlachos, Nickolai Zeldovich. SOSP'17

[Payment Networks] [Teechain: A Secure Payment Network with Asynchronous Blockchain Access](https://arxiv.org/pdf/1707.05454.pdf). Joshua Lind, Oded Naor, Ittay Eyal, Florian Kelbert, Peter Pietzuch, Emin Gun Sirer. SOSP'19

[Consensus][Fast and Secure Global Payments with Stellar](https://www.scs.stanford.edu/~dm/home/papers/lokhava:stellar-core.pdf). Marta Lokhava, Giuliano Losa, David Mazières, Graydon Hoare, Nicolas Barry, Eliezer Gafni, Jonathan Jove, Rafał Malinowski, Jed McCaleb. SOSP'19

[Consensus][Notary: A Device for Secure Transaction Approval](https://pdos.csail.mit.edu/papers/notary:sosp19.pdf). Anish Athalye, Adam Belay, Frans Kaashoek, Robert Morris, Nickolai Zeldovich.  SOSP'19

## VLDB
[Storage][ForkBase: An Efficient Storage Engine for Blockchain and Forkable Applications](http://www.vldb.org/pvldb/vol11/p1137-wang.pdf). Sheng Wang, Tien Tuan Anh Dinh, Qian Lin, Zhongle Xie, Meihui Zhang, Qingchao Cai, Gang Chen, Beng Chin Ooi, Pingcheng Rua. VLDB'18. 

[Privacy][A Demonstration of Sterling: A Privacy-Preserving Data Marketplace](http://www.vldb.org/pvldb/vol11/p2086-hynes.pdf). Nick Hynes1, David Dao, David Yan, Raymond Cheng, Dawn Song. VLDB'19. 

[Application][CAPER: A Cross-Application Permissioned Blockchain](http://www.vldb.org/pvldb/vol12/p1385-amiri.pdf). Mohammad Javad Amiri, Divyakant Agrawal, Amr El Abbadi. VLDB'19. 

[Application][BlockchainDB - A Shared Database on Blockchains](http://www.vldb.org/pvldb/vol12/p1597-el-hindi.pdf). Muhammad El-Hindi,
Carsten Binnig, Arvind Arasu, Donald Kossmann, Ravi Ramamurthy. VLDB'19.

[Provenance][Fine-Grained, Secure and Efficient Data Provenance on Blockchain Systems](http://www.vldb.org/pvldb/vol12/p975-ruan.pdf). Pingcheng Ruan, Gang Chen, Tien Tuan Anh Dinh, Qian Lin, Beng Chin Ooi, Meihui Zhang. VLDB'19. 

[Application][Blockchain Meets Database: Design and Implementation of a Blockchain Relational Database](http://www.vldb.org/pvldb/vol12/p1539-nathan.pdf). Senthil Nathan, Chander Govindarajan, Adarsh Saraf, Manish Sethi, and Praveen Jayachandran. VLDB'19.

## SRDS
[Consensus][Bloxy: Providing Transparent and Generic BFT-Based Ordering Services for Blockchains](https://www.researchgate.net/publication/340304077_Bloxy_Providing_Transparent_and_Generic_BFT-Based_Ordering_Services_for_Blockchains).Signe Rüsch, Rüdiger Kapitza and Kai Bleeke. SRDS '19.

[Application][Blockchain-based Metadata Protection for Archival Systems](https://ieeexplore.ieee.org/document/9049624).	Arnaud L'Hutereau, Dorian Burihabwa, Pascal Felber, Hugues Mercier and Valerio Schiavoni. SRDS '19.

[Application][Trusted Computing meets Blockchain: Rollback Attacks and a Solution for Hyperledger Fabric](https://ieeexplore.ieee.org/document/9049585). Marcus Brandenburger, Christian Cachin, Rüdiger Kapitza and Alessandro Sorniotti. SRDS '19

## PODC
[Consensus-PoW] [FruitChains: A Fair Blockchain](https://eprint.iacr.org/2016/916.pdf).Rafael Pass, Elaine Shi. PODC'17

[Sidechain] [Atomic Cross-Chain Swaps](https://arxiv.org/abs/1801.09515). Maurice Herlihy. PODC'18

[Consessus] [Brief Announcement: Sustainable Blockchains through Proof of eXercise](https://haslab.uminho.pt/ashoker/files/pox-podc.pdf). Ali Shoker. PODC'18

[Consensus][The Consensus Number of a Cryptocurrency](https://arxiv.org/pdf/1906.05574.pdf). R. Guerraoui, P. Kuznetsov, M. Monti, M. Pavlovic, D. Seredinschi. PODC'19

[Consensus-BFT][Communication Complexity of Byzantine Agreement, Revisited](https://arxiv.org/abs/1805.03391). I. Abraham, T. Chan, D. Dolev, K. Nayak, R. Pass, L. Ren, E. Shi. PODC'19

[Consensus-BFT][Exact Byzantine Consensus on Undirected Graphs under Local Broadcast Model](https://arxiv.org/pdf/1903.11677.pdf). M. Khan, S. Naqvi, N. Vaidya. PODC'19

[Consensus-BFT][Asymptotically Optimal Validated Asynchronous Byzantine Agreement](https://research.vmware.com/files/attachments/0/0/0/0/0/7/8/practical_aba_2_.pdf). I. Abraham, D. Malkhi, A. Spiegelman. PODC'19

[Consensus-BFT][HotStuff: BFT Consensus with Linearity and Responsiveness](https://www.cs.unc.edu/~reiter/papers/2019/PODC.pdf). M. Yin, I. Abraham, G. Gueta, D. Malkhi, M. Reiter. PODC'19

## CCS
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

[Economic][The Gap Game](http://delivery.acm.org/10.1145/3250000/3243737/p713-tsabary.pdf?ip=142.231.81.31&id=3243737&acc=ACTIVE%20SERVICE&key=FD0067F557510FFB%2E26E2C50968A06846%2E4D4702B0C3E38B35%2E4D4702B0C3E38B35&__acm__=1572896863_842d24816daa8481df9c256f8a9cb16d). Itay Tsabary, Ittay Eyal. CCS '18.

[Payment Networks] [General State Channel Networks](https://eprint.iacr.org/2018/320.pdf) Dziembowski S, Faust S, Hostáková K. CCS '18.

[System Design] [FairSwap: How to fairly exchange digital goods](https://eprint.iacr.org/2018/740) Dziembowski S, Faust S, Eckey L. CCS '18.

[System] [RapidChain: Scaling Blockchain via Full Sharding](https://eprint.iacr.org/2018/460.pdf). Mahdi Zamani, Mahnush Movahedi, Mariana Raykova. CCS '18.

[Consensus][BEAT: Asynchronous BFT Made Practical](https://www.csee.umbc.edu/~hbzhang/files/beat.pdf). Sisi Duan, Michael K. Reiter, Haibin Zhang. CCS '18.

[Consensus Applcation][Efficient Publicly Verifiable 2PC over a Blockchain with Applications to Financially-Secure Computations](http://homes.sice.indiana.edu/yh33/mypub/pvc.pdf).	Ruiyu Zhu, Changchang Ding, Yan Huang. CCS '19.

[Network][Erlay: Efficient Transaction Relay for Bitcoin](https://arxiv.org/abs/1905.10518).	Gleb Naumenko, Gregory Maxwell, Pieter Wuille, Alexandra (Sasha) Fedorova, Ivan Beschastnikh. CCS '19.

[Sidechain][HyperService: Interoperability and Programmability across Heterogeneous Blockchains](https://arxiv.org/abs/1908.09343).	Zhuotao Liu, Yangxi Xiang,Jian Shi, Peng Gao, Haoyu Wang, Xusheng Xiao, Bihan Wen, Yih-Chun Hu. CCS '19.

[Cryptography][MatRiCT: Efficient, Scalable and Post-Quantum Blockchain Confidential Transactions Protocol](https://eprint.iacr.org/2019/1287.pdf).	Muhammed F. Esgin, Raymond K. Zhao, Ron Steinfeld, Joseph K. Liu, Dongxi Liu. CCS '19. 

[Payment][Omniring: Scaling Up Private Payments Without Trusted Setup — Formal Foundations and a Construction of Ring Confidential Transactions with Log-size Proofs]().	Russell W. F. Lai, Viktoria Ronge, Tim Ruffing, Dominique Schröder, Sri Aravinda Krishnan Thyagarajan, Jiafan Wang. CCS '19. 

[Consensus][Prism: Deconstructing the Blockchain to Approach Physical Limits](https://dl.acm.org/doi/abs/10.1145/3319535.3345655?download=true).	Vivek Bagaria, Sreeram Kannan, David Tse, Giulia Fanti, Pramod Viswanath. CCS '19. 

[Smart contract][Learning to Fuzz from Symbolic Execution with Application to Smart Contracts](https://files.sri.inf.ethz.ch/website/papers/ccs19-ilf.pdf).	Jingxuan He, Mislav Balunovic, Nodar Ambroladze, Petar Tsankov, Martin Vechev. CCS '19. 

[Ledger][SAMPL: Scalable Auditability of Monitoring Processes using Public Ledgers](https://www.cs.nmsu.edu/~roopa/sampl.pdf). Roopa Vishwanathan, Gaurav Panwar, Satyajayant Misra, Austin Bos. CCS '19. 

[Payment Networks][Atomic Multi-Channel Updates with Constant Collateral in Payment-Channel Networks](https://eprint.iacr.org/2019/583.pdf). Christoph Egger, Pedro Moreno-Sanchez, Matteo Maffei. CCS '19. 

[Payment][Security Analysis and Implementation of Relay-Resistant Contactless Payments](). Ioana Boureanu, Tom Chothia, Alexandre Debant, Stéphanie Delaune CCS '20.

[Smart Contract][ACE: Asynchronous and Concurrent Execution of Complex Smart Contracts](). Karl Wüst, Sinisa Matetic, Silvan Egli, Kari Kostiainen, Srdjan Capkun. CCS '20.

[Transactions][Pointproofs: Aggregating Proofs for Multiple Vector Commitments](). Sergey Gorbunov, Leonid Reyzin, Hoeteck Wee, Zhenfei Zhang. CCS '20.

[Mining][BDoS: Blockchain Denial-of-Service Attacks](). Michael Mirkin, Yan Ji, Jonathan Pang, Ariah Klages-Mundt, Ittay Eyal, Ari Juels. CCS '20.

[Consensus][Blinder -- Scalable, Robust Anonymous Committed Broadcast](). Avishay Yanai, Ittai Abraham, Benny Pinkas. CCS '20.

[Consensus][Dumbo: Faster Asynchronous BFT Protocols](). Bingyong Guo; Zhenliang Lu, Jing Xu, Zhenfeng Zhang.  CCS '20.

[Consensus][On the Optimality of Optimistic Responsiveness](). Ittai Abraham, Kartik Nayak, Ling Ren, Nibesh Shrestha. CCS '20.

[Cryptography][Asynchronous Distributed Key Generation for Computationally Secure Randomness, Consensus, and Threshold Signatures](). 
Eleftherios Kokoris Kogias; Dahlia Malkhi; Alexander Spiegelman. CCS '20.

[Consensus][Everything is a Race and Nakamoto Always Wins](). Xuechao Wang, Ertem Nusret Tas, David Tse, Amir Dembo, Sreeram Kannan, Ofer Zeitouni, Pramod Viswanath. CCS '20.

[Consensus][Tight Consistency Bounds for Bitcoin](). Peter Gaži, Aggelos Kiayias, Alexander Russell. CCS '20.

## IPDPS
[Consensus][G-PBFT: A Location-based and Scalable Consensus Protocol for IoT-Blockchain Applications](http://www4.comp.polyu.edu.hk/~csbxiao/paper/2020/IPDPS_GPBFT_2020.pdf). LapHou Lao, Xiaohai Dai, Bin Xiao, and Songtao Guo. IPDPS '20.

[BFT][Byzantine Generalized Lattice Agreement](https://arxiv.org/pdf/1910.05768.pdf). Giuseppe Antonio Di Luna, Emmanuelle Anceaume, and Leonardo Querzoni. IPDPS '20. 


## SIGMOD
[Measurement][BLOCKBENCH: A Framework for Analyzing Private Blockchains](https://www.comp.nus.edu.sg/~ooibc/blockbench.pdf). Tien Tuan Anh Dinh, Ji Wang, Gang Chen, Rui Liu, Beng Chin Ooi, Kian-Lee Tan. SIGMOD '17.

[Database][Blurring the Lines between Blockchains and Database Systems: the Case of Hyperledger Fabric](https://dl.acm.org/doi/pdf/10.1145/3299869.3319883?download=true). Ankur Sharma, Felix Martin Schuhknecht, Divya Agrawal, Jens Dittrich. SIGMOD '19.

[Database][vChain: Enabling Verifiable Boolean Range Queries over Blockchain Databases](https://arxiv.org/pdf/1812.02386.pdf).Cheng Xu, Ce Zhang, Jianliang Xu. SIGMOD '19.

[Consensus-sharding][Towards Scaling Blockchain Systems via Sharding](https://www.comp.nus.edu.sg/~hungdang/papers/sharding.pdf). Hung Dang, Tien Tuan Anh Dinh, Dumitrel Loghin, Ee-Chien Chang, Qian Lin, and Beng Chin Ooi. SIGMOD '19.

[Database][Confidentiality Support over Financial Grade Consortium Blockchain](https://dl.acm.org/doi/abs/10.1145/3318464.3386127). Yan, YingWei, Changzheng Guo, Xuepeng Lu, Xuming Zheng, Xiaofu Liu, Qi Zhou, Chenhui Song, Xuyang Zhao, Boran Zhang, Hui Jiang, Guofei. SIGMOD '20.

## SPAA
[Consensus-DAG][Why BlockDAGs Excel Blockchains](https://tik-db.ee.ethz.ch/file/b0a2132681958e4cb69055bab4bf6ad8/The_Append_Memory_Model.pdf).	Darya Melnyk and Roger Wattenhofer. SPAA' 20

[Consensus-BFT][Fast Byzantine Agreement for Permissioned Distributed Ledgers](https://dl.acm.org/doi/pdf/10.1145/3350755.3400219).	Thomas Locher. SPAA' 20

## INFOCOM
[Network][Stochastic Models and Wide-Area Network Measurements for Blockchain Design and Analysis](https://www.researchgate.net/publication/321369565_Stochastic_Models_and_Wide-Area_Network_Measurements_for_Blockchain_Design_and_Analysis). Nikolaos Papadis, Sem Borst, Anwar Walid, Mohamed Grissa, Leandros Tassiulas. INFOCOM'18

[Transaction][Understanding ethereum via graph analysis](https://www4.comp.polyu.edu.hk/~csxluo/EthereumGraphAnalysis.pdf). Ting Chen,Yuxiao Zhu, Zihao Li, Jiachi Chen, Xiaoqi Li, Xiapu Luo, Xiaodong Lin, Xiaodong Lin. INFOCOM'18

[Security][Corking by Forking: Vulnerability Analysis of Blockchain](https://ieeexplore.ieee.org/document/8737490). Shengling Wang and Chenyu Wang, Qin Hu. INFOCOM'19

[Scalability][ACCEL: Accelerating the Bitcoin Blockchain for High-throughput, Low-latency Applications](https://ieeexplore.ieee.org/document/8737556). Adiseshu Hari, Murali Kodialam, T. V Lakshman. INFOCOM'19

[Application][A Blockchain based Witness Model for Trustworthy Cloud Service Level Agreement Enforcement](https://ieeexplore.ieee.org/document/8737580). Huan Zhou, Xue Ouyang,  Zhijie Ren, Jinshu Su, Cees de Laat and Zhiming Zhao. INFOCOM'19

[Network][Modeling the Impact of Network Connectivity on Consensus Security of Proof-of-Work Blockchain](https://www.cnsr.ictas.vt.edu/publication/Modeling_Yang.pdf).
Yang Xiao, Ning Zhang, Wenjing Lou and Thomas Hou. INFOCOM'20

[Off-chain][Secure Balance Planning of Off-blockchain Payment Channel Networks](https://www.u-aizu.ac.jp/~pengli/files/pcn_planning_infocom2020.pdf). Peng Li and Toshiaki Miyazaki, Wanlei Zhou. INFOCOM'20. 


[Consensus][A Weak Consensus Algorithm and Its Application to High-Performance Blockchain](). Qin Wang, Rujia Li. INFOCOM'21.  

[Mining][Characterizing Ethereum's Mining Power Decentralization at a Deeper Level](). Liyi Zeng, Yang Chen, Shuo Chen, Xian Zhang, Zhongxin Guo, Wei Xu, Thomas Moscibroda. INFOCOM'21.  

[Consensus][On the Performance of Pipelined HotStuff](). Jianyu Niu, Fangyu Gai, Mohammad Jalalzai, Chen Feng. INFOCOM'21.

## ICDCS
[Application] [Transform Blockchain into Distributed Parallel Computing Architecture for Precision Medicine](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8416392).Zonyin Shae, Jeffrey J.P. Tsai. ICDCS'18

[PoW][Selfish Mining in Ethereum](https://arxiv.org/abs/1901.04620) Jianyu Niu and Chen Feng. ICDCS'19

[Consensus][Trust Mends Blockchains: Living up to Expectations](http://kth.diva-portal.org/smash/get/diva2:1316199/FULLTEXT01.pdf). Leila Bahri and Sarunas Girdzijauskas. ICDCS'19

[Application][Hierarchical Edge-Cloud Computing for Mobile Blockchain Mining Game](https://pdfs.semanticscholar.org/cfe0/77c9b880c2a0dfb495448a068fdf1db07b6e.pdf). Suhan Jiang, Xinyi Li and Jie Wu. ICDCS'19

[Scalability][OptChain: Optimal Transactions Placement for Scalable Blockchain Sharding](http://optnetsci.cise.ufl.edu/papers/icdcs19truc.pdf). Lan Nguyen, Truc Nguyen, Thang Dinh and My Thai. ICDCS'19

[Consensus][Jidar: A Jigsaw-like Data Reduction Approach without Trust Assumptions for Bitcoin System](https://www.researchgate.net/publication/336945962_Jidar_A_Jigsaw-like_Data_Reduction_Approach_Without_Trust_Assumptions_for_Bitcoin_System). Xiaohai Dai, Jiang Xiao, Wenhui Yang, Chaofan Wang and Hai Jin. ICDCS'19

[Scalability][ParBlockchain: Leveraging Transaction Parallelism in Permissioned Blockchain Systems](https://arxiv.org/pdf/1902.01457.pdf). Mohammad Javad Amiri, Divyakant Agrawal and Amr El Abbadi. ICDCS'19

[Application][Optimal Admission Control For Secondary Users using Blockchain Technology In Cognitive Radio Networks](https://ieeexplore.ieee.org/document/8885039). Wenlong Ni, Yuhong Zhang and Wei Li. ICDCS'19

[Application][Resource Allocation and Consensus on Edge Blockchain in Pervasive Edge Computing Environments](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8884875). Yaodong Huang, Jiarui Zhang, Jun Duan, Bin Xiao, Fan Ye and Yuanyuan Yang. ICDCS'19

[Application][Xyreum: A High-Performance and Scalable Blockchain for IIoT Security and Privacy](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8885084). Abubakar Sadiq Sani, Dong Yuan, Wei Bao, Phee Lep Yeoh, Zhaoyang Dong, Branka Vucetic and Elisa Bertino. ICDCS'19

[Consensus-PoS][Consistency of Proof-of-Stake Blockchains with Concurrent Honest Slot Leaders](https://arxiv.org/abs/2001.06403). Aggelos Kiayias, Saad Quader, Alexander Russell. ICDCS'20

[Network][Fair and Efficient Gossip in Hyperledger Fabric](https://arxiv.org/pdf/2004.07060.pdf). Nicolae Berendea, Hugues Mercier, Emanuel Onica, Etienne Rivière. ICDCS'20

[PoW][An Analysis of Blockchain Consistency in Asynchronous Networks: Deriving a Neat Bound](https://arxiv.org/abs/1909.06587). Jun Zhao, Jing Tang, Li Zengxiang, Huaxiong Wang, Kwok-Yan Lam, Kaiping Xue. ICDCS'20

## NSDI
[Consensus-PoW] [Bitcoin-NG: A Scalable Blockchain Protocol](https://www.usenix.org/system/files/conference/nsdi16/nsdi16-paper-eyal.pdf). Eyal I, Gencer AE, Sirer EG, Van Renesse R. NSDI ’16

[System][Monoxide: Scale Out Blockchain with Asynchronized Consensus Zones](https://www.usenix.org/system/files/nsdi19-wang-jiaping.pdf). Jiaping Wang, Hao Wang. NSDI'19

[Network][High Throughput Cryptocurrency Routing in Payment Channel Networks](https://www.usenix.org/system/files/nsdi20-paper-sivaraman.pdf). Vibhaalakshmi Sivaraman, Shaileshh Bojja Venkatakrishnan, Kathleen Ruan, Parimarjan Negi and Lei Yang, Radhika Mittal, Giulia Fanti, Mohammad Alizadeh. NSDI ’20

## OSDI
[System][Blockene: A High-throughput Blockchain Over Mobile Devices](https://arxiv.org/pdf/2010.07277). Sambhav Satija and Apurv Mehra, Sudheesh Singanamalla, Karan Grover, Muthian Sivathanu, Nishanth Chandran, Divya Gupta, and Satya Lokam. OSDI'20 

[Consensus][Byzantine ordered consensus without Byzantine oligarchy](https://www.microsoft.com/en-us/research/uploads/prod/2020/10/paper-5f89e2898ee53.pdf) Yunhao Zhang, Srinath Setty, Qi Chen, and Lidong Zhou, Lorenzo Alvisi. OSDI'20 

## DSN
[Smart Contract][FabZK: Supporting Privacy-Preserving, Auditable Smart Contracts in Hyperledger Fabric](). Hui Kang, Ting Dai, Nerla Jean-Louis and Shu Tao. Xiaohui Gu.  DSN '19

[Consensus-BFT][SBFT: a Scalable and Decentralized Trust Infrastructure](). Guy Golan Gueta, Ittai Abraham, Shelly Grossman, Dahlia Malkhi, Benny Pinkas, Michael K. Reiter, Dragos-Adrian Seredinschi, Orr Tamir, Alin Tomescu.  DSN '19

[Payment Channel][FSTR: Funds Skewness aware Transaction Routing for Payment Channel Networks](). Siyi Lin, Jingjing Zhang, Weigang Wu. DSN '20

[Incentive][On Incentive Compatible Role-based Reward Distribution in Algorand](https://arxiv.org/abs/1911.03356). Mehdi Fooladgar, Mohammad Hossein Manshaei, Murtuza Jadliwala, Mohammad Ashiqur Rahman.  DSN '20

[Consensus-BFT][EPIC: Efficient Asynchronous BFT with Adaptive Security]().Chao Liu, Sisi Duan, Haibin Zhang. DSN '20 

[Smart Contract][SMACS: Smart Contract Access Control Service](https://arxiv.org/abs/2003.07495). Bowen Liu, Siwei Sun, Pawel Szalachowski. DSN '20

[Incentive][Data-Driven Model-Based Analysis of the Ethereum Verifier's Dilemma](https://arxiv.org/pdf/2004.12768.pdf). Maher Alharby, Roben Lunardi, Amjad Aldweesh, Aad van Moorsel. DSN '20

[Smart Contract][Smart Contracts on the Move](https://arxiv.org/pdf/2004.05933.pdf). Enrique Fynn, Alysson Bessani, Fernando Pedone. DSN '20 

[Consensus][From Byzantine Replication to Blockchain: Consensus is only the Beginning](https://arxiv.org/pdf/2004.14527.pdf). Alysson Bessani, Eduardo Alchieri, João Sousa, André Oliveira, Fernando Pedone. DSN '20

[Payment Channel][Online Payments by Merely Broadcasting Messages](https://arxiv.org/pdf/2004.13184.pdf). Daniel Collins, Rachid Guerraoui, Jovan Komatovic, Petr Kuznetsov, Matteo Monti, Matej Pavlovic, Yvonne-Anne Pignolet, Dragos-Adrian Seredinschi, Andrei Tonkikh, Athanasios Xygkis.  DSN '20 


## CoNEXT
[Consensus-PoW] [On the Necessity of a Prescribed Block Validity Consensus: Analyzing Bitcoin Unlimited Mining Protocol](https://eprint.iacr.org/2017/686.pdf). Ren Zhang, Bart Preneel. CoNEXT '17

[Consensus][Stellar: Network Attack Mitigation using Advanced Blackholing](https://www.de-cix.net/Files/2731074c857497be3827ac9537b6e486f27aa57c/Research-paper-Stellar-Network-Attack-Mitigation-using-Advanced-Blackholing.pdf)(.Christoph Dietzel, Matthias Wichtlhuber, Georgios Smaragdakis, Anja Feldmann. CoNEXT '18

[Mining][Mining the Web with Webcoin](http://networks.cs.northwestern.edu/publications/webcoin/conext18-final22.pdf). Uri Klarman, Marcel Flores, Aleksandar Kuzmanovic. CoNEXT '18

[Application][Blockchain-based Real-time Cheat Prevention and Robustness for Multi-player Online Game](https://dl.acm.org/doi/10.1145/3281411.3281438). Sukrit Kalra, Rishabh Sanghi, Mohan Dhawan. CoNEXT '18

[Layer2][Flash: Efficient Dynamic Routing for Offchain Networks](http://www.cs.jhu.edu/~xinjin/files/CoNEXT19_Flash.pdf). Peng Wang, Hong Xu, Xin Jin, Tao Wang.  CoNEXT '19

## PLDI
[Smart Contract][Behavioral Simulation for Smart Contracts](). Sidi Mohamed Beillahi, Gabriela Ciocarlie, Michael Emmi, Constantin Enea. PLDI '2020

[Smart Contract][Ethainter: A Smart Contract Security Analyzer for Composite Vulnerabilities](). Lexi Brent, Neville Grech, Sifis Lagouvardos, Bernhard Scholz, Yannis Smaragdakis. PLDI '2020

[Smart Contract][Securing Smart Contract with Runtime Validation](). Ao Li, Jemin Andrew Choi, Fan Long. PLDI '2020

[Smart Contract][Practical Smart Contract Sharding with Ownership and Commutativity Analysis]() George Pîrlea, Amrit Kumar, Ilya Sergey. PLDI '2021


## FC
[Economic-PoW] [Majority Is Not Enough: Bitcoin Mining Is Vulnerable](https://arxiv.org/pdf/1311.0243). Eyal I, Sirer EG. FC '14.

[Consensus-PoW] [Secure High-Rate Transaction Processing in Bitcoin](http://www.cs.huji.ac.il/~avivz/pubs/15/btc_ghost_full.pdf). Sompolinsky Y, Zohar A. FC '15.

[ChainStructure][Inclusive Block Chain Protocols](https://fc15.ifca.ai/preproceedings/paper_101.pdf). Yoad Lewenberg, Yonatan Sompolinsky, Aviv Zohar. FC '15.

[Consensus] [Cryptocurrencies without Proof of Work](http://fc16.ifca.ai/bitcoin/papers/BGM16.pdf). Bentov I, Gabizon A, Mizrahi A. FC '16.

[Economic-PoW] [Optimal Selfish Mining Strategies in Bitcoin](http://fc16.ifca.ai/preproceedings/30_Sapirshtein.pdf). Sapirshtein A, Sompolinsky Y, Zohar A. FC '16.

[Consensus-PoS] [A Proof-of-Stake protocol for consensus on Bitcoin subchains](http://eprint.iacr.org/2017/417.pdf). Bartoletti M, Lande S, & Podda A S. FC '17.

[FC Accepted Paper Link:] [FC'15](https://fc15.ifca.ai/schedule.html), [FC'16](https://fc16.ifca.ai/program.html), [FC'17](https://fc17.ifca.ai/program.html), [FC'18](https://fc18.ifca.ai/program.html), [FC'19](https://fc19.ifca.ai/program.html). [FC'20](https://fc20.ifca.ai/). [FC'21](https://fc21.ifca.ai/).

## EC
[Economic-PoW] [An Economic Analysis of Difficulty Adjustment Algorithms in Proof-of-Work Blockchain Systems](https://econ.hkbu.edu.hk/eng/Doc/Shunya_NODA_POW.pdf). Shunya Noda, Kyohei Okumura and Yoshinori Hashimoto. EC '20.

## License
[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)


This list is released into the public domain.
