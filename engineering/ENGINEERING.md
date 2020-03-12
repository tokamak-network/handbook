# 엔지니어링

## 목차

* [공통사항](#공통사항)
  * [커뮤니케이션](#커뮤니케이션)
  * [온더 레포지토리](#온더-레포지토리)
  * [코드 품질과 표준](#코드-품질과-표준)
  * [데모](#데모)
  * [코드리뷰](#코드리뷰)
  * [개발 리소스](#개발-리소스)
  * [아마존 웹 서비스](#아마존-웹-서비스)
  * [네이버 클라우드](#네이버-클라우드)
* [개발자 OJT 프로그램](#개발자-ojt-프로그램)
* [스마트 컨트렉트](#스마트-컨트렉트)
  * [스마트 컨트렉트 개발팀의 비전과 목표](#스마트-컨트렉트-개발팀의-비전과-목표)
  * [ICO와 토큰](#ICO와-토큰)
  * [오디팅(auditing)](#오디팅)
* [코어 개발](#코어-개발)
* [리서처](#리서처)
* [프론트엔드](#프론트엔드)

## 공통사항

### 커뮤니케이션

1. [슬렉 채널](https://onther.slack.com/messages/G9Y5915B7/) : 깃헙에 issue로 낼 만한 것이 아니면, #dev 채널을 주요한 커뮤니케이션 수단으로 사용한다.
2. [온더 깃헙](https://github.com/Onther-Tech) : 온더의 모든 프로젝트는 클라이언트의 특별한 요구가 없는 한 public으로 작업한다.

### 온더 레포지토리

온더는 수 많은 [프로젝트](#프로젝트)들로 이루어져 있다. 각각의 [프로젝트](#프로젝트)는 (일반적으로)깃헙 레포지토리를 생성하며, 이 목록은 [온더 깃헙](https://github.com/onther-tech)에서 확인할 수 있다.
레포지토리는 프로젝트의 역할을 상속한다.

새로운 레포지토리를 만들 때에는 다음의 절차를 밟는다.

(초안, 작업중)

1. github.com/onther-tech 네임스페이스 아래에 만들었는지 확인한다.
2. 깃헙에 프로젝트명으로 레포지토리를 추가한다.
3. 온더 구글 드라이브에 진행중 프로젝트에 프로젝트 폴더를 생성한다.

### 코드 품질과 표준

우리는 코드의 품질을 유지하고, 표준을 지켜야 한다. 온더의 [개발 가이드]()를 준수해야 하며, 그룹별로 다음의 가이드 문서를 따른다.

* [스마트 컨트렉트 가이드]()
* [코어 개발 가이드]()
* [리서칭 가이드]()

### 데모

[동작하는 소프트웨어는 진행도를 나타내는 가장 중요한 척도](http://agilemanifesto.org/principles.html)라는 아이디어는 에자일의 중요한 원칙 중 하나다. 데모를 통해서 프로젝트의 버그를 더 쉽게 찾을 수 있고, 불확실한 부분을 더욱 분명히 할 수 있다. 또한 데모는 팀원들에게 가장 손쉬우면서도 투명하게 [결과물]()을 알릴 수 있는 방법이다. **개발자는 적어도 매주 1번 이상의 데모([세미나](https://github.com/Onther-Tech/handbook/blob/master/general/WorkProcess.md#%EC%84%B8%EB%AF%B8%EB%82%98))를 팀장과 팀원에게 보여야 한다.** 데모 미팅은 30분 이내로 이뤄진다. 중요한 점은 데모가 얼마나 디테일하게 만들어졌느냐가 아니라 요구사항이 얼마나 반영되었고, 제품 및 서비스의 목적에 충실하느냐의 측면에 중점을 두어야 한다는 점이다.

### 코드리뷰

머지 요청(merge request)를 할 때에 코드리뷰는 필수다. [코드리뷰 가이드]() 참조

### 개발 리소스

리소스를 사용할 때에는 다음의 원칙을 따른다:

* 항상 비용을 고려하고, 줄일 수 있으면 줄여라
* 누구든 얼마든지 머신을 늘릴 수 있다
* 일을 마치고, 이를 제거하는 것은 만든 사람이 책임진다. 사용하지 않으면 지워라.
* 만약 오래도록 사용하지 않는 머신이 발견되면, 이를 만든 사람에게 쓰는건지 안쓰는건지 물어봐라.
* 인스턴스의 가장 앞에 본인의 이름을 넣어라. 예를들어 이름이 kevin이면, ex) kevin-machine-for-testing

#### 아마존 웹 서비스

1. 키 관리 : 아마존 웹서비스의 키는 --에 있으며, 누구든 이에 접근해 사용할 수 있다.
<!-- 2. -->

#### 네이버 클라우드

<!-- 1.
2. -->

### 프로젝트

프로젝트는 프로젝트 오너(owner), 메인테이너(maintainer), 리뷰어(reviewer) 등 최소한 3개 이상의 롤을 가진 팀으로 구성된다.프로젝트를 통해 생성된 각각의 레포지토리는 이 롤을 그대로 상속한다.

* 프로젝트 오너(owner) : 프로젝트의 목적과 비전을 제시하고, 주요 자원을 할당하고, 업무의 우선순위를 정하고 일정을 제어한다.

* 메인테이너(maintainer) : 메인 개발자. 소스 코드의 구조(산출물의 검수), 사용된 Framework, 개발 환경 등 저장소에 포함된 모든 내용물들을 숙지, 특히나 pull request를 통한 merge여부를 최종 결정한다. 메인테이너는 직접 commit할 수 있다.

* 리뷰어(reviewer) : 다수의 이슈와 리뷰가 동시다발적으로 이뤄질 때, 메인테이너를 보조하는 역할. 이슈 트레킹, pull request에 대한 의견을 내고 메인테이너를 계속 멘션하여 프로젝트 진행을 도움.


## 개발자 OJT 프로그램
온더의 모든 개발자는 맡은 직무와 관계없이 이더리움을 포함한 블록체인 전반에 대한 기초적인 원리와 개념을 이해해야 한다. 또한, 직무에 따라 특정 주제에 대한 심화적인 이해가 반드시 필요하다. 이를 위해 온더는 새롭게 합류한 개발자 팀원에게 최고의 OJT 프로그램을 제공한다. 이에 대한 자세한 내용은 아래와 같다. 단, 본인의 경력을 이미 증명 했다면, 아래의 과정은 일부 생략될 수 있다.

* [General](#General)
* [Bitcoin](#Bitcoin)
* [Ethereum](#Ethereum)
* [Research](#Research)
* [Project-Tokamak Network](#Project-Tokamak-Network)
* [Project-zk-DEX](#Project-zk-DEX)

대부분의 주제는 자기 주도 학습으로 진행되며, 학습의 결과는 세미나, 원페이퍼, 테스트, 미니프로젝트 등으로 팀원과 함께 공유한다. OJT의 목적은 배움과 성장으로, 평가의 목적이 아니다. 따라서 공유한 학습의 결과물을 바탕으로 업무능력에 대한 어떠한 평가도 하지 않는다. 또한, 각 학습주제별로 특정 학습 결과물 공유 방식이 권장되지만, 반드시 이를 따르지 않아도 된다.


### 학습 결과물 공유
세미나는 학습한 내용을 슬라이드 등으로 정리하여 발표하는 것을 의미한다. 원페이퍼는 어떠한 형태로든 자신이 공부한 내용을 스스로 정리하여 문서화하는 것을 의미한다. 반드시 하나의 페이퍼에 정리되어야 할 필요는 없다. 테스트는 온더 내부에서 작성된 테스트 문항을 통해 진행된다. 테스트 결과는 어떠한 형태로든 평가의 수단으로 사용 되지 않는다. 미니프로젝트는 특정 주제에 한하여 실제 진행되고 있는 업무와 비슷한 성격을 가진 단순한 프로젝트를 짧은 기간 동안 수행하는 것을 의미한다.




### General

General에서 다루는 내용들은 팀에 대한 소개와 사업방향 등으로, 내부 팀원이 직접 소개한다.

#### Introduction

1. [온더 회사소개(onther.io계정필요)](https://drive.google.com/drive/folders/0B5sY8bbGT-SNamU4N2thOVRsT0U?usp=sharing) : 회사에 관한 일반사항, 사업분야, 진행했던 프로젝트, 대표자 이력 등
2. [Ignite(30 min)](https://docs.google.com/presentation/d/1S3AmvyrEJOjyc6oQWiBr_qfZjR_RMCFiakeM1fbBblQ/edit#slide=id.g78e1bb24ee_0_6): 온더가 하고자 하는 비즈니스와 해당 업의 본질
3. [Understanding Smart Contract](https://docs.google.com/presentation/d/1YSlrtG4FFYagcniBc13prmUBUOWY04XrKatIxm2OJ_4/edit?usp=sharing) : 스마트 컨트렉트란 무엇이며 어떻게 세상을 바꿀 것인가?

#### Blockchain

- [탈중앙화 의의와 함의(30min)](https://docs.google.com/presentation/d/1kNQxJgbaTSx93R3owcYAtdQZnx3IBEiU8HfXmUlsDQc/edit?usp=sharing)
- [퍼블릭 블록체인 vs 프라이빗 블록체인(30min) —> 탈중앙화의 레벨, 수준, 정도](https://docs.google.com/presentation/d/1bQiA_cObRb_ZfsBiuxagE5McRO9RDPMz2cs-2jOq0xM/edit?usp=sharing)
- [엔터프라이즈 이더리움의 토카막 네트워크(20min) —> BM](https://docs.google.com/presentation/d/1Hkw_PC0AvpjC-_XHQL5GOdhkJUgLOKGRn6DkXZ-w6ao/edit?usp=sharing)
- [블록체인 기업의 핵심 역량](https://medium.com/onther-tech/%EB%B8%94%EB%A1%9D%EC%B2%B4%EC%9D%B8-%EA%B8%B0%EC%97%85%EC%9D%98-%ED%95%B5%EC%8B%AC-%EC%97%AD%EB%9F%89-3210cf8651eb)


### Bitcoin

**Why study?**
비트코인은 모든 블록체인들의 출발점으로 블록체인의 가장 핵심적이고 기본적인 원리만을 단순화하여 배울 수 있는 가장 좋은 재료이다.


#### Bitcoin
|Topics|Difficulty|Tags|Remarks|
|---|---|---|---|
|  [Mastering Bitcoin](https://github.com/bitcoinbook/bitcoinbook/blob/develop/book.asciidoc)   |  Basic |  seminar, one-paper, test  |    |
|  [Bitcoin Whitepaper](https://bitcoin.org/bitcoin.pdf)   |  Basic |  seminar, one-paper  |    |
|  [블록체인 기반기술의 이해 1편](https://youtu.be/yoAAZcXPx7k)   |  Basic |  one-paper, test  |    |
|  [블록체인 기반기술의 이해 2편](https://youtu.be/Ix-4Ul37WWE)   |  Basic |  one-paper, test  |    |
|  [Bitcoins the hard way: Using the raw Bitcoin protocol](http://www.righto.com/2014/02/bitcoins-hard-way-using-raw-bitcoin.html)   |  Advanced |  seminar, one-paper, test  |    |
|  [Bitcoin mining the hard way: the algorithms, protocols, and bytes](http://www.righto.com/2014/02/bitcoin-mining-hard-way-algorithms.html)   |  Advanced |  seminar, one-paper, test  |    |


#### Bitcoin Core
|Topics|Difficulty|Tags|Remarks|
|---|---|---|---|
|  [Bitcoin Transaction and Script by Thomas Shin](https://docs.google.com/presentation/d/11c2c40zXyXU3kIwhA8F0_US_zvECpD_lW1xRz4OVsgY/edit#slide=id.p3)   |  Advanced |  one-paper, test  |    |
|  [Bitcoin OP_RETURN by Thomas Shin](https://docs.google.com/presentation/d/1H46MtFgLbP7_GWI4AOoz4YaWvni79lo56IjBrUk__6o/edit?usp=sharing)   |  Advanced |  one-paper, test  |    |
|  [Bloom Filter by Jason](https://docs.google.com/presentation/d/1FipuUsbBBL_lCcIcvHRrZQ6sspB17R2AWucKY0zHrt8/edit?usp=sharing)   |  Advanced |  one-paper, test  |    |


### Ethereum

#### Ethereum-General
|Topics|Difficulty|Tags|Remarks|
|---|---|---|---|
|  [Mastering Ethereum](https://github.com/ethereumbook/ethereumbook)   |  Basic |  seminar, one-paper, test  |    |
|  [Ethereum Whitepaper](https://github.com/ethereum/wiki/wiki/%5BKorean%5D-White-Paper)   |  Basic |  seminar, one-paper  |    |
|  [Ethereum Yellowpaper](http://gavwood.com/paper.pdf)   |  Advanced |  seminar, one-paper, test  |    |
|  [RLP씹어먹기](https://docs.google.com/presentation/d/1nSoRv4hCmona_N1VENZdZ_POVV-LZpxOSNBntareZuA/edit?usp=sharing)   |  Advanced |  seminar, one-paper, test  |    |
|  [머클과 머클 패트리샤 트리](https://docs.google.com/presentation/d/1J8vbpvo7E8B0-h9uHsm7Sp94g3CA2VjjvTIqVNucwyg/edit?usp=sharing)   |  Advanced |  seminar, one-paper, test  |    |




#### Ethereum-Smart Contract
|Topics|Difficulty|Tags|Remarks|
|---|---|---|---|
|  [Ethereum and Solidity: The Complete Developer's Guide](https://www.udemy.com/ethereum-and-solidity-the-complete-developers-guide/)   |  Basic |  one-paper  |    |
|  [Truffle](https://docs.google.com/presentation/d/1ONHk1ZwNXPe9650Nivv9xaNdN9ec45X22D136RyLAME/edit?usp=sharing)   |  Basic |  one-paper  |    |
|  [Zeppelin Solidity](https://github.com/OpenZeppelin/zeppelin-solidity)   |  Basic |  seminar, one-paper  |    |
|  [늑대 컨트렉트](https://docs.google.com/presentation/d/16MaPJcTZ3IV9KNd_N_KvGpWhtYrQelsXFBEtw0468fE/edit?usp=sharing)   |  Basic |  one-paper  |    |
|  [변장한 늑대](https://medium.com/onther-tech/%EB%B3%80%EC%9E%A5%ED%95%9C-%EB%8A%91%EB%8C%80-%EC%8A%A4%EB%A7%88%ED%8A%B8%ED%95%98%EC%A7%80-%EB%AA%BB%ED%95%9C-%EC%8A%A4%EB%A7%88%ED%8A%B8-%EA%B3%84%EC%95%BD-45ece882e2b3)   |  Basic |  one-paper  |    |
|  [DAICO](https://docs.google.com/presentation/d/1vcFjuHobwt2Q7A_wQOTUakkujWqh-8lGGsFBoARCusk/edit?usp=sharing)   |  Basic |  one-paper  |    |
|  [Minime Token](https://github.com/Giveth/minime)   |  Advanced |  one-paper  |  [Minime Token by Thoms.s](https://docs.google.com/presentation/d/1BFGDuX1nM_H8u-v6INLmEWFa5wmRpXx5prYqvl4R1_E/edit?usp=sharing)  |
|  [Zeppline Audit Blog](https://blog.zeppelin.solutions/tagged/security)   |  Advanced |  seminar, one-paper  |    |
|  [Consensys Smart Contract Security Best Practices](https://consensys.github.io/smart-contract-best-practices/)   |  Advanced |  seminar, one-paper  |    |
|  [Auditing Smart Contract by 4000D](https://docs.google.com/presentation/d/1I5JjEVCFsD6UbKOLERQ8pOTsF2fEsnj5RBcDKU_aozc/edit?usp=sharing)   |  Advanced |  one-paper  |    |
|  [실제 오딧 보고서(onther.io계정 필요)](https://docs.google.com/document/d/1aCZ2MowRnpd_GZ-pH0jIS7IQ5ZJXiGKgYxReCDtk1Fc/edit?usp=sharing)   |  Advanced |  one-paper  |    |




#### Ethereum - Client
|Topics|Difficulty|Tags|Remarks|
|---|---|---|---|
|  [A Tour of Go](https://tour.golang.org/welcome/1)   |  Basic |  one-paper  |    |
|  [JSON RPC](https://infura.io/docs)([Alt1](https://github.com/ethereum/wiki/wiki/JSON-RPC), [Alt2](https://github.com/ethereum/go-ethereum/wiki/JavaScript-Console))   |  Basic |  seminar, mini-project  |  [Implementation1](https://github.com/ethereum/go-ethereum/blob/d90d1db609c8d77baa422d49bd371207c06b4711/internal/ethapi/backend.go) [Implementation2](https://github.com/ethereum/go-ethereum/blob/38d1b0cba277db17129a4870158115c5a428cffc/eth/backend.go) |
|  [4000d의 go-ethereum 코어 패키지 리스팅자료](https://docs.google.com/spreadsheets/d/1QJOnkI-qRb8CtJcZqeU_OxyGqCoFFIE5cx564XObIVE)   |  Advanced |  seminar, one-paper  |    |
|  [go-ethereum 분석 1 - Carl(4000d)](https://drive.google.com/open?id=1gDCJEYr_xyxRpftQh_ZxVixoNtsxebKTr_TUBkO7CH8)   |  Advanced |  seminar, one-paper  |    |
|  [go-ethereum 분석 2 - Carl(4000d)](https://docs.google.com/presentation/d/1pTVHwC63HrIkLjD8s7z0OcdUv-HGGGQpqUR4Kocxg_w)   |  Advanced |  seminar, one-paper  |    |
|  [geth 실행 로직 - Aiden](https://docs.google.com/presentation/d/1io_gKpVOOg8UCSd-tQqKQJ4hLo3crRicU1bMZpRJ3jg)   |  Advanced |  seminar, one-paper  |    |
|  [go-ethereum 씹어먹기 #0 : Package Overview - Aiden](https://docs.google.com/presentation/d/1hD5Q1B9J1BXBh5WvnpNgccQR2CKK7p-eQe2NPR9wO4s)   |  Advanced |  seminar, one-paper  |    |
|  [go-ethereum 씹어먹기 #1 : Node - Aiden](https://docs.google.com/presentation/d/1XJrLDnx_7fzy8xsxJev-OZpfGCXD6gr4dd5cENuzKOk)   |  Advanced |  seminar, one-paper  |    |
|  [go-ethereum 씹어먹기 #2 : Mining & P2p - Aiden](https://docs.google.com/presentation/d/1eKrgv1YotLCM1bD4_BOgWibP3a4t8Uz2mWAFdSyMkYY)   |  Advanced |  seminar, one-paper  |    |
|  [Geth Package 분석 : state, trie, internal/ethapi, rawdb, ethdb - Jason](https://docs.google.com/presentation/d/1_9TZJEB--JmaU4T78If_vwvNcKls2vBUVnXqZqkUylQ)   |  Advanced |  seminar, one-paper  |    |
|  [Geth Package 분석 : cmd/geth - Thomas](https://drive.google.com/open?id=1WFaWG3DRrKES6YrhFyLIvumn8PuLarmw55jek_8vzuo)   |  Advanced |  seminar, one-paper  |    |
|  [Geth Package 분석 : /eth, /core, /core/vm - Thomas](https://docs.google.com/presentation/d/1UE4mMz7395pZmVOhFecnNv33AN0sGaNsmyr0hB2uNDs)   |  Advanced |  seminar, one-paper  |    |
|  [Geth Package 분석 : /miner, /worker - Thomas](https://drive.google.com/open?id=1rQngQ0d6GaFMuxTCW5gZ2O12MZpqZzx9UpLcle9I6XQ)   |  Advanced |  seminar, one-paper  |    |
|  [Geth Package 분석 : p2p Layer - Thomas](https://drive.google.com/open?id=1GmdQjJoomJcaSc9vu3e4DVo9iLSow1vAqzUKtHZUAbM)   |  Advanced |  seminar, one-paper  |    |
|  [Geth Package 분석 : Txpool - Thomas](https://drive.google.com/open?id=1MYcwJOyi_FbAVufuEu___gvTmLuGcm_7jD7MZMG0KsY)   |  Advanced |  seminar, one-paper  |    |
|  [Geth Package 분석 : params, core/vm, ethdb, trie - Jake](https://docs.google.com/presentation/d/1DUqRdXDYNWnGcJsvN3M-0Ll8BJ09ZroSYl5BCh7yMt0)   |  Advanced |  seminar, one-paper  |    |
|  [Geth Package 분석 : fetcher, downloader, rawdb, ethdb - Jin](https://drive.google.com/open?id=1Wtv_BoYGeM6ocA3XsP-6JINkzW1ETOSvOdKjavkJpjc)   |  Advanced |  seminar, one-paper  |    |



### Research


#### Layer-2(Plasma)

|Topics|Difficulty|Tags|Remarks|
|---|---|---|---|
|  [Plasma 가볍게 훑어보기](http://blog.onther.io/ethereum/scalability/plasma/plasma-general/)   |  Basic |  one-paper  |    |
|  [Plasma 101 : Let’s Scale with Cryptoeconomics](https://medium.com/onther-tech/plasma-101-lets-scale-with-cryptoeconomics-ee0c9fac4989)   |  Basic |  one-paper  |    |
|  [Plasma 102 : Detail Structure and Use Cases](https://medium.com/onther-tech/plasma-102-detail-structure-and-use-cases-914507781bd4)   |  Basic |  one-paper  |    |
|  [State Channel Basic](http://blog.onther.io/ethereum/scalability/statechannel/state-channel-basic/)   |  Basic |  one-paper  |    |
|  [Plasma Whitepaper](https://www.plasma.io/plasma.pdf)   |  Advanced |  one-paper  |    |
|  [Deep Dive Into Plasma MVP](http://blog.onther.io/ethereum/scalability/plasma/Deep-Dive-Into-Plasma-MVP/)   |  Advanced |  one-paper  |    |
|  [Plasma ERC721 implementation (Loomnetwork)](https://medium.com/onther-tech/plasma-erc721-implementation-loomnetwork-9f8ec59bb25b)   |  Advanced |  one-paper  |    |
|  [Data Availability problem in implementing Plasma design](https://medium.com/onther-tech/data-availability-problem-in-implementing-plasma-design-6e23df1a147f)   |  Advanced |  one-paper  |    |
|  [일반상태(튜링완전) 플라즈마 관련 연구 분석](http://blog.onther.io/ethereum/scalability/plasma/analysis-of-general-state-plasma-models/)   |  Advanced |  one-paper  |    |
|  [Plasma World Map](http://blog.onther.io/ethereum/scalability/plasma/Plasma-World-Map/)   |  Advanced |  one-paper  |    |
|  [Zero Knowledge Proof and Plasma](http://blog.onther.io/ethereum/scalability/zkp/Zero-Knowledge-Proof-and-Plasma/)   |  Advanced |  one-paper  |    |





#### Ethereum 2.0


|Topics|Difficulty|Tags|Remarks|
|---|---|---|---|
|  [ETH 2.0 Explained: Phase 0](https://medium.com/onther-tech/%EC%9D%B4%EB%8D%94%EB%A6%AC%EC%9B%802-0-%EA%B9%8A%EC%9D%B4%EB%B3%B4%EA%B8%B0-%EC%8B%9C%EB%A6%AC%EC%A6%88-eth-2-0-explained-phase-0-1%ED%8E%B8-74ee5659a40a)   |  Advanced |  one-paper  |    |
|  [Cross Shard Communication -1- 비동기 커뮤니케이션](https://medium.com/onther-tech/%EC%9D%B4%EB%8D%94%EB%A6%AC%EC%9B%802-0-%EA%B9%8A%EC%9D%B4%EB%B3%B4%EA%B8%B0-%EC%8B%9C%EB%A6%AC%EC%A6%88-cross-shard-communication-async-2%ED%8E%B8-ac78e921e8a4)   |  Advanced |  one-paper  |    |
|  [Cross Shard Communication -2- 동기 커뮤니케이션](https://medium.com/onther-tech/%EC%9D%B4%EB%8D%94%EB%A6%AC%EC%9B%802-0-%EA%B9%8A%EC%9D%B4%EB%B3%B4%EA%B8%B0-%EC%8B%9C%EB%A6%AC%EC%A6%88-cross-shard-communication-sync-3%ED%8E%B8-cbff047e8f0d)   |  Advanced |  one-paper  |    |
|  [CBC casper explained (1/2)](https://medium.com/onther-tech/cbc-casper-explained-1-2-59fe82a00769)   |  Advanced |  one-paper  |    |
|  [CBC casper explained (2/2)](https://medium.com/onther-tech/%EC%9D%B4%EB%8D%94%EB%A6%AC%EC%9B%802-0-%EA%B9%8A%EC%9D%B4%EB%B3%B4%EA%B8%B0-%EC%8B%9C%EB%A6%AC%EC%A6%88-cbc-casper-explained-2-2-5%ED%8E%B8-458bc3eb24f1)   |  Advanced |  one-paper  |    |
|  [ETH 2.0 Explained: Phase 1](https://medium.com/onther-tech/%EC%9D%B4%EB%8D%94%EB%A6%AC%EC%9B%802-0-%EA%B9%8A%EC%9D%B4%EB%B3%B4%EA%B8%B0-%EC%8B%9C%EB%A6%AC%EC%A6%88-eth-2-0-explained-phase-1-6%ED%8E%B8-cf65c5c0b924)   |  Advanced |  one-paper  |    |
|  [스태이트리스 클라이언트(Stateless Client)](https://medium.com/onther-tech/%EC%9D%B4%EB%8D%94%EB%A6%AC%EC%9B%802-0-%EA%B9%8A%EC%9D%B4%EB%B3%B4%EA%B8%B0-%EC%8B%9C%EB%A6%AC%EC%A6%88-%EC%8A%A4%ED%83%9C%EC%9D%B4%ED%8A%B8%EB%A6%AC%EC%8A%A4-%ED%81%B4%EB%9D%BC%EC%9D%B4%EC%96%B8%ED%8A%B8-stateless-client-7%ED%8E%B8-b2e96d9f071b)   |  Advanced |  one-paper  |    |
|  [ETH 2.0 Explained: Phase 2](https://medium.com/onther-tech/%EC%9D%B4%EB%8D%94%EB%A6%AC%EC%9B%802-0-%EA%B9%8A%EC%9D%B4%EB%B3%B4%EA%B8%B0-%EC%8B%9C%EB%A6%AC%EC%A6%88-eth-2-0-explained-phase-2-8%ED%8E%B8-b9efc2dfe9e)   |  Advanced |  one-paper  |    |
|  [Execution Environment](https://medium.com/onther-tech/%EC%9D%B4%EB%8D%94%EB%A6%AC%EC%9B%802-0-%EA%B9%8A%EC%9D%B4%EB%B3%B4%EA%B8%B0-%EC%8B%9C%EB%A6%AC%EC%A6%88-eth-2-0-explained-execution-environment-9%ED%8E%B8-17ff1ead2f9f)   |  Advanced |  one-paper  |    |
|  [Ethereum 2.0 - Randomness](http://blog.onther.io/ethereum/scalability/ethereum2.0/Ethereum-2.0-Randomness/)   |  Advanced |  one-paper  |    |




### Project-Tokamak Network
Tokamak Network와 zk-DEX는 온더의 주요 프로젝트로 아래의 모든 내용들에 대해 완벽하게 숙지해야 한다. 각자의 직무에 따라 관련 주제별로 미니프로젝트를 진행할 수 있다.


### Intro
- [Tokamak Network : Turing Complete Plasma Chain](https://youtu.be/T8DmzygngQA)
- Plasma EVM for dummies: [slide](https://docs.google.com/presentation/d/1zcNkME2jpMtKJsIER5CUiRtEsfnejol6snfcfzlhRW8/edit?usp=sharing), [video](https://youtu.be/qWovBjf5wXI)
- [Plasma EVM Basic(by Carl Park)](https://docs.google.com/presentation/d/14MAgkUFH_lq9Q_X-gXh61GbJatfdfHqc3R45480F-K0/edit?usp=sharing)

### Deep Dive
- [Whitepaper](https://github.com/Onther-Tech/papers/blob/master/docs/Tokamak_Whitepaper2(200221).pdf)
- [Techpaper](https://github.com/Onther-Tech/papers/blob/master/docs/tech-paper-kr.pdf)
- [Documentation](https://docs.tokamak.network/)

**Economics**
- Economic Description of Tokamak Network: [Slide](https://docs.google.com/presentation/d/1uG12SYjcPWVCE9JvHBYjMbk5P80KO7CzLt_rkE4h2RM/edit?usp=sharing), [Video](https://www.youtube.com/watch?v=gW7FCiBgBI4&t=2s)
- 토카막 네트워크 이코노믹 페이퍼 : [https://hackmd.io/@dwmnux6AQZWPyG-VSBXm1Q/rJgPxWYTm?type=view](https://hackmd.io/@dwmnux6AQZWPyG-VSBXm1Q/rJgPxWYTm?type=view)

**Comparison with Other Layer-2 Solutions**
- [Plasma vs Rollup vs Sidechain Comparison Memo(60 min)](https://www.notion.so/onther/Plasma-vs-optimistic-zk-Roll-up-5017e5f6044d45b49157d8351c27de88)

**Data availability**
- [(온더콘2)Data availability solution in plasma for global state - Continuous Rebase](http://blog.onther.io/ethereum/scalability/plasma/plsmaevm/DA-solution-continuous-rebase/)

**Computation Challenge**
- [춤추는 철학자의 문제](https://medium.com/onther-tech/%EC%B6%A4%EC%B6%94%EB%8A%94-%EC%B2%A0%ED%95%99%EC%9E%90%EC%9D%98-%EB%AC%B8%EC%A0%9C-%EA%B2%80%EC%A6%9D-%EA%B2%8C%EC%9E%84-%EA%B7%B8%EB%A6%AC%EA%B3%A0-%EC%82%AC%EC%9D%B4%EB%93%9C-%EC%B2%B4%EC%9D%B8%EA%B3%BC-%EB%8D%B0%EC%9D%B4%ED%84%B0-%EA%B0%80%EC%9A%A9%EC%84%B1-dancing-philosophers-problem-verification-game-sidechain-fa2b5e1e0ca3)
- [Let’s play with Truebit(scrypt interactive game)](http://blog.onther.io/ethereum/scalability/Let's-play-with-Truebit/)

**Requestable Contracts**
- [(온더콘2)Examples and Best Practices for Requestable Contracts](http://blog.onther.io/ethereum/scalability/plasma/plsmaevm/Examples-and-Best-Practices-for-Requestable-Contracts/)




### Project-zk-DEX

- [프라이버시를 보장하는 스테이블 코인 zk-DAI 깊게 살펴보기](http://blog.onther.io/ethereum/scalability/zkp/zk-dai-deep-dive/)
- [영지식 증명을 활용한 프라이버시 토큰(zk-ERC20) 구현](http://blog.onther.io/ethereum/scalability/zkp/zk-erc20/)

### Deep Dive
- [zk-DEX paper](https://github.com/Onther-Tech/papers/blob/master/docs/zk_DEX.pdf)
- [zk-DEX slide](https://docs.google.com/presentation/d/10B62tisUkyhA5VvkpDQg8D8Z9NV0WYxZne2RgE-lVOk/edit#slide=id.g5d3ffe1c9f_6_525)