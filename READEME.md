# 20191126 study
===

**1. JSON.stringfy()** 

**2. JSON.parse()**

**4. .pop()**

**6. .filter**

**5. forEach**

**6. for**

**7. map()**



### 자바스크립트와 JSON
---

- JSON이란? 
JSON은 자바스크립트의 객체 표기법을 제한하여 만든 텍스트 기반의 데이터 교환 표준이다.
따라서 JSON 데이터는 자바스크립트가 자주 사용되는 웹 환경에서 사용하는 것이 유리하다.

자바스크립트에서 JSON 데이터를 분석하고 사용하는 것은 매우 간단하다.
자바스크립트는 JSON 데이터를 처리하기 위한 메소드를 제공하고 있다.

---


### JSON.parse() 메소드

JSON.parse() 메소드는 인수로 전달받은 문자열을 자바스크립트 객체로 변환하여 반환한다.

문법 
***JSON.parse(text)***


```javascript

const list = '[{"name":"eggs","price":1},{"name":"coffee","price":9.99},{"name":"rice","price":4.04},{"name":"brice","price":4.04},{"name":"arice","price":4.04}]';
console.log(typeof(list));      //string

const list2 = JSON.parse(list);
console.log(typeof (list2));        //object

```  



### JSON.stringify() 메소드

JSON.stringify() 메소드는 인수로 전달받은 자바 스크립트 객체를 문자열로 변환하여 반환한다.

문
***JSON.stringify(value, replacer, space)***

value(필수): JSON 문자열로 변환할 값이다. (배열, 객체, 또는 숫자, 문자 등)

replacer(선택): 함수 또는 배열이 될 수 있다. 이 값이 null 이거나 제공되지 않으면 객체의 모든 속성들이 JSON 문자열 결과에 포함된다.


```javascript

const list3 = JSON.stringify(list2);
console.log(typeof(list3));     //string


```

### Array.pop() 메소드

Array.pop()메소드는 배열에서 마지막 요소를 제거하고 그 요소를 반환한다.

문법
***arr.pop()***

빈 배열에 pop() 을 호출하면, undefined 를 반환한다.

```javascript

const fruits = [ "apple", "orange", "strawberry", "grapefruit", "fig" ];

console.log(fruits.pop());       // pig
console.log(fruits);        // Array [ "apple", "orange", "strawberry", "grapefruit"]

```


### Array.pop() 메소드

Array.pop() 메소드는 주어진 함수의 테스트를 통과하는 모든 요소를 모아 새로운 배열을 반환한다.

```javascript


```