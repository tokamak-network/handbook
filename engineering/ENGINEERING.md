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

[동작하는 소프트웨어는 진행도를 나타내는 가장 중요한 척도](http://agilemanifesto.org/principles.html)라는 아이디어는 에자일의 중요한 원칙 중 하나다. 데모를 통해서 프로젝트의 버그를 더 쉽게 찾을 수 있고, 불확실한 부분을 더욱 분명히 할 수 있다. 또한 데모는 팀원들에게 가장 손쉬우면서도 투명하게 [결과물]()을 알릴 수 있는 방법이다. **개발자는 적어도 매주 1번 이상의 데모([세미나](#세미나))를 팀장과 팀원에게 보여야 한다.** 데모 미팅은 30분 이내로 이뤄진다. 중요한 점은 데모가 얼마나 디테일하게 만들어졌느냐가 아니라 요구사항이 얼마나 반영되었고, 제품 및 서비스의 목적에 충실하느냐의 측면에 중점을 두어야 한다는 점이다.

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

온더의 모든 개발자는 맡은 업무와 상관없이 (이더리움)블록체인에 대한 기초적인 원리와 개념을 이해하고 있어야 한다. 이를 위해 우리는 신입 개발자를 위한 최고의 OJT 프로그램을 가지고 있으며, 이에 대한 자세한 내용은 아래에 적혀져 있다. 다만 본인의 경력(혹은 포트폴리오)을 증명했다면, 아래의 과정은 일부가 건너 뛰어지거나 생략될 수 있다.

* [공통과정](#공통과정)
* [스마트 컨트렉트 테크트리](#스마트-컨트렉트-테크트리)
* [코어 테크트리](#코어-테크트리)
* [리서쳐 테크트리](#리서쳐-테크트리)

### 공통과정
  * 듣는것
    1. [온더 회사소개(onther.io계정필요)](https://drive.google.com/drive/folders/0B5sY8bbGT-SNamU4N2thOVRsT0U?usp=sharing) : 회사에 관한 일반사항, 사업분야, 진행했던 프로젝트, 대표자 이력 등
    2. [사업방향에 관하여(onther.io계정필요)](https://docs.google.com/presentation/d/1S3AmvyrEJOjyc6oQWiBr_qfZjR_RMCFiakeM1fbBblQ/edit?usp=sharing) : 온더가 하고자 하는 비즈니스와 해당 업의 본질
    3. [Understanding Smart Contract](https://docs.google.com/presentation/d/1YSlrtG4FFYagcniBc13prmUBUOWY04XrKatIxm2OJ_4/edit?usp=sharing) : 스마트 컨트렉트란 무엇이며 어떻게 세상을 바꿀 것인가?
    4. [마이너의 이해(onther.io계정필요)](https://docs.google.com/presentation/d/1d8X4KVdYe8JnSHDYajaWCkzBiGaOKgtdbOaKjUoCdpo/edit?usp=sharing) : 마이너에 관한 일반사항, 노드에 대한 이해
    5. [ICO Contract Development Process(onther.io계정필요)](https://docs.google.com/presentation/d/1l_QZyU9dVQb4ejYKAbtEb1ibsUrjV12dxNmbrn0GlNw/edit?usp=sharing) : ICO와 토큰 개발 과정에 대한 이해
    6. [2018 dappchain(onther.io계정필요)](https://docs.google.com/presentation/d/1v_JqyGL9DNrnU9p8kjOZbb6_rfsnyQ-NkQiblYJ8KNo/edit?usp=sharing) : 2018년 온더의 주요 목표 및 프로젝트
  * 직접 하는것 : 비트코인 이해 --> 이더리움 이해 순으로 진행, 혼자 공부하고 [발표자료]() 형식으로 만들어 온라인(오프라인) 세미나를 진행, 세미나 시간은 본인이 정해 구글 캘린더에 공유한 후 슬렉 #notice 채널에 공지, 해당 시간에 누구든지 와서 듣고 묻고 답할 수 있음.
    1. [Mastering Bitcoin](https://github.com/bitcoinbook/bitcoinbook/blob/develop/book.asciidoc) 정리 및 분석
       * 2,4장 정리 후 세미나(1시간)
       * 5,6장 정리 후 세미나(1시간)
       * 7,8장 정리 후 세미나(1시간)
    2. Bitcoin Hardway 블로그 정리
       * [Bitcoins the hard way: Using the raw Bitcoin protocol](http://www.righto.com/2014/02/bitcoins-hard-way-using-raw-bitcoin.html) : 읽고 이해하고 발표(1시간)
       * [Bitcoin mining the hard way: the algorithms, protocols, and bytes](http://www.righto.com/2014/02/bitcoin-mining-hard-way-algorithms.html) : 읽고 이해하고 발표(1시간)
    3. [비트코인 백서](https://bitcoin.org/bitcoin.pdf) : 정리 및 발표(1시간)
    4. [이더리움 백서](https://github.com/ethereum/wiki/wiki/%5BKorean%5D-White-Paper) : 읽고 정리 및 발표(1시간)
    5. [이더리움 베이지 페이퍼](https://github.com/chronaeon/beigepaper/blob/master/beigepaper.pdf) : 읽고 정리 및 발표(1시간)
       * [RLP씹어먹기](https://docs.google.com/presentation/d/1nSoRv4hCmona_N1VENZdZ_POVV-LZpxOSNBntareZuA/edit?usp=sharing)
       * [머클과 머클 패트리샤 트리](https://docs.google.com/presentation/d/1J8vbpvo7E8B0-h9uHsm7Sp94g3CA2VjjvTIqVNucwyg/edit?usp=sharing)
    6. [이더리움 황서](http://gavwood.com/paper.pdf) : 읽고 정리 및 발표(3시간)
       * 황서를 봐야 하는 이유?
       * mathematical notation : 노테이션을 알고 나면 추가적인 알고리즘 / 개념 이해는 더욱 빠르고 정확하게 가능
       * [gitter](https://gitter.im/ethereum/yellowpaper)를 통한 질의응답 가능
       * 빠른 업데이트 : zk-SNARK verification 이 비잔티움 포크 후 precompile contract으로 추가 될 예정
       * public review


### 스마트 컨트렉트 테크트리
  1. Udemy 강의 : [Ethereum and Solidity: The Complete Developer's Guide](https://www.udemy.com/ethereum-and-solidity-the-complete-developers-guide/) 완강, 24시간 소요
  2. [트러플 쓰기](https://docs.google.com/presentation/d/1ONHk1ZwNXPe9650Nivv9xaNdN9ec45X22D136RyLAME/edit?usp=sharing)
  3. [Zeppelin Solidity](https://github.com/OpenZeppelin/zeppelin-solidity) 공부 및 정리
  4. [Minime Token](https://github.com/Giveth/minime) 공부 및 정리
     [Minime Token by Thoms.s](https://docs.google.com/presentation/d/1BFGDuX1nM_H8u-v6INLmEWFa5wmRpXx5prYqvl4R1_E/edit?usp=sharing)
  5. 오디팅(auditing)
     * [제플린의 오딧 블로그](https://blog.zeppelin.solutions/tagged/security) 내용 정리
     * [Consensys Smart Contract Security Best Practices](https://consensys.github.io/smart-contract-best-practices/)
     * [Auditing Smart Contract by 4000D](https://docs.google.com/presentation/d/1I5JjEVCFsD6UbKOLERQ8pOTsF2fEsnj5RBcDKU_aozc/edit?usp=sharing)
     * [실제 오딧 보고서(onther.io계정 필요)](https://docs.google.com/document/d/1aCZ2MowRnpd_GZ-pH0jIS7IQ5ZJXiGKgYxReCDtk1Fc/edit?usp=sharing) 분석
  6. 탈중앙화된 스마트 컨트렉트 설계(개발 윤리)
     * [늑대 컨트렉트](https://docs.google.com/presentation/d/16MaPJcTZ3IV9KNd_N_KvGpWhtYrQelsXFBEtw0468fE/edit?usp=sharing)
     * [DAICO](https://docs.google.com/presentation/d/1vcFjuHobwt2Q7A_wQOTUakkujWqh-8lGGsFBoARCusk/edit?usp=sharing)

### 코어 테크트리

  1. 비트코인 코어
     * [Bitcoin Transaction and Script by Thomas Shin](https://docs.google.com/presentation/d/11c2c40zXyXU3kIwhA8F0_US_zvECpD_lW1xRz4OVsgY/edit#slide=id.p3)
     * [Bitcoin OP_RETURN by Thomas Shin](https://docs.google.com/presentation/d/1H46MtFgLbP7_GWI4AOoz4YaWvni79lo56IjBrUk__6o/edit?usp=sharing)
     * [Bloom Filter by Jason](https://docs.google.com/presentation/d/1FipuUsbBBL_lCcIcvHRrZQ6sspB17R2AWucKY0zHrt8/edit?usp=sharing)

  2. 파이더리움([pyethereum](https://github.com/ethereum/pyethereum))으로 이더리움 코어 까보기
     * [키와 어카운트 까보기](https://github.com/ethereum/pyethereum/blob/develop/ethereum/tools/keys.py)
     * [EVM 까보기](https://github.com/ethereum/pyethereum/blob/develop/ethereum/vm.py)
     * [블록 까보기](https://github.com/ethereum/pyethereum/blob/develop/ethereum/block.py)
     * [메세지와 reciept](https://github.com/ethereum/pyethereum/blob/develop/ethereum/messages.py)
     * [state 까보기](https://github.com/ethereum/pyethereum/blob/develop/ethereum/state.py)
     * [Transaction 까보기](https://github.com/ethereum/pyethereum/blob/develop/ethereum/transactions.py)
     * [옵코드의 종류와 가스테이블](https://github.com/ethereum/pyethereum/blob/develop/ethereum/opcodes.py)
     * [머클 패트리샤 트리](https://github.com/ethereum/pyethereum/blob/develop/ethereum/trie.py)
     * [PoW와 체인](https://github.com/ethereum/pyethereum/tree/develop/ethereum/pow)
     * [precompile 함수](https://github.com/ethereum/pyethereum/blob/develop/ethereum/specials.py)

   3. 고-이더리움([go-ethereum](https://github.com/ethereum/go-ethereum)) 코어 까보기
      * [4000d의 go-ethereum 코어 분석자료](https://docs.google.com/spreadsheets/d/1QJOnkI-qRb8CtJcZqeU_OxyGqCoFFIE5cx564XObIVE/edit?usp=sharing)
      * 주요 로직과 라이브러리를 분석/분해하고 필요한 기능을 하나씩 넣어봄 ex) gas fee를 수정해본다던지

   4. [플라즈마 MVP 분석](https://github.com/omisego/plasma-mvp)
      * [Deep Dive Into Plasm MVP by Kevin](https://docs.google.com/presentation/d/1gLgeA6_o1WTz7PtSrzclmx8moZ9oAxTG5ZJl8U1tgqg/edit?usp=sharing)

### 리서쳐 테크트리
  * [ERC20 시총 상위 100개 코인](https://etherscan.io/tokens)의 ICO모델, 비즈니스모델, 컨트렉트 코드 및 라이브러리를 순서대로 정리
  * [Ethereum Casper의 이해](https://docs.google.com/presentation/d/1Kidwr3VsP8C1wA2a8Pzxtuess-lnLSNx5CMqN1sE3SU/edit?usp=sharing)
  * [Whisper 프로토콜](https://docs.google.com/presentation/d/1zA9_66ywegS3Jl_brus9sfjcElqVzQT1qvYPhyJKsJY/edit?usp=sharing)

## 스마트 컨트렉트 개발팀

### 스마트 컨트렉트 개발팀의 비전과 목표

### ICO와 토큰

### 오디팅

## 코어 개발

### 코어 개발팀의 비전과 목표

### 플라즈마

## 리서처

### 리서치팀의 비전과 목표

### 토큰 이코노미 분석

### 이슈 트레킹

## 프론트엔드
