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
