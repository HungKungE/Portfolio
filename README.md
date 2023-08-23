# 박상찬 Portfolio

### Intro
안녕하세요. 백엔드 개발자를 꿈꾸는 박상찬입니다.

---

### Contact

- E-mail : jonsun59@gmail.com
- GitHub : https://github.com/HungKungE
- Phone : 010-6336-5171

---

### Skills
- 개발 언어
<div>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=white">
  <img src="https://img.shields.io/badge/Typescript-3178C6?style=for-the-badge&logo=typescript&logoColor=white">
  <img src="https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white">
  <img src="https://img.shields.io/badge/python-3776AB?style=for-the-badge&logo=python&logoColor=white"> 
</div>
</br>

- 프레임워크 & 라이브러리
<div>
  <img src="https://img.shields.io/badge/react-61DAFB?style=for-the-badge&logo=react&logoColor=black"> 
  <img src="https://img.shields.io/badge/Express-339933?style=for-the-badge&logo=Node.js&logoColor=white">
  <img src="https://img.shields.io/badge/actix_web-000000?style=for-the-badge&logo=rust&logoColor=white">
  <img src="https://img.shields.io/badge/Flask-3776AB?style=for-the-badge&logo=python&logoColor=white"> 
</div>
</br>

- SQL
<div>
  <img src="https://img.shields.io/badge/mysql-4479A1?style=for-the-badge&logo=mysql&logoColor=white">
  <img src="https://img.shields.io/badge/postgresql-4169E1?style=for-the-badge&logo=postgresql&logoColor=white">
</div>
</br>

- DevOps
<div>
  <img src="https://img.shields.io/badge/aws-232F3E?style=for-the-badge&logo=amazon&logoColor=white">
</div>
</br>

- 협업
<div>
  <img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white">
  <img src="https://img.shields.io/badge/docs-4285F4?style=for-the-badge&logo=google&logoColor=white">
  <img src="https://img.shields.io/badge/sheets-34A853?style=for-the-badge&logo=google&logoColor=white">
  <img src="https://img.shields.io/badge/figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white">
  <img src="https://img.shields.io/badge/notion-000000?style=for-the-badge&logo=notion&logoColor=white">
</div>
</br>

---

## Project

### 1. [태블릿 전용 문제집 사이트](https://github.com/HungKungE/Jogiyo-v2)

태블릿의 터치펜을 사용해서 문제집의 문제를 풀고 채점 하는 사이트.
이외에도 학업에 도움을 주는 여러 서비스를 제공한다.

| 개발 기간 | 2022.08 - 2022.10 |
| ------ | ------ |
| 서비스 | 문제 풀기, 문제집 검색, 오답노트, 일일 단어장(커리큘럼) 등 |
| 사용 문제집 | EBS수능특강, 수능완성, 평가원 시험지 등 |

**사용 Skills**
```sh
React, Typescript, Tailwind-Css, Rust, NginX, PostgreSQL
```

**주요 개발 내용**
|내 역할|개발 내용| 상세 설명 |
| ----- | ------ | ------ |
|FE|페이지 디자인|문제집 검색 페이지, 회원정보 입력 페이지|
|BE|커리큘럼 api| 커리큘럼 추가, 수정, 삭제, 열람 |

---

### 2. [필기 노트 + 커뮤니티]()

아이패드의 notability, GoodNotes 처럼 필기 기능을 제공하는 사이트.
추가로 이런 필기 파일을 다른 사용자들과 공유하거나,
일상 이야기를 나누는 커뮤니티의 기능도 가지고 있다.

| 개발 기간 | 2022.10 - 2022.12 |
| ------ | ------ |
| 서비스 | 필기, 개인 필기 관리, 필기 공유, 사용자 그룹(커뮤니티)|

**사용 Skills**
```sh
React, Typescript, Tailwind-Css, Rust, NginX, PostgreSQL
```

**주요 개발 내용**
|내 역할|개발 내용| 상세 설명 |
| ----- | ------ | ------ |
|FE|페이지 디자인|개인 필기 노트 페이지, 사용자 그룹 페이지|
|BE|사용자 필기 노트 api| 노트 추가, 삭제, 열람, 수정|

---

### 3. [FindVibe - 사진 촬영 위치 예측 웹 서비스](https://github.com/HungKungE/FINDVIBE)

딥러닝을 통해서 사진을 분석하여 사진을 촬영한 위치를 예측한다.
찍힌 곳의 위치가 아닌, 그 사진을 찍은 사람의 위치나 방향정보를
예측하므로 같은 구도로 사진을 찍고 싶어하는 사람들에게
유용한 정보를 제공할수 있다.

|개발 기간 | 2023.03 - 2023.06|
| ------ | ------ |
|서비스 | 사진 업로드, 사진 촬영 장소 예측 | 

**사용 Skills**
```sh
React, Typescript, Tailwind-Css, NodeJs, Python, MySQL, AWS, Docker
```

**주요 개발 내용**
|내 역할|개발 내용| 상세 설명 |
| ----- | ------ | ------ |
|BE|Auth api|회원가입, 로그인, 로그아웃, 유효성 검사|
|BE|User api|닉네임 중복 확인, 닉네임과 비밀번호 수정|
|BE|Predict api-1|Google Cloud Vision Api를 통한 사진 위치 예측|
|BE|Predict api-2|Python 딥러닝모델을 통한 사진 위치 예측 요청|
|BE|Predict api-3|예측 요청 시, 전달받은 이미지 관리|
|BE|Predict api-4|예측 요청 Log 생성, 열람|
|BE|File api|Image 제공|
---

### 4. [KeywordKatch - 키워드 기반 기사 추천 웹 서비스](https://github.com/HungKungE/KeywordKatch-Publisher)
하루에 수많은 기사가 갱신되는 시대에 맞춰
내가 관심있는 정보를 담은 기사를 골라서 이메일로 알림을 주는
웹 서비스이다.

|개발 기간 | 2023.03 - 2023.06|
| ------ | ------ |
|서비스 | 사용자 정보 입력, 사용자 조건 검색, 사용자 간의 대화| 

**사용 Skills**
```sh
React, Typescript, Tailwind-Css, Spring, Python, AWS, RDS, Docker, MSA
```

**주요 개발 내용**
|내 역할|사용 스킬| 개발 내용 |
| ----- | ------ | ------ |
|publisher|HTML| 기사 내용을 담을 이메일 폼을 생성|
|publisher|SMTP| 이메일 서버 연결, 이메일 전송|
|publisher|Flask| publisher server 구현, client에 기사 내용 전달|


---

### 5. [WiseConnect - 중장년층 취업 매칭 사이트]()

취업 시장에서 약자인 정년퇴직자들의 재취업 매칭을 통해 사회적인 문제를 해결하고자 개발한 사이트.

|개발 기간 | 2023.06 - 2023.07|
| ------ | ------ |
|서비스 | 사용자 정보 입력, 사용자 조건 검색, 사용자 간의 대화| 

**사용 Skills**
```sh
React, Typescript, Tailwind-Css, Rust, NginX, PostgreSQL
```

**주요 개발 내용**
|내 역할|개발 내용| 상세 설명 |
| ----- | ------ | ------ |
|BE|User api| 사용자 정보 열람, 수정|
|BE|User api| 사용자 조건 검색|
---
