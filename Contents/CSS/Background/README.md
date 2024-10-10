# 배경 스타일
## 배경 색과 배경 범위
- `background-color`: 배경색을 지정한다. (16진수, RGB, 색상명 사용 가능)
- `background-clip`: 배경이 적용될 범위 지정.
    - `border-box`: 테두리까지만
    - `padding-box`: 패딩까지만
    - `content-box`: 내용 부분만
## 배경 이미지
- `background-image`: 배경 이미지 설정.
    - `url()`: 배경 이미지의 경로 지정 (ex. `url(./image.png)`)
- `background-repeat`: 배경 이미지 반복 설정.
    - `repeat`: 가로 세로 반복
    - `no-repeat`: 반복 안함
    - `space`: 이미지 사이 여백 분배
    - `round`: 이미지 크기 재조정 후 반복
- `background-size`: 배경 이미지의 크기를 설정한다.
    - `contain`: 요소 안에 이미지 맞춤
    - `cover`: 요소 전체 덮음
- `background-attachment`: 배경 고정 여부를 설정한다.
    - `scroll`: 스크롤 시 배경도 이동
    - `fixed`: 배경 고정
- `background-position`: 배경이 반복되지 않는 경우 이미지 위치를 설정한다.

## 그라데이션
- `linear-gradient`: 선형 그라데이션을 설정한다. (방향, 각도, 색상 중지점)
- `radial-gradient`: 원형 그라데이션을 설정한다. (모양, 크기, 위치)
- `repeating-linear-gradient`: 패턴이 있는 선형 그라데이션을 생성한다. (패턴 생성).

## 에제
[./Background.html](./Background.html)