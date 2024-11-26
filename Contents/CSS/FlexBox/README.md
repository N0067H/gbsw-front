# FlexBox
웹 요소를 가로로 배치하다가 화면에 가득 차면 아래로 내려서 다시 옆으로 배치하는 방식이다. 여유 공간이 있으면 너비, 높이, 위치를 자유롭게 조정할 수도 있다.

## FlexBox Container
먼저, FlexBox를 만드려면 container라는 것을 구현해야한다.
```html
<style>
.flex-container {
  display: flex;
}
</style>

<div class="flex-container">
  <div>1</div>
  <div>2</div>
  <div>3</div>
</div> 
```

## Flex Direction과 Wrap
`flex-direction`과 `flex-wrap` 속성을 사용하면 container 내 요소가 배치되는 방식과 줄바꿈 여부를 결정할 수 있다.

```html
<style>
    .flex-container {
      display: flex;
      flex-direction: row;
      flex-wrap: wrap;
      gap: 10px;
    }
    .flex-item {
      background-color: #f0f0f0;
      padding: 20px;
      text-align: center;
    }
    </style>
    
    <div class="flex-container">
      <div class="flex-item">1</div>
      <div class="flex-item">2</div>
      <div class="flex-item">3</div>
      <div class="flex-item">4</div>
      <div class="flex-item">5</div>
      <div class="flex-item">6</div>
    </div>
    
    <style>
    .flex-container {
      background-color: yellow;
      padding: 50px;
      display: flex;
      flex-direction: row;
      flex-wrap: wrap;
      gap: 10px;
      justify-content: center;
      align-items: center;
    }
    .flex-item {
      background-color: lightgray;
      padding: 20px;
      text-align: center;
      width: 100px;
    }
</style>
    
<div class="flex-container">
    <div class="flex-item">1</div>
    <div class="flex-item">2</div>
    <div class="flex-item">3</div>
    <div class="flex-item">4</div>
    <div class="flex-item">5</div>
    <div class="flex-item">6</div>
</div>
```