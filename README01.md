### 확장프로그램 설치하기

![image](https://github.com/OnlyREHA/sass/assets/145514740/d17732d8-fb0f-4a50-9120-8a84191f361b)

### 밑에 watching 누르면 style.css로 자동 번역

![image](https://github.com/OnlyREHA/sass/assets/145514740/dcdd6de4-d288-4a66-b2d4-59e24acdcb1e)


### 네스팅 (nesting) -- 품다

![image](https://github.com/OnlyREHA/sass/assets/145514740/3c9a294a-d920-4240-99d1-c40196f15d7a)

### 저장경로


"savePath": null, --> null 이면 scss파일과 같은 위치에 style.css가 생긴다

"savePath": ~/css, --> ~ 은 style.scss를 의미, /는 style.scss가 있는 폴더를 의미, scss파일과 같은 위치에 css폴더가 생성되고 그 css폴더안에 컴파일된 style.css가 생긴다

"savePath": "~/../css" --> style,scss가 있는 폴더(부모)와 같은 위치에 css폴더를 생성되고 그 css폴더안에 컴파일된 style.css가 생긴다

![image](https://github.com/OnlyREHA/sass/assets/145514740/1c187569-a11c-4ebe-869b-69b2e54922fa)


### 변수만들기

 📌 scss에서 변수 --> $로 시작한다(영문,숫자,-,_)만 사용할수 있다.
 
 📌 숫자로 시작하면 안됨

 ### 인터폴레이션 방법 
 
 (보간법) : 변수나 표현식을 문자열 내에 삽입하는 기능을 의미

 ![image](https://github.com/OnlyREHA/sass/assets/145514740/ac17a3f3-c82f-413b-82eb-904f5dd9deb1)

 ### Partials (파샬 - 부분적인)

 : 소스에 반복되는 부분을 분산시켜서 모듈화 시키는 기능(관련된 것끼리 묶어서 분리,분산하는 것)

 - 파샬 파일명은 입력할때에는 _파일명 -> 파일을 불러올때는 @import "파일명" ( _ ,확장명 없이) 경로는 상대경로를 사용한다

 - scss는 _로 시작하는 파일은 컴파일하지 않는다.



















