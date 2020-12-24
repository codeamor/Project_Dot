# SCSS

> className (BEM)

- my-menu\_\_item_visible

<br>

> 변수명 (camelCase)

- $footerGray: #333337;
- $labelGreen: #87af0f;
- $textContent: #666;

: 변수가 사용되는 곳의 역할 + 변수의 특성

<br>

> mixin

- 기본값도 정의 (아무 인자가 없을 경우 패딩 10px, 마진 20px)

```scss
@mixin box-default($padding: 10px, $margin: 20px) {
  padding: $padding;
  margin-bottom: $margin;
}
```

```scss
div {
  @include box-default(20px, 30px);
}
```

<br>

- 검색 엔진 최적화를 위한 Semantic 태그
  > Semantic tag

```html
<header>헤더</header>
<nav>네비게이션</nav>
<aside>사이드에 위치하는 공간</aside>
<section>본문의 여러 내용(article)을 포함하는 공간</section>
<article>본문의 주 내용이 들어가는 공간</article>
<footer>문서 또는 섹션의 바닥글</footer>
```
