# 🐝 Honey Spot - KHU 세모톤 2팀

<img width="5334" height="3000" alt="세모톤 2조 최종 발표-1" src="https://github.com/user-attachments/assets/dbd31dc1-8d2e-484f-ac67-2831ba390445" />

> 여행 중 마주칠 수 있는 위험부터 숨겨진 맛집까지, 지도 위에 핀으로 소통하는 안심 여행 정보 공유 플랫폼입니다.

## 💡 프로젝트 소개
**TravelApp**은 사용자가 직접 지도 위에 핀(Pin)을 꽂아 실시간으로 지역 정보를 공유하는 위치 기반(LBS) 애플리케이션입니다. 
'소매치기 주의 구역'과 같은 위험(DANGER) 정보부터 로컬 맛집(RESTAURANT), 주의(CAUTION) 구역까지 다양한 정보를 한눈에 파악하여 안전하고 즐거운 여행을 돕는 것을 목표로 합니다.

## 🛠️ 기술 스택 (Tech Stack)

### 💻 Backend
* **Framework:** Spring Boot 3.x
* **Language:** Java 17+
* **Database:** Spring Data JPA
* **Security:** Spring Security, JWT Auth
* **Infrastructure:** Oracle Cloud (배포 완료)

### 📱 Frontend
* **Framework:** Flutter
* **Language:** Dart

## 📌 핵심 비즈니스 기능
1. **위치 기반 핀(Pin) 시스템:** 위도와 경도 좌표를 기반으로 특정 위치에 정보 핀을 생성 및 관리합니다.
2. **지도 바운딩 박스(Bounding Box) 탐색:** 사용자의 현재 지도 화면(남서쪽/북동쪽 좌표)을 계산하여, 화면 영역 내에 존재하는 핀만 빠르고 효율적으로 필터링하여 제공합니다.
3. **안전한 인증 인가:** 신뢰할 수 있는 정보 공유를 위해, 인증된 유저만 핀을 등록하고 정보를 수정할 수 있도록 관리합니다.

## 📁 Repositories
* 📱 **[semothon_frontend](https://github.com/KHU-Semothon/semothon_frontend):** 사용자 인터페이스 및 지도 연동을 담당하는 플러터(Flutter) 애플리케이션 저장소입니다.
* ⚙️ **[semothon_backend](https://github.com/KHU-Semothon/semothon_backend):** 핵심 비즈니스 로직과 REST API를 제공하는 백엔드 서버 저장소입니다.
* 📚 **[notion](https://www.notion.so/dangyee/2-32cf2c4ba6ec809e9de9ff8f8c6120d3?source=copy_link)** 기능과 API 명세서, 회의록을 작성했습니다.

## 👨‍💻 팀원 소개 (Team)

| 직무 | 이름 | GitHub | 
| :---: | :---: | :--- | 
| **Frontend** | 이동헌 | [@eseatuna1203](https://github.com/eseatuna1203) | 
| **Frontend** | 박성준 | [@khuseongjun](https://github.com/khuseongjun) | 
| **Frontend** | 김재형 | [@jaehk28-hash](https://github.com/jaehk28-hash) | 
| **Frontend** | 이재민 | [@kummi0709](https://github.com/kummi0709) | 
| **Backend** | 한성희 | [@tjdgml02](https://github.com/tjdgml02) | 

---
*이 프로젝트는 KHU Semothon 기간 동안 기획 및 개발되었습니다.*
