# 유현승

정합성, 성능, 유지보수성을 기준으로 구조를 설계하는 백엔드 개발자입니다.  
실서비스 운영, 결제 시스템 설계, AWS 인프라 이전, 레거시 SQL 최적화 경험을 바탕으로 운영 안정성·장애 대응·변경 비용까지 함께 고려하는 개발을 지향합니다.

---

## 핵심 성과

- **3만+ 가입자 / MAU 3,500+ / 약 2년 운영** 규모의 학생 커뮤니티 서비스 개발 및 운영
- **누적 결제 4,000+건 / 결제 장애 0건 / CS 0건**을 달성한 결제 시스템 설계 및 고도화
- Oracle INSERT 성능 **2,176ms → 31ms (-98%)** 개선
- 기능 구현을 넘어 **운영 안정성, 장애 격리, 변경 비용**까지 함께 고려하는 개발 지향

---

## 프로젝트 경험

| 기간 | 프로젝트 | 소개 | 역할 | 기술 |
|---|---|---|---|---|
| 2023.10 ~ 2025.11 | [시대생](https://github.com/uoslife) | 3만+ 가입자 규모의 서울시립대 학생 커뮤니티 서비스 개발 및 운영 | Backend Lead | ![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white) ![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white) |
| 2025.04 ~ 2025.06 | [시대팅](https://github.com/uoslife) 시즌6 | 1:1 미팅 구조에 맞춘 결제 흐름 고도화 및 운영 안정성 강화 | Backend Lead | ![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white) ![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white) ![PortOne](https://img.shields.io/badge/PortOne-4B5AE4?style=flat-square) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) |
| 2024.02 ~ 2024.06 | [시대팅](https://github.com/uoslife) 시즌4 | 학생 미팅 서비스에 유료 결제 시스템을 처음 도입하고 운영 | Backend Developer | ![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white) ![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white) ![PortOne](https://img.shields.io/badge/PortOne-4B5AE4?style=flat-square) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) |
| 2024.07 ~ 2024.12 | 통계 입력 시스템 | Oracle/MyBatis 기반 통계 시스템 조회·백업 성능 개선 | Backend Intern (한국통계정보원 인턴) | ![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white) ![Spring MVC](https://img.shields.io/badge/Spring%20MVC-6DB33F?style=flat-square&logo=spring&logoColor=white) ![MyBatis](https://img.shields.io/badge/MyBatis-000000?style=flat-square) ![Oracle](https://img.shields.io/badge/Oracle-F80000?style=flat-square&logo=oracle&logoColor=white) |
| 2023.06 ~ 2023.09 | [QR 모바일 주문 서비스](https://github.com/UOS2021) | 키오스크 UI 문제를 줄이기 위한 QR 기반 모바일 주문 서비스 개발 | Backend Developer | ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) |

---

## 주요 기여

### [시대생](https://github.com/uoslife)
- **총 가입자 3만+ / MAU 3,500+ / 약 2년 운영** 규모 서비스 개발 및 운영
- 인증/인가, 시간표, 학적, 공지 등 핵심 기능의 백엔드 구현
- **백엔드 리드 및 운영진**으로서 기능 확장과 운영 안정화에 기여
- 인증 체계 개선, 인프라 이전, 전용 수집 서버 분리로 **운영 효율과 장애 격리 구조** 강화

### [시대팅](https://github.com/uoslife)
- 시즌4에서 유료 결제 시스템을 처음 도입하고, 시즌6에서 1:1 구조에 맞춰 결제 흐름을 고도화
- 상태 전이, 멱등성, 주문 단위 유니크 제약, 웹훅 검증 구조를 적용해 **중복 결제와 상태 불일치 방지**
- **누적 결제 4,000+건 / 결제 장애 0건 / CS 0건** 달성
- PG 테스트 API 기반 사전 검증으로 운영 단계의 결제 리스크 최소화

### 한국통계정보원 인턴
- 복잡한 통계표 조회 쿼리 리팩토링으로 SQL 구조 개선
- Oracle INSERT 성능 **2,176ms → 31ms (-98%)** 개선
- 반복 로직을 비트마스크 기반으로 전환해 조회 성능 및 코드 단순성 향상
- 레거시 통계 시스템의 조회·백업 구조 개선 경험 축적

---

## 기술 문서

- [Spring MVC에서 JSON 요청 바인딩 문제 해결](https://www.notion.so/iambusy/Spring-MVC-JSON-15376d34e2a58021aa10ff9499a02194?source=copy_link)
- [리스트 반복문 대신 비트마스크 한 줄로 끝내기](https://www.notion.so/iambusy/29076d34e2a580498303f7dea0bd392c?source=copy_link)
- [Oracle INSERT 쿼리 최적화](https://www.notion.so/iambusy/Oracle-INSERT-2-176ms-31ms-16c76d34e2a580fea733e6b46de4e3d3?source=copy_link)
- [통계표 기본 정보 조회 쿼리 최적화](https://www.notion.so/iambusy/15276d34e2a580218054d6bb98effb55?source=copy_link)
- [로컬 & 배포 환경에서 AWS 자격 증명 흐름 정리](https://www.notion.so/iambusy/AWS-33676d34e2a5807ea194ce262f3fe402?source=copy_link)
- [결제 시스템 연동 가이드 - PortOne 기반](https://www.notion.so/iambusy/PortOne-33676d34e2a580cc98d3fb55da29272a?source=copy_link)

---

## 기술 스택

### Backend
![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Spring MVC](https://img.shields.io/badge/Spring%20MVC-6DB33F?style=flat-square&logo=spring&logoColor=white)
![JPA](https://img.shields.io/badge/JPA-59666C?style=flat-square)
![MyBatis](https://img.shields.io/badge/MyBatis-000000?style=flat-square)

### Database
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=flat-square&logo=oracle&logoColor=white)

### Infra / Tools
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

---

## 학력

- 2026.01 ~ 현재 : SSAFY 15기
- 2018.03 ~ 2026.02 : 서울시립대학교 컴퓨터과학부
- 2015.02 ~ 2018.02 : 선린인터넷고등학교 정보통신과

## 자격증

- 정보처리기사 (2024.09)
- SQLD (2024.09)
- TOEIC Speaking IH (2025.10)

---

## 활동 지표

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=UDADDY&show_icons=true&theme=tokyonight)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=UDADDY&layout=compact&theme=tokyonight)

[![Solved.ac Profile](http://mazassumnida.wtf/api/v2/generate_badge?boj=gustmd5715)](https://solved.ac/profile/gustmd5715)

---

## 연락처

- 이메일: gustmd5715@gmail.com
- GitHub: [github.com/UDADDY](https://github.com/UDADDY)
