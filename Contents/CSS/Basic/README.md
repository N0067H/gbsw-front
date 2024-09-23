# CSS 기본
### 스타일을 사용하는 이유?
> - 말 그대로 내용과 상관 없이 문서의 디자인을 바꿀 수 있음.<br>
> - 다양한 기기 사양에 맞는 디자인을 제공할 수 있음.

## CSS 기본 형식
```
SELECTOR {
    PROPERTY: VALUE;
}
```

- SELECTOR: CSS가 적용될 HTML 요소
- PROPERTY: 적용할 속성
- VALUE: 적용할 속성의 값

중괄호 안에 스타일 규칙을 나열하는데 각 규칙은 세미콜론으로 구분함.

## 스타일시트와 적용 우선순위
```html
<!--index.html-->
<h1 style="color: red">RED</h1>
```
먼저, html 요소에 바로 직접 적용하는 **인라인 스타일**이 평가됨.<br><br>

```html
<!--index.html-->
<head>
    <style>
        h1 {
            color: red;
        }
    </style>
</head>
<body>...</body>
```
다음으로, `<style>` 태그를 사용한 **내부 스타일 시트**가 평가됨.<br><br>

```css
/* index.css */
h1 {
    color: red;
}
```
마지막으로, 외부 파일로부터 불러온 **외부 스타일 시트**가 평가됨.

## 스타일 상속
```html
<div class="div1">
    <div class="div2">
    </div>
</div>
```
위와 같이 중첩된 요소의 경우 외부 요소가 부모, 내부 요소를 자식으로 취급함.
부모 요소에 적용한 스타일은 기본적으로 자식 요소에 상속되는데 `width`, `height` 같이 요소 자체에 의미를 두는 속성은 상속되지 않음.<br>

### 강제로 상속받기
`width`, `height` 같은 요소 자체에 의미를 두는 속성은 기본적으로 상속되지 않는다.
```css
.div1 {
  color: red;
  width: 200px;
}

.div2 {
  width: inherit;
}
```
자식 요소의 스타일 속성 값으로 `inherit` 를 지정해주면 부모의 해당 요소를 강제로 상속받음.
