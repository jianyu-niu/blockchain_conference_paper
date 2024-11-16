# Academic Blockchain Conference Papers
A curated list of blockchain-related academic papers. All papers are sorted based on the conference name and published year.
Welcome developers or researchers to add more published papers to this list. 

## Table of Listed Conferences
|     Security & Privacy & Crypto     |               Networking & Database               | Software Engineering & Programming Language | System Architecture  |
| :---------------------------------: | :-----------------------------------------------: | :-----------------------------------------: | :------------------: |
|          [CRYPTO](#crypto)          | [SIGMETRICS & Performance](#sigmetricperformance) |                [ICSE](#icse)                |  [ACM SOSP](#sosp)   |
|       [EUROCRYPT](#eurocrypt)       |                   [ICDE](#icde)                   |            [ESEC/FSE](#esecfse)             |  [USENIX OSDI](#osdi) |
| [USENIX Security](#usenix-security) |                   [VLDB](#vldb)                   |                 [ASE](#ase)                 |  [EuroSys](#eurosys) |
|           [IEEE S&P](#sp)           |               [ACM SIGMOD](#sigmod)               |              [ACM PLDI](#pldi)              |  [EuroS&P](#eurosp)  |
|            [NDSS](#ndss)            |             [IEEE INFOCOM](#infocom)              |            [ACM OOPSLA](#oopsla)            |  [SRDS](#srds)       |
|           [ACM CCS](#ccs)           |                   [NSDI](#nsdi)                   |                [ACM EC](#ec)                |  [ACM PODC](#podc)   |
|             [IEEE DSN](#dsn)        |               [ACM CoNEXT](#conext)               |               [ISSTA](#issta)               |  [IEEE IPDPS](#ipdps) |
|              [FC](#fc)              |              [ACM MobiHoc](#mobihoc)              |              [ACM POPL](#popl)              |  [IEEE ICDCS](#icdcs) |
|            [IMC](#imc)              |                                                   |              [APACSCI ABER](#aber)          |  [ACM SOCC](#socc)   |

<!--
## Table of Listed Journals
- [IEEE Transaction on Knowledger and Data Engineering(TKDE)](#tkde)
- [ACM Computing Surveys (ACM CSUR)](#acmcsur)
- [ACM Distributed Ledger Technologies: Research and Practice (ACM DLT)](#acmdlt)
- [IEEE Journal on Selected Areas in Communications](#jsac)
- [IEEE Transactions on Network Science and Engineering](#tnse)
Key Words: Topics: System Architecture, Consensus(Proof-of-X and BFT), Layer 2 (Off-chain, Payment Networks, Sidechain, Crosschain), Network, Smart Contracts, Application (Trasactions), Cryptograph, Storage (light client); Contents: privacy, security, economics (incentive).
-->

## CRYPTO
[The Bitcoin Backbone Protocol with Chains of Variable Difficulty](https://eprint.iacr.org/2016/1048). Juan A. Garay and Aggelos Kiayias and Nikos Leonardos. Crypto '17.

[Ouroboros Praos: An adaptively-secure, semi-synchronous proof-of-stake protocol](http://eprint.iacr.org/2017/573.pdf). Bernardo D, Gazi P, Kiayias A, Russell A. Crypto '17.

[Order-Fairness for Byzantine Consensus](https://eprint.iacr.org/2020/269.pdf) Mahimna Kelkar,Fan Zhang,Ari Juels. Crypto '20.

## EUROCRYPT
[Consensus-PoW] [The Bitcoin Backbone Protocol: Analysis and Applications](https://eprint.iacr.org/2014/765.pdf). Garay J, Kiayias A, Leonardos N. EUROCRYPT '15.

[Consensus-PoW] [Analysis of the Blockchain Protocol in Asynchronous Networks](https://eprint.iacr.org/2016/454.pdf). Pass R, Seeman L, abhi shelat. EUROCRYPT '17

[Consensus][Thunderella: Blockchains with Optimistic Instant Confirmation](https://eprint.iacr.org/2017/913.pdf). Rafael Pass, Elaine Shi. EUROCRYPT '18.

[Consensus-PoS][Ouroboros Praos: An adaptively-secure, semi-synchronous proof-of-stake blockchain](https://eprint.iacr.org/2017/573.pdf). Bernardo David, Peter Gaži, Aggelos Kiayias, Alexander Russell. EUROCRYPT '18. 

[Consensus][Consensus through Herding](https://link.springer.com/content/pdf/10.1007%2F978-3-030-17653-2_24.pdf). T-H. Hubert Chan Rafael Pass Elaine Shi. EUROCRYPT '19. 

[Consensus-PoS][Proof-of-Stake Protocols for Privacy-Aware Blockchains](https://link.springer.com/content/pdf/10.1007%2F978-3-030-17653-2_23.pdf). Chaya Ganesh Claudio Orlandi Daniel Tschudi. EUROCRYPT '19. 

[Payment Channel][Multi-Party Virtual State Channels](https://link.springer.com/content/pdf/10.1007%2F978-3-030-17653-2_21.pdf). Stefan Dziembowski Lisa Eckey Sebastian Faust Julia Hesse Kristina Hostáková. EUROCRYPT '19. 

[Cryptography-Privacy][Aggregate Cash Systems: A Cryptographic Investigation of Mimblewimble](https://link.springer.com/content/pdf/10.1007%2F978-3-030-17653-2_22.pdf). Georg Fuchsbauer Michele Orrù Yannick Seurin. EUROCRYPT '19. 

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

[Smart Contract][Semantic Understanding of Smart Contracts: Executable Operational Semantics of Solidity](https://ieeexplore.ieee.org/document/9152785). Jiao, Jiao, Shuanglong Kan, Shang-Wei Lin, David Sanan, Yang Liu, and Jun Sun. IEEE S&P '20

[Exchange][High-Frequency Trading on Decentralized On-Chain Exchanges]() Liyi Zhou, Kaihua Qin, Christof Ferreira Torres, Duc V Le, Arthur Gervais, Tyler Crain, Christopher Natoli, Vincent Gramoli. IEEE S&P '21.  

[Payment][A2L: Anonymous Atomic Locks for Scalability in Payment Channel Hubs]() Erkan Tairi, Pedro Moreno-Sanchez, Matteo Maffei. IEEE S&P '21. 

[Consensus][Ebb-and-Flow Protocols: A Resolution of the Availability-Finality Dilemma]() Joachim Neu, Ertem Nusret Tas, David Tse. IEEE S&P '21.  

[Sidechain][MAD-HTLC: Because HTLC is Crazy-Cheap to Attack]() Itay Tsabary, Matan Yechieli, Alex Manuskin, Ittay Eyal. IEEE S&P '21.  

[PoS][On the Anonymity Guarantees of Anonymous Proof-of-Stake Protocols]() Varun Madathil, Alessandra Scafuro, Kartik Nayak, Markulf Kohlweiss. IEEE S&P '21. 

[Defi][On the Just-In-Time Discovery of Profit-Generating Transactions in DeFi Protocols]() Liyi Zhou, Kaihua Qin, Antoine Cully, Benjamin Livshits, Arthur Gervais. IEEE S&P '21. 

[Smart Contract][SGUARD: Smart Contracts Made Vulnerability-Free]() Long H. Pham, Jun Sun, Tai Duy Nguyen. IEEE S&P '21. 

[Consensus][Red Belly: A Secure, Fair and Scalable Open Blockchain]() Tyler Crain, Christopher Natoli, Vincent Gramoli. IEEE S&P '21.

[Smart Contract][ZeeStar: Private Smart Contracts by Homomorphic Encryption and Zero-knowledge Proofs]() Samuel Steffen, Benjamin Bichsel, Roger Baumgartner, Martin Vechev. IEEE S&P '22.

[Smart Contract][SAILFISH: Vetting Smart Contract State-Inconsistency Bugs in Seconds]() Priyanka Bose, Dipanjan Das, Yanju Chen, Yu Feng, Christopher Kruegel, Giovanni Vigna. IEEE S&P '22.

[Payment][MatRiCT+: More Efficient Post-Quantum Private Blockchain Payments]() Muhammed F. Esgin, Ron Steinfeld, Raymond K. Zhao. IEEE S&P '22.

[Security][Quantifying Blockchain Extractable Value:How dark is the forest?]() Kaihua Qin, Liyi Zhou, Arthur Gervais. IEEE S&P '22.

[Exchange][Universal Atomic Swaps: Secure Exchange of Coins Across All Blockchains]() Sri AravindaKrishnan Thyagarajan, Giulio Malavolta, Pedro Moreno-Sanchez. IEEE S&P '22.

[Consensus][Using Throughput-Centric Byzantine Broadcast to Tolerate Malicious Majority in Blockchains]() Ruomu Hou, Haifeng Yu, Prateek Saxena. IEEE S&P '22.

[Consensus][Foundations of Dynamic BFT](https://eprint.iacr.org/2022/597) Sisi Duan, Haibin Zhang. IEEE S&P '22.

[Smart Contract][Clockwork Finance: Automated Analysis of Economic Security in Smart Contracts]() Kushal Babel, Philip Daian, Mahimna Kelkar, Ari Juels. IEEE S&P '23.

[Mining][WeRLman: To Tackle Whale (Transactions), Go Deep (RL)](). Roi Bar-Zur, Ameer Abu-Hanna, Ittay Eyal, Aviv Tamar. IEEE S&P '23. 

[Consensus][Bitcoin-Enhanced Proof-of-Stake Security: Possibilities and Impossibilities](). Ertem Nusret Tas, David Tse, Fangyu Gai, Sreeram Kannan, Mohammad Ali Maddah-Ali, Fisher Yu. IEEE S&P '23.

[Channel][BlindHub: Bitcoin-Compatible Privacy-Preserving Payment Channel Hubs Supporting Variable Amounts](). Xianrui Qin, Shimin Pan, Arash Mirzaei, Zhimei Sui, Oguzhan Ersoy, Amin Sakzad, Muhammed Esgin, Joseph.  IEEE S&P '23.

[Consensus][Tyr: Finding Consensus Failure Bugs in Blockchain System with Behaviour Divergent Model](). Yuanliang Chen, Fuchen Ma, Yuanhang Zhou, Yu Jiang, Ting Chen, Jiaguang Sun. IEEE S&P '23. 

[Consensus][Optimistic Fast Confirmation While Tolerating Malicious Majority in Blockchains](). Ruomu Hou, Haifeng Yu. IEEE S&P '23.

[Contracts][Clockwork Finance: Automated Analysis of Economic Security in Smart Contracts](). Kushal Babel, Philip Daian, Mahimna Kelkar, Ari Juels. IEEE S&P '23.

[Cross-chain][Sweep-UC: Swapping Coins Privately](). Lucjan Hanzlik, Julian Loss, Sri AravindaKrishnan Thyagarajan, Benedikt Wagner. IEEE S&P '23.

[Crypto][Efficient Zero-Knowledge Arguments For Paillier Cryptosystem Paillier](). Borui Gong, Wang Fat Lau, Man Ho Au, Rupeng Yang, Haiyang Xue, Lichun Li. IEEE S&P '24.

[Consensus][Chronos: Finding Timeout Bugs in Practical Distributed Systems by Deep-Priority Fuzzing with Transient Delay](). Yuanliang Chen, Fuchen Ma, Yuanhang Zhou, Ming Gu, Qing Liao, Yu Jiang. IEEE S&P '24.

[Execution][Specular: Towards Secure, Trust-minimized Optimistic Blockchain Execution](). Zhe Ye, Ujval Misra, Jiajun Cheng, Andy Zhou, Dawn Song. IEEE S&P '24.

[Application][Conning the Crypto Conman: End-to-End Analysis of Cryptocurrency-based Technical Support Scams](). Bhupendra Acharya, Muhammad Saad, Antonio Emanuele Cinà, Lea Schönherr, Hoang Dai Nguyen, Adam Oest, Phani Vadrevu, Thorsten Holz. IEEE S&P '24.

[Storage][NURGLE: Exacerbating Resource Consumption in Blockchain State Storage via MPT Manipulation](). Zheyuan He, Zihao Li, Ao Qiao, Xiapu Luo, Xiaosong Zhang, Ting Chen, Shuwei Song, Dijun Liu, Weina Niu. IEEE S&P '24.

[Smart Contracts][Nyx: Detecting Exploitable Front-Running Vulnerabilities in Smart Contracts](). Wuqi Zhang, Zhuo Zhang, Qingkai Shi, Lu Liu, Lili Wei, Yepang Liu, Xiangyu Zhang, Shing-Chi Cheung. IEEE S&P '24.

[Consensus][Larger-scale Nakamoto-style Blockchains Don't Necessarily Offer Better Security](). Jannik Albrecht, Sebastien Andreina, Frederik Armknecht, Ghassan Karame, Giorgia Marson, Julian Willingmann. IEEE S&P '24.

[Smart Contracts][Large-Scale Study of Vulnerability Scanners for Ethereum Smart Contracts](). Christoph Sendner, Lukas Petzi, Jasper Stang, Alexandra Dmitrienko. IEEE S&P '24.

[Crypto][SwiftRange: A Short and Efficient Zero-Knowledge Range Argument For Confidential Transactions and More](). Nan Wang, Sid Chi-Kin Chau, DongXi Liu, Nan Wang, Sid Chi-Kin Chau. IEEE S&P '24.

[Crypto][Certifying Zero-Knowledge Circuits with Refinement Types](). Junrui Liu, Ian Kretz, Hanzhi Liu, Bryan Tan, Jonathan Wang, Yi Sun, Luke Pearson, Anders Miltner, IÅŸÄ±l Dillig, Yu Feng. IEEE S&P '24.

[Crypto][Ligetron: Lightweight Scalable End-to-End Zero-Knowledge Proofs. Post-Quantum ZK-SNARKs on a Browser](). Carmit Hazay, Muthuramakrishnan Venkitasubramaniam, Ruihan Wang. IEEE S&P '24.

[Crypto][Pianist: Scalable zkRollups via Fully Distributed Zero-Knowledge](). Tianyi Liu, Tiancheng Xie, Jiaheng Zhang, Dawn Song, Yupeng Zhang, Tianyi Liu, Yupeng Zhang. IEEE S&P '24.


## USENIX SECURITY
[Network-security] [Eclipse Attacks on Bitcoin's Peer-to-Peer Network](https://www.usenix.org/system/files/conference/usenixsecurity15/sec15-paper-heilman.pdf). Heilman E, Kendler A, Zohar A, Goldberg S. USENIX '15 Security Symposium.

[Consensus-PoW] [Enhancing Bitcoin Security and Performance with Strong Consistency via Collective Signing](https://www.usenix.org/system/files/conference/usenixsecurity16/sec16_paper_kokoris-kogias.pdf). Kogias EK, Jovanovic P, Gailly N, Khoffi I, Gasser L, Ford B. USENIX '16 Security Symposium.

[Mining][SmartPool: Practical Decentralized Pooled Mining](https://www.usenix.org/system/files/conference/usenixsecurity17/sec17-luu.pdf). Loi Luu,  Yaron Velner, Jason Teutsch, TrueBit Foundation; Prateek Saxena.USENIX '17 Security Symposium.

[Mining][REM: Resource-Efficient Mining for Blockchains](https://eprint.iacr.org/2017/179). Fan Zhang and Ittay Eyal and Robert Escriva and Ari Juels and Robbert van Renesse. USENIX '17 Security Symposium.

[Smart contract][teEther: Gnawing at Ethereum to Automatically Exploit Smart Contracts](https://www.usenix.org/system/files/conference/usenixsecurity18/sec18-krupp.pdf).Johannes Krupp and Christian Rossow. USENIX '18 Security Symposium.

[Anonymity Privacy][An Empirical Analysis of Anonymity in Zcash](https://www.usenix.org/system/files/conference/usenixsecurity18/sec18-kappos.pdf). George Kappos, Haaroon Yousaf, Mary Maller, and Sarah Meiklejohn. USENIX '18 Security Symposium.

[Smart contract][Arbitrum: Scalable, private smart contracts](https://www.usenix.org/system/files/conference/usenixsecurity18/sec18-kalodner.pdf). Harry Kalodner, Steven Goldfeder, Xiaoqi Chen, S. Matthew Weinberg,
and Edward W. Felten. USENIX '18 Security Symposium.

[Transaction Analysis][Tracing Transactions Across Cryptocurrency Ledgers](https://smeiklej.com/files/usenix19.pdf). Haaroon Yousaf, George Kappos, and Sarah Meiklejohn. USENIX '19 Security Symposium.

[Smart Contract][The Art of The Scam: Demystifying Honeypots in Ethereum SmartContracts](https://www.usenix.org/system/files/sec19-torres.pdf). ChristofFerreira Torres, Mathis Steichen, and Radu State, University of Luxembourg. USENIX '19 Security Symposium.

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

[Transaction][How to Peel a Million: Validating and Expanding Bitcoin Clusters]() George Kappos and Haaroon Yousaf, Rainer Stütz and Sofia Rollet, Bernhard Haslhofer, Sarah Meiklejohn. USENIX '22 Security Symposium. 

[Payment][Twilight: A Differentially Private Payment Channel Network]() Maya Dotan, Saar Tochner, Aviv Zohar, and Yossi Gilad. USENIX '22 Security Symposium. 

[Consensus][ACon^2: Adaptive Conformal Consensus for Provable Blockchain Oracles]() Sangdon Park, Osbert Bastani, and Taesoo Kim. USENIX '23 Security Symposium. 

[Smart Contract-security][Panda: Security Analysis of Algorand Smart Contracts]() Zhiyuan Sun, Xiapu Luo, and Yinqian Zhang. USENIX '23 Security Symposium.

[Smart Contract][The Blockchain Imitation Game](https://www.usenix.org/conference/usenixsecurity23/presentation/qin) Kaihua Qin, Stefanos Chaliasos, Liyi Zhou, Benjamin Livshits, Dawn Song, and Arthur Gervais. USENIX '23 Security Symposium.

[Smart Contract][Proxy Hunting: Understanding and Characterizing Proxy-based Upgradeable Smart Contracts in Blockchains](https://www.usenix.org/conference/usenixsecurity23/presentation/bodell) William E Bodell III, Sajad Meisami, and Yue Duan. USENIX '23 Security Symposium.

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

[Consensus-BFT][Speeding Dumbo: Pushing Asynchronous BFT to Practice](). Bingyong Guo, Yuan Lu, Zhenliang Lu, Qiang Tang, jing xu, Zhenfeng Zhang. NDSS '22. 

[Consensus-PoW][NC-Max: Breaking the Security-Performance Tradeoff in Nakamoto Consensus](). Ren Zhang, Dingwei Zhang, and Quake Wang, Shichen Wu, Jan Xie, Bart Preneel. NDSS '22. 

[Consensus-PoET][Multi-Certificate Attacks against Proof-of-Elapsed-Time and Their Countermeasures](). Huibo Wang, Guoxing Chen, Yinqian Zhang, Zhiqiang Lin. NDSS '22. 

[Smart Contract][POSE: Practical Off-chain Smart Contract Execution](). Tommaso Frassetto, Patrick Jauernig, David Koisser, David Kretzler, Benjamin Schlosser, Sebastian Faust, and Ahmad-Reza Sadeghi. NDSS '23.  

[Smart Contract][Smarter Contracts: Detecting Vulnerabilities in Smart Contracts with Deep Transfer Learning](). Christoph Sendner, Huili Chen, Hossein Fereidooni, Lukas Petzi, Jan König, Jasper Stang, and Alexandra Dmitrienko, Ahmad-Reza Sadeghi, Farinaz Koushanfar. NDSS '23.  

[Consensus][LOKI: State-Aware Fuzzing Framework for the Implementation of Blockchain Consensus Protocols](). Fuchen Ma, Yuanliang Chen, Meng Ren, Yuanhang Zhou, and Yu Jiang, Ting Chen, Huizhong Li, Jiaguang Sun. NDSS '23.   

[Security][BlockScope: Detecting and Investigating Propagated Vulnerabilities in Forked Blockchain Projects](https://www.ndss-symposium.org/ndss-paper/blockscope-detecting-and-investigating-propagated-vulnerabilities-in-forked-blockchain-projects/). Xiao Yi, Yuzhou Fang, Daoyuan Wu, and Lingxiao Jiang. NDSS '23.

[Payment Channel][Breaking And Fixing UTXO-Based Virtual Channels](). Lukas Aumayr, Pedro Moreno-Sanchez, Aniket Kate, Matteo Maffei. NDSS '23.  

[Consensus][Partitioning Ethereum without Eclipsing It](). Hwanjo Heo and Seungwon Woo, Tae Ung Yoon, Min Suk Kang and Seungwon Shin. NDSS '23.  

[Security][Double and Nothing: Understanding and Detecting Cryptocurrency Giveaway Scams](https://double-and-nothing.github.io/). Xigao Li, Anurag Yepuri, and Nick Nikiforakis. NDSS '23.   

[Payment Channel][He-HTLC: Revisiting Incentives in HTLC]() Sarisht Wadhwa and Jannis Stoeter, Fan Zhang, Kartik Nayak. NDSS '23.   

[Consensus][Separation is Good: A Faster Order-Fairness Byzantine Consensus](). Ke Mu, Bo Yin, Alia Asheralieva, Xuetao Wei. NDSS '24.  

[Smart Contract][Abusing the Ethereum Smart Contract Verification Services for Fun and Profit](). Pengxiang Ma, Ningyu He, Yuhua Huang, Haoyu Wang, Xiapu Luo. NDSS '24.  

[Consensus][Security-Performance Tradeoff in DAG-based Proof-of-Work Blockchain Protocols](). Shichen Wu, Puwen Wei, Ren Zhang, Bowen Jiang. NDSS '24.  

[Consensus][Proof of Backhaul: Trustfree Measurement of Broadband Bandwidth](). Peiyao Sheng, Nikita Yadav, Vishal Sevani, Arun Babu, Anand Svr), Himanshu Tyagi, Pramod Viswanath. NDSS '24.  

[System][A Two-Layer Blockchain Sharding Protocol Leveraging Safety and Liveness for Enhanced Performance](). Yibin Xu, Jingyi Zheng, Boris Düdder, Tijs Slaats, Yongluan Zhou. NDSS '24.  

[Consensus][Front-running Attack in Sharded Blockchains and Fair Cross-shard Consensus](). Jianting Zhang, Wuhui Chen, Sifu Luo, Tiantian Gong, Zicong Hong, Aniket Kate. NDSS '24.  



## CCS
[Consensus-PoW-Mining] [Double-Spending Fast Payments in Bitcoin](https://www.eecis.udel.edu/~ruizhang/CISC859/S17/Paper/p9.pdf). Karame, Ghassan O. and Androulaki, Elli and Capkun, Srdjan. CCS '12.

[Privacy] [Deanonymisation of Clients in Bitcoin P2P Network](https://arxiv.org/pdf/1405.7418.pdf). Biryukov A, Khovratovich D, Pustogarov I. CCS '14.

[Privacy] [Provisions: Privacy-preserving proofs of solvency for Bitcoin exchanges](https://eprint.iacr.org/2015/1008.pdf). Dagher GG, Bünz B, Bonneau J, Clark J, Boneh D. CCS '15

[Economic] [Demystifying incentives in the consensus computer](https://eprint.iacr.org/2015/702). Loi Luu, Jason Teutsch, Raghav Kulkarni and Prateek Saxena. CCS '15

[PoW-Network] [Tampering with the Delivery of Blocks and Transactions in Bitcoin](https://eprint.iacr.org/2015/578.pdf).Gervais, Arthur and Ritzdorf, Hubert and Karame, Ghassan O. and Capkun, Srdjan. CCS '15

[Consensus-PoW-Mining] [Non-outsourceable Scratch-Off Puzzles to Discourage Bitcoin Mining Coalitions](http://soc1024.ece.illinois.edu/nonoutsourceable_full.pdf). Andrew Miller, Elaine Shi, Ahmed Kosba, and Jonathan Katz. CCS '15

[System] [The Honey Badger of BFT Protocols](https://infoscience.epfl.ch/record/222858/files/199.pdf). Miller A, Xia Y, Croman K, Shi E, Song D. CCS '16.

[Smart Contracts] [Making Smart Contracts Smarter](https://www.comp.nus.edu.sg/~loiluu/papers/oyente.pdf). Luu L, Chu DH, Olickel H, Saxena P, Hobor A. CCS '16.

[Economic] [On the instability of Bitcoin without the block reward](http://www.cs.princeton.edu/~smattw/CKWN-CCS16.pdf). Carlsten M, Kalodner H, Weinberg SM, Narayanan A. CCS '16.

[Smart Contracts] [Town crier: An authenticated data feed for smart contracts](http://delivery.acm.org/10.1145/2980000/2978326/p270-zhang.pdf?ip=46.176.188.9&id=2978326&acc=OA&key=4D4702B0C3E38B35%2E4D4702B0C3E38B35%2E4D4702B0C3E38B35%2E594C525CFFA2AFAF&CFID=923932938&CFTOKEN=56121949&__acm__=1492299159_38039f3afa858f241818fdcf190e0200). Zhang F, Cecchetti E, Croman K, Juels A, Shi E. CCS '16.

[Privacy] [On the Security and Performance of Proof of Work Blockchains](https://eprint.iacr.org/2016/555.pdf). Gervais A, Karame GO, Karl Wüst, Glykantzis V, Ritzdorf H, Capkun S. CCS '16.

[System] [A Secure Sharding Protocol For Open Blockchains](https://www.comp.nus.edu.sg/~loiluu/papers/elastico.pdf). Loi Luu, Viswesh Narayanan, Chaodong Zheng, Kunal Baweja, Seth Gilbert, Prateek Saxena. CCS '16.

[Payment Networks] [Revive: Rebalancing Off-Blockchain Payment Networks](https://eprint.iacr.org/2017/823.pdf). Khalil, R., & Gervais, A. CCS '17.

[Economic] [The Gap Game](http://delivery.acm.org/10.1145/3250000/3243737/p713-tsabary.pdf?ip=142.231.81.31&id=3243737&acc=ACTIVE%20SERVICE&key=FD0067F557510FFB%2E26E2C50968A06846%2E4D4702B0C3E38B35%2E4D4702B0C3E38B35&__acm__=1572896863_842d24816daa8481df9c256f8a9cb16d). Itay Tsabary, Ittay Eyal. CCS '18.

[Payment Networks] [General State Channel Networks](https://eprint.iacr.org/2018/320.pdf) Dziembowski S, Faust S, Hostáková K. CCS '18.

[System Design] [FairSwap: How to fairly exchange digital goods](https://eprint.iacr.org/2018/740) Dziembowski S, Faust S, Eckey L. CCS '18.

[System] [RapidChain: Scaling Blockchain via Full Sharding](https://eprint.iacr.org/2018/460.pdf). Mahdi Zamani, Mahnush Movahedi, Mariana Raykova. CCS '18.

[Consensus] [BEAT: Asynchronous BFT Made Practical](https://www.csee.umbc.edu/~hbzhang/files/beat.pdf). Sisi Duan, Michael K. Reiter, Haibin Zhang. CCS '18.

[Consensus Applcation] [Efficient Publicly Verifiable 2PC over a Blockchain with Applications to Financially-Secure Computations](http://homes.sice.indiana.edu/yh33/mypub/pvc.pdf).	Ruiyu Zhu, Changchang Ding, Yan Huang. CCS '19.

[Network] [Erlay: Efficient Transaction Relay for Bitcoin](https://arxiv.org/abs/1905.10518).	Gleb Naumenko, Gregory Maxwell, Pieter Wuille, Alexandra (Sasha) Fedorova, Ivan Beschastnikh. CCS '19.

[Sidechain] [HyperService: Interoperability and Programmability across Heterogeneous Blockchains](https://arxiv.org/abs/1908.09343).	Zhuotao Liu, Yangxi Xiang,Jian Shi, Peng Gao, Haoyu Wang, Xusheng Xiao, Bihan Wen, Yih-Chun Hu. CCS '19.

[Cryptography][MatRiCT: Efficient, Scalable and Post-Quantum Blockchain Confidential Transactions Protocol](https://eprint.iacr.org/2019/1287.pdf).	Muhammed F. Esgin, Raymond K. Zhao, Ron Steinfeld, Joseph K. Liu, Dongxi Liu. CCS '19. 

[Payment][Omniring: Scaling Up Private Payments Without Trusted Setup — Formal Foundations and a Construction of Ring Confidential Transactions with Log-size Proofs]().	Russell W. F. Lai, Viktoria Ronge, Tim Ruffing, Dominique Schröder, Sri Aravinda Krishnan Thyagarajan, Jiafan Wang. CCS '19. 

[Consensus][Prism: Deconstructing the Blockchain to Approach Physical Limits](https://dl.acm.org/doi/abs/10.1145/3319535.3345655?download=true).	Vivek Bagaria, Sreeram Kannan, David Tse, Giulia Fanti, Pramod Viswanath. CCS '19. 

[Smart contract][Learning to Fuzz from Symbolic Execution with Application to Smart Contracts](https://files.sri.inf.ethz.ch/website/papers/ccs19-ilf.pdf).	Jingxuan He, Mislav Balunovic, Nodar Ambroladze, Petar Tsankov, Martin Vechev. CCS '19. 

[Smart contract][TokenScope: Automatically Detecting Inconsistent Behaviors of Cryptocurrency Tokens in Ethereum](https://www4.comp.polyu.edu.hk/~csxluo/TokenScope.pdf). Ting Chen, Xiapu Luo, Ting Wang, Rong Cao. CCS '19. 

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

[Consensus][Multi-Threshold Byzantine Fault Tolerance](https://eprint.iacr.org/2021/671.pdf).Atsuki Momose, Ling Ren. CCS '21.

[Consensus][Revisiting Nakamoto Consensus in Asynchronous Networks: A Comprehensive Analysis of Bitcoin Safety and Chain Quality](http://www.cs.ucf.edu/~msaad/ccs_21.pdf).Muhammad Saad, Afsah Anwar, Srivatsan Ravi, and David Mohaisen. CCS '21.

[Consensus][BFT Protocol Forensics](https://arxiv.org/abs/2010.06785). Peiyao Sheng, Gerui Wang, Kartik Nayak, Sreeram Kannan, Pramod Viswanath. CCS '21.

[Consensus][Securing Parallel-chain Protocols under Variable Mining Power](https://arxiv.org/abs/2105.02927) Xuechao Wang, Viswa Virinchi Muppirala, Lei Yang, Sreeram Kannan, Pramod Viswanath. CCS '21.

[Beacon][RandPiper-Reconfiguration-Friendly Random Beacons with Quadratic Communication](https://eprint.iacr.org/2020/1590). Adithya Bhat and Nibesh Shrestha and Aniket Kate and Kartik Nayak. CCS '21.

[Consensus][Asynchronous Data Dissemination and its Applications](https://eprint.iacr.org/2021/777) Sourav Das and Zhuolun Xiang and Ling Ren. CCS '21.

[Consensus][Dumbo-NG: Fast Asynchronous BFT Consensus with Throughput-Oblivious Latency](https://arxiv.org/abs/2209.00750). Yingzi Gao, Yuan Lu, Zhenliang Lu, Qiang Tang, Jing Xu, Zhenfeng Zhang. CCS '22.

[Consensus] [Bolt-Dumbo Transformer: Asynchronous Consensus As Fast As the Pipelined BFT](https://arxiv.org/pdf/2103.09425.pdf). Yuan Lu, Zhenliang Lu, Qiang Tang. CCS '22. 

[Consensus] [Bullshark: DAG BFT Protocols Made Practical](https://arxiv.org/abs/2209.05633). Alexander Spiegelman, Neil Giridharan, Alberto Sonnino, Lefteris Kokoris-Kogias. CCS '22. 

[Consensus] [Constant Latency in Sleepy Consensus](). Atsuki Momose, Ling Ren. CCS '22.

[Consensus] [ENGRAFT: Enclave-guarded Raft on Byzantine Faulty Nodes]()	Weili Wang , Sen Deng, Jianyu Niu, Michael K. Reiter, Yinqian Zhang. CCS '22.

[Transactions] [Empirical Analysis of EIP-1559: Transaction Fees, Waiting Times, and Consensus Security]() Yulin Liu, Yuxuan Lu, Kartik Nayak, Fan Zhang, Luyao Zhang,  Yinhong Zhao. CCS '22.

[Consensus] [Minotaur: Multi-Resource Blockchain Consensus]().	Matthias Fitzi, Xuechao Wang, Sreeram Kannan, Aggelos Kiayias, Nikos Leonardos, Pramod Viswanath, Gerui Wang. CCS '22.

[Consensus] [PACE: Fully Parallelizable BFT from Reproposable Byzantine Agreement]().	Haibin Zhang, Sisi Duan. CCS '22.

[Payment channel] [Sleepy Channels: Bi-directional Payment Channels without Watchtowers](). Lukas Aumayr, Sri AravindaKrishnan Thyagarajan, Giulio Malavolta, Pedro Moreno-Sanchez, Matteo Maffei. CCS '22.

[Transactions] [Watch Your Back: Identifying Cybercrime Financial Relationships in Bitcoin through Back-and-Forth Exploration](). Gibran Gomez, Pedro Moreno-Sanchez, Juan Caballero. CCS '22.

[Cross-chain] [zkBridge: Trustless Cross-chain Bridges Made Practical](). Tiancheng Xie, Jiaheng Zhang, Zerui Cheng, Fan Zhang, Yupeng Zhang, Yongzheng Jia, Dan Boneh, Dawn Song. CCS '22.

[Consensus][Themis: Fast, Strong Order-Fairness in Byzantine Consensus](). Mahimna Kelkar, Soubhik Deb, Sishan Long, Ari Juels, Sreeram Kannan. CCS '23.

[Consensus][Fait Accompli Committee Selection: Improving the Size-Security Tradeoff of Stake-Based Committees](https://dl.acm.org/doi/10.1145/3576915.3623194). Peter Gaži, Aggelos Kiayias, Alexander Russell. CCS '23. 

[Consensus][Uncle Maker: (Time)Stamping Out The Competition in Ethereum](). Aviv Yaish, Gilad Stern, Aviv Zohar. CCS '23. 

[Smart Contract][Fuzz on the Beach: Fuzzing Solana Smart Contracts](). Sven Smolka, Jens-Rene Giesen, Pascal Winkler, Oussama Draissi, Lucas Davi, Ghassan Karame, Klaus Pohl. CCS '23. 

[Governance][How Hard is Takeover in DPoS Blockchains? Understanding the Security of Coin-based Voting Governance]() Chao Li, Balaji Palanisamy, Runhua Xu, Li Duan, Jiqiang Liu, Wei Wang. CCS '23. 

[Mining][Under the Dark: A Systematical Study of Stealthy Mining Pools (Ab)use in the Wild](). Zhenrui Zhang, Geng Hong, Zhuoqun Fu, Jia Zhang, Mingxuan Liu, Chuhan Wang, Jianjun Chen, Baojun Liu, Haixin Duan, Chao Zhang, Min Yang. CCS '23. 

[Transactions][Cybercrime Bitcoin Revenue Estimations: Quantifying the Impact of Methodology and Coverage](). Gibran Gomez, Kevin Van Liebergen, Juan Caballero. CCS '23. 

[Crypto][LedgerLocks: A Security Framework for Blockchain Protocols Based on Adaptor Signatures](). Erkan Tairi, Pedro Moreno-Sanchez, Clara Schneidewind. CCS '23. 

[Consensus][Abraxas: Throughput-Efficient Hybrid Asynchronous Consensus](). Erica Blum, Jonathan Katz, Julian Loss, Kartik Nayak, Simon Ochsenreither. CCS '23. 

[Consensus][ParBFT: Faster Asynchronous BFT Consensus with a Parallel Optimistic Path](). Xiaohai Dai, Bolin Zhang, Hai Jin, Ling Ren. CCS '23.

[Consensus][Towards Practical Sleepy BFT](). Dahlia Malkhi, Atsuki Momose, Ling Ren. CCS '23.

[Transactions][TxPhishScope: Towards Detecting and Understanding Transaction-based Phishing on Ethereum]().Bowen He, Yuan Chen, Zhuo Chen, Xiaohui Hu, Yufeng Hu, Lei Wu, Rui Chang, Haoyu Wang, Yajin Zhou. CCS '23. 

[Defi][Demystifying DeFi MEV Activities in Flashbots Bundle](). Zihao Li, Jianfeng Li, Zheyuan He, Xiapu Luo, Ting Wang, Xiaoze Ni, Wenwu Yang, Xi Chen, Ting Chen. CCS '23. 

[Consensus][CryptoConcurrency: (Almost) Consensusless Asset Transfer with Shared Accounts](). Andrei Tonkikh, Pavel Ponomarev, Petr Kuznetsov,  Yvonne-Anne Pignolet. CCS '23. 

[Security Analysis]Phoenix: Detect and Locate Resilience Issues in Blockchain via Context-Sensitive Chaos](). Fuchen Ma, Yuanliang Chen, Yuanhang Zhou, Jingxuan Sun, Zhuo Su, Yu Jiang, Jiaguang Sun, Huizhong Li. CCS '23. 

[Consensus][Analyzing the Real-World Security of the Algorand Blockchain](). Erica Blum, Derek Leung, Julian Loss, Jonathan Katz, Tal Rabin. CCS '23. 

[Consensus][Interchain Timestamping for Mesh Security](). Ertem Nusret Tas, Runchao Han, David Tse, Mingchao Yu. CCS '23. 


## SOSP
[Consensus] [Algorand: Scaling Byzantine Agreements for Cryptocurrencies](https://people.csail.mit.edu/nickolai/papers/gilad-algorand.pdf). Yossi Gilad, Rotem Hemo, Silvio Micali, Georgios Vlachos, Nickolai Zeldovich. SOSP'17

[Payment Networks] [Teechain: A Secure Payment Network with Asynchronous Blockchain Access](https://arxiv.org/pdf/1707.05454.pdf). Joshua Lind, Oded Naor, Ittay Eyal, Florian Kelbert, Peter Pietzuch, Emin Gun Sirer. SOSP'19

[Consensus] [Fast and Secure Global Payments with Stellar](https://www.scs.stanford.edu/~dm/home/papers/lokhava:stellar-core.pdf). Marta Lokhava, Giuliano Losa, David Mazières, Graydon Hoare, Nicolas Barry, Eliezer Gafni, Jonathan Jove, Rafał Malinowski, Jed McCaleb. SOSP'19

[Consensus] [Notary: A Device for Secure Transaction Approval](https://pdos.csail.mit.edu/papers/notary:sosp19.pdf). Anish Athalye, Adam Belay, Frans Kaashoek, Robert Morris, Nickolai Zeldovich. SOSP'19

[Database] [Basil: Breaking up BFT with ACID (transactions)](https://dl.acm.org/doi/pdf/10.1145/3477132.3483552). Florian Suri-Payer, Matthew Burke, Yunhao Zhang, Zheng Wang, Lorenzo Alvisi, and Natacha Crooks. SOSP'21

[Network] [Bidl: A High-throughput, Low-latency Permissioned Blockchain Framework for Datacenter Networks](https://dl.acm.org/doi/pdf/10.1145/3477132.3483574). Ji Qi, Xusheng Chen, Yunpeng Jiang, Jianyu Jiang, Tianxiang Shen, Shixiong Zhao, Sen Wang, Gong Zhang, Li Chen, Man Ho Au, and Heming Cui. SOSP'21

[Consensus] [Kauri: Scalable BFT Consensus with Pipelined Tree-Based Dissemination and Aggregation](https://dl.acm.org/doi/pdf/10.1145/3477132.3483584). Ray Neiheiser, Miguel Matos, and Luís Rodrigues. SOSP'21

[Smart Contract] [Forerunner: Constraint-based Speculative Transaction Execution for Ethereum](https://dl.acm.org/doi/pdf/10.1145/3477132.3483564). Yang Chen, Zhongxin Guo, Runhuai Li, Shuo Chen, Lidong Zhou, Yajin Zhou, and Xian Zhang. SOSP'21

[Consensus] [Rabia: Simplifying State-Machine Replication Through Randomization](https://dl.acm.org/doi/pdf/10.1145/3477132.3483582). Haochen Pan, Jesse Tuglu, Neo Zhou, Tianshu Wang, Yicheng Shen, Xiong Zheng, Joseph Tassarotti, Lewis Tseng, Roberto Palmieri. SOSP'21

[Consensus] [Flexible-Advancement in Asynchronous BFT Consensus](). Shengyun Liu, Wenbo Xu, Chen Shan, Xiaofeng Yan, Tianjing Xu, Bo Wang, Lei Fan, Fuxi Deng, Ying Yan and Hui Zhang. SOSP'23 

## OSDI
[System][Blockene: A High-throughput Blockchain Over Mobile Devices](https://arxiv.org/pdf/2010.07277). Sambhav Satija and Apurv Mehra, Sudheesh Singanamalla, Karan Grover, Muthian Sivathanu, Nishanth Chandran, Divya Gupta, and Satya Lokam. OSDI'20 

[Consensus][Byzantine ordered consensus without Byzantine oligarchy](https://www.microsoft.com/en-us/research/uploads/prod/2020/10/paper-5f89e2898ee53.pdf) Yunhao Zhang, Srinath Setty, Qi Chen, and Lidong Zhou, Lorenzo Alvisi. OSDI'20 

[Smart Contract][Finding Consensus Bugs in Ethereum via Multi-transaction Differential Fuzzing](https://www.usenix.org/system/files/osdi21-yang.pdf). Youngseok Yang, Taesoo Kim, Byung-Gon Chun. OSDI'21

[Decentralized Service][Bringing Decentralized Search to Decentralized Services](https://www.usenix.org/system/files/osdi21-li.pdf). Mingyu Li, Jinhao Zhu, Tianxu Zhang, Cheng Tan, Sebastian Angel, and Haibo Chen. OSDI'21

## Eurosys
[Consensus] [Hybrids on Steroids: SGX-Based High Performance BFT](https://www4.cs.fau.de/Publications/2017/behl_17_eurosys.pdf). Johannes Behl, Tobias Distler, Rüdiger Kapitza. EuroSys'17.

[System] [Hyperledger Fabric: A Distributed Operating System for Permissioned Blockchains](https://arxiv.org/pdf/1801.10228.pdf). Elli Androulaki, Artem Barger, Vita Bortnikov, Christian Cachin, Konstantinos Christidis, Angelo De Caro, David Enyeart, Christopher Ferris, Gennady Laventman, Yacov Manevich, Srinivasan Muralidharan, Chet Murthy, Binh Nguyen, Manish Sethi, Gari Singh, Keith Smith, Alessandro Sorniotti, Chrysoula Stathakopoulou, Marko Vukolić, Sharon Weed Cocco, Jason Yellick. EuroSys'18.

[Consensus] [DAMYSUS: Streamlined BFT Consensus Leveraging Trusted Components](https://dl.acm.org/doi/pdf/10.1145/3492321.3519568). Jeremie Decouchant, David Kozhaya, Vincent Rahli, Jiangshan Yu. EuroSys'22.

[Consensus] [State Machine Replication Scalability Made Simple](https://dl.acm.org/doi/pdf/10.1145/3492321.3519579). Chrysoula Stathakopoulou, Matej Pavlovic, Marko Vukolic. EuroSys'22.

[Consensus] [Narwhal and Tusk: A DAG-based Mempool and Efficient BFT Consensus](https://dl.acm.org/doi/abs/10.1145/3492321.3519594). George Danezis, Lefteris Kokoris-Kogias, Alberto Sonnino, Alexander Spiegelman. EuroSys'22.

[Consensus] [Dissecting BFT Consensus: In Trusted Components we Trust!](). Suyash Gupta, Sajjad Rahnama, Shubham Pandey, Natacha Crooks, Mohammad Sadoghi.  EuroSys'23

[Consensus] [Diablo: A Benchmark Suite for Blockchains](). Vincent Gramoli, Rachid Guerraoui, Andrei Lebedev, Chris Natoli, Gauthier Voron. EuroSys'23


## NSDI
[Consensus-PoW] [Bitcoin-NG: A Scalable Blockchain Protocol](https://www.usenix.org/system/files/conference/nsdi16/nsdi16-paper-eyal.pdf). Eyal I, Gencer AE, Sirer EG, Van Renesse R. NSDI ’16

[System][Monoxide: Scale Out Blockchain with Asynchronized Consensus Zones](https://www.usenix.org/system/files/nsdi19-wang-jiaping.pdf). Jiaping Wang, Hao Wang. NSDI'19

[Network][High Throughput Cryptocurrency Routing in Payment Channel Networks](https://www.usenix.org/system/files/nsdi20-paper-sivaraman.pdf). Vibhaalakshmi Sivaraman, Shaileshh Bojja Venkatakrishnan, Kathleen Ruan, Parimarjan Negi and Lei Yang, Radhika Mittal, Giulia Fanti, Mohammad Alizadeh. NSDI ’20

[Consensus-BFT] [DispersedLedger: High-Throughput Byzantine Consensus on Variable Bandwidth Networks](https://arxiv.org/pdf/2110.04371.pdf). Lei Yang, Seo Jin Park, Sreeram Kannan, Kannan S, David Tse. NSDI ’22

[System][SPEEDEX: A Scalable, Parallelizable, and Economically Efficient Decentralized EXchange](https://www.usenix.org/system/files/nsdi23-ramseyer.pdf). Geoffrey Ramseyer, Ashish Goel, David Mazières. NSDI '23

[System][Hamilton: A High-Performance Transaction Processor for Central Bank Digital Currencies](https://www.usenix.org/system/files/nsdi23-lovejoy.pdf). James Lovejoy, Madars Virza, Cory Fields, Kevin Karwaski, Anders Brownworth, Neha Narula. NSDI '23


## Sigmetric&Performance
[Network][Stability and Scalability of Blockchain Systems](). Aditya Gopalan, Abishek Sankararaman, Anwar Walid, Sriram Vishwanath. Sigmetric '20.

[Layer-2][Privacy-Utility Tradeoffs in Routing Cryptocurrency over Payment Channel Networks](). Weizhao Tang, Weina Wang, Giulia Fanti, Sewoong Oh. Sigmetric '20.

[Network][Understanding (Mis)Behavior on the EOSIO Blockchain](). Yuheng Huang, Haoyu Wang, Lei Wu, Gareth Tyson, Xiapu Luo, Run Zhang, Xuanzhe Liu, Gang Huang, Xuxian Jiang. Sigmetric '20.

[Incentive][Incentive Analysis of Bitcoin-NG, Revisited](https://arxiv.org/abs/2001.05082).Jianyu Niu, Ziyu Wang, Fangyu Gai and Chen Feng. Performance '20.

[Transactions][Tracking Counterfeit Cryptocurrency End-to-end]() Bingyu Gao, Haoyu Wang, Pengcheng Xia, Siwei Wu, Yajin Zhou, Xiapu Luo, Gareth Tyson. Sigmetric '21.

## SIGMOD
[Measurement][BLOCKBENCH: A Framework for Analyzing Private Blockchains](https://www.comp.nus.edu.sg/~ooibc/blockbench.pdf). Tien Tuan Anh Dinh, Ji Wang, Gang Chen, Rui Liu, Beng Chin Ooi, and Kian-Lee Tan. SIGMOD '17.

[Database][Blurring the Lines between Blockchains and Database Systems: the Case of Hyperledger Fabric](https://dl.acm.org/doi/pdf/10.1145/3299869.3319883?download=true). Ankur Sharma, Felix Martin Schuhknecht, Divya Agrawal, and Jens Dittrich. SIGMOD '19.

[Database][vChain: Enabling Verifiable Boolean Range Queries over Blockchain Databases](https://arxiv.org/pdf/1812.02386.pdf). Cheng Xu, Ce Zhang, and Jianliang Xu. SIGMOD '19.

[Consensus-sharding][Towards Scaling Blockchain Systems via Sharding](https://www.comp.nus.edu.sg/~hungdang/papers/sharding.pdf). Hung Dang, Tien Tuan Anh Dinh, Dumitrel Loghin, Ee-Chien Chang, Qian Lin, and Beng Chin Ooi. SIGMOD '19.

[Database][Confidentiality Support over Financial Grade Consortium Blockchain](https://dl.acm.org/doi/abs/10.1145/3318464.3386127). Yan, YingWei, Changzheng Guo, Xuepeng Lu, Xuming Zheng, Xiaofu Liu, Qi Zhou, Chenhui Song, Xuyang Zhao, Boran Zhang, Hui Jiang, and Guofei. SIGMOD '20.

[Database] [A Transactional Perspective on Execute-order-validate Blockchains](https://dl.acm.org/doi/10.1145/3318464.3389693). Pingcheng Ruan, Dumitrel Loghin, Meihui Zhang, Gang Chen, and Beng Chin Ooi. SIGMOD '20.

[Database] [FalconDB: Blockchain-based Collaborative Database](https://dl.acm.org/doi/10.1145/3318464.3380594). Yanqing Peng, Min Du, Feifei Li, Raymond Cheng, and Dawn Song. SIGMOD '20.

[Database] [Blockchains vs. Distributed Databases: Dichotomy and Fusion](https://www.comp.nus.edu.sg/~ooibc/bcvsdb.pdf). Pingcheng Ruan, Tien Tuan Anh Dinh, Dumitrel Loghin, Meihui Zhang, Gang Chen, Qian Lin and Beng Chin Ooi. SIGMOD '21.

[Benchmark] [Why Do My Blockchain Transactions Fail? A Study of Hyperledger Fabric](https://arxiv.org/pdf/2103.04681.pdf). Jeeta Ann Chacko, Ruben Mayer, and Hans-Arno Jacobsen. SIGMOD '21.

[Consensus-sharding] [SharPer: Sharding Permissioned Blockchains Over Network Clusters](https://sites.cs.ucsb.edu/~amiri/papers/sharper.pdf). Mohammad Javad Amiri, Divyakant Agrawal, and Amr El Abbadi. SIGMOD '21.

[PoS] [Do the Rich Get Richer? Fairness Analysis for Blockchain Incentives](https://arxiv.org/pdf/2103.14713.pdf). Yuming Huang, Jing Tang, Qianhao Cong, Andrew Lim, and Jianliang Xu.

[Privacy] [P^2B-Trace: Privacy-Preserving Blockchain-based Contact Tracing to Combat Pandemics](https://dl.acm.org/doi/abs/10.1145/3448016.3459237). Zhe Peng, Cheng Xu, Haixin Wang, Jinbin Huang, Jianliang Xu, and Xiaowen Chu. SIGMOD '21.

[Privacy] [DIV: Resolving the Dynamic Issues of Zero-knowledge Set Membership Proof in the Blockchain](https://dl.acm.org/doi/abs/10.1145/3448016.3457248). Zihuan Xu, and Lei Chen. SIGMOD '21.

[Privacy] [When the Recursive Diversity Anonymity Meets the Ring Signature](https://dl.acm.org/doi/abs/10.1145/3448016.3452825). Wangze Ni, Peng Cheng, Lei Chen, Xuemin Lin. SIGMOD '21.

[Database] [SQL Ledger: Cryptographically Verifiable Data in Azure SQL Database](https://dl.acm.org/doi/pdf/10.1145/3448016.3457558). Panagiotis Antonopoulos, Raghav Kaushik, Hanuma Kodavalla, Sergio Rosales Aceves, Reilly Wong, Jason Anderson, and Jakub Szymaszek. SIGMOD '21

## VLDB
[Storage] [ForkBase: An Efficient Storage Engine for Blockchain and Forkable Applications](http://www.vldb.org/pvldb/vol11/p1137-wang.pdf). Sheng Wang, Tien Tuan Anh Dinh, Qian Lin, Zhongle Xie, Meihui Zhang, Qingchao Cai, Gang Chen, Beng Chin Ooi, Pingcheng Rua. VLDB'18. 

[Privacy] [A Demonstration of Sterling: A Privacy-Preserving Data Marketplace](http://www.vldb.org/pvldb/vol11/p2086-hynes.pdf). Nick Hynes1, David Dao, David Yan, Raymond Cheng, Dawn Song. VLDB'19. 

[Application] [CAPER: A Cross-Application Permissioned Blockchain](http://www.vldb.org/pvldb/vol12/p1385-amiri.pdf). Mohammad Javad Amiri, Divyakant Agrawal, Amr El Abbadi. VLDB'19. 

[Application] [BlockchainDB - A Shared Database on Blockchains](http://www.vldb.org/pvldb/vol12/p1597-el-hindi.pdf). Muhammad El-Hindi,
Carsten Binnig, Arvind Arasu, Donald Kossmann, Ravi Ramamurthy. VLDB'19.

[Provenance] [Fine-Grained, Secure and Efficient Data Provenance on Blockchain Systems](http://www.vldb.org/pvldb/vol12/p975-ruan.pdf). Pingcheng Ruan, Gang Chen, Tien Tuan Anh Dinh, Qian Lin, Beng Chin Ooi, Meihui Zhang. VLDB'19. 

[Application] [Blockchain Meets Database: Design and Implementation of a Blockchain Relational Database](http://www.vldb.org/pvldb/vol12/p1539-nathan.pdf). Senthil Nathan, Chander Govindarajan, Adarsh Saraf, Manish Sethi, and Praveen Jayachandran. VLDB'19.

[Consensus] [FireLedger: A High Throughput Blockchain Consensus Protocol](http://www.vldb.org/pvldb/vol13/p1525-buchnik.pdf). Yehonatan Buchnik, and Roy Friedman. VLDB'20.

## ICSE
[Smart Contract] [Gigahorse: Thorough, Declarative Decompilation of Smart Contracts](https://ieeexplore.ieee.org/document/8811905). Neville Grech, Lexi Brent, Bernhard Scholz, Yannis Smaragdakis. ICSE '2019.

[Smart Contract] [Gap between theory and practice: an empirical study of security patches in solidity](https://doi.org/10.1145/3377811.3380424). Sungjae Hwang, Sukyoung Ryu. ICSE '2020.

[Smart Contract] [Targeted greybox fuzzing with static lookahead analysis](https://dl.acm.org/doi/10.1145/3377811.3380388). Valentin Wüstholz, Maria Christakis. ICSE '2020.

[Smart Contract] [Empirical Review of Automated Analysis Tools on 47,587 Ethereum Smart Contracts](https://arxiv.org/pdf/1910.10601.pdf). T Durieux, JF Ferreira, R Abreu, P Cruz. ICSE '2020

[Smart Contract] [sFuzz-An Efficient Adaptive Fuzzer for Solidity Smart Contracts](https://arxiv.org/pdf/2004.08563.pdf). TD Nguyen, LH Pham, J Sun, Y Lin, QT Minh. ICSE '2020

[Smart Contract] [Smart Contract Security: a Practitioners' Perspective](http://arxiv.org/abs/2102.10963). Zhiyuan Wan, Xin Xia, David Lo, Jiachi Chen, Xiapu Luo, Xiaohu Yang.  ICSE '2021

[Application] [Utilizing Parallelism in Smart Contracts on Decentralized Blockchains by Taming Application-Inherent Conflicts](https://dl.acm.org/doi/10.1145/3510003.3510086). Péter Garamvölgyi, Yuxi Liu, Dong Zhou, Fan Long, Ming Wu.  ICSE '2022

[Smart Contract] [FlashSyn: Flash Loan Attack Synthesis via Counter Example Driven Approximation](https://arxiv.org/pdf/2206.10708.pdf). Zhiyang Chen, Sidi Mohamed Beillahi, Fan Long. ICSE '2024

[Smart Contract] [SCVHunter: Smart Contract Vulnerability Detection Based on Heterogeneous Graph Attention Network](https://dl.acm.org/doi/abs/10.1145/3597503.3639213). Feng Luo, Ruijie Luo, Ting Chen, Ao Qiao, Zheyuan He, Shuwei Song, Yu Jiang, Sixing Li. ICSE '2024

[Smart Contract] [Are We There Yet? Unraveling the State-of-the-Art Smart Contract Fuzzers](https://arxiv.org/pdf/2402.02973.pdf). Shuohan Wu, Zihao Li, Luyi Yan, Weimin Chen, Muhui Jiang, Chenxu Wang, Xiapu Luo, Hao Zhou. ICSE '2024

[Smart Contract] [Smart Contract and DeFi Security Tools: Do They Meet the Needs of Practitioners?](https://arxiv.org/pdf/2304.02981). Stefanos Chaliasos, Marcos Antonios Charalambous, Liyi Zhou, Rafaila Galanopoulou, Arthur Gervais, Dimitris Mitropoulos, Ben Livshits. ICSE '2024

[Smart Contract] [Safeguarding DeFi Smart Contracts against Oracle Deviations](https://arxiv.org/pdf/2401.06044). Xun Deng, Sidi Mohamed Beillahi, Cyrus Minwalla, Han Du, Andreas Veneris, Fan Long. ICSE '2024

[Smart Contract] [GPTScan: Detecting Logic Vulnerabilities in Smart Contracts by Combining GPT with Program Analysis](https://arxiv.org/pdf/2308.03314). Yuqiang Sun, Daoyuan Wu, Yue Xue, Han Liu, Haijun Wang, Zhengzi Xu, Xiaofei Xie, Yang Liu. ICSE '2024

## ESEC/FSE

[Smart Contract] [Towards automated verification of smart contract fairness](https://dl.acm.org/doi/10.1145/3368089.3409740). Ye Liu, Yi Li, Shang-Wei Lin, Rong Zhao. ESEC/FSE '20.

[Smart Contract] [Harvey: a greybox fuzzer for smart contracts](https://dl.acm.org/doi/10.1145/3368089.3417064).Valentin Wüstholz, Maria Christakis. ESEC/FSE '20.

[Application] [Making smart contract development more secure and easier](https://dl.acm.org/doi/abs/10.1145/3468264.3473929). Meng Ren, Fuchen Ma, Zijing Yin, Ying Fu, Huizhong Li, Wanli Chang, Yu Jiang. ESEC/FSE '21.

[Smart Contract] [iBatch: saving Ethereum fees via secure and cost-effective batching of smart-contract invocations](https://dl.acm.org/doi/10.1145/3468264.3468568). Yibo Wang, Qi Zhang, Kai Li, Yuzhe Tang, Jiaqi Chen, Xiapu Luo, Ting Chen. ESEC/FSE '21.

[Decentralized Application] [ÐArcher: Detecting On-Chain-Off-Chain Synchronization Bugs in Decentralized Applications](https://arxiv.org/abs/2106.09440). Wuqi Zhang, Lili Wei, Shuqing Li, Yepang Liu, Shing-Chi Cheung. ESEC/FSE '21.

[Security] [An Empirical Study of Blockchain System Vulnerabilities: Modules, Types, and Patterns](https://dl.acm.org/doi/abs/10.1145/3540250.3549105). Xiao Yi, Daoyuan Wu, Lingxiao Jiang, Yuzhou Fang, Kehuan Zhang, and Wei Zhang. ESEC/FSE '22.

[Smart Contract] [Static Application Security Testing (SAST) Tools for Smart Contracts: How Far Are We?)](https://arxiv.org/pdf/2404.18186). Kaixuan Li, Yue Xue, Sen Chen, Han Liu, Kairan Sun, Ming Hu, Haijun Wang, Yang Liu, Yixiang Chen. ESEC/FSE '24.

[Smart Contract] [Demystifying Invariant Effectiveness for Securing Smart Contracts](https://arxiv.org/abs/2404.14580). Zhiyang Chen, Ye Liu, Sidi Mohamed Beillahi, Yi Li, Fan Long. ESEC/FSE '24.

[Smart Contract] [Efficiently Detecting Reentrancy Vulnerabilities in Complex Smart Contracts](https://arxiv.org/abs/2403.11254). Zexu Wang, Jiachi Chen, Yanlin Wang, Yu Zhang, Weizhe Zhang, Zibin Zheng. ESEC/FSE '24.

## ASE
[Smart Contract] [ContractFuzzer: fuzzing smart contracts for vulnerability detection](https://doi.org/10.1145/3238147.3238177). Bo Jiang, Ye Liu, W. K Chan. ASE '18.

[Smart Contract] [Summary-based symbolic evaluation for smart contracts](https://doi.org/10.1145/3324884.3416646). Yu Feng, Emina Torlak, Rastislav Bodik. ASE '20.

[Smart Contract] [Demystifying loops in smart contracts](https://dl.acm.org/doi/10.1145/3324884.3416626). Benjamin Mariano, Yanju Chen, Yu Feng, Shuvendu K. Lahiri, Isil Dillig. ASE '20.

[Smart Contract] [Cross-contract static analysis for detecting practical reentrancy vulnerabilities in smart contracts](https://dl.acm.org/doi/10.1145/3324884.3416553). Yinxing Xue, Mingliang Ma, Yun Lin, Yulei Sui, Jiaming Ye, Tianyong Peng. ASE '20.

[Smart Contract] [SMARTIAN: Enhancing Smart Contract Fuzzing with Static and Dynamic Data-Flow Analyses](https://ieeexplore.ieee.org/document/9678888). Jaeseung Choi, Doyeon Kim, Soomin Kim, Gustavo Grieco, Alex Groce, Sang Kil Cha. ASE '21.

[Smart Contract] [Automating User Notice Generation for Smart Contract Functions](https://ieeexplore.ieee.org/document/9678552). Xing Hu, Zhipeng Gao, Xin Xia, David Lo, Xiaohu Yang. ASE '21.

[Smart Contract] [Characterizing Transaction-Reverting Statements in Ethereum Smart Contracts](https://arxiv.org/abs/2108.10799). Lu Liu, Lili Wei, Wuqi Zhang, Ming Wen, Yepang Liu, Shing-Chi Cheung. ASE '21

## ISSTA
[Smart Contract] [Exploiting The Laws of Order in Smart Contracts](https://dl.acm.org/doi/10.1145/3293882.3330560). Aashish Kolluri, Ivica Nikoli ́ c, Ilya Sergey, Aquinas Hobor, Prateek Saxena. ISSTA '19

[Smart Contract] [EShield: protect smart contracts against reverse engineering](https://dl.acm.org/doi/abs/10.1145/3395363.3404365).
Wentian Yan, Jianbo Gao, Zhenhao Wu, Yue Li, Zhi Guan, Qingshan Li, Zhong Chen. ISSTA '20

[Smart Contract] [How effective are smart contract analysis tools? evaluating smart contract static analysis tools using bug injection](https://dl.acm.org/doi/10.1145/3395363.3397385). Asem Ghaleb, Karthik Pattabiraman. ISSTA '20

[Smart Contract] [eTainter: Detecting Gas-Related Vulnerabilities in Smart Contracts](https://doi.org/10.1145/3533767.3534378). Asem Ghaleb, Julia Rubin, Karthik Pattabiraman. ISSTA '22

[Smart Contract] [Finding Permission Bugs in Smart Contracts with Role Mining](https://doi.org/10.1145/3533767.3534372). Ye Liu, Yi Li, Shang-Wei Lin, Cyrille Artho. ISSTA '22

[Smart Contract] [Park: Accelerating Smart Contract Vulnerability Detection via Parallel-fork Symbolic Execution](https://doi.org/10.1145/3533767.3534395). Peilin Zheng, Zibin Zheng, Xiapu Luo. ISSTA '22

[Smart Contract] [WASAI: Uncovering Vulnerabilities in Wasm Smart Contracts](https://doi.org/10.1145/3533767.3534218). Weimin Chen, Zihan Sun, Haoyu Wang, Xiapu Luo, Haipeng Cai, Lei Wu. ISSTA '22

[Smart Contract] [Beyond “Protected” and “Private”: An Empirical Security Analysis of Custom Function Modifiers in Smart Contracts](https://dl.acm.org/doi/abs/10.1145/3597926.3598125). Yuzhou Fang, Daoyuan Wu, Xiao Yi, Shuai Wang, Yufan Chen, Mengjie Chen, Yang Liu, and Lingxiao Jiang. ISSTA '23

## POPL

[Smart Contract] [Online detection of effectively callback free objects with applications to smart contracts](https://dl.acm.org/doi/10.1145/3158136). SHELLY GROSSMAN, ITTAI ABRAHAM, GUY GOLAN-GUETA, YAN MICHALEVSKY, NOAM RINETZKY, MOOLY SAGIV, YONI ZOHAR. POPL '18.

[Smart Contract] [SolType: Refinement Types for Arithmetic Overflow in Solidity](https://dl.acm.org/doi/abs/10.1145/3498665?af=R). BRYAN TAN, BENJAMIN MARIANO, SHUVENDU K. LAHIRI, ISIL DILLIG, YU FENG. POPL '22.

## ABER

[Application] [Blockchain-based cyber-security proposal in commerce mobile platforms for social and sustainability businesses](https://doi.org/10.54517/m.v5i1.2415). SAIFALMAJD MOHAMMED HASSAN ALMASSRI, KHALID HUSSAIN, HALAWATI BINTI ABD JALIL SAFUAN, BASHEER RISKHAN. ABER '24.

## IPDPS
[Consensus][G-PBFT: A Location-based and Scalable Consensus Protocol for IoT-Blockchain Applications](http://www4.comp.polyu.edu.hk/~csbxiao/paper/2020/IPDPS_GPBFT_2020.pdf). LapHou Lao, Xiaohai Dai, Bin Xiao, and Songtao Guo. IPDPS '20.

[BFT][Byzantine Generalized Lattice Agreement](https://arxiv.org/pdf/1910.05768.pdf). Giuseppe Antonio Di Luna, Emmanuelle Anceaume, and Leonardo Querzoni. IPDPS '20. 


## EuroS&P
[Smart Contract][Ekiden: A Platform for Conﬁdentiality-Preserving, Trustworthy, and Performant Smart Contracts](https://arxiv.org/pdf/1804.05141.pdf). Raymond Cheng, Fan Zhang, Jernej Kos, Warren He, Nicholas Hynes, Noah Johnson, Ari Juels, Andrew Miller, Dawn Song. EuroS&P '19.

[Random Beacons][Fully Distributed Verifiable Random Functions and their Application to Decentralised Random Beacons](). David Galindo, Jia Liu, Mihai Ordean, Jin-Mann Wong. EuroS&P '21.

## SRDS
[Consensus] [Bloxy: Providing Transparent and Generic BFT-Based Ordering Services for Blockchains](https://www.researchgate.net/publication/340304077_Bloxy_Providing_Transparent_and_Generic_BFT-Based_Ordering_Services_for_Blockchains). Signe Rüsch, Rüdiger Kapitza and Kai Bleeke. SRDS '19.

[Application] [Blockchain-based Metadata Protection for Archival Systems](https://ieeexplore.ieee.org/document/9049624). Arnaud L'Hutereau, Dorian Burihabwa, Pascal Felber, Hugues Mercier and Valerio Schiavoni. SRDS '19.

[Application] [Trusted Computing meets Blockchain: Rollback Attacks and a Solution for Hyperledger Fabric](https://ieeexplore.ieee.org/document/9049585). Marcus Brandenburger, Christian Cachin, Rüdiger Kapitza and Alessandro Sorniotti. SRDS '19.

[Application] [NF-Crowd: Nearly-free Blockchain-based Crowdsourcing](). Chao Li, Balaji Palanisamy, Runhua Xu, Jian Wang, Jiqiang Liu. SRDS '20.

[Query][An Efficient Query Scheme for Hybrid Storage Blockchains Based on Merkle Semantic Trie](). Qingqi Pei, Enyuan Zhou, Yang Xiao, Deyu Zhang, Dongxiao Zhao. SRDS '20.
		
[Smart contract][Protect Your Smart Contract Against Unfair Payment](). Yue Li, Han Liu, Zhiqiang Yang, Bin Wang, Qian Ren, Lei Wang, Bangdao Chen. SRDS '20.

[Consensus] [Threat Adaptive Byzantine Fault Tolerant State-Machine Replication](). Douglas Simões Silva, Rafal Graczyk, Jérémie Decouchant, Marcus Völp and Paulo Esteves-Verissimo. SRDS '21.

[Consensus] [Adding Fairness to Order: Preventing Front-Running Attacks in BFT Protocols using TEEs](). Chrysoula Stathakopoulou, Signe Rüsch, Marcus Brandenburger and Marko Vukolic. SRDS '21.

[Consensus] [How to Trust Strangers: Composition of Byzantine Quorum Systems](). Orestis Alpos, Christian Cachin and Luca Zanolini. SRDS '21.

[Consensus] [Making Reads in BFT State Machine Replication Fast, Linearizable, and Live](). Christian Berger, Hans P. Reiser and Alysson Bessani. SRDS '21.

[Provenance] [Vassago: Efficient and Authenticated Provenance Query on Multiple Blockchains](). Rui Han, Jiang Xiao, Xiaohai Dai, Shijie Zhang, Yi Sun, Baochun Li and Hai Jin. SRDS '21.

## PODC
[Consensus-PoW] [FruitChains: A Fair Blockchain](https://eprint.iacr.org/2016/916.pdf).Rafael Pass, Elaine Shi. PODC'17

[Smart Contracts] [Adding Concurrency to Smart Contracts](https://dl.acm.org/doi/10.1145/3087801.3087835). Maurice Herlihy. PODC'17

[Sidechain] [Atomic Cross-Chain Swaps](https://arxiv.org/abs/1801.09515). Maurice Herlihy. PODC'18

[Consessus] [Brief Announcement: Sustainable Blockchains through Proof of eXercise](https://haslab.uminho.pt/ashoker/files/pox-podc.pdf). Ali Shoker. PODC'18

[Consensus] [The Consensus Number of a Cryptocurrency](https://arxiv.org/pdf/1906.05574.pdf). R. Guerraoui, P. Kuznetsov, M. Monti, M. Pavlovic, D. Seredinschi. PODC'19

[Consensus-BFT] [Communication Complexity of Byzantine Agreement, Revisited](https://arxiv.org/abs/1805.03391). I. Abraham, T. Chan, D. Dolev, K. Nayak, R. Pass, L. Ren, E. Shi. PODC'19

[Consensus-BFT] [Exact Byzantine Consensus on Undirected Graphs under Local Broadcast Model](https://arxiv.org/pdf/1903.11677.pdf). M. Khan, S. Naqvi, N. Vaidya. PODC'19

[Consensus-BFT] [Asymptotically Optimal Validated Asynchronous Byzantine Agreement](https://research.vmware.com/files/attachments/0/0/0/0/0/7/8/practical_aba_2_.pdf). I. Abraham, D. Malkhi, A. Spiegelman. PODC'19

[Consensus-BFT] [HotStuff: BFT Consensus with Linearity and Responsiveness](https://www.cs.unc.edu/~reiter/papers/2019/PODC.pdf). M. Yin, I. Abraham, G. Gueta, D. Malkhi, M. Reiter. PODC'19

## SPAA
[Consensus-DAG][Why BlockDAGs Excel Blockchains](https://tik-db.ee.ethz.ch/file/b0a2132681958e4cb69055bab4bf6ad8/The_Append_Memory_Model.pdf). Darya Melnyk and Roger Wattenhofer. SPAA' 20

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

[Application][Blockchain Based Non-repudiable IoT Data Trading: Simpler, Faster, and Cheaper](https://ieeexplore.ieee.org/document/9796857). Fei Chen, Jiahao Wang, Changkun Jiang, Tao Xiang, Yuanyuan Yang. INFOCOM'22.

[Scalability][BrokerChain: A Cross-Shard Blockchain Protocol for Account/Balance-based State Sharding](https://ieeexplore.ieee.org/document/9796859). Huawei Huang, Xiaowen Peng, Jianzhou Zhan, Shenyang Zhang, Yue Lin, Zibin Zheng, Song Guo. INFOCOM'22.

[Scalability][S-Store:: A Scalable Data Store towards Permissioned Blockchain Sharding](https://ieeexplore.ieee.org/document/9796800). Xiaodong Qi. INFOCOM'22.

[Netowrk][Dino: A Block Transmission Protocol with Low Bandwidth Consumption and Propagation Latency](https://ieeexplore.ieee.org/abstract/document/9796837). Zhenxing Hu and Zhen Xiao. INFOCOM'22.

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

[Consensus][Dissecting the Performance of Chained-BFT](https://arxiv.org/abs/2103.00777). Fangyu Gai, Ali Farahbakhsh, Jianyu Niu, Chen Feng, Ivan Beschastnikh, Hao Duan. ICDCS'21

[Consensus][Strengthened Fault Tolerance in Byzantine Fault Tolerant Replication](https://arxiv.org/abs/2101.03715). Zhuolun Xiang, Dahlia Malkhi, Kartik Nayak, Ling Ren. ICDCS'21

[Consensus][Leopard: Towards High Throughput-Preserving BFT for Large-scale Systems](https://ieeexplore.ieee.org/document/9912165). Kexin Hu, Kaiwen Guo, Qiang Tang, Zhenfeng Zhang, Hao Cheng, Zhiyang Zhao. ICDCS'22

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

[Consensus][Marlin: Two-Phase BFT with Linearity](https://eprint.iacr.org/eprint-bin/getfile.pl?entry=2022/551&version=20220516:022614&file=551.pdf). Xiao Sui, Sisi Duan, Haibin Zhang. DSN'22

## CoNEXT
[Consensus-PoW] [On the Necessity of a Prescribed Block Validity Consensus: Analyzing Bitcoin Unlimited Mining Protocol](https://eprint.iacr.org/2017/686.pdf). Ren Zhang, Bart Preneel. CoNEXT '17

[Consensus][Stellar: Network Attack Mitigation using Advanced Blackholing](https://www.de-cix.net/Files/2731074c857497be3827ac9537b6e486f27aa57c/Research-paper-Stellar-Network-Attack-Mitigation-using-Advanced-Blackholing.pdf)(.Christoph Dietzel, Matthias Wichtlhuber, Georgios Smaragdakis, Anja Feldmann. CoNEXT '18

[Mining][Mining the Web with Webcoin](http://networks.cs.northwestern.edu/publications/webcoin/conext18-final22.pdf). Uri Klarman, Marcel Flores, Aleksandar Kuzmanovic. CoNEXT '18

[Application][Blockchain-based Real-time Cheat Prevention and Robustness for Multi-player Online Game](https://dl.acm.org/doi/10.1145/3281411.3281438). Sukrit Kalra, Rishabh Sanghi, Mohan Dhawan. CoNEXT '18

[Layer2][Flash: Efficient Dynamic Routing for Offchain Networks](http://www.cs.jhu.edu/~xinjin/files/CoNEXT19_Flash.pdf). Peng Wang, Hong Xu, Xin Jin, Tao Wang.  CoNEXT '19

## MobiHoc
[Consensus-sharding] [User Distributions in Shard-based Blockchain Network: Queueing Modeling, Game Analysis, and Protocol Design](https://dl.acm.org/doi/abs/10.1145/3466772.3467051). Canhui Chen, Qian Ma, Xu Chen, Jianwei Huang. MobiHoc '21

## PLDI
[Smart Contract][Behavioral Simulation for Smart Contracts](). Sidi Mohamed Beillahi, Gabriela Ciocarlie, Michael Emmi, Constantin Enea. PLDI '2020

[Smart Contract][Ethainter: A Smart Contract Security Analyzer for Composite Vulnerabilities](). Lexi Brent, Neville Grech, Sifis Lagouvardos, Bernhard Scholz, Yannis Smaragdakis. PLDI '2020

[Smart Contract][Securing Smart Contract with Runtime Validation](). Ao Li, Jemin Andrew Choi, Fan Long. PLDI '2020

[Smart Contract][Practical Smart Contract Sharding with Ownership and Commutativity Analysis]() George Pîrlea, Amrit Kumar, Ilya Sergey. PLDI '2021

## SOCC
[Network] [Gosig: A Scalable and High-Performance Byzantine Consensus for Consortium Blockchains](https://www.cs.toronto.edu/~fanl/papers/gosig-socc20.pdf). Peilun Li, Guosai Wang, Xiaoqi Chen, Fan Long, Wei Xu. SOCC'21.

[Network] [Shrec: Bandwidth-Efficient Transaction Relay in High-Throughput Blockchain Systems](https://www.cs.toronto.edu/~fanl/papers/shrec-socc20.pdf). Yilin Han, Chenxing Li, Peilun Li, Ming Wu, Dong Zhuo, Fan Long. SOCC'21.

## OOPSLA
[Smart Contract] [MadMax: Surviving Out-of-Gas Conditions in Ethereum Smart Contracts](https://dl.acm.org/doi/10.1145/3276486).  Neville Grech, Michael Kong, Anton Jurisevic, Lexi Brent, Bernhard Scholz, Yannis Smaragdakis. OOPSLA '18.

[Smart Contract] [Safer smart contract programming with Scilla](https://dl.acm.org/doi/10.1145/3360611). Ilya Sergey, Vaivaswatha Nagaraj, Jacob Johannsen, Amrit Kumar, Anton Trunov, Ken Chan Guan Hao. OOPSLA '19.

[Smart Contract] [Detecting Nondeterministic Payment Bugs in Ethereum Smart Contracts](https://home.cse.ust.hk/~shuaiw/papers/oopsla19.pdf). Shuai Wang, Chengyu Zhang, Zhendong Su. OOPSLA '19.

[Smart Contract] [Precise static modeling of Ethereum ”memory“](https://dl.acm.org/doi/10.1145/3428258). Sifis Lagouvardos, Neville Grech, Ilias Tsatiris, Yannis Smaragdakis. OOPSLA '20.

[Smart Contract] [Rich Specifications for Ethereum Smart Contract Verification](https://dl.acm.org/doi/10.1145/3485523). Christian Bräm, Marco Eilers, Peter Müller, Robin Sierra, Alexander J. Summers. OOPSLA '21.

[Smart Contract] [Symbolic Value-Flow Static Analysis: Deep, Precise, Complete Modeling of Ethereum Smart Contracts](https://dl.acm.org/doi/10.1145/3485540). Yannis Smaragdakis, Neville Grech, Sifis Lagouvardos, Konstantinos Triantafyllou, Ilias Tsatiris. OOPSLA '21.

[Smart Contract] [Elipmoc: advanced decompilation of Ethereum smart contracts](https://dl.acm.org/doi/10.1145/3527321). Neville Grech, Sifis Lagouvardos, Ilias Tsatiris, Yannis Smaragdakis. OOPSLA '22.

## ICDE
[Storage] [CUB, a Consensus Unit-Based Storage Scheme for Blockchain System](https://ieeexplore.ieee.org/abstract/document/8509246). Zihuan Xu, Siyuan Han, Lei Chen. 2018.

[Database] [SEBDB:Semantics Empowered BlockChain DataBase](https://ieeexplore.ieee.org/abstract/document/8731416). Yanchao Zhu, Zhao Zhang, Cheqing Jin, Aoying Zhou, Ying Yan. 2019.

[Query] [Authenticated Keyword Search in Scalable Hybrid-Storage Blockchains](https://ieeexplore.ieee.org/abstract/document/9458753). Ce Zhang, Cheng Xu, Haixin Wang, Jianliang Xu, Byron Choi. 2021.

## FC
[Economic-PoW] [Majority Is Not Enough: Bitcoin Mining Is Vulnerable](https://arxiv.org/pdf/1311.0243). Eyal I, Sirer EG. FC '14.

[Consensus-PoW] [Secure High-Rate Transaction Processing in Bitcoin](http://www.cs.huji.ac.il/~avivz/pubs/15/btc_ghost_full.pdf). Sompolinsky Y, Zohar A. FC '15.

[ChainStructure][Inclusive Block Chain Protocols](https://fc15.ifca.ai/preproceedings/paper_101.pdf). Yoad Lewenberg, Yonatan Sompolinsky, Aviv Zohar. FC '15.

[Consensus] [Cryptocurrencies without Proof of Work](http://fc16.ifca.ai/bitcoin/papers/BGM16.pdf). Bentov I, Gabizon A, Mizrahi A. FC '16.

[Economic-PoW] [Optimal Selfish Mining Strategies in Bitcoin](http://fc16.ifca.ai/preproceedings/30_Sapirshtein.pdf). Sapirshtein A, Sompolinsky Y, Zohar A. FC '16.

[Consensus-PoS] [A Proof-of-Stake protocol for consensus on Bitcoin subchains](http://eprint.iacr.org/2017/417.pdf). Bartoletti M, Lande S, & Podda A S. FC '17.

[Transaction-Prioritization-MEV] [Dissecting Bitcoin and Ethereum Transactions: On the Lack of Transaction Contention and Prioritization Transparency in Blockchains](https://fc23.ifca.ai/preproceedings/8.pdf). Johnnatan Messias, Vabuk Pahari, Balakrishnan Chandrasekaran, Krishna P. Gummadi, and Patrick Loiseau. FC' 23.

[FC Accepted Paper Link:] [FC'15](https://fc15.ifca.ai/schedule.html), [FC'16](https://fc16.ifca.ai/program.html), [FC'17](https://fc17.ifca.ai/program.html), [FC'18](https://fc18.ifca.ai/program.html), [FC'19](https://fc19.ifca.ai/program.html). [FC'20](https://fc20.ifca.ai/), [FC'21](https://fc21.ifca.ai/), [FC'22](https://fc22.ifca.ai/program.html), [FC'23](https://fc23.ifca.ai/program.html).

## EC
[Economic-PoW] [An Economic Analysis of Difficulty Adjustment Algorithms in Proof-of-Work Blockchain Systems](https://econ.hkbu.edu.hk/eng/Doc/Shunya_NODA_POW.pdf). Shunya Noda, Kyohei Okumura and Yoshinori Hashimoto. EC '20.

## IMC
[Transaction-Prioritization] [Selfish & Opaque Transaction Ordering in the Bitcoin Blockchain: The Case for Chain Neutrality](https://dl.acm.org/doi/10.1145/3487552.3487823). Johnnatan Messias, Mohamed Alzayat, Balakrishnan Chandrasekaran, Krishna P. Gummadi, Patrick Loiseau, and Alan Mislove. IMC '21.

[Defi] [A flash(bot) in the pan: measuring maximal extractable value in private pools](https://dl.acm.org/doi/abs/10.1145/3517745.3561448). Ben Weintraub, Christof Ferreira Torres, Cristina Nita-Rotaru, and Radu State. IMC '22.

<!--
## Journals

## TKDE
[Smart Contract] [A High Performance Concurrency Protocol for Smart Contracts of Permissioned Blockchain](https://ieeexplore.ieee.org/document/9356389). Cheqing Jin, Shuaifeng Pang, Xiaodong Qi, Zhao Zhang, and Aoying Zhou. 2021.

[Storage] [A Reliable Storage Partition for Permissioned Blockchain](https://ieeexplore.ieee.org/document/9152150). Xiaodong Qi, Zhao Zhang, Cheqing Jin, and Aoying Zhou. 2021.

## ACMCSUR
[Layer2] [A Survey on Blockchain Interoperability: Past, Present, and Future Trends](https://dl.acm.org/doi/10.1145/3471140). Rafael Belchior, André Vasconcelos, Sérgio Guerreiro, Miguel Correia. 2021.

## ACMDLT
[Layer2] [Do You Need a Distributed Ledger Technology Interoperability Solution?](https://dl.acm.org/doi/10.1145/3564532). Rafael Belchior, Luke Riley, Thomas Hardjono, André Vasconcelos, Miguel Correia. 2022.

## JSAC
[Network] [TIPS: Transaction Inclusion Protocol with Signaling in DAG-based Blockchain](https://arxiv.org/pdf/2207.04841.pdf). Canhui Chen, Xu Chen, Zhixuan Fang. 2022.

## TNSE
[Consensus-PoW] [Impact of temporary fork on the evolution of mining pools in blockchain networks: An evolutionary game analysis](https://arxiv.org/pdf/2011.07238.pdf). Canhui Chen, Xu Chen, Jiangshan Yu, Weigang Wu, Di Wu. 2020.
-->

## License
[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)


This list is released into the public domain.
