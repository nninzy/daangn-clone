# 당근마켓 클론코딩 (FE-study 내 개인 작업물)

## 프로젝트 목적

1. `HTML`과 `CSS`에 대한 연습

    * 반응형 웹 페이지 연습

2. 스터디 => 깃&깃허브를 통한 작업 연습

    * PR을 통한 코멘트 연습 => [FE-study github repository](https://github.com/chae-yoon/FE-STUDY)

3. 당근마켓 코드 & 스터디원 코드와 비교해서 보다 나은 방법 찾기

    * [팀원 피드백 및 미팅 내용 정리](FE-study_feedback/)

---

## [TIL](til/)

= 작업 기록 (날짜별 작업한 범위 및 새롭게 배운 내용 정리) / 당근마켓 홈페이지 원본 스크린샷 이미지 모음 / 나의 최종 작업물 스크린샷 이미지 모음

<!-- ### 기획안 및 TIL 노션 정리 페이지

<a href="https://min-z.notion.site/838b6037118347cbb74563a958845f29">
    <img 
        src="http://img.shields.io/badge/notion-000000?style=flat&logo=notion&link=https://min-z.notion.site/cce273910bef4ed0a8ea204e6f83da1e"
        style="height : auto; margin-left : 10px; margin-right : 10px;"/>
</a> -->

---

## HTML 파일 설명

= 당근마켓 클론코딩을 구성하는 html 파일 리스트

### [index.html](index.html) = 당근마켓 최상단 페이지 (중고거래 페이지와 동일)

* [index__hot-articles.html](index__hot-articles.html) : 중고거래 인기매물 페이지

* [index__trust.html](index__trust.html) : 믿을 수 있는 중고거래 페이지

* [index__top-keyword.html](index__top-keyword.html) : 중고거래 인기 검색어 페이지

### [nearby-store.html](nearby-store.html) = 동네가게 페이지

### [jobs.html](jobs.html) = 알바 페이지

### [realty.html](realty.html) = 부동산 직거래 페이지

### [cars.html](cars.html) = 중고차 직거래 페이지

### 세부 페이지 리스트

* [chat.html](chat.html) = footer 내 채탕하기 카테고리 페이지

* [login.html](login.html) = header 내 채팅하기 버튼 페이지

* [articles__item.html](articles__item.html) = 중고거래 제품 상세 페이지

* [articles__store.html](articles__store.html) = 동네가게 제품 상세 페이지
---

## [src](src/) 폴더 내 파일(CSS, JS) 설명

= CSS, js, 이미지, svg 파일 등이 있는 곳

### [css > components](src/css/components/)

= 웹 페이지 내 공통적으로 존재 or 독립적인 component의 스타일 모음

* [articles--column.css](src/css/components/articles--column.css)

    판매 상품 중 사진과 설명이 세로로 되어 있는 요소

* [articles--row.css](src/css/components/articles--row.css)

    판매 상품 중 사진과 설명이 가로로 되어 있는 요소

* [banner.css](src/css/components/banner.css)

    동네 가게 ~ 중고차 페이지에 있는 앱 다운로드 등을 설명하는 요소

* [footer.css](src/css/components/footer.css)

    대부분의 웹사이트에서 사용하는 footer

* [footer--sub.css](src/css/components/footer--sub.css)

    당근채팅, 당근로그인 페이지에서 사용하는 footer

* [hearder.css](src/css/components/header.css)

    대부분의 웹사이트에서 사용하는 header

* [header--sub.css](src/css/components/header--sub.css)

    당근채팅, 당근로그인 페이지에서 사용하는 header

* [index__install-modal.css](src/css/components/index__install-modal.css)

    index 페이지가 태블릿 이하 사이즈일 때 나타나는 modal
    
    (아직 X 버튼에 대한 JS 설정 안함)
* [screen-thumnails.css](src/css/components/screen-thumbnails.css)

    주요 페이지 (header nav에 있는 요소들) main element 최상단 section

### [css > screens](src/css/screens/)

= 각 웹 페이지별 스타일 모음

### [css > reset.css](src/css/reset.css)

= 브라우저에서 기본적으로 지원해주는 스타일에 대한 재설정

### [css > styles.css](src/css/styles.css)

= html에 연결되는 가장 기본적인 스타일

### [css > variables.css](src/css/variables.css)

= 전체 스타일에서 사용되는 CSS 변수 모음 (색상, 여백 등)

---
