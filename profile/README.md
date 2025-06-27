# 🔐 세종대학교 SSG 보안 동아리 아카이브 웹사이트

> **SSG(Security Study Group)**는 세종대학교 정보보안 연구 동아리입니다.  
> 저희는 보안 지식을 정리하고 공유하기 위한 **아카이브 웹사이트**를 운영하고 있으며,  
> 웹 시스템은 **마이크로서비스 아키텍처(MSA)** 기반으로 구성되어 있습니다.

---

##  목차

1. [프로젝트 개요](#프로젝트-개요)  
2. [아키텍처 개요](#아키텍처-개요)  
3. [주요 기능](#주요-기능)  
4. [팀원 소개](#팀원-소개)  
5. [사이트 주소](#사이트-주소)  
6. [테스트 및 배포](#테스트-및-배포)  
7. [참고 자료](#참고-자료)  

---

##  프로젝트 개요

| 항목 | 내용 |
|------|------|
| 프로젝트명 | SSG Archive |
| 주관 | 세종대학교 정보보안 동아리 SSG |
| 목표 | 보안 학습자료, 회고, 스터디 기록 등을 정리한 오픈 아카이브 구축 |
| 기술스택 | Java, Spring Boot Cloud, Redis, Kafka, Docker, React, Nginx 등 |
| 아키텍처 | 마이크로서비스 아키텍처 (MSA) 기반 분산 시스템 구성 |

---

##  아키텍처 개요

> 저희는 기능별로 분리된 독립적인 서비스를 운영하고 있으며,  
> API Gateway와 서비스 레지스트리(Eureka)를 포함해 **MSA 기반 구조**를 사용합니다.


- 각 서비스는 독립적으로 배포 및 확장 가능  
- Kafka 기반 이벤트 브로커 연동  
- Redis로 인증 캐싱 처리

---

##  주요 기능

---

##  팀원 소개

| 역할 | 프로필 | 이름 | 담당 |
|------|--------|------|------|
| 팀원 | <img src="https://github.com/Sigmaith.png" width="80" /> | [정수미](https://github.com/Sigmaith) | 백엔드 |
| 팀원 | <img src="https://github.com/PlusUltraCode.png" width="80" /> | [이동호](https://github.com/PlusUltraCode) | 백엔드 |
| 팀원 | <img src="https://avatars.githubusercontent.com/u/101076058?v=4" width="80" /> | [이해건](https://github.com/SISUinSea) | 백엔드 |
| 팀원 | <img src="https://avatars.githubusercontent.com/u/121525026?v=4" width="80" /> | [최하은](https://github.com/haeun320) | 프론트엔드 |
| 팀원 | <img src="https://avatars.githubusercontent.com/u/77979028?v=4" width="80" /> | [김법균](https://github.com/bk-git-hub) | 프론트엔드 |


---

##  사이트 주소

 공식 배포 주소: 
 테스트 주소:

---

##  테스트 및 배포

- GitHub Actions 기반 CI/CD 자동화
- 테스트 환경: Docker Compose 기반 내부 배포
- 운영 환경: Nginx + Docker Swarm 기반 분산 배포

---

##  참고 자료

- [보안 스터디 아카이브 Notion]
- [SSG 동아리 소개 페이지]

---

 문의: 
