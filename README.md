# 다같이 화하학 시뮬레이션 — 올리는 방법

## 처음 한 번
1. GitHub에서 새 저장소 만들기 (Public, 예: `chem-sims`)
2. 이 폴더 안의 내용물(index.html, sims.json, README.md, assets 폴더)을 Upload files로 올리고 Commit
3. Settings → Pages → Deploy from a branch → main / (root) → Save
4. 1~2분 뒤 `https://chem-pot.github.io/저장소이름/` 에서 확인

## 링크
| 무엇 | 주소 |
|---|---|
| 첫 화면 | `.../저장소이름/` |
| 통합과학 물질과 규칙성 | `.../#/tonghap/1` |
| 화학 3단원 | `.../#/chem/3` |
| 과학의 역사와 문화 (목록) | `.../#/history` |
| 기후변화와 환경생태 (목록) | `.../#/climate` |
| 융합과학 탐구 (목록) | `.../#/fusion` |

## 새 시뮬레이션 추가
1. GitHub에 시뮬레이션 폴더 올리기 — 추천 위치
   - 통합과학·화학: `sims/tonghap/u1/실험이름/index.html`, `sims/chem/u3/실험이름/index.html`
   - 아래 세 과목: `sims/history/실험이름/index.html`
2. 사이트 맨 아래 **관리** → 해당 칸에 `+ 시뮬레이션 추가` → 제목, 경로 입력
3. **sims.json 내려받기** → 저장소 루트에 덮어쓰기 → 1~2분 뒤 반영

- 통합과학·화학: 단원 → 시뮬레이션 2단계, 괄호 숫자는 시뮬레이션 개수
- 아래 회색 세 과목: 단원 없이 시뮬레이션 버튼이 바로 보이고, 누르면 바로 열림
- 다른 곳에 올린 시뮬레이션은 경로 칸에 `https://...` 전체 주소를 넣으면 됩니다.
