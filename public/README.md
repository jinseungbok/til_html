# header 영역 html 작업해 보기

```html
<body>
  <div>
    <!-- 전체 레이아웃 -->
    <!-- 상단 -->
    <header class="'header">
      <div class="layout">
        <!-- 상단의 위 -->
        <div class="header_top">
          <div class="header_top_left">
            <!-- 로고 -->
            <div class="logo">
              <a href="http://www.interpark.com" target="_blank">
                <img src="images/logo.svg" alt="로고" title="인터파크" />
              </a>
            </div>
            <!-- 제품 검색 -->
            <div class="search">
              <!-- 제품 검색 API 연동 -->
              <form class="search_form" action="good-search.html" method="get">
                <input
                  type="text"
                  name="keyword"
                  placeholder="제품을 검색해 주세요."
                />
                <input type="submit" value="검색" />
              </form>
            </div>
          </div>
          <div class="header_top_right">
            <ul class="member">
              <li><a href="#">로그인</a></li>
              <li><a href="#">회원가입</a></li>
            </ul>
          </div>
        </div>
        <!-- 상단의 아래 -->
        <div class="header_bottom">
          <div class="header_bottom_nav">
            <ul class="nav">
              <li><a href="#">홈</a></li>
              <li><a href="#">투어</a></li>
              <li><a href="#">티켓</a></li>
            </ul>
          </div>
          <div class="header_bottom_eventmenu">이벤트 메뉴</div>
          <ul class="coupon_list">
            <li>
              <a href="#-event"
                >해외여행쿠폰 <img src="images/badge_hot.svg" alt="해외여행쿠폰"
                title="해외여행쿠폰"
              </a>
            </li>
            <li>
              <a href="#"
                >국내여행쿠폰 <img src="images/badge_hot.svg" alt="국내여행쿠폰"
                title="국내여행쿠폰"
              </a>
            </li>
            <li><a href="#">여행혜택존</a></li>
            <li><a href="#">여행준비</a></li>
          </ul>
        </div>
      </div>
    </header>
  </div>
</body>
```

<!DOCTYPE html>
<html lang="ko">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>나의 til</title>
  </head>
  <body>
    <!-- 전체 레이아웃  -->
    <div class="wrap">
      <!-- 상단 -->
      <header class="header">
        <div class="layout">
          <!-- 상단의 위 -->
          <div class="header_top">
            <div class="header_top_left">
              <!-- 로고 -->
              <div class="logo">
                <a href="http://www.interpark.com" target="_blank">
                  <img src="images/logo.svg" alt="로고" title="인터파크" />
                </a>
              </div>
              <!-- 제품검색 -->
              <div class="search">
                <!-- 제품 검색 API 연동 -->
                <form class="search_form">
                  <input type="text" placeholder="제품을 검색해 주세요." />
                  <input type="submit" value="검색" />
                </form>
              </div>
            </div>
            <div class="header_top_right">
              <ul class="member">
                <li><a href="#">로그인</a></li>
                <li><a href="#">회원가입</a></li>
              </ul>
            </div>
          </div>
          <!-- 상단의 아래 -->
          <div class="header_bottom">
            <div class="header_bottom_nav">
              <ul class="nav">
                <li><a href="#">홈</a></li>
                <li><a href="#">투어</a></li>
                <li><a href="#">티켓</a></li>
              </ul>
            </div>
            <div class="header_bottom_eventmenu">
              <ul class="cupon">
                <li>
                  <a href="#">
                    해외여행쿠폰
                    <img
                      src="images/badge_hot.svg"
                      alt="해외여행쿠폰"
                      title="해외여행쿠폰"
                    />
                  </a>
                </li>
                <li>
                  <a href="#">
                    국내여행쿠폰
                    <img
                      src="images/badge_hot.svg"
                      alt="국내여행쿠폰"
                      title="국내여행쿠폰"
                    />
                  </a>
                </li>
                <li><a href="#">여행혜택존</a></li>
                <li><a href="#">여행준비</a></li>
              </ul>
            </div>
          </div>
        </div>
      </header>
      <!-- 메인 -->
      <main>
        <div class="layout">
          <!-- Banner -->
          <div class="banner">
            <div class="banner_list">
              <a href="#">
                <img src="images/v1.png" alt="banner" title="배너" />
              </a>
            </div>
            <div class="banner_list">
              <a href="#">
                <img src="images/v2.jpg" alt="banner2" title="배너2" />
              </a>
            </div>
            <button class="slide_bt banner_left">
              <img src="images/slider_arrow.svg" alt="left" title="left" />
            </button>
            <button class="slide_bt banner_right">
              <img src="images/slider_arrow.svg" alt="right" title="right" />
            </button>
          </div>
          <!-- Tour -->
          <div class="tour">
            <div class="section_top">
              <h2 class="section_title">투어 특가</h2>
              <span class="section_desc">마감임박! 금주의 특가 여행 추천</span>
            </div>
            <div class="section_list">
              <!--Start 목록영역 -->
              <div class="section_category">
                <ul class="section_category_bts">
                  <li><button>마감임박</button></li>
                  <li><button>패키지</button></li>
                  <li><button>국내숙소</button></li>
                  <li><button>해외숙소</button></li>
                  <li><button>투어/입장권</button></li>
                </ul>
              </div>
              <div class="section_slide">
                <!--Start 추후 JSON 데이터 연동으로 변경 예정 -->
                <div class="item">
                  <a href="#">
                    <img src="images/v3.jpg" alt="나트랑" title="나트랑" />
                    <span>나트랑</span>
                    <span>[10%쿠폰] 아동 동반 가족여행 강력 추천</span>
                    <p>
                      방콕/파타야 5일, 중대형기종(347석) 탑승, 24년 오픈 5성
                      윈덤 좀티엔 파타야,마사지 2시간,핵심일정 포함
                    </p>
                    <span><b>109,000</b>원~</span>
                  </a>
                </div>
                <div class="item">
                  <a href="#">
                    <img src="images/v3.jpg" alt="나트랑" title="나트랑" />
                    <span>나트랑</span>
                    <span>[10%쿠폰] 아동 동반 가족여행 강력 추천</span>
                    <p>
                      방콕/파타야 5일, 중대형기종(347석) 탑승, 24년 오픈 5성
                      윈덤 좀티엔 파타야,마사지 2시간,핵심일정 포함
                    </p>
                    <span><b>109,000</b>원~</span>
                  </a>
                </div>
                <div class="item">
                  <a href="#">
                    <img src="images/v3.jpg" alt="나트랑" title="나트랑" />
                    <span>나트랑</span>
                    <span>[10%쿠폰] 아동 동반 가족여행 강력 추천</span>
                    <p>
                      방콕/파타야 5일, 중대형기종(347석) 탑승, 24년 오픈 5성
                      윈덤 좀티엔 파타야,마사지 2시간,핵심일정 포함
                    </p>
                    <span><b>109,000</b>원~</span>
                  </a>
                </div>

                <!--End 추후 JSON 데이터 연동으로 변경 예정 -->
              </div>
              <!--End 목록영역 -->
            </div>
            <div class="section_bts">
              <a href="#">
                투어 홈 바로가기
                <img
                  src="images/icon_linkArrow.svg"
                  alt="투어 홈 바로가기"
                  title="투어 홈 바로가기"
                />
              </a>
            </div>
          </div>
          <!-- Trip -->
          <div></div>
          <!-- Ticket -->
          <div></div>
          <!-- Live -->
          <div></div>
        </div>
      </main>
      <!-- 하단 -->
      <footer>
        <div></div>
      </footer>
    </div>

  </body>
