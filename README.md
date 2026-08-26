# 안민성 | Backend Developer

광고 자동화, 이커머스, 의료·뷰티 플랫폼을 개발해 온 약 5년 경력의 백엔드 중심 풀스택 개발자입니다.

Laravel과 CodeIgniter 기반 실무에서 요구사항 분석, 데이터베이스와 API 설계, 관리자 시스템 개발, 외부 API 연동, 배포와 운영까지 수행했습니다. 최근에는 Java·Spring Boot 기반 프로젝트를 통해 객체지향 설계, 인증·권한, 트랜잭션과 동시성 제어 역량을 확장하고 있습니다.

React와 Next.js 프론트엔드 경험을 바탕으로 화면, API, 데이터 흐름을 하나의 시스템 관점에서 판단하며, 기능 구현 이후의 데이터 정합성, 운영 안정성과 유지보수성까지 함께 고려합니다.

[Portfolio](https://lupusportfolio.com) · [Email](mailto:ms1114@kakao.com)

## What I Do

- 기존 서비스와 운영 프로세스를 분석하고 요구사항, 데이터 구조와 기능 흐름을 다시 설계합니다.
- 역할별 접근 경계와 도메인 책임을 나누고 API와 비즈니스 로직을 구현합니다.
- 트랜잭션, 행 잠금, 멱등성, 유니크 제약과 큐를 활용해 데이터 정합성을 지킵니다.
- 광고·결제·SMS·실시간 통신 등 외부 시스템을 연동하고 실패와 재처리를 고려합니다.
- 관리자 화면부터 배포와 운영까지 연결해 반복 업무와 운영 문제를 개선합니다.

## Tech Stack

**Backend**

![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=flat-square&logo=laravel&logoColor=white)
![CodeIgniter](https://img.shields.io/badge/CodeIgniter-EF4223?style=flat-square&logo=codeigniter&logoColor=white)

**Data & Infrastructure**

![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

**Frontend**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=111111)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)

## Experience

| 기간 | 회사 | 주요 업무 |
| --- | --- | --- |
| 2026.01 ~ 현재 | 뷰랩스 | 성형·뷰티 플랫폼 리뉴얼 기획, 백엔드 API와 관리자 시스템 설계·개발 |
| 2024.05 ~ 2025.03 | 세이브마케팅 | 광고 관리 프로그램 개발·유지보수, 광고 API 연동과 보안 개선 |
| 2023.01 ~ 2024.04 | 케어랩스 | Google·Kakao·Facebook 광고 데이터 수집과 캠페인 운영 자동화 |
| 2020.12 ~ 2022.04 | 메씨인터내셔날 | 웹사이트 빌더, 쇼핑몰과 행사 ERP 백엔드 개발 |
| 2019.06 ~ 2019.11 | 메이크24 | 기업·소상공인 웹사이트 제작과 PHP 서비스 운영·유지보수 |

## Work Projects

### 뷰랩 성형·뷰티 플랫폼 리뉴얼

기존 앱·서버와 운영 프로세스를 분석한 뒤 Staff, Hospital, Beauty, User의 접근 경계와 도메인 구조를 재설계했습니다. Laravel 12 백엔드와 Next.js 관리자 시스템을 중심으로 병원·의료진·이벤트·지갑·채팅·알림·SMS 기능을 구현하고 있습니다.

- [Backend](https://github.com/xowlsakffl/beaulab_backend)
- [Frontend](https://github.com/xowlsakffl/beaulab_frontend)

### 제니스 광고 운영 시스템

노후 PHP 환경의 광고 관리 도구를 개선하고 Google·Kakao·Facebook 광고 API, 반복 스케줄러, 캠페인 제어와 성과 데이터 수집을 연결했습니다. 광고 운영 백오피스와 랜딩 유입 데이터 수집 모듈을 역할별 저장소로 분리해 정리했습니다.

- [광고 운영 백오피스](https://github.com/xowlsakffl/php_ci4_zenith)
- [광고 랜딩 운영 모듈](https://github.com/xowlsakffl/php_zenith_operate)

### 이벤츠팩 웹사이트 빌더

페이지 조각과 입력 컴포넌트를 조합해 행사 웹사이트를 제작하고, 신청 폼과 관리자 기능까지 구성하는 빌더 솔루션입니다. 빌더 관리자와 사용자 인증·API의 책임을 두 저장소로 분리했습니다.

- [빌더 관리자](https://github.com/xowlsakffl/php_laravel_EventPack_admin)
- [사용자 인증·API](https://github.com/xowlsakffl/php_laravel_EventsPack_dev1)

### 백락온 이커머스

일반 구매, 정기배송과 연계상품의 서로 다른 주문 구조를 설계하고 상품 탐색부터 결제, 주문 이력, SMS 알림과 관리자 처리까지 연결한 Laravel 기반 건강식품 쇼핑몰입니다.

- [Repository](https://github.com/xowlsakffl/php_laravel_100rakon)

## Personal Projects

| 프로젝트 | 핵심 내용 | 저장소 |
| --- | --- | --- |
| K-뷰티 플랫폼 | 지역·업종별 업체 탐색과 이벤트·예약으로 확장하는 사업화 프로젝트. Spring Boot 운영 API와 Next.js 관리자 구현 | [Backend](https://github.com/xowlsakffl/platform_backend) · [Frontend](https://github.com/xowlsakffl/platform_frontend) |
| SNS Service | JWT 인증, 게시글·댓글·좋아요, SSE 알림, 신고·자동 블라인드와 관리자 기능 | [Repository](https://github.com/xowlsakffl/sns_service) |
| GameHub | 멀티 모듈 Spring Boot, WebSocket 채팅과 파티·멤버 권한 관리 | [Repository](https://github.com/xowlsakffl/gameHub-multi-module-) |
| GearHub | Spring Boot와 React로 구현한 상품·장바구니·주문 중심 전자제품 이커머스 | [Backend](https://github.com/xowlsakffl/Gearhub_springboot) · [Frontend](https://github.com/xowlsakffl/Gearhub_react) |
| 주차장 추천 | 위치와 조건을 기준으로 공공 주차장 데이터를 조회·추천하는 Spring Boot 서비스 | [Repository](https://github.com/xowlsakffl/parking-recommendation) |
| 빗썸 자동매수 | 거래소 API, 주문 전 검증, 일일 예산과 중복 매수 방지를 중심으로 구성한 Python 자동화 | [Repository](https://github.com/xowlsakffl/auth-bithumb-buyer) |

## Contact

- Email: [ms1114@kakao.com](mailto:ms1114@kakao.com)
- Portfolio: [lupusportfolio.com](https://lupusportfolio.com)
