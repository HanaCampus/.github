# HanaCampus
[디지털 하나로 금융 서비스 개발 2기] - 0차 프로젝트
- 디지털 하나 路 교육생들이 사용할 수 있는 게시판입니다.
- 다양한 카테고리와 기능이 존재합니다.

## 목차
[1. 프로젝트 개요](#1-프로젝트-개요)

[2. 기능 설명](#2-기능-설명)

[3. 기술 스택](#3-기술-스택)

[4. ERD](#4-erd)

<br/><br/><br/>

## 1. 프로젝트 개요
| 항목 | 내용 |
| --- | --- |
| 프로젝트 소개 | 디지털 하나 路 교육생들을 위한 대화의 장! 취업, 맛집 등 나만의 꿀팁을 교육생들과 공유하고 win-win 합시다! |
| 개발 인원 | 총 4명 (서비스 기능 별 개발 분담) |
| 개발 기간 | 총 14일 (2024. 04. 26 ~ 2024 05. 09) |
<br/>

## 2. 기능 설명
### ➊ 회원가입 및 로그인
| 회원가입 | 로그인 |
|:---:|:---:|
| <img width="480" height="320"> | <img src="https://github.com/user-attachments/assets/7c2435fd-fa32-4dc8-a534-a9de5cc9cd0d" width="480" height="320"> |
| ✔️ 회원가입 시 닉네임과 성별을 입력합니다. | ✔️ 카카오 계정으로 로그인이 가능합니다. |
<br/>

### ➋ 게시글 조회
| <img src="https://github.com/user-attachments/assets/0b06ce1d-5765-4bc5-8856-4b4b2475bfd0" width="480" height="320"> <img src="https://github.com/user-attachments/assets/fa14e3d3-dd88-48ff-ab04-5874ab8401c0" width="480" height="320"> <img src="https://github.com/user-attachments/assets/3d5590dd-6a31-45ab-8e16-993fe40256c4" width="480" height="320"> <img width="480" height="320"> |
| --- |
| ✔️ 원하는 카테고리 게시판에 접근하여 게시글을 조회할 수 있습니다. |
| ✔️ 게시글과 댓글에 ‘좋아요’ 등록과 게시글 스크랩이 가능합니다. |
| ✔️ 게시글 조회 메뉴에서 게시글 또는 댓글에 대한 신고를 할 수 있습니다. |
<br/>

### ➌ 게시글 작성
| <img src="https://github.com/user-attachments/assets/fa90f3cd-7a1b-41b8-bde3-832eec2e4cfc" width="480" height="320"> |
|---|
| ✔️ 게시글 작성 버튼을 클릭하여 게시글을 작성할 수 있습니다.<br/>✔️ 위지윅(WYSIWYG) 방식의 WebEditor인 Summernote 라이브러리를 적용했습니다.<br/>✔️ 링크와 사진을 쉽게 첨부할 수 있습니다. |
<br/>

### ➍ 마이페이지
| <img src="https://github.com/user-attachments/assets/3c4f45db-3d41-468a-ab90-d1f6efe4c7ce" width="480" height="320"> |
|---|
| ✔️ 게시글 작성 버튼을 클릭하여 게시글을 작성할 수 있습니다.<br/>✔️ 위지윅(WYSIWYG) 방식의 WebEditor인 Summernote 라이브러리를 적용했습니다.<br/>✔️ 링크와 사진을 쉽게 첨부할 수 있습니다. |
<br/>

### ➎ 관리자 페이지
| <img src="https://github.com/user-attachments/assets/5d01e6f9-860a-42eb-bff3-4062b91fa013" width="480" height="320"> <img src="https://github.com/user-attachments/assets/9a01efe0-9dc8-408e-a311-bc66be2ca8e1" width="480" height="320"> <img src="https://github.com/user-attachments/assets/07775e89-6089-490b-868f-21e9b093c27a" width="480" height="320"> <img width="480" height="320"> |
| --- |
| ✔️ 게시글과 댓글에 대한 신고 내역과 완료된 신고 내역을 확인할 수 있습니다. |
| ✔️ 7일, 30일, 365일, 영구 단위로 유저 정지가 가능합니다. |
<br/>

## 3. 기술 스택
| 기술              | 사용 |
| ---------------- | --- |
| Frontend         | <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=TypeScript&logoColor=white"/> <img src="https://img.shields.io/badge/React Native-61DAFB?style=flat-square&logo=React&logoColor=black"/> <img src="https://img.shields.io/badge/styled components-DB7093?style=flat-square&logo=styled-components&logoColor=white"/> |
| Backend          | <img src="https://img.shields.io/badge/java-007396?style=flat&logo=OpenJDK&logoColor=white"/> <img src="https://img.shields.io/badge/Spring Boot-6DB33F?style=flat&logo=Spring Boot&logoColor=white"> <img src="https://img.shields.io/badge/Spring Security-6DB33F?style=flat&logo=Spring Security&logoColor=white"> <img src="https://img.shields.io/badge/Swagger-85EA2D?style=flat&logo=Swagger&logoColor=black"> |
| Database         | <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=MySQL&logoColor=white"> <img src="https://img.shields.io/badge/Redis-DC382D?style=flat&logo=Redis&logoColor=white"> |
| Deploy           | <img src="https://img.shields.io/badge/amazonec2-FF9900?style=flat&logo=amazonec2&s&logoColor=white"> <img src="https://img.shields.io/badge/amazonrds-527FFF?style=flat&logo=amazonrds&s&logoColor=white"> |
| API              | <img src="https://img.shields.io/badge/OpenAI-412991?style=flat&logo=OpenAI&logoColor=white"/> <img src="https://img.shields.io/badge/%EA%B8%88%EC%9C%B5%EA%B0%90%EB%8F%85%EC%9B%90-0033A0?style=flat&logoColor=white"/> <img src="https://img.shields.io/badge/ETRI-FF6600?style=flat&logo=ETRI&logoColor=white"/> <img src="https://img.shields.io/badge/CoolSMS-3C9DD0?style=flat&logo=CoolSMS&logoColor=white"/> |
| Cooperative Tool | <img src="https://img.shields.io/badge/github-181717?style=flat&logo=github&logoColor=white"> <img src="https://img.shields.io/badge/git-F05032?style=flat&logo=git&logoColor=white"> |
| IDE              | <img src="https://img.shields.io/badge/Visual Studio Code-007ACC?style=flat&logo=Visual Studio Code&logoColor=white"/> <img src="https://img.shields.io/badge/intellijidea-000000?style=flat&logo=intellijidea&logoColor=white"> |
<br/>

## 4. ERD
<img src="https://github.com/user-attachments/assets/5e20feff-7d24-415a-8f6b-75f622d82b29" width="75%"/>
<br/><br/>

