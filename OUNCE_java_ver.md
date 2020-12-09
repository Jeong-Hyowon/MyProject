# :heart_eyes_cat: Ounce Server Refactoring version :heart_eyes_cat:

<div>
 <img src="https://user-images.githubusercontent.com/58697091/101301210-72051280-387b-11eb-954e-05a6833320c6.png" width="200" height="200">

</div>
<br>


입맛이 까다롭기로 소문난 반려동물 고양이. 맛있게 먹으면서도 건강한 제품을 찾아 나서는 집사들은, 캣푸드의 가장 작은 단위 1온스도 신중하게 선택합니다.

수많은 유목민 집사들에게 구조적이고 감각적인 도구가 되어줄 어플리케이션,

"집사를 위한 똑똑한 기록장, OUNCE"

<br>

### :pencil2: Pain Point
:smiley_cat: 다양한 제품을 돌아가면서 잘 먹는 제품들을 찾아두지만, 
그 개수가 많아지면서 기억하기 어려움

:smiley_cat: 88%의 집사가 사용하는 휴대폰 메모장에서는 
외래어 제품을 줄글로 기록해 직관적인 파악이 어려움

<br>

### :rainbow: Solution
:smiley_cat: 접근성이 좋은 휴대폰 App을 통해 기록

:smiley_cat: 사진, 정렬, 필터, 해시태그 기능을 활용해 구조적으로 기록하고 조회

:smiley_cat: 다묘 가정을 위해 여러마리를 등록하고 관리

<br>


### :open_file_folder: IA

![기능 명세](https://user-images.githubusercontent.com/58697091/101558176-c6d29580-3a01-11eb-87cd-4b41472ba609.PNG)

<br>

### :crystal_ball: ERD 

![ERD](https://user-images.githubusercontent.com/58697091/101423735-1733ef80-393d-11eb-97e1-f5dda43147b4.PNG)


<br>

### :computer: Configuration
* MAVEN
* MYBATIS
* JDBC
* LOMBOK
* MYSQL
* JWT
* FIREBASE
* SLF4J 
* HTTPCOMPONENTS
<br>

### :globe_with_meridians: SERVER ARCHITECTURE
![아키텍처](https://user-images.githubusercontent.com/58697091/101440988-61c46480-395b-11eb-8cfc-95dca2ee4ded.jpg)

<br>


###  :paperclip: Core Functions


####  - 고양이 등록 :cat2:
: 로그인 후 고양이의 이름과 만난 날짜를 최소 한 마리 이상 등록합니다.
 
 
####  - 메인 :page_facing_up:  
: 고양이를 만난 순간부터 잘 먹는 제품을 찾아 떠나는 여정은 시작됩니다.
고양이 정보와 함께, 기호도가 좋은 리뷰의 개수에 따라 다양한 테마가 보여집니다.


####  - 필터 / 정렬 :cat:  
: 작성한 리뷰 리스트를 다양한 기준으로 정렬하고 필터링합니다.


#### - 직관적인 기록 :pencil2:
: 제품을 검색해 기본적인 제품 사진과 제품명은 제공받고, 집사들이 가장 많이 기록하는 요소들을 중심으로 리뷰 작성틀을 제공합니다.

<br>