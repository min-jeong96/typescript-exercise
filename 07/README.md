# EXERCISE 07

- ```swap()```d ```any``` 타입이 아닌 타입을 지정하면서, 어떤 타입으로든 받을 수 있게 해야 한다.
  - ```test.ts```에서 오류가 나는 이유: ```string```, ```number```, ```boolean```이라는 원시 타입으로 인해, 명시하지 않은 ```swap()``` 함수의 parameter 타입이나 반환된 배열의 타입이 ```any```가 되기 때문. (```isNotAny```여야 타입이 같은지 비교하는 ```type-assertions```.)

## Generic Type

- 선언 시점이 아니라 ***생성 시점에 타입을 명시***하여 하나의 타입만이 아닌 다양한 타입을 사용할 수 있도록 하는 기법이다.
- 한 번의 선언으로 다양한 타입에 재사용이 가능하다.
- ```<T>```로 작성하는 경우가 많은데, 이는 Generic을 선언할 때 관용적으로 사용되는 식별자로 ```타입 파라미터(Type parameter)```라 한다.

---