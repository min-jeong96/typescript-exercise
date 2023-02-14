# EXERCISE 04

- ```isAdmin(person: Person)```, ```isUser(person: Person)```라는 타입 검사 목적의 함수 반환 값을 ```is``` 문법을 사용해 사용자 정의 Type Guard 함수로 만든다.

## Type Guard

### 사용자 정의 Type Guard

- JavaScript는 풍부한 런타임 내부 검사를 지원하지는 않는다.
- ```instanceof```나 ```typeof```와 같은 연산자를 일반 JavaScript 객체(interface, type 등)에 맞게 사용할 수 없다. (object가 된다.)
- 사용자 정의 Type Guard 함수는 ```어떤 인자가 어떤 타입이 맞는지``` 값을 리턴한다.

출처: https://www.typescriptlang.org/docs/handbook/advanced-types.html
출처: https://radlohead.gitbook.io/typescript-deep-dive/type-system/typeguard#type-guards