# π‘ starbucks_example

### π‘ SEO (κ²μ μμ§ μ΅μ ν, Search Engine Optimization)
- κ΅¬κΈμ΄λ λ€μ΄λ² λ±μ μμ μ μΉ μ¬μ΄νΈ/νμ΄μ§λ₯Ό λΈμΆν  μ μλλ‘ μ λ³΄λ₯Ό μ΅μ ννλ μμ

### π‘ BEM (Block Element Modifier)
- HTML ν΄λμ€ μμ±μ μλͺλ²
  - μμ__μΌλΆλΆ
    - Underscore(Lodash) κΈ°νΈλ‘ μμμ μΌλΆλΆμ νμ
    - ```HTML
      <div class="container">
        <div class="container__name"></div>
        <div class="item">
          <div class="item__name"></div>
        </div>
      </div>
      ```
  - μμ--μν
    - Hyphen(Dash) κΈ°νΈλ‘ μμμ μνλ₯Ό νμ
    - ```HTML
      <div class="btn btn--primary"></div>
      <div class="btn btn--success"></div>
      <div class="btn btn--error"></div>
      ```
### π‘ lodash cdn
  - ```JS
    _.throttle(function, μκ°(ms))
    addEventListener('scroll', _.throttle(function() {
    }, 300));
    ```
  - μ΄λ€ μμ μμ κ³μν΄μ λΆλ¬μ€λ κ²μ μκ°μ λμ΄ λΆλ¬μ€λλ‘ λͺμνλ CDN(Contents Delivery Network)

### π‘ gsap cdn
  - ```JS
    gsap.to(μμ, μκ°(s), {κ°μ²΄ μμ});
    ```
  - CSSμ μ λλ©μ΄μ ν¨κ³Όλ₯Ό JSμμ μ μ΄νκΈ° μν cdn

### π‘ swiper js
  - ```JS
    const swiper = new Swiper(μ νμ, μ΅μ)
    ```
  - Swipe ν¨κ³Όλ₯Ό μ£ΌκΈ° μν API
  - π[swiper JS](https://swiperjs.com/)
