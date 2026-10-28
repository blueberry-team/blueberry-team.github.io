# 블루베리팀 법적 고지

블루베리팀 앱의 개인정보처리방침, 이용약관, 계정 삭제 안내 모음.

- 사이트: https://blueberry-team.github.io/
- 배포: `main` 브랜치에 머지하면 GitHub Pages로 자동 배포. 반영까지 1~2분 소요
- 빌드 과정 없음. HTML 파일을 직접 수정

## 파일 위치

앱마다 폴더 하나. 주소는 `https://blueberry-team.github.io/<폴더>/<파일>` 형식.

| 파일 | 내용 |
|---|---|
| `privacy-policy.html` | 개인정보처리방침 |
| `terms.html` | 이용약관 |
| `delete-account.html` | 계정 삭제 안내 |
| `refund.html` | 환불 정책 |
| `support.html` | 고객 지원 |
| `licenses.html` | 오픈 소스 라이선스 |
| `index.html` | 앱 첫 화면 |

루트 `index.html`은 전체 앱 목록 페이지.

| 폴더 | 앱 |
|---|---|
| `beforebed` | 한판만 네크로맨서 |
| `foodimo` | 푸디모 |
| `greedytd` | 탐욕의 타워디펜스 |
| `lingding` | 링딩 |
| `pomomine` | 폰 대신 곡괭이 |
| `seedday` | 씨드데이 |
| `snug` | Snug : Study Room |
| `soweird` | DrawEng |
| `thick` | 한 획 캐치마인드 |
| `umaso` | 우마소 |

## 수정 방법

GitHub 웹에서 수정 가능. 개발 도구 설치 불필요.

1. 수정할 파일 열기. 예: `umaso/privacy-policy.html`
2. 오른쪽 위 연필 아이콘으로 편집
3. **Commit changes**에서 **Create a new branch for this commit and start a pull request** 선택
4. PR 생성 후 검토를 받아 머지
5. 1~2분 뒤 사이트에서 반영 여부 확인

- `main` 브랜치에 직접 커밋하지 않음
- 수정 권한은 `blueberry-team` 조직 멤버 중 저장소 쓰기 권한이 있는 사람에게만 있음
- 참고: [GitHub에서 파일 편집하기](https://docs.github.com/ko/repositories/working-with-files/managing-files/editing-files)

## 주의 사항

- 폴더 이름과 파일 이름 변경 금지. 스토어와 앱에 등록된 주소가 깨짐
- 저장소 이름 변경 금지. `blueberry-team.github.io`가 아니면 조직 사이트 주소로 배포되지 않음
- 새 앱 추가 시 폴더를 만들고 루트 `index.html` 목록에 링크 추가
