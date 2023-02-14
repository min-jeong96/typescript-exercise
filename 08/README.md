# EXERCISE 08

- ```PowerUser```는 ```User```와 ```Admin```의 모든 property를 가지면서 ```type: 'powerUser```를 갖는 타입이어야 한다.

## Intersection: & Operator

- 이미 존재하는 타입/인터페이스로 새로운 타입을 만들 때 사용한다.
- ```&``` 연산자로 나열된 타입의 property를 모두 가진 타입이 된다.

## ```Omit<Type, Keys>```

- ```Type```에서 ```Keys```를 제외한 Type.
- ```Keys```는 ```string``` 이거나 ```union string('key1' | 'keyw2' | ...)```이 올 수 있다.

---

출처: https://www.typescriptlang.org/ko/docs/handbook/2/objects.html#intersection-types