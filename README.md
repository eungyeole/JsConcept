## 1. TypeValue
  - String : 모든 문자열
  - Number : 정수, 실수, NaN, infinity
  - Boolean : true, false
  - Null : null
  - Undefined : undefined

## 2. Wrapper Object
  - 원시 타입의 객체 형태
  - 원시타입에서 new 키워드로 생성
  - Wrapper Object가 있기때문에 원시타입에서도 생성자 및 해당 메소드를 사용할수있음
  - Wrapper Object가 없는 원시타입(null, undefined)
  
## 3. AutoBoxing
  - 원시 타입(Primitive Type)이 생성자(constructor) 및 해당 메소드(method)를 쓸수 있는 이유
  - 원시 타입(Primitive Type)에서 특정 property나 method를 호출하려고 할때 javascript는 임시로 Wrapper Object로 변환하여 접근

## 4. 원시타입 ( Boolean, Null, Undefind, String, Number, Symbol )
  - 원시타입은 immutable data type이기 때문에, 값이 변경될 경우, 새로운 값을 할당을 받음.
  
  
## 5. 객체타입 ( Object )
  - 메모리상의 실제 객체의 위치를 나타내는 주소값을 할당받음.
  
## [원시타입 vs 참조타입]
`
int i = null;//불가능

Integer integer = null; //가능
`