</html>

# CSS

- html 을 꾸며주기
- display 중요함.
- position 중요함.

## 1. css 작성법 3가지

- 작성법 3가지 중에 누가 최종적으로 적용되는가? (누가 힘이 쎈가?)

### 1.1. inline 방식

- html 태그에 직접 작성해 주는 방식

### 1.2. link 방식

- file 로 작성해서 link 하는 방식 (경로/파일명.css)
- css 폴더/common.css 파일을 생성

### 1.3. @import 방식

- css 파일에서 또다른 css 파일을 참조하는 방식

## 2. 모든 태그에 초기화 진행하기

- 웹브라우저 마다 기본적인 css 는 적용이 되어있음.
- 그래서, 웹브라우저 마다 모양이 다르게 보인다.
- 아래 내용은 기본 css 값으로 추천합니다.

```css
@charset "utf-8";
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;

  /* outline-style: none; */
}
```

## 3. 선택하는 법 (selector)

### 3.1. 태그 선택법

```css
태그 {
}
```

- css/common.css 예제

```css
@charset "utf-8";
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;

  /* outline-style: none; */
}

/* 태그 선택 : 추천하는 각 태그별 기본값 */
a {
  text-decoration: none;
  /* 디자인 보고 수정 */
  color: #000000;
}
ul {
  list-style: none;
}
html {
  width: 100%;
  /* 디자인 보고 수정 */
  font-size: 12px;
}
body {
  width: 100%;
  font-size: 1rem;
  /* 디자인 보고 수정 */
  color: #000000;
  /* 글꼴이 필요로 함. */
}
```

### 3.2. 클래스 선택법

```css
태그.클래스명 {
}
```

```css
.클래스명 {
}
```

### 3.3. 단계별 선택법

```css
태그 > 태그 > 태그 {
}
```

```css
.클래스 > 태그 > 태그 {
}
```

### 3.4. 범위 선택법

```css
태그 태그 {
}
```

```css
.클래스 태그 {
}
```

## 4. display 의 이해

### 4.1. display:block

