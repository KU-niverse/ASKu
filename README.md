# ASKu   [![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2FKU-niverse%2FASKu&count_bg=%23ECC2B4&title_bg=%238B0C2A&icon=&icon_color=%23E7E7E7&title=ASKu&edge_flat=false)](https://hits.seeyoufarm.com)

<div align="center">
    <a href="https://asku.wiki/">
        <img src="https://github.com/KU-niverse/ASKu/assets/70438098/2b8221c2-5944-4ce9-8bd4-b480d767907b" alt="ASKu_logo" />
    </a>
</div>

<br />

## 📝 서비스 기획 의도

**저희는 세가지 문제를 해결하기 위해 ASKu를 제작 중입니다.**

1. 에브리타임, 고파스, 교내 포털, 행정실 등 너무나 다양하게 퍼져있는 정보의 소스
2. 유용한 정보가 올라오더라도 커뮤니티의 특성으로 인한 정보 보존의 어려움
3. 학생들이 교내 행정 사항에 대해 알기 위한 소모적인 과정 축소

이러한 문제점을 해결하기 위해 **교내 위키 서비스**와 **AI 하호 챗봇 서비스**를 제작하였습니다.
<br/>
<br/>

### 교내 위키 서비스

이중전공이나 전과, 교환학생 정보를 에브리타임, 고파스의 검색 페이지를 수도 없이 넘기며 찾는 것은 매우 소모적인 일이었습니다.

우리 학교 내 정보를 누구보다 쉽게 접근할 수 있어야 할 학생들에게 교내 정보를 얻는 과정이 지나치게 번거롭다고 판단하였습니다.

그래서 저희는 검색 한 번으로 관련된 모든 정보를 손쉽게 열람할 수 있는 **교내 정보 위키 서비스**를 개발했습니다.

이제는 유용한 정보가 올라오면 스크랩할 필요 없이 바로 확인할 수 있으며, 교우들이 제공하는 양질의 정보를 지속적으로 보존함으로써 가치 있는 지식의 축적과 공유를 추구할 수 있습니다.


### AI 하호 챗봇 서비스

기존의 학생들은 오로지 평일 10시부터 17시 사이에만 행정에 대해 정보를 얻을 수 있었습니다. 

하지만 한정된 시간이 아닌 언제든 궁금할 때 행정에 대한 정보를 얻을 수 있다면 어떨까요?

기존에 주말이나 저녁만 되도 연락이 되지 않는 행정실…전화하기 부담스러운 행정실을 벗어나고자 학칙에 대한 질문에 대해 24시간 대답해주는 AI 챗봇 서비스를 만들고자합니다.

더불어 교내 위키 서비스에 쌓인 데이터를 학습하여 고려대학교의 모든 정보에 답변하는 AI 챗봇으로 발전시키고자 합니다.

<br/>


## 💻 메인 기능 

- 기본적인 **WIKI 문서 작성/수정/목차/북마크/히스토리** 등의 기능을 제공합니다.

- WIKI 문서의 내용에 대해 질문을 할 수 있는 **질문하기** 기능과 의견을 나눌 수 있는 **토론하기** 기능을 제공합니다.

- **실시간 인기 검색어**와 **실시간 인기 질문**을 통해 인기있는 WIKI 문서를 확인할 수 있습니다.

- **문서별 기여도**와 **뱃지 기능**을 통하여 WIKI 서비스 이용을 유도합니다.

- 질문에 대한 답변을 생성하는 **AI 하호 챗봇** 기능을 제공합니다.

- AI 하호 챗봇의 정확도와 신빙성을 위해 **챗봇 답변을 생성한 레퍼런스**를 제공합니다.

<br />

## 🗃 사이트 구조 개요

**ASKu** 은 프론트엔드와 백엔드가 따로 분리되어 있는 구조입니다.

프론트엔드는 `React.js` 로 개발되었습니다.
백엔드는 `Node.js` 로 개발되었으며, AI 챗봇은 `django` 로 `django-rest-framework` 를 이용한 API 서버로 구성되어있습니다.

각 파트의 작업 내용은 다음 링크에서 확인할 수 있습니다. 
- [ASKu Front](https://github.com/KU-niverse/ASKu-Front)
- [ASKu Back](https://github.com/KU-niverse/ASKu-api)
- [ASKu AI](https://github.com/KU-niverse/ASKu-AI-API)


<!--전체 아키텍쳐 그림 추가-->


<br/>

## 🧑🏻‍💻 팀 소개

### 1) Lead

- [최영섭](https://github.com/youngsupchoi) : 서비스 기획, 프론트/백엔드/AI 개발

### 2) Front

- [김미강](https://github.com/mkngkm): 프론트 리더, 프론트 개발
- [조성민](https://github.com/noviceo): 서비스 기획, 프론트 개발
- [정다현](https://github.com/dhyun22): 프론트 개발

### 3) Back

- [김수인](https://github.com/starcat37): 백엔드 리더, 백엔드 개발
- [임재민](https://github.com/jaemin8852): 서비스 기획, 백엔드 개발

### 4) AI

- [양현진](https://github.com/HyeonJin-Yang): AI 리더, AI 개발
- [최지현](https://github.com/Jihyun-Choi): AI 개발, PM
- [원다혜](https://github.com/dahyewon): AI 개발, 마케팅

### 5) Design

- [정지원](https://www.instagram.com/520.10000/): 디자인, 마케팅



