# EXERCISE 08

- ```UsersApiResponse```, ```AdminsApiResponse```를 삭제한다.
- generic type ```ApiResponse<T>```을 맞게 작성하여 모든 API의 ```response``` 타입으로 사용하도록 변경한다.
  - ```status```가 ```'success'```, ```'error'```일 수 있으며, 각각 값에 따라 갖는 property가 다르다.
  - ```'success'```일 경우는 ```data``` property를 반환해야 하는데, 이는 배열일 수도 있고 배열이 아닌 객체일 수도 있다.
  - ```'error'```일 경우는 ```error``` property를 반환해야 하는데, 이 ERROR_MESSAGE는 항상 ```string```이다.
- 작성되어있는 function마다 ```response``` parameter의 type을 ```ApiResponse<T>```에 맞게 수정해준다.

읽어보기: https://www.typescriptlang.org/ko/docs/handbook/2/generics.html