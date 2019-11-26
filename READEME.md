# 20191126 study
===


```
const list = '[{"name":"eggs","price":1},{"name":"coffee","price":9.99},{"name":"rice","price":4.04},{"name":"brice","price":4.04},{"name":"arice","price":4.04}]'



```

### 자바스크립트와 JSON
---

- JSON이란? 
JSON은 자바스크립트의 객체 표기법을 제한하여 만든 텍스트 기반의 데이터 교환 표준이다.
따라서 JSON 데이터는 자바스크립트가 자주 사용되는 웹 환경에서 사용하는 것이 유리하다.

자바스크립트에서 JSON 데이터를 분석하고 사용하는 것은 매우 간단하다.
자바스크립트는 JSON 데이터를 처리하기 위한 메소드를 제공하고 있다.

1. JSON.stringfy()
2. JSON.parse()
3. toJSON()

---------------



### JSON.stringify() 메소드

JSON.stringify() 메소드는 인수로 전달받은 자바 스크립트 객체를 문자열로 변환하여 반환한다.


JSON.stringify(value, replacer, space)

value(필수): JSON 문자열로 변환할 값이다. (배열, 객체, 또는 숫자, 문자 등)

replacer(선택): 함수 또는 배열이 될 수 있다. 이 값이 null 이거나 제공되지 않으면 객체의 모든 속성들이 JSON 문자열 결과에 포함된다.

```
const 
```