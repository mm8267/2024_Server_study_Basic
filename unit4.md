### ⭐️ 4주차 과제 제출 ⭐️

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
![image](https://github.com/GDSC-Hanyang/2024_Server_study_Basic/assets/145014275/04c267cf-8ab6-432f-a44f-1d1c9225d69f)
![image](https://github.com/GDSC-Hanyang/2024_Server_study_Basic/assets/145014275/641c2797-e082-44b7-8aed-40481980b752)
![image](https://github.com/GDSC-Hanyang/2024_Server_study_Basic/assets/145014275/87b6b6c6-b77e-448f-88ef-fb49326cd218)
![image](https://github.com/GDSC-Hanyang/2024_Server_study_Basic/assets/145014275/3dd34ab4-1fb8-472f-9bc6-c5ee6b46cee2)
![image](https://github.com/GDSC-Hanyang/2024_Server_study_Basic/assets/145014275/f5917092-63bd-432f-8313-5a2c6c56f1bb)
![image](https://github.com/GDSC-Hanyang/2024_Server_study_Basic/assets/145014275/35633307-1686-43f1-87df-49efc5cbef2b)
1. 계정 생성 화면: 사용자가 새 계정을 생성하기 위한 초기 단계. 전화번호 또는 이메일을 통해 계정을 만들 수 있음, 국가 선택과 다음 버튼이 있음.
2. 이름 및 프로필 설정 화면: 사용자 이름을 설정하는 화면. 프로필 구성
3. 신규 계정 기본 화면: 새로 생성된 계정의 메인 페이지. 게시물, 팔로워, 팔로잉 수가 모두 0인 초기 상태
4. 계정 설정 화면: 사용자가 계정의 세부 설정을 조정할 수 있는 메뉴. 프로필 편집, 비밀번호 변경, 보안 설정 가능
5. 프로필 편집 화면: 사용자가 자신의 공개 프로필 정보를 수정할 수 있는 화면. 이름, 사용자 이름, 소개 등을 변경 가능
6. 다른 사용자의 인스타그램 포스트 화면: 다른 사용자가 올린 게시물을 보여주는 화면. 좋아요 수, 캡션, 해시태그 등의 정보가 포함되어있음.
<br/>

3. ERD 설계하기
   - 2번에서 진행한 내용을 바탕으로 직적 ERD 제작 툴을 사용해 작성해봅시다. (완성 후 캡쳐본 올리기)
![image](https://github.com/GDSC-Hanyang/2024_Server_study_Basic/assets/145014275/03481227-f04f-4e36-9e94-174feea90603)
아직 작업 중 
<br/>

4. AWS RDS 구축하기
   - ERD를 바탕으로 내가 기존에 만들어둔 AWS에서 RDS를 만들어 봅시다. (완성 후 캡쳐본 올리기)
![image](https://github.com/GDSC-Hanyang/2024_Server_study_Basic/assets/145014275/09b78f9a-bdce-434d-8110-565d09bab467)
아직 작업 중
<br/>
