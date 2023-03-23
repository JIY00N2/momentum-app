## day4 #3.6~3.8

### 2023.03.23 Preview

### 1. 함수 + 조건문

```javascript
const h1 = document.querySelector("h1");
function handleTitleClick() {
  const currentColor = h1.style.color;
  let newColor;
  if (currentColor === "blue") {
    newColor = "tomato";
  } else {
    newColor = "blue";
  }
  h1.style.color = newColor;
}
```

### 2. style 작업은 css, animation 작업은 js

### 3. raw string이 반복되면 const로 만들어준다.(변수명으로 저장시에 오류를 추적할 수 있음)

### 4. class는 css파일에 .으로 표헌, id는 #으로 표현

### 5. className -> classList -> toggle