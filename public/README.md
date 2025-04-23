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

- html을 꾸며주기
- display 중요함
- position 중요함

## 1. css 작성법 3가지

- 작성법 3가지 중에 누가 최종적으로 적용되는가? (누가 힘이 쎈가?)

### 1.1. inline 방식

- html 태그에 직접 작성해 주는 방식
  ex. <body style="background-color: skyblue; color : red;">
  > >  <style>
        body {background-color: hotpink; color : red;}
      </style>
    </head>

### 1.2. link 방식

- file로 작성해서 link 하는 방식(경로/파일명.css)
- css 폴더/common.css 파일을 생성

### 1.3. @import 방식

- css 파일에서 또다른 css 파일을 참조하는 방식
- css에서 css를 부르는 방식이 생각 외로 많음

## 2. 모든 태그에 초기화 진행하기

- 웹 브라우저 마다 기본적인 css는 적용이 되어 있음
- 그래서, 웹 브라우저마다 모양이 다르게 보인다.
- 아래 내용은 기본 css 값으로 추천합니다.

```
/* outline-style: none; */
```

## 3. 선택하는 법 (selector)

### 1. 태그 선택법

```css
태그.클래스명 {
}
```

```css
클래스명 {
}
```

- css/common.css 예제
```
@charset "utf-8";
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;

  /* outline-style: none; */
}

/* 태그 선택 : 추천하는 태그 기본값*/
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
  font-size: 16px;
}
body {
  width: 100%;
  font-size: 1rem;
  /* 디자인 보고 수정 */
  color: #000000;
}
/* 태그 선택 : 추천하는 태그 기본값*/
```

### 2. 클래스 선택법
