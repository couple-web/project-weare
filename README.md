<p align="center">
  <img src="https://user-images.githubusercontent.com/대표이미지링크" width="200px" />
</p>

<h1 align="center">💑 WE ARE - 커플 감성 기록 & 추천 플랫폼</h1>
<p align="center">
  사랑하는 사람과의 순간을 기록하고 공유하는  
  <br />
  감성 기반 맞춤형 커플 웹 애플리케이션
</p>

---

## 🗂️ 저장소 구성

| 구분 | 링크 |
|------|------|
| 📌 소개 리포지토리 | [WE ARE - 소개용](https://github.com/couple-web/couple-web) |
| 💻 프론트엔드 | [프론트 저장소 링크](https://github.com/...) |
| 🔧 백엔드 | [백엔드 저장소 링크](https://github.com/...) |

---

## 📷 서비스 개요

- **개발 기간**: 2025.03.28 ~ 2025.05.09  
- **사용자 대상**: 연인 커플
- **핵심 목적**:
  - 추억 기록 및 공유 기능
  - 데이트 장소 추천
  - 일정 기반 날씨 알림
  - 감성적 UI를 통한 사용자 경험 향상

---

## ✨ 주요 기능

- ✅ 커플 캘린더 (일정 등록, 기념일, 날씨 기반 알림)
- ✅ 데이트 장소 추천 (AI + 지역 필터링 + 지도)
- ✅ 감성 앨범 (사진 기록 기반 UI)
- ✅ 실시간 채팅 (WebSocket)
- ✅ 관리자 통계 대시보드 (유저 수, 인기 장소 등)
- ✅ 공식 기념일 + 사용자 맞춤 알림 기능

---

## 🛠 사용 기술 스택

| 구분 | 기술 |
|------|------|
| **Frontend** | React, Zustand, Styled-components, Axios |
| **Backend** | Spring Boot, JPA, MySQL, JWT, WebSocket, Scheduler |
| **Infra / API** | AWS EC2, Nginx, Jenkins, Kakao Maps API, OpenWeather API, Hugging Face |

---

## 🔌 주요 API 및 활용

- **Google Maps API**: 실시간 지도, 커스텀 마커, 위치 기반 검색
- **OpenWeather API**: 기념일 3일/7일 전 날씨 알람
- **NAVER Search API**: 나이대/성별 선물 추천
- **Hugging Face**: AI 기반 장소 추천

---

## 👨‍👩‍👧‍👦 팀원 소개

| 이름 | 역할 | 주요 담당 |
|------|------|------------|
| **남재우** | 팀장 / 프론트 | 지도 API, 관리자 통계, 인덱스 UI |
| **유서영** | 프론트 | 앨범 구현, DTO 구조 설계, UX 설계 |
| **오정재** | 백엔드 | 기념일, TO-DO, DB 구조, 콘솔 디버깅 |
| **강준우** | 백엔드 | WebSocket 알림, 유저 프로필, UI/UX 디자인 |

---

## 📊 작업 기여 비율

| 항목 | 비율 |
|------|------|
| 리액트 작업 | 35% |
| 백엔드 작업 | 17% |
| 기능 및 주제 기획 | 12% |
| 레퍼런스 조사 | 12% |
| 발표 준비 | 10% |
| 와이어프레임 작성 | 7% |
| ERD 및 DB 설계 | 7% |

---

## 🖼️ 주요 화면

| 인트로 | 장소 추천 | 앨범 | 관리자 통계 |
|--------|-----------|------|--------------|
| ![](https://user-images.githubusercontent.com/인트로이미지링크) | ![](https://user-images.githubusercontent.com/지도링크) | ![](https://user-images.githubusercontent.com/앨범링크) | ![](https://user-images.githubusercontent.com/통계링크) |

---

## 🚀 실행 방법

```bash
# 프론트
npm install
npm start

# 백엔드
./gradlew build
java -jar build/libs/your-app.jar
