# 직종별 설문 게이트웨이

- 게이트웨이: `https://계정명.github.io/저장소명/`
- 관리자: `https://계정명.github.io/저장소명/admin.html`
- 데이터: `data/surveys.json` (관리자 페이지에서 수정)

## 처음 설정
1. 이 폴더의 파일을 저장소에 올립니다 (`data` 폴더 구조 유지).
2. Settings → Pages → Branch: `main`, 폴더 `/(root)` → Save
3. 토큰 발급: Settings(개인) → Developer settings → Fine-grained tokens
   - Repository access: 이 저장소만 선택
   - Permissions → Contents: Read and write
4. admin.html에서 토큰 입력 → 불러오기 → 수정 → 저장

## 주의
- 토큰을 파일·저장소·메신저에 남기지 마세요.
- surveys.json 내용(직종명·링크)은 누구나 볼 수 있습니다.
- 저장 후 반영까지 보통 1~2분 걸립니다.
