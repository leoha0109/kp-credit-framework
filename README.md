# Korean Paper · 신용 분석 프레임워크 (v3.6)

**2026년 6월 ‧ 하나증권 글로벌 자산 리서치 (Hana Securities · Global Asset Research)**

KP (Korean Paper) 시장 신용 분석을 위한 ★ 통합 working surface — ★ 7개 산업 라이브러리 + 28개 발행자 데이터베이스 + 3-시나리오 stress test + 8-case backtest + Quarterly Review 자동화 + KP 월간 리포트 운영 매뉴얼 ★ 단일 dashboard 통합.

## Live Dashboard

★ **https://leoha0109.github.io/kp-credit-framework/**

대시보드는 ★ 7개 tab으로 구성: ★ 개요 · v3.6 매트릭스 · 산업 라이브러리 · 발행자 28 · 시나리오 · Backtest · 작업 흐름.

---

## Framework 신뢰도 — 4차원 정량 입증

| 차원 | 측정값 | 근거 |
|---|---|---|
| **Backward-looking 정확도** | **90.1%** | Stage 6 backtest 8 case 평균 |
| **Self-consistency 정합성** | **97.2%** | Quick Win 1 — Stage 3 ↔ Stage 5 cross-check |
| **평균 Lead time** | **10.1 개월** | Framework 사전 감지 가능 평균 |
| **Gap closure** | **3 / 5** | 5개 잔여 gap 중 3개 ★ 구조적 보완 완료 |

---

## 7개 산업 라이브러리

1. **금융** (3-A) — KDB · KEXIM · 시중은행 · 금융지주 (★ KP 시장 비중 25-30%)
2. **전력·가스 GRE** (3-B) — KEPCO · KOGAS · KHNP · LH · 도로공사 (★ Sov 동조 100%)
3. **석유화학** (3-C) — LG Chem · LGES · 롯데화학 · SK Innovation (★ Backtest 90% / Lead 6.5개월)
4. **자동차** (3-D) — Hyundai Motor · Kia · Mobis · Glovis (★ Backtest 85%)
5. **반도체** (3-E) — Samsung Electronics · SK Hynix (★ Backtest 88.5% / Lead 13개월)
6. **철강** (3-F) — POSCO Holdings · 본체 · International · 현대제철 (★ **Backtest 98%** / Lead 15개월)
7. **건설** (3-G, v3.4 신규) — POSCO E&C 등 11개 발행자 (★ honest framework — 글로벌 등급 부재)

---

## 향후 6-12개월 ★ 핵심 Catalyst 2개

| Catalyst | 발행자 | 시점 | 확률 |
|---|---|---|---|
| **Moody's Stable revision** | Samsung Electronics | 2026.06-12 | **50%** |
| **Moody's 동조 강등** (Baa1→Baa2) | POSCO Holdings + 본체 | 2026 Q3-Q4 | **65%** |

★ 양 catalyst는 ★ 5-페르소나 시뮬레이션으로 ★ 사전 모델링 완료.

---

## Framework 진화

| 버전 | 일자 | 핵심 추가 |
|---|---|---|
| v3.2 | 2026.05.29 | 외부지원 매트릭스 6단계 진화 base |
| v3.3 | 2026.06.01 | Stage 5-6 + Cross-industry + Quick Win 1 통합 |
| v3.4 | 2026.06.01 | Stage 3-G 건설 + POSCO Group 4사 trajectory |
| v3.5 | 2026.06.01 | 옵션 X — KP 월간 리포트 템플릿 + 운영 매뉴얼 |
| **v3.6** | **2026.06.02** | **Gap Closure — Stage 6 8 case + Stage 7 자동화 + Stage 3-G v2** |

★ 모든 버전은 ★ **Single source of truth** 원칙 — 이전 내용 ★ 완전 보존 + 신규 섹션 append.

---

## Source

본 dashboard는 ★ 53개 산출물 + 약 33,984줄 분석 결과의 ★ 종합 시각화:
- 40개 markdown 문서 (Stage 1-6 + Quick Win 1-2 + 옵션 X + Gap Closure)
- 12개 Python 모듈 (Stage 4 코드 + Stage 5 시뮬레이터 + Stage 6 backtest + Stage 7 자동화)
- 1개 HTML dashboard (★ 본 사이트)

---

## 활용 시나리오

1. **★ 일상 모니터링** — Tab IV (28 발행자 DB) + Tab V (시나리오 확률) 매일 점검
2. **★ KP 월간 리포트 작성** — Tab VII (작업 흐름)의 12개월 캘린더 + 4-step paragraph flow + Topic × 페르소나 매트릭스 직접 참조
3. **★ Semi-annual Forum** — Tab VII §VII-E의 12-slide PPT 양식 직접 활용
4. **★ Quarterly Review** (★ 3/6/9/12월) — Tab VII §VII-D의 5-step Checklist + Stage 7 자동화 module
5. **★ Stakeholder 설명** — Tab I (개요) 6 stat cards + Matrix evolution table

---

## 변경 이력 + 갱신

★ 본 framework은 ★ 매분기말 (3/6/9/12월) ★ Quarterly Review를 통해 ★ 점진 갱신.
★ 등급 변동 + 시나리오 확률 + Framework gap ★ 모두 추적.

---

*Compiled · June 2026 ‧ For analytical use*
