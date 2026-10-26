![프로필 배너](https://github.com/user-attachments/assets/658b4a3a-30ab-4517-8e55-8ae0a5db61fd)

# 안민성 | 백엔드 개발자

광고 자동화, 이커머스, 의료·뷰티 플랫폼을 개발해 온 약 5년 경력의 백엔드 중심 풀스택 개발자입니다.

기존 시스템과 운영 업무를 분석하고, 요구사항 정리부터 데이터베이스·API 설계, 백엔드와 관리자 화면 개발, 배포·운영까지 맡아 왔습니다. 기능 구현뿐 아니라 실제 사용 흐름과 변경·장애에 대응할 수 있는 구조를 함께 고민합니다.

실무에서는 **PHP·Laravel·CodeIgniter**를 사용했습니다. 현재는 그 경험을 바탕으로 **Java·Spring Boot 기반 K-뷰티 플랫폼을 개인 사업화 프로젝트로 기획·개발**하고 있습니다. React·Next.js 프론트엔드도 함께 개발하며 화면과 API, 데이터의 흐름을 연결합니다.

**[포트폴리오](https://lupusportfolio.com) · [이메일](mailto:ms1114@kakao.com)**

## 경력 요약

| 기간 | 회사 | 담당 업무 |
| --- | --- | --- |
| 2026.01 ~ 현재 | 뷰랩스 | 플랫폼 리뉴얼 기획, 백엔드·관리자 시스템 설계 및 개발 주도 |
| 2024.05 ~ 2025.03 | 세이브마케팅 | Laravel 광고 관리 프로그램 개발·유지보수, 광고 API 연동 및 보안 강화 |
| 2023.01 ~ 2024.04 | 케어랩스 | 광고 운영 시스템 리뉴얼, 광고 데이터 수집 및 캠페인 운영 자동화 |
| 2020.12 ~ 2022.04 | 메씨인터내셔날 | 웹사이트 빌더, 쇼핑몰 및 행사 ERP 백엔드 개발 |
| 2019.06 ~ 2019.11 | 메이크24 | 기업·소상공인 웹사이트 제작 및 운영·유지보수 |

## 대표 프로젝트

### 뷰랩 | 실무 · 뷰랩스

**기존 서비스 분석과 기획부터 백엔드·관리자 시스템 재설계까지 맡은 성형·뷰티 플랫폼 리뉴얼**

사용자와 파트너, 내부 운영자의 기능이 섞여 있고 권한·API·데이터 처리 기준이 일관되지 않던 시스템을 분석했습니다. PM과 요구사항과 화면 흐름을 정리하고, 데이터 모델과 API 설계부터 백엔드·관리자 프론트엔드 구현까지 주도했습니다.

- Staff·Hospital·Beauty·User의 API와 앱 경계를 나누고 서버에서 접근 권한을 검증하도록 재구성
- 병원·뷰티 업체 등록과 검수, 의료진·전문가, 이벤트·콘텐츠·고객 관리부터 지갑·채팅·알림까지 주요 운영 기능 구현
- 도메인별 Action·Query, 공통 응답·예외·운영 이력을 구성하고 트랜잭션·행 잠금·멱등성·큐로 중복 요청과 비동기 처리에 대응
- Next.js 모노레포에서 운영자·서비스 사용자·파트너 앱의 역할을 구분하고 공통 API·인증·UI 패키지 구성

**개선한 점:** 메뉴 노출에 의존하던 권한 처리를 서버 검증으로 전환하고, 도메인별 변경 범위와 운영 이력을 구분해 유지보수와 문제 추적의 기준을 마련했습니다.

**앱 구현 범위:** Staff 주요 운영 기능, User 인증·채팅·알림, Hospital 계정 생성·비밀번호 재설정 흐름을 구현했습니다. user-web은 서비스 앱의 웹 버전이며, Hospital·Beauty 앱은 파트너 관리자용으로 구성했습니다.

**기술:** PHP · Laravel 12 · MySQL · Redis · Horizon · Reverb · Next.js · TypeScript · AWS

[백엔드 저장소](https://github.com/xowlsakffl/beaulab_backend) · [프론트엔드 저장소](https://github.com/xowlsakffl/beaulab_frontend)

### K-뷰티 플랫폼 | 개인 · 사업화 목표로 개발 중

**뷰티 업체 탐색과 비교부터 이벤트 신청·상담·예약까지 연결하기 위해 기획한 서비스**

업체 위치뿐 아니라 시술 종류와 가격, 담당 전문가와 작업 이미지를 함께 비교할 수 있는 서비스를 만들고 있습니다. 혼자 기획과 데이터 모델·API 설계, Spring Boot 백엔드와 Next.js 운영자·파트너 화면 개발을 진행하고 있습니다.

- **현재 구현:** 업체·전문가 관리, 파트너 가입과 다중 업체 온보딩, 이벤트 검수, 공지사항·FAQ 운영 기능
- **접근 제어:** Staff·Partner·User별 API 경계, JWT·회전형 갱신 세션, 역할과 리소스 소유권에 따른 서버 권한 검증
- **데이터 관리:** 트랜잭션·잠금과 수정 버전 검증으로 동시 변경에 대응하고, 변경 전후 값과 수행자를 공통 이력으로 기록
- **프론트엔드:** 운영자 웹과 파트너 포털을 분리하고 API·인증·타입·관리자 UI를 공통 패키지로 구성

**설계에 집중한 점:** 계정과 업체의 관계, 입점·검수 상태, 접근 권한과 변경 이력을 먼저 정리했습니다. 한 계정의 여러 업체 관리와 운영자·파트너의 협업을 고려한 구조입니다.

**후속 개발:** 사용자 업체 탐색, 이벤트 신청, 상담·예약 및 후기. 현재 구현한 관리자 기능과 구분해 단계적으로 개발하고 있습니다.

**기술:** Java 21 · Spring Boot 4 · Spring Security · Spring Data JPA · MySQL · Redis · Next.js · TypeScript

[백엔드 저장소](https://github.com/xowlsakffl/platform_backend) · [프론트엔드 저장소](https://github.com/xowlsakffl/platform_frontend)

### 제니스 광고 운영 시스템 | 실무 · 케어랩스

**느린 PHP 5.x 레거시 도구를 리뉴얼하고 수작업 광고 운영을 자동화한 프로젝트**

기존 도구와 운영 업무를 분석해 리뉴얼 범위를 정리하고, 광고 매체 API 연동부터 캠페인 자동화, 랜딩 페이지와 신청 데이터 처리까지 개발했습니다. 운영 담당자와 요구사항을 조율하고 배포 후 수집 실패와 광고 API 변경에도 대응했습니다.

- PHP 8·CodeIgniter 4 기반으로 재구성하고 Google·Kakao·Facebook 광고 데이터를 API로 수집, Naver를 포함한 매체별 계정·성과 데이터를 통합 조회
- 조건별 캠페인 상태·예산·목표 전환 자동화와 실행 결과·실패 원인 로그 구현
- 랜딩 페이지·신청 폼 구성부터 중복 검증, 상태 분류, 외부 제휴사 전송·재전송까지 처리 흐름 연결

**개선한 점:** 여러 매체의 광고 운영과 신청 데이터 처리를 한 시스템으로 연결하고, 반복 수작업을 자동화해 운영 부담을 줄였습니다.

**기술:** PHP · CodeIgniter 4 · MySQL · AWS EC2·RDS · Linux · 광고 매체 API

[광고 운영 시스템](https://github.com/xowlsakffl/php_ci4_zenith) · [랜딩 운영 모듈](https://github.com/xowlsakffl/php_zenith_operate)

## 기술과 사용 경험

| 구분 | 기술 | 사용 경험 |
| --- | --- | --- |
| 백엔드 · 실무 | PHP, Laravel, CodeIgniter | 플랫폼·광고·커머스 API, 관리자 시스템, 외부 연동 및 유지보수 |
| 백엔드 · 개인 | Java, Spring Boot, Spring Security, JPA | K-뷰티 플랫폼과 개인 서비스의 인증·권한, 도메인 로직 및 API 개발 |
| 데이터 | MySQL, Redis | 데이터 모델링, 트랜잭션·잠금, 캐시·큐와 인증 상태 관리 |
| 프론트엔드 | React, Next.js, TypeScript, JavaScript, jQuery | 실무 관리자 화면, 모노레포 공통 패키지 및 개인 서비스 개발 |
| 인프라·협업 | AWS, Linux, Git, Jira, Slack | 서비스 배포·운영, 변경 관리 및 협업 |

## 그 외 실무 프로젝트

메씨인터내셔날에서 개발한 프로젝트입니다. 프로젝트별 상세 설명과 화면은 [포트폴리오](https://lupusportfolio.com)에서 확인할 수 있습니다.

| 프로젝트 | 담당 내용 | 기술 | 저장소 |
| --- | --- | --- | --- |
| 이벤츠팩 웹사이트 빌더 | 레이아웃 조각·기능팩을 조합하는 관리자와 사이트 구성 API 개발. 반복 제작하는 행사 사이트의 구성을 공통 구조로 설계 | Laravel, MySQL, Passport | [관리자](https://github.com/xowlsakffl/php_laravel_EventPack_admin) · [사용자 API](https://github.com/xowlsakffl/php_laravel_EventsPack_dev1) |
| 백락온 쇼핑몰 | 상품 유형별 주문 구조, 회원·장바구니·결제·관리자 개발. Toss Payments 결제와 가상계좌 콜백, Aligo 주문 알림 연동 | Laravel, MySQL, Toss Payments | [저장소](https://github.com/xowlsakffl/php_laravel_100rakon) |

## 그 외 개인 프로젝트

| 프로젝트 | 구현 내용 | 기술 | 저장소 |
| --- | --- | --- | --- |
| 빗썸 자동매수 | 거래소 API 연동, 주문 전 검증, 일일 예산과 중복 매수 방지 | Python, ccxt, pandas | [저장소](https://github.com/xowlsakffl/auth-bithumb-buyer) |
| 게임허브 | 멀티 모듈 백엔드의 채팅·파티·권한 구현. 프론트는 인증·파티 목록·친구 기능까지 연동했고 채팅·파티 관리 화면은 후속 범위 | Spring Boot, React, MySQL | [저장소](https://github.com/xowlsakffl/gameHub-multi-module-) |
| SNS | JWT 인증, 게시글·댓글·좋아요, SSE 알림, 신고·자동 블라인드와 관리자 기능 | Spring Boot, React, MariaDB, Redis | [저장소](https://github.com/xowlsakffl/sns_service) |
| 주차장 찾기 | 주소 검색, 거리 계산, 추천 순위와 길안내를 연결한 주차장 추천 | Spring Boot, Handlebars, MariaDB, Kakao Local API | [저장소](https://github.com/xowlsakffl/parking-recommendation) |
| 기어허브 | 상품·장바구니·주문·관리자 기능을 구현한 전자제품 이커머스. 실제 결제 승인 없이 주문을 생성하는 데모 결제 제공 | Spring Boot, React, MySQL | [백엔드](https://github.com/xowlsakffl/Gearhub_springboot) · [프론트엔드](https://github.com/xowlsakffl/Gearhub_react) |
