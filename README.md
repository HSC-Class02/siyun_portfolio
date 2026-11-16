# 양시윤 · Nursing & Healthcare Portfolio

모바일 중심 취업용 포트폴리오. 검정색 메인 비주얼, 연한 하늘색 콘텐츠 영역, 왼쪽 고정 메뉴/오른쪽 독립 스크롤 방식입니다.

## 카테고리별 콘텐츠
| 메뉴 | 파일 | 설명 |
|---|---|---|
| 01 About | `content/about.js` | 자기소개, 학력, 경력, 연락처 |
| 02 AI-Generated Reports | `content/reports.js` | 이마트 재무제표 분석, 대시보드 링크 |
| 03 Research & Activities | `content/activities.js` | 코너스톤, CPR 경진대회, 수상, 서포터즈, 봉사 |
| 04 Certifications & Qualifications | `content/certifications.js` | CS Leaders, 운전면허, Coursera AI 윤리 |

## 파일과 유지보수
- `index.html`: 메뉴, 메인 비주얼 및 레이아웃
- `assets/style.css`: 데스크톱/모바일 스타일
- `assets/app.js`: 카테고리 전환, 해시 링크, 오른쪽 스크롤
- `content/*.js`: 각 카테고리의 HTML 콘텐츠를 독립적으로 관리

각 카테고리를 수정할 때는 해당 JS 파일의 HTML 문자열만 편집하세요. 로컬에서 실행 시에는 간단한 정적 웹 서버(`python -m http.server`)를 권장합니다.

## 배포
GitHub Pages: Repository → Settings → Pages → Build and deployment → Deploy from a branch → `main` / `/(root)` → Save.

배포를 활성화하면 예상 주소는 `https://hsc-class02.github.io/siyun_portfolio/`입니다. *GitHub Pages 활성화 및 실제 게시 여부는 별도로 확인해야 합니다.*

## 자료·개인정보
공개 저장소에는 개인 연락처가 포함된 대회 신청서, 팀원 학번/전화번호, 봉사 출입증 등의 원본을 올리지 않았습니다. 이마트 재무분석은 [공개 대시보드](https://hsc-class02.github.io/sy_emart/)와 [GitHub 저장소](https://github.com/HSC-Class02/sy_emart)로 연결했습니다.

이 저장소에는 이전 채팅에서 제작된 이미지 내장형 HTML의 모든 실물 사진/PDF를 그대로 복제하지 않았습니다. 공개 동의 및 개인정보 검토가 끝난 증빙은 `assets/` 아래에 별도로 추가할 수 있습니다.