- 벽돌 처럼 한 영역을 모두 차지한다.
- 공간이 남더라도 절대로 양보하지 않음.
- div, ul, li, h1~h6, p 태그 등은 default 로 block 이 적용되어짐.

### 4.2. display:inline

- 글자처럼 한줄에 배치가 가능하다.
- 그러나, width, height 등이 적용안됨.
- img, span, b 태그 등은 default 로 inline 이 적용되어짐.

### 4.3. display:inline-block;

- 글자처럼 한줄에 배치가 가능하다.
- 그러나, width, height 등이 적용됨.
- Enter 줄 내림 공백을 없애려면 font-size:0 적용

### 4.4. block 을 유지하면서 inline 적용하기

### 4.4.1. overflow:hidden 으로 레이아웃 유지

```css
@charset "utf-8";
.box_wrap {
  display: block;
  border: 3px solid red;
  overflow: hidden;
}
.box {
  display: block;
  width: 50px;
  border: 3px solid black;
  float: left;
}
```

### 4.4.2. clearboth 클래스 만들어서 레이아웃 유지

```css
.box_wrap {
  display: block;
  border: 3px solid red;
}
.clearboth::after {
  content: "";
  display: block;
  width: 100%;
  clear: both;
}
.box {
  display: block;
  width: 50px;
  border: 3px solid black;
  float: left;
}
```

### 4.4.3. height 를 주어서 레이아웃 유지

```css
.box_wrap {
  display: block;
  border: 3px solid red;
  height: 100px;
}
.box {
  display: block;
  width: 50px;
  border: 3px solid black;
  float: left;
}
```

### 4.5. display: none

- 화면에 내용을 안보이게 함.
- 실제로 태그가 없는 것처럼 작동함.
- `js 에서 태그를 찾아서 기능을 부여 못할 수도 있다.`

### 4.6. 가능하면 flex 적극 도입

- https://studiomeal.com/archives/197

## 5. CSS 적용 우선 순위

### 5.1. 태그 CSS 가 만약 중복이라면

- 1번 `인라인 스타일 시트는 가장 우선 적용`이 된다.

- 2번 `작성 순서가 마지막에 것이 적용`된다.

```css
div {
  background-color: yellowgreen;
}
/* 아래에 작성했으므로 덮어쒸움 */
div {
  background-color: orange;
}
```

- 3번 `클래스가 태그 보다 우선순위가 높다`

```css
.box_wrap {
  background-color: hotpink;
}
div {
  background-color: yellowgreen;
}
```

- 4번 `클래스가 중복이라면 작성순서가 나중이 우선권`

```html
<style>
  .box_wrap {
    background-color: hotpink;
  }
  .hi {
    background-color: yellowgreen;
  }
</style>
<div class="box_wrap hi">안녕</div>
```

- 5번 `아이디는 최우선권을 가진다`

```html
<style>
  #gogo {
    background-color: brown;
  }
  .box_wrap {
    background-color: hotpink;
  }
  .hi {
    background-color: yellowgreen;
  }
</style>
<div id="gogo" class="hi box_wrap">안녕</div>
```

- 6번 `단계 선택이 범위선택 보다 우선권 가짐`

```html
<style>
  ul > li > a {
    background-color: green;
  }
  ul a {
    background-color: red;
  }
</style>

<ul class="menu">
  <li><a href="#">HTML</a></li>
  <li><a href="#">CSS</a></li>
  <li><a href="#">JS</a></li>
</ul>
```

### 5.2. 무조건 적용하기

```html
<style>
  div {
    background-color: yellow !important;
  }
</style>

<div style="background-color: green">안녕</div>
```

### 5.3. 우선 순위 정리

- 작성 순서를 고려함.
  `태그 < 클래스 < 아이디 < 인라인`
- 랜더링 과정을 고려함.
  `태그 ==> 태그 구조(DOM) ==> 태그 css ==> 클래스 css ==> 인라인 css`
- 웹브라우저의 `F12` 을 참조하자.
- `!important` 는 정말 해결이 필요한 곳에만 활용

## 6. 글꼴 설정

- 반드시 글꼴 설정 후 작업이 진행 되어야 합니다.
- 글자의 종류와 글자 간의 간격, 행간의 간격, 글꼴의 크기 등이 너비, 높이 등의 단위가 됩니다.
- body 셋팅을 위한 자료임.

### 6.1. 글꼴 구하기

- `웹 폰트`와 `로컬 폰트`의 구분 및 이해
- [구글폰트](https://fonts.google.com/)
- [눈누](https://noonnu.cc/font_page/pick)
- [깃허브](https://github.com/orioncactus/pretendard)
- [아이콘 폰트](https://fontawesome.com/icons)

### 6.2. 글꼴 활용하기
- css/common.css 참조

## 7. CSS 살펴보기
- margin (영역 바깥으로의 여백)
  - margin-top 은 오류가 발생할 수 있음