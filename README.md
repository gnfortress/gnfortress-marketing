# gnfortress-marketing

> **gnFortress** (by 가디언넷 / Guardiannet) 의 마케팅·세일즈 자산 저장소.

한국 ISMS-P 중심의 클라우드 보안 플랫폼 **gnFortress** 의 GTM(Go-To-Market) 자료를 관리합니다.

## ⚠️ 기밀 — Private 유지 필수
이 저장소에는 **경쟁 전략·가격 가설** 등 대외비 자료가 포함됩니다.
**절대 Public 으로 전환하지 마세요.** 접근은 내부 마케팅·영업 인원으로 제한합니다.

## 📂 구성

### 랜딩페이지 (배포 대상)
| 경로 | 내용 |
|---|---|
| `public/index.html` | gnFortress 랜딩페이지 (셀프서비스 + 도입 상담). **Firebase Hosting 배포 대상** |
| `firebase.json` · `.firebaserc` | Firebase Hosting 설정 (`public/` 만 배포, `*.md` 제외) |

> "무료로 시작"은 제품 가입(`http://192.168.2.132/login`)으로, HostIPS·관제는 상담 폼(mailto)으로 연결됩니다.

### 전략 문서 (내부 전용 · 미배포)
| 파일 | 내용 | 분류 |
|---|---|---|
| `whitepaper_isms_p_outline.md` | 「클라우드 ISMS-P 인증 완벽 대비 가이드」 백서 목차 | 내부 |
| `battlecard_competitive.md` | 경쟁사 배틀카드 (Wiz/국내대형/수동점검/AWS네이티브) | 🔒 대외비 |
| `pricing_packaging.md` | 가격·패키징 설계 (Free/Starter/Pro/Enterprise) | 🔒 대외비 |
| `entitlements_design.md` | 티어별 실행 한도 설계 | 🔒 대외비 |
| `onboarding_flow_design.md` | 신청→승인→온보딩 플로우 설계 | 내부 |

## 🧭 브랜드 체계
- **플랫폼**: gnFortress (CNAPP) — "클라우드 보안의 삼중 방패"
- **Posture** (CSPM, 셀프) · **Workload / HostIPS** (CWPP, 상담) · **관제** (XDR, 상담)
- 회사: 가디언넷(Guardiannet) — 국내 금융권 1위 클라우드 보안

## 🔗 깔때기(Funnel)
백서(인지) → 랜딩(전환) → 배틀카드(영업) → 가격(수익화) → CWPP 업셀(확장)
- 점검(Posture) = 셀프서비스 즉시 가입
- 방어(HostIPS) · 관제(XDR) = 도입 상담 (전문가 설치)
