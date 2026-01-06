# Contributing Guide

지금지하철(Subway Now) 프로젝트에 관심을 가져주셔서 감사합니다 🚇  
이 문서는 프로젝트에 기여할 때 지켜야 할 기본적인 약속과 규칙을 설명합니다.

---

## 🧭 기본 원칙

- 모든 변경 사항은 **명확한 목적**을 가져야 합니다.
- 작은 변경이라도 **커밋 단위는 의미 있게** 나눕니다.
- 코드보다 **가독성과 유지보수성**을 우선합니다.
- “지금 이 순간 필요한 지하철 정보”라는 서비스 방향성을 존중합니다.

---

## 🌱 브랜치 전략

- `main`
  - 항상 배포 가능한 상태를 유지합니다.
- 기능/수정 작업은 아래 형식의 브랜치를 사용합니다.

### 형식
- feature/기능명
- fix/버그명
- refactor/대상
- chore/설정

### 예시
- feature/realtime-arrival-api
- fix/duplicate-station-response

---

## 📝 Commit Message Convention

모든 커밋 메시지는 아래 규칙을 따릅니다.

### type 목록
| type | 설명 |
|---|---|
| feat | 새로운 기능 추가 |
| fix | 버그 수정 |
| refactor | 리팩토링 (기능 변경 없음) |
| chore | 빌드, 설정, 의존성 |
| docs | 문서 수정 |
| test | 테스트 추가/수정 |
| style | 포맷, 스타일 변경 |
| config | 환경 설정 변경 |

### 형식
[#][type] 설명

### 예시
- [#][FEAT] 지하철 실시간 도착 정보 조회 API 추가
- [#][FIX] 환승역 도착 정보 중복 표시 오류 수정
- [#][CONFIG] prod 환경 캐시 TTL 조정
