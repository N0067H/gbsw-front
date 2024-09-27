# CSS 박스 모델
> 박스 모델은 HTML에서 요소가 차지하는 공간을 의미한다.

## 박스 모델의 기본 구성
- 콘텐츠(content) 영역
- 패딩(padding): 콘텐츠와 테두리 사이의 공간
- 테두리(border): 박스의 경계
- 마진(margin): 다른 박스와의 여백

## 크기 스타일 프로퍼티
- `width`, `height`: 크기값이나 백분율로 요소의 가로/세로 크기를 설정한다.
- `width`, `height`: 크기값이나 백분율로 요소의 가로/세로 크기를 설정한다.
- `max-width`, `max-height`: 요소의 최대 크기를 제한한다.
- `box-sizing`: 박스 크기 계산 방식
  - `border-box`: 테두리까지 포함한 전체 크기를 기준으로 계산한다.
  - `content-box`(Default): 콘텐츠만을 기준으로 크기를 계산한다.

## 테두리 스타일 프로퍼티
> 스타일은 top, right, bottm, left 순서로 지정해야 한다.
- `box-shadow`: 가로, 세로, 흐림, 번짐, 색상, inset을 지정한다.
- `border-style`: 테두리 스타일을 설정한다.
- `border-width`: 테두리 두께를 설정한다.
- `border-color`: 테두리 색상을 설정한다.
- `border-radius`: 특정 모서리, 혹은 전체를 둥글게 만든다.

## 여백 스타일 프로퍼티
- `margin`: 크기값이나 백분율을 사용해서 바깥 여백을 설정한다.
- `padding`: 크기값이나 백분율을 사용해서 내부 여백을 설정한다.

> `margin` 값을 `auto`로 지정하면 요소가 중앙 정렬된다. 하지만 배치할 요소의 `width` 값이 지정되어 있어야 한다.

> 세로로 배치된 요소의 margin 값이 겹칠 경우 더 큰 margin 값으로 적용된다. 이를 **margin 중첩 현상**이라고 한다.




