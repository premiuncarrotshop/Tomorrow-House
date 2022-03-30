# 내일의집

### 1.GNB

- 로그인을 하지 않은 경우

```html
<div class="gnb-button-group">
  <button
    class="gnb-search-button gnb-icon-button lg-hidden"
    type="button"
    aria-label="검색창 열기 버튼"
  >
    <i class="ic-search"></i>
  </button>

  <a href="/" class="gnb-icon-button" aria-label="장바구니 페이지로 이동">
    <i class="ic-cart"></i>
  </a>

  <div class="gnb-auth sm-hidden">
    <a href="/">로그인</a>
    <a href="">회원가입</a>
  </div>
</div>
```

- 로그인을 했을 경우

```html
<div class="gnb-button-group">
  <button
    class="gnb-search-button gnb-icon-button lg-hidden"
    type="button"
    aria-label="검색창 열기 버튼"
  >
    <i class="ic-search"></i>
  </button>

  <a
    href="/"
    class="gnb-icon-button sm-hidden"
    aria-label="스크랩북 페이지로 이동"
  >
    <i class="ic-bookmark"></i>
  </a>

  <a
    href="/"
    class="gnb-icon-button sm-hidden"
    aria-label="내 소식 페이지로 이동"
  >
    <i class="ic-bell"></i>
  </a>

  <a
    href="/"
    class="gnb-icon-button"
    aria-label="장바구니 페이지로 이동, 5개의 상품이 장바구니에 담겨있습니다."
  >
    <i class="ic-cart"></i>
    <strong class="badge">3</strong>
  </a>

  <button
    class="gnb-avatar-button sm-hidden"
    type="button"
    aria-label="마이메뉴 열기 버튼"
  >
    <div class="avatar-32">
      <img src="./assets/images/img-user-01.jpg" alt="사달라 아저씨" />
    </div>
  </button>
</div>
```

### 2. Sidebar

- 로그인을 하지 않은 경우

```html
<div class="sidebar-auth">
  <a class="btn-fill-primary btn-40" href="/">로그인</a>
  <a class="btn-outlined btn-40" href="/">회원가입</a>
</div>
```

- 로그인을 했을 경우

```html
<div class="sidebar-user">
  <a href="/">
    <div class="avatar-24">
      <img src="./assets/images/img-user-01.jpg" alt="사달라 아저씨" />
    </div>
    <strong class="username">사달라사달라사달라사달라사달라사달라사달</strong>
  </a>
</div>
```
