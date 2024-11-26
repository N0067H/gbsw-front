## 반응형 웹
반응형 웹이란 웹 페이지의 레이아웃이나 요소들이 다양한 화면 크기에 따라 자동으로 적응하도록(배치 따위가 바뀜) 만드는 디자인 방법이다.

### 미디어쿼리
HTML/CSS에선 미디어쿼리라는 기능을 사용해 반응형 규칙을 구현한다.
```css
@media (min-width: 1000px) {
  .container {
    background: pink;
  }
}
```
위 CSS로 예를 들면, 가로 길이가 1000 이상일 경우, `container` 클래스의 배경 색을 `pink`로 바꾼다.

[./1000Pink.html](1000Pink.html)