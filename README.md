## 생각을 정리합시다

| Mobile | Tablet | Desktop| class           |
| ------ | ------ | ------ | ----------------|
| o      | x      | x      | .sm-only    |
| o      | o      | x      | .lg-hidden |
| x      | o      | x      | .md-only    |
| x      | o      | o      | .sm-hidden  |
| x      | x      | o      | .lg-only   |
| o      | x      | o      | .md-hidden  |


#내일의 집

###1. GNB

로그인을 하지 않은 경우
```html
<div class="button-group">
                  <button 
                  class="gnb-icon-button is-search lg-hidden" 
                  type="button" 
                  aria-label="검색창 열기 버튼"
                  >
                    <i class="ic-search"></i>
                  </button>
                  <a
                  class="gnb-icon-button is-cart" 
                  href="/" 
                  aria-label="장바구니 페이지로 이동"
                  >
                    <i class="ic-cart"></i>
                  </a>
                  <div class="gnb-auth sm-hidden">
                    <a href="/">로그인</a>
                    <a href="/">회원가입</a>
                  </div>
                </div>
```
-로그인을 했을 경우
```
<div class="button-group">
                    <button 
                    class="gnb-icon-button is-search lg-hidden" 
                    type="button" 
                    aria-label="검색창 열기 버튼"
                    >
                      <i class="ic-search"></i>
                    </button>

                  <a 
                  class="gnb-icon-button sm-hidden" 
                  href="/" 
                  aria-label="스크랩북 페이지로 이동"
                  >
                    <i class="ic-bookmark"></i>
                  </a>

                  <a 
                  class="gnb-icon-button sm-hidden" 
                  href="/" 
                  aria-label="내 소식 페이지로 이동"
                  >
                    <i class="ic-bell"></i>
                  </a>
          
                  <a
                  class="gnb-icon-button is-cart" 
                  href="/" 
                  aria-label="장바구니 페이지로 이동"
                  >
                    <i class="ic-cart"></i>
                    <strong class="badge">5</strong>
                  </a>

                  <button 
                  class="gnv-avatar-button sm-hidden" 
                  type="button" 
                  aria-label="마이메뉴 열기 버튼"
                  >
                    <div class="avatar-32">
                      <img src="./assets/images/img-user-01.jpg" alt="사달라 아저씨">
                    </div>
                  </button>
                </div>
```
