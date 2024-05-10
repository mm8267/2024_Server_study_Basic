![image](https://github.com/mm8267/2024_Server_study_Basic/assets/144704798/fcb4f974-bf6e-4412-9db1-aeee90e36c08)![image](https://github.com/mm8267/2024_Server_study_Basic/assets/144704798/e762a880-4be1-44bf-89ef-813bf8b9bf14)### ⭐️ 4주차 과제 제출 ⭐️

## ❗️ 강의 수강 여부
수강한 강의에 체크표시 해주세요~

- [o] 데이터베이스
- [o] 데이터베이스_MySQL
- [o] 리눅스에 MySQL 설치하기

<br>

## ❗️ 3주차 과제
1. 관계형 데이터베이스 이론적으로 이해하기
  테이블로 이루어져 있음. 이 테이블은 키와 밸류의 관계를 나타냄. -> 데이터의 종속성을 관계로 표현하는 것이 특징
MS-SQL, MySQL, MariaDB, Oracle 등
열(column)
각각의 열은 유일한 이름을 가지며, 자신만의 타입을 가진다. 이러한 열을 필드(field) 또는 속성(attribute)라고 부른다.

행(row)
행은 관계된 데이터의 묶음을 의미한다. 한 테이블의 모든 행은 같은 수의 열을 가진다.
이러한 행은 튜플(tuple) 혹은 레코드(record)라고 한다.

값(value)
테이블은 각각 행과 열에 대응하는 값을 가진다. 이러한 값은 열의 타입에 맞는 값이어야 한다.

키(key)
키는 하나의 테이블을 구성하는 여러 열 중에서 특별한 의미를 지닌 하나 또는 여러 열의 조합을 의미한다. 기본키(primary key), 후보키(candidate key), 외래키(foreign key), 복합키(composite key)등이 있다.

관계(relationship)
테이블 간의 관계는 관계를 맺는 테이블 수에 따라 나뉜다.관계형 데이터베이스에서는 이러한 관계를 나타내기 위해 외래키를 사용한다. 외래키 는 한 테이블의 키 중에서 다른 테이블의 행을 식별할 수 있는 키를 의미한다.

일대일(one to one) 관계
일대다(one to many) 관계
다대다(many to many) 관계

스키마(schema)
스키마는 테이블을 디자인하기 위한 청사진. 이러한 스키마는 테이블의 각 열에 대한 항목과 타입뿐 아니라 기본 키와 외래 키에도 나타내야 함.
<br/>

2. 원하는 서비스(당근마켓, 인스타그램 등) 분석하기
   - 원하는 서비스를 하나 타겟팅 후 페이지 4장가량을 선정하고 (캡쳐본 올리기) 데이터베이스에 들어갈 내용을 적어주세요.
![image](https://github.com/mm8267/2024_Server_study_Basic/assets/144704798/40b38cd0-47dd-4c47-9dfc-0469bdad9010)
![image](https://github.com/mm8267/2024_Server_study_Basic/assets/144704798/5f98d3df-ca9a-4f19-9f0e-598a7586b6bd)
![image](https://github.com/mm8267/2024_Server_study_Basic/assets/144704798/124a95ca-cfb6-4987-a316-6f0e62a7a4c3)
![image](https://github.com/mm8267/2024_Server_study_Basic/assets/144704798/210c0f79-8cee-4dcd-99ba-92d7f027f96c)
![image](https://github.com/mm8267/2024_Server_study_Basic/assets/144704798/2cf1e2b6-bb98-4be8-b4aa-33d221400e2d)
![image](https://github.com/mm8267/2024_Server_study_Basic/assets/144704798/90852190-18b2-4c37-8c30-bc7ebd7edbac)
![image](https://github.com/mm8267/2024_Server_study_Basic/assets/144704798/f28d0b3f-085a-418b-98a9-0fec3c70af86)


1. 로그인 페이지:
* entity: Users
* 속성: UserID, Password, Email, SocialLoginType
* 기능: 사용자 로그인 정보 확인 및 소셜 로그인 연동
2. 메인 페이지:
* entity: Products, Promotions
* 속성: ProductID, Name, Price, DiscountRate, PromotionDetails
* 기능: 제품 및 프로모션 정보 표시, 다양한 할인 혜택 및 추천 제품 목록 제공
3. 사용자 프로필 페이지:
* entity: Users, Wishlist, Posts
* 속성: UserID, Username, ProfileImage, WishlistID, PostID
* 기능: 사용자 프로필 정보, 사용자의 위시리스트, 게시물 조회
4. 상품 목록 페이지:
* entity: Products, Categories
* 속성: ProductID, Name, Price, CategoryID, ImageURL, StockStatus
* 기능: 카테고리별 제품 목록 제공, 제품 검색 및 필터링
5. 상품 상세 페이지:
* entity: Products, ProductDetails, Reviews, Comments
* 속성: ProductID, Description, Price, DiscountRate, ReviewID, CommentID
* 기능: 상품 상세 정보, 리뷰, 사용자 댓글 및 평점 표시
6. 리뷰 section:
* entity: Reviews
* 속성: ReviewID, UserID, ProductID, Rating, Content, DatePosted
* 기능: 상품에 대한 사용자 리뷰 및 평점 표시
7. 문의 section:
* entity: Questions, Answers
* 속성: QuestionID, AnswerID, UserID, ProductID, Content, DatePosted
* 기능: 상품 관련 질문 및 답변 제공
<br/>

3. ERD 설계하기
   - 2번에서 진행한 내용을 바탕으로 직적 ERD 제작 툴을 사용해 작성해봅시다. (완성 후 캡쳐본 올리기)
![image](https://github.com/mm8267/2024_Server_study_Basic/assets/144704798/4978393f-1978-485c-a21e-d5430c93c9c4)

<br/>

4. AWS RDS 구축하기
   - ERD를 바탕으로 내가 기존에 만들어둔 AWS에서 RDS를 만들어 봅시다. (완성 후 캡쳐본 올리기)

아직 작업 중
<br/>
