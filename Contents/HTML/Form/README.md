# HTML Form
## Keywords
### `<form>` 태그
폼(form)은 사용자가 웹사이트를 통해 서버로 입력을 보낼 수 있는 모든 요소를 말한다.<br>

`<form>` 태그를 사용하면 폼을 정의할 수 있다.
- `action` attribute: 사용자가 데이터를 제출했을 때, 데이터를 처리할 URL을 지정한다.
- `method` attribute: 사용자가 데이터를 제출했을 때, 전송 방법(HTTP Method)을 지정한다.

### 폼 요소
폼 요소는 `<form>` 태그 내부에 정의할 수 있는 요소를 말한다.
- `<label for="{element}">`: 폼 요소를 설명하는 요소이다. 라벨을 클릭하면 라벨과 연결된 요소로 포커싱된다.

- `<input type="text">`: 사용자에게 입력을 받을 수 있는 텍스트박스를 정의한다.
- `<input type="password">`: 사용자가 입력하는 값을 masking 하여 보이지 않게 한다.
- `<input type="checkbox">`: 사용자에게 클릭을 통한 선택지를 제공한다.

- `<fieldset>`: 그룹박스를 만들어 요소들을 묶는다.
  - `<legend>`: 그룹박스의 제목을 정의한다.

## Examples
[Form.html](./Form.html)