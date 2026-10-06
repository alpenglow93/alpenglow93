# Backend Developer

**Java / Spring 기반 백엔드 개발자**를 준비하고 있습니다.  
국비 과정에서 Spring Boot·Oracle 기반 웹 서비스를 팀 단위로 개발했고, Vue로 화면 구현까지 담당했습니다.  
실습을 통해 Jenkins·Docker 기반 배포 자동화 흐름도 경험했습니다.  
"돌아가는 코드"를 넘어 **왜 안 되는지 끝까지 원인을 찾는 개발자**가 되려고 합니다.

- 📧 Email: 0405_jh@naver.com

<br>

## 🛠 Tech Stack

**Backend**  
![Java](https://img.shields.io/badge/Java-007396?style=flat&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat&logo=springboot&logoColor=white)
![JPA](https://img.shields.io/badge/JPA-59666C?style=flat&logo=hibernate&logoColor=white)
![MyBatis](https://img.shields.io/badge/MyBatis-000000?style=flat)

**Database**  
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=flat&logo=oracle&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)

**Frontend**  
![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=flat&logo=vuedotjs&logoColor=white)
![Thymeleaf](https://img.shields.io/badge/Thymeleaf-005F0F?style=flat&logo=thymeleaf&logoColor=white)
![JSP](https://img.shields.io/badge/JSP-007396?style=flat)

**DevOps**  
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat&logo=jenkins&logoColor=white)
![AWS EC2](https://img.shields.io/badge/AWS_EC2-FF9900?style=flat&logo=amazonec2&logoColor=white)
![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=flat&logo=ubuntu&logoColor=white)

**Etc.**  
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

<br>

## 📂 Projects

### 🎓 EduVantage (학습관리시스템) — 팀 프로젝트 · [Repo](https://github.com/java-last-project/EduVantage)
`Spring Boot` `JPA` `MyBatis` `Thymeleaf` `Vue` `Pinia` `Oracle`

- **담당:** 강사 페이지, 관리자 페이지
- 페이지 특성에 따라 Thymeleaf(SSR)와 Vue(CSR)를 혼용하는 구조 설계
- 강의 등록/수정, 수강생 관리

### 🛒 3hose (신발 물류 관리 시스템 + 쇼핑몰) — 팀 프로젝트 · [Repo](https://github.com/SIST-SWMS/2026-web-project)
`Java Servlet` `JSP` `MyBatis` `Oracle` `Vue 3` `Axios`

- **담당:** 장바구니, 주문/결제 (프로젝트 내 가장 복잡한 도메인)
- 수량·사이즈 변경(재고 조회 연동), 선택 삭제, 단건/다건 주문, 시퀀스 기반 주문번호 발급
- **Jsoup 크롤러를 자발적으로 제작**해 실제 쇼핑몰 상품 데이터를 수집 → Oracle INSERT SQL 자동 생성
- 트러블슈팅: MyBatis `ORA-17004` null 바인딩 원인(insert 시 VO 누락) 추적 및 해결
- 회고: 메서드별 SqlSession 분리로 인한 트랜잭션 정합성 문제를 인지하고 개선 과제로 정리

<br>

## 🧪 학습 · 실습

### 🚀 CI/CD 배포 파이프라인 구축 실습
`Jenkins` `GitHub Webhook` `AWS EC2` `Docker` `Ubuntu`

- GitHub push → Jenkins(Webhook 감지) → AWS EC2 자동 배포 흐름을 직접 구성
- Spring Boot 프로젝트를 Docker 이미지로 빌드해 Docker Hub에 배포, Docker Compose로 컨테이너 실행
- DB 접속 정보를 환경변수(`--env-file`)로 분리해 컨테이너에 주입

<br>

## 📈 지금 공부하고 있는 것
- **📚 북스테이션 — Spring Boot + React 개인 프로젝트 (진행 중)** · [Backend](https://github.com/alpenglow93/BookStation-backend) / [Frontend](https://github.com/alpenglow93/BookStation-frontend)

  처음 접하는 React와 AI API 연동을 학습하며, 사용자 맞춤 추천 기능을 구현하고 있습니다.
