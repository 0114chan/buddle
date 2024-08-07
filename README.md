# 암호화 문서 관리 시스템

## 프로젝트 개요
이 프로젝트는 사용자들이 중요한 개인 문서와 정보를 안전하게 저장하고 관리할 수 있는 웹 기반 플랫폼입니다. 고급 암호화 기술을 사용하여 데이터를 보호하고, 사용자에게 다양한 보안 기능을 제공합니다.

## 주요 기능
1. 강력한 사용자 인증 시스템 (다단계 인증 포함)
2. 문서 업로드, 암호화, 저장 (CRUD 기능)
3. 안전한 파일 첨부 및 다운로드
4. 암호화된 문서 목록 조회 및 상세 조회
5. 문서 공유 기능 (제한된 시간 동안만 접근 가능한 링크 생성)
6. 활동 로그 및 보안 감사 기능

## 기술 스택
- 프론트엔드: React, CryptoJS
- 백엔드: Spring Boot, Spring Security
- 데이터베이스: MySQL
- 인증: JWT (JSON Web Tokens)
- 기타: HTTPS, bcrypt (비밀번호 해싱)

## 시스템 요구사항
- Java 11 이상
- Node.js 14 이상
- MySQL 5.7 이상


### 백엔드 설정
1. 프로젝트를 클론합니다:

CRUD는 데이터베이스 및 RESTful API에서 가장 기본적인 데이터 처리 기능을 나타내는 약어입니다. 각 문자는 다음을 의미합니다:

C - Create (생성)

새로운 데이터 레코드를 생성하는 작업
예: 데이터베이스에 새 사용자 정보 추가


R - Read (읽기)

기존 데이터를 조회하거나 검색하는 작업
예: 사용자 목록 조회 또는 특정 사용자 정보 검색


U - Update (갱신)

기존 데이터를 수정하는 작업
예: 사용자의 이메일 주소 변경


D - Delete (삭제)

기존 데이터를 삭제하는 작업
예: 사용자 계정 삭제



CRUD는 대부분의 소프트웨어 애플리케이션에서 기본적으로 구현되는 기능들입니다. 이는 데이터베이스 관리 시스템(DBMS)뿐만 아니라 웹 애플리케이션, 모바일 앱, API 등 다양한 환경에서 사용됩니다.
웹 개발에서 CRUD 작업은 일반적으로 다음과 같은 HTTP 메서드와 매핑됩니다:

Create: POST 요청
Read: GET 요청
Update: PUT 또는 PATCH 요청
Delete: DELETE 요청
