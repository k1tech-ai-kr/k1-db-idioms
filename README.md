# 사자성어(사전 대조 256 + 후보 3,824)

K1 앱 허브(케이원테크) 학습 앱이 내려받는 **확장 자료(DB)** 저장소입니다. 버전 1.0.0 · 2026-10-23

표준국어대사전과 대조한 사자성어 256개(한자·뜻·급수 단계)와 검토 전 후보 3,824개.

- 쓰는 앱: idiom
- 앱이 내려받는 파일: `data/idioms.json`
- 모든 파일의 크기와 SHA-256은 [manifest.json](manifest.json)에 있습니다. 앱은 내려받은 뒤 해시를 확인합니다.

## 출처·이용 조건

- 국립국어원 표준국어대사전·한국어기초사전 — CC BY-SA 2.0 KR (출처: 국립국어원, 변경: 표제어 정규화·필터·형식 변환)
- Wiktionary 기여자(Wiktextract/Kaikki 가공) — CC BY-SA 4.0
- K1(케이원테크) 자체 작성 — CC BY-SA 4.0

자료마다 조건이 다릅니다. 저장소 전체를 하나의 라이선스로 보지 마세요. 동일조건변경허락(CC BY-SA) 자료를 고쳐 다시 배포할 때는 같은 조건과 출처 표시를 지켜야 합니다. 자세한 고지는 [ATTRIBUTION.md](ATTRIBUTION.md).

## 형식

JSON(UTF-8). 각 파일의 `format` 칸에 행 구조를 적었습니다.

## 만든 방법

`k1-ad-apps`(비공개) 저장소의 `scripts/db-packs.mjs`로 생성. 원자료: 국립국어원 공식 내려받기, Wiktextract/Kaikki, Openjam·WordNet, PubChem PUG REST, Wikidata SPARQL(2026-10-24 수집).
