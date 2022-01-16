# 💡 starbucks_example

### 💡 SEO (검색 엔진 최적화, Search Engine Optimization)
- 구글이나 네이버 등에 자신의 웹 사이트/페이지를 노출할 수 있도록 정보를 최적화하는 작업

### 💡 BEM (Block Element Modifier)
- HTML 클래스 속성의 작명법
  - 요소__일부분
    - Underscore(Lodash) 기호로 요소의 일부분을 표시
    - ```HTML
      <div class="container">
        <div class="container__name"></div>
        <div class="item">
          <div class="item__name"></div>
        </div>
      </div>
      ```
  - 요소--상태
    - Hyphen(Dash) 기호로 요소의 상태를 표시
    - ```HTML
      <div class="btn btn--primary"></div>
      <div class="btn btn--success"></div>
      <div class="btn btn--error"></div>
      ```
### 💡 lodash cdn
  - ```JS
    _.throttle(function, 시간(ms))
    addEventListener('scroll', _.throttle(function() {
    }, 300));
    ```
  - 어떤 작업 시에 계속해서 불러오는 것을 시간을 두어 불러오도록 명시하는 CDN(Contents Delivery Network)

### 💡 gsap cdn
  - ```JS
    gsap.to(요소, 시간(s), {객체 요소});
    ```
  - CSS의 애니메이션 효과를 JS에서 제어하기 위한 cdn
