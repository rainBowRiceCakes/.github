# 🌈 DGD – RainbowRiceCake Organization

**RainbowRiceCake**는  
사용자 · 파트너(가맹점) · 라이더를 연결하는  
통합 배달/서비스 플랫폼 **DGD**를 개발하는 팀입니다.

React 생태계를 기반으로 한 최신 웹 기술을 활용하여  
역할별로 최적화된 사용자 경험을 제공하는 것을 목표로 합니다.

---

## 🔗 Live Demo

- **DGD Main (User / Partner / Rider)**  
  👉 https://app2.green-meerkat.kro.kr/

- **DGD Admin (관리자 페이지)**  
  👉 https://app3.green-meerkat.kro.kr/

- **DGD 시연영상**  
  👉 https://youtu.be/R-VGD7_iKck/

> 서버는 별도로 구성되어 운영 중이며,  
> 위 링크를 통해 전체 서비스를 실시간으로 확인할 수 있습니다.

---

## 📦 Repositories

| Repository | Description |
|----------|------------|
| **RainbowRiceCake_Main** | 사용자 / 파트너 / 라이더 통합 서비스 (Main Web App) |
| **RainbowRiceCake_Admin** | 관리자 전용 대시보드 |
| **RainbowRiceCake_Server** | 백엔드 서버 |

---

## 🚀 Project Overview

### 👤 User
- 서비스 랜딩 페이지 및 정보 제공
- 지점 찾기 (Kakao Maps API)
- 로그인 / 회원가입 (JWT, 소셜 로그인)
- 마이페이지 및 이용 내역 조회
- FAQ / 공지사항 / 문의

### 🏪 Partner
- 매장 및 메뉴 관리
- 주문 현황 확인
- 매출 및 정산 관리
- 프로모션 관리

### 🛵 Rider
- 배차 및 배달 상태 관리
- 배달 이력 및 정산 내역 조회
- 실시간 위치 기반 서비스 (예정)

### 👨🏻‍💻 Admin
- 전체 서비스 대시보드 (주문 · 매출 통계)
- 회원 관리 (User / Partner / Rider)
- 매장(파트너) 관리
- 주문 상태 관리 및 신규 주문 생성
- 정산 · 송장 관리
- 공지사항 및 Q&A 관리

### ⚙️ Server
- RESTful API 제공
- JWT 기반 인증 / 권한 관리
- 주문 · 사용자 · 파트너 · 라이더 도메인 처리
- 데이터베이스 연동 및 비즈니스 로직 처리

---

## 🛠 Tech Stack

### Frontend
- **React 19**, **Vite**
- Redux Toolkit / Redux Thunk
- React Router DOM v7
- CSS Modules
- Framer Motion
- PWA (vite-plugin-pwa)

### Network & Utilities
- Axios
- Dayjs
- ExcelJS, FileSaver (엑셀 다운로드)

### External APIs
- Kakao Maps API
- Daum Postcode
- Chart.js (react-chartjs-2)

---

## 👥 Team
- 정의욱 ([@uiwook](https://github.com/uiwook)): 팀 총괄, PM, 어드민 페이지 담당
- 정준영 ([@wjdwnsdud95](https://github.com/wjdwnsdud95)): 어드민 대시보드 (Chart.js) 로그인 기능 및 메인 페이지(Carousel) 담당
- 최설아 ([@Sarangheayo](https://github.com/Sarangheayo)): 전체 메인 페이지 담당
- 송보미 ([@itsurfavsong](https://github.com/itsurfavsong)): 기사, 파트너 페이지 담당

---

## 📝 License
This project is licensed under the **MIT License**.
