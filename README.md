# Candy Pangpang Back - Teacher/Student 페이지 백업

## 🍭 프로젝트 개요
이 저장소는 Candy Shop 교육 플랫폼의 안정적인 Teacher/Student 페이지 소스코드 백업입니다.

## 📁 주요 파일 구조

### 핵심 페이지
- `src/pages/TeacherPage.js` - 교사 인터페이스 (학생 관리, 익명모드, AI 분석)
- `src/pages/StudentPage.js` - 학생 인터페이지 (토큰 시스템, 학습일지, 감정 출석)

### 주요 컴포넌트
- `src/components/StudentCard.js` - 학생 카드 (레벨, 경험치, 프로필)
- `src/components/DataBoardModal.js` - 데이터 전광판 모달
- `src/components/EmotionDashboardModal.js` - 감정 분석 대시보드
- `src/components/LearningJournalModal.js` - 학습일지 모달
- `src/components/EmotionAttendanceModal.js` - 감정 출석 모달
- `src/components/AIAnalysisModal.js` - AI 분석 모달

### 유틸리티
- `src/utils/anonymousMode.js` - 익명모드 (포켓몬 이름 매핑)

### 리소스
- `public/` - 메론 이미지 (melon1.png ~ melon8.png) 및 기타 리소스

## 🎯 주요 기능

### Teacher Page
- 학생 관리 시스템
- 익명모드 (포켓몬 이름)
- AI 분석 기능
- 감정 대시보드
- 데이터 전광판

### Student Page  
- 일일 메시지 토큰 시스템 (10/10)
- 학습일지 작성
- 감정 출석 체크
- 친구 메시지 전송

## 🔧 기술 스택
- React.js
- Firebase (Firestore, Auth)
- Material-UI
- 실시간 데이터 동기화

## 📅 백업 정보
- **백업 일자**: 2025년 9월 27일
- **소스 버전**: 안정적인 롤백 버전 (2025년 9월 23일 기준)
- **Firebase 호스팅**: https://candy-shop-8394b.web.app/

## 🚀 복구 방법
문제 발생 시 이 저장소의 소스코드를 원본 프로젝트에 복사하여 사용하세요.

```bash
# 소스 파일 복구
cp -r src/* /path/to/main/project/src/
cp package.json firebase.json firestore.rules /path/to/main/project/
cp -r public/* /path/to/main/project/public/
```

---
🤖 Generated with [Claude Code](https://claude.ai/code)