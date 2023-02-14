# EXERCISE 05

- ```filterUsers()```의 필터링 조건이 되는 ```criteria``` parameter를 ```User```가 아닌 ```User``` Type의 모든 Subset이 오도록 타입을 지정해주어야 한다.
- ```User```는 항상 ```type: 'user'```라는 고정된 값을 가지므로, 필터링 조건에서 ```type``` property는 제외한다.

## ```Partial<Type>```

- ```Type```의 가능한 모든 subset type.

## ```Omit<Type, Keys>```

- ```Type```에서 ```Keys```를 제외한 Type.
- ```Keys```는 ```string``` 이거나 ```union string('key1' | 'keyw2' | ...)```이 올 수 있다.

출처: https://www.typescriptlang.org/docs/handbook/utility-types.html#partialtype
출처: https://www.typescriptlang.org/docs/handbook/utility-types.html#omittype-keys