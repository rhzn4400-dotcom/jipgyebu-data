# jipgyebu-data

「집계부」 앱이 내려받는 아파트 관리비 데이터 파일을 배포하는 저장소입니다.

- **파일**: [Releases](../../releases) 에 매달 올라갑니다. 앱은 항상 최신 릴리스(`releases/latest/download/manifest.json`)를 받습니다.
  - `manifest.json` — 데이터 버전 · 기준월 · 파일 목록과 SHA-256
  - `shard-index.db.gz` — 전국 단지 목록 (단지 검색용)
  - `shard-01.db.gz` ~ `shard-16.db.gz` — 시도별 관리비 데이터
- **출처**: 국토교통부 공동주택관리정보시스템(K-apt) 공개자료를 가공한 통계입니다. 공공누리 이용조건에 따라 출처를 표시합니다.
- **개인정보처리방침**: https://rhzn4400-dotcom.github.io/jipgyebu-data/

이 저장소에는 이용자 정보가 올라오지 않습니다. 앱은 이 파일들을 내려받기만 하고, 모든 비교 계산은 기기 안에서 합니다.
