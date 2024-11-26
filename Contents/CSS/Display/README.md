# CSS 요소 배치/정렬

### `display` 프로퍼티
- `block`: 인라인 요소를 블록 요소로 변환한다.
- `inline`: 블록 요소를 인라인 요소로 변환한다.
- `inline-block`: 인라인과 블록 요소의 속성을 모두 가짐.
> `inline-block`은 마진, 패딩, 크기 등 지정 가능하다.
- `none`: 요소가 존재하지만 화면에 표시되지는 않는다.

### `float` 프로퍼티
- `left`: 요소를 왼쪽으로 정렬된다.
- `right`: 요소를 오른쪽으로 정렬된다.
- `none`: floating이 적용되지 않는 기본값이다.
### `clear` 프로퍼티
- `left`: 왼쪽에 적용된 floating을 무효화한다.
- `right`: 오른쪽에 적용된 floating을 무효화한다.
- `both`: 양쪽에 적용된 floating을 무효화한다.

### `position` 프로퍼티
- `static`: 기본값, `top`, `bottom`, `left`, `right` 같은 속성이 적용되지 않음.

- `relative`: 기본 위치를 기준으로 `top`, `left`, `right`, `bottom` 값을 사용해 위치를 조정할 수 있다. 이동하더라도 요소의 레이아웃은 그대로 남는다.

- `absolute`: 가장 가까운 super 중 `position`이 `relative`, `absolute`, `fixed`인 요소를 기준으로 위치를 결정한다. 최상위 요소일 경우 `<body>`를 기준으로 배치한다. 절대적인 레이아웃을 가지므로 다른 요소들이 그 자리를 채운다.

- `fixed`: 뷰포트(브라우저)를 기준으로 고정된다. 스크롤을 해도 위치가 변하지 않는다.

- `sticky`: 스크롤 위치에 따라 `relative`와 `fixed` 사이를 전환한다. 스크롤을 내려 특정 지점에 도달하면 그 위치에 고정된다. top, left 같은 위치 속성들과 함께 사용해야 한다.

### `overflow` 프로퍼티
- `visible`: 기본값으로, 요소의 콘텐츠가 넘쳐도 잘리지 않고 그대로 표시된다. 다른 요소의 레이아웃을 침범할 수 있다.

- `hidden`: 요소 크기를 초과하는 콘텐츠는 잘려서 보이지 않고. 스크롤바가 표시되지 않기 때문에, 잘린 부분은 볼 수 없다.

- `scroll`: 요소의 콘텐츠가 넘치면 항상 스크롤바가 표시된다.

- `auto`: 콘텐츠가 넘칠 때만 자동으로 스크롤바가 표시된다. 콘텐츠가 요소 안에 다 들어가면 스크롤바가 나타나지 않는다. `scroll`보다 더 유연하다.

- `overflow-x`: 요소의 수평 넘침을 제어한다.

- `overflow-y`: 요소의 수직 넘침을 제어한다.

## 예제
- [Display](Display.html)<br>
- [Layout 1](Layout1.html)<br>
- [Layout 2](Layout2.html)<br>
- [Position](Position.html)<br>
