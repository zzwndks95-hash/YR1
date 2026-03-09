# Brainflow — ADHD 투두 & 머니

ADHD 친화적 할 일 관리 + 가계부 + 저축 목표 + 통장 쪼개기 웹앱

## 기능

- **오늘 3개 집중**: 매일 할 일을 3개만 선택해서 집중
- **포모도로 타이머**: 25분 집중 / 5분 휴식 내장
- **가계부**: 수입/지출 원탭 기록, 카테고리별 분석, 도넛 차트
- **고정지출 관리**: 월세, 통신비, 보험 등 한눈에
- **저축 목표**: 목표 금액 설정 + 진행률 시각화
- **통장 쪼개기**: 월급 자동 분배 비율 설계
- **데이터 백업/복원**: JSON 파일로 내보내기/불러오기
- **PWA**: 홈 화면에 추가하면 앱처럼 사용 가능
- **오프라인 지원**: Service Worker로 오프라인에서도 동작

## GitHub Pages 배포 방법

1. GitHub에서 새 저장소(repository)를 만드세요
2. 이 폴더의 모든 파일을 업로드하세요:
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `icon-192.png`
   - `icon-512.png`
3. 저장소 Settings → Pages → Source를 `main` 브랜치로 설정
4. 몇 분 후 `https://[username].github.io/[repo-name]` 에서 접속 가능

## 모바일에서 앱처럼 쓰기

- **iOS**: Safari에서 접속 → 공유 버튼 → "홈 화면에 추가"
- **Android**: Chrome에서 접속 → "홈 화면에 추가" 팝업 클릭

## 기술 스택

- React 18 (CDN)
- Vanilla CSS (커스텀 디자인 시스템)
- localStorage (로컬 데이터 저장)
- Service Worker (오프라인 캐싱)
- PWA (Progressive Web App)
