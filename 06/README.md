# EXERCISE 06

- ```filterPersons()```가 필터링하는 ```personType```에 따라 ```User[]```, ```Admin[]```로 반환해야 한다.
  - TypeScript는 function의 parameter 개수 또는 return type이 다른 function의 overloading을 지원한다.

- ```criteriaKeys```는 어떤 Interface가 오더라도 해당 Interface의 가능한 key 배열을 반환해야 한다.

## function-overload

- TypeScript는 function의 parameter 개수 또는 return type이 다른 function의 overloading을 지원한다.

## Generic Type

- 선언 시점이 아니라 ***생성 시점에 타입을 명시***하여 하나의 타입만이 아닌 다양한 타입을 사용할 수 있도록 하는 기법이다.
- 한 번의 선언으로 다양한 타입에 재사용이 가능하다.
- ```<T>```로 작성하는 경우가 많은데, 이는 Generic을 선언할 때 관용적으로 사용되는 식별자로 ```타입 파라미터(Type parameter)```라 한다.

---

출처: https://www.typescriptlang.org/docs/handbook/2/functions.html#function-overloads <br>
출처: https://www.typescriptlang.org/ko/docs/handbook/2/generics.html <br>
출처: https://poiemaweb.com/typescript-generic