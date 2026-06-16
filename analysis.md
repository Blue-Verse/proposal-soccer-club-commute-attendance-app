# 축구단 전용 등하원 및 출결 관리 앱/웹 구축 — 제안 분석 로그

> 생성일: 2026-06-16
> 공고 URL: https://www.wishket.com/project/156106/

## 1. 공고 파싱 결과

```yaml
job:
  title: "축구단 전용 등하원 및 출결 관리 앱/웹 구축"
  category: "앱(iOS/Android) + 관리자 웹 + 백엔드 + CRM 연동"
  budget_range: "15,000,000원"
  duration: "60일"
  tech_stack: [React Native, React.js, Node.js, MySQL, Firebase Realtime DB, AWS, FCM]
  description: "학부모/학생/선생님용 등하원·출결 관리 앱 + 관리자 웹. 기존 CRM DB 연동, 백그라운드 GPS 실시간 추적, QR 출결, 멀티테넌트(SaaS 확장형) DB 설계"
  requirements:
    - 기존 CRM DB 연동 API + 3권한(학부모/학생/선생님) 로그인·라우팅
    - Tenant ID 기반 멀티테넌트 DB 설계 (기능 구현은 제외)
    - 백그라운드 GPS 실시간 위치 송신 + 지도 표시 + 운행 기록
    - QR 출석 체크 + 수동 탑승/하차 체크 + FCM 푸시
    - 학부모 커뮤니티(공지/게시판) + 관리자 웹 대시보드/노선·정류장 관리
  client_questions: []
  deadline: "2026-06-23"
  job_post_url: "https://www.wishket.com/project/156106/"
  urls: []
  images: []
```

## 2. URL/이미지 분석

참고 URL/이미지 없음 — 공고 본문에 레퍼런스 사이트, Figma, 이미지 첨부가 포함되지 않음. 클라이언트가 내부 전산팀 작성 스토리보드(요구사항 정의서·화면설계서·IA)를 착수 시 제공 예정.

## 3. 실현 가능성 분석 (내부용)

- 프로젝트 유형: 모바일 앱(RN, 조건부 가능 +20%) + 실시간 GPS 추적(주의 +25%) + 풀스택 + 관리자 웹
- 기획 공수: 제외 (클라이언트 스토리보드 제공)
- 기본 공수(AI 미반영): 디자인 15 + 앱FE 40 + 관리자웹 20 + BE 30 + QA/배포 12 ≈ 117 M/D
- AI 반영(약 50% 절감) + 버퍼: ≈ 70 M/D
- 1인 기준 달력 환산: 70 × 7/5 ≈ 98일 → 클라이언트 예상 60일 초과
- 다수 인력(2~3인) 병행 시: 약 49일 → 60일 내 가능
- 판정: 다수 인력 투입으로 디자인↔개발↔백엔드 병행 시 60일 유지 가능. 가격 경쟁력 위해 금액 85% 적용.

## 4. 포트폴리오 매칭

| 순위 | 프로젝트 | 매칭 근거 | 점수 |
|------|----------|-----------|------|
| 1 | Pilates App (프랜차이즈 통합 관리 앱) | 3종 권한, 출결 관리, CRM, 관리자 웹, React Native, 다지점 확장형(SaaS analog), 3플랫폼 동시 출시 | ★★★★★ |
| 2 | Harmony Link (돌봄시설 통합 관리) | 멀티테넌트 SaaS DB 설계, 보호자(학부모) 실시간 푸시 소통, RBAC 권한, 관리자 웹 | ★★★★★ |
| 3 | Calendar Share (실시간 동기화 소셜 앱) | Firebase Realtime DB 실시간 동기화(위치 추적), QR 스캔, 7종 FCM 푸시 + 딥링크 | ★★★★☆ |

## 5. 최종 제안 요약

- 지원 금액: 12,750,000원 (VAT 별도) — 클라이언트 예상 15,000,000원의 85%
- 지원 기간: 60일 (클라이언트 예상 유지, 다수 인력 병행)
- 핵심 제안 포인트:
  1. 3권한 출결·CRM·운영 앱을 앱+웹 동시 출시한 경험 직접 적용
  2. 백그라운드 실시간 위치·지도 안정 구현 (Firebase Realtime DB)
  3. SaaS 확장형 멀티테넌트 DB(Tenant ID) 설계
  4. QR 출결 + FCM 푸시로 보호자 알림 흐름 완성
  5. 기획 공수 제외, 디자인·개발 중심 효율적 견적

## 6. 최종 산출물

### 제안서 사이트 URL
https://proposal-router.claude-ai-b27.workers.dev/proposal-soccer-club-commute-attendance-app/

### 지원 금액
12,750,000원 (VAT 별도)

### 지원 기간
60일

### 클라이언트 질문 답변
없음 (공고에 클라이언트 질문 없음)

### 지원 내용
안녕하세요, 축구단 전용 등하원 및 출결 관리 앱/웹 구축 프로젝트에 지원합니다.

본 프로젝트에 대한 상세 제안서(견적서, 공수계산서, PRD, 일정, 포트폴리오)를 별도 페이지로 준비하였습니다. 아래 링크에서 확인해 주시면 감사하겠습니다.
▶ 제안서 상세 페이지: https://proposal-router.claude-ai-b27.workers.dev/proposal-soccer-club-commute-attendance-app/
▶ 위시켓 포트폴리오: https://www.wishket.com/partners/p/blueverse1/

---

<프로젝트 진행 제안>

■ 프로젝트 분석
- 학부모·학생·선생님 3권한 전용 등하원·출결 관리 앱 + 관리자 웹 구축
- 기존 자체 제작 CRM DB 연동 및 회원 정보 동기화
- 백그라운드 GPS 실시간 위치 추적 + 지도 표시, 차량 운행 기록
- 차량 내 QR 간편 출석 + 탑승/하차 수동 체크 + 탑승·하차·도착 FCM 푸시
- 추후 SaaS 확장을 고려한 Tenant ID 기반 멀티테넌트 DB 설계
- 클라이언트 제공 스토리보드 기준, 기획 공수 제외 디자인·개발 중심 진행

■ 작업 일정
[Phase 1: 설계 & 디자인] Day 1–14
- 스토리보드 기반 앱·관리자 웹 UI/UX 디자인, 멀티테넌트 DB/ERD 설계, API 명세, CRM 연동 스펙

[Phase 2: 핵심 개발 1] Day 15–35
- CRM 연동·3권한 인증, 백엔드 핵심 API, 백그라운드 GPS 송신, 실시간 지도 표시

[Phase 3: 핵심 개발 2] Day 36–50
- QR 출결·FCM 푸시, 출결 히스토리, 학부모 커뮤니티, 관리자 웹 대시보드·노선/정류장 관리

[Phase 4: QA & 배포] Day 51–60
- 통합 테스트, iOS·Android 백그라운드 GPS 안정화, 보안 점검, 스토어 제출·배포

■ 마일스톤 및 산출물
- M1(Day 14): 디자인 원본·ERD·API 명세 승인
- M2(Day 35): 3권한 로그인·CRM 연동·실시간 지도 동작
- M3(Day 50): QR 출결·FCM 푸시·관리자 웹 기능
- M4(Day 60): QA 통과·배포·산출물 이관(소스코드, 관리자 매뉴얼, DB 설계서)

■ 미팅 시 협의 필요 사항
- 기존 CRM DB 스키마 및 연동 방식(API/직접 접근) 공유
- 지도 SDK 선택(Google Maps 등) 및 외부 API 키 발급
- 앱 스토어 개발자 계정 및 푸시(FCM/APNs) 인증서 준비
- 백그라운드 위치 추적 정책(송신 주기, 배터리 절감 수준) 협의

---

<유사 프로젝트 진행 경험>

▶ 프랜차이즈 통합 관리 앱 (예약·출결·CRM) (4개월)
- 프로젝트 유형: B2B2C 앱 / 출결·CRM·커뮤니티
- 핵심 기능: 회원·강사·관리자 3~4종 권한별 화면, 출결 관리, 예약·결제·CRM·매출 대시보드·커뮤니티·푸시 알림
- 유사점: 학부모·학생·선생님 3권한 구조, 출결 관리, CRM, 관리자 웹, 푸시 알림 직접 대응 + 다지점 확장형 설계
- 기술 스택: React Native, React, Node.js, FCM/APNs

▶ 돌봄시설 통합 관리 플랫폼 (멀티테넌트) (약 6개월)
- 프로젝트 유형: 헬스케어 SaaS / 멀티플랫폼
- 핵심 기능: 멀티테넌트 아키텍처, 보호자 실시간 푸시 소통, 출석·기록 디지털화, RBAC 6역할 보안, 140+ API
- 유사점: SaaS 확장형 멀티테넌트 DB 설계, 보호자(학부모) 실시간 푸시, 권한별 접근 제어, 관리자 웹
- 기술 스택: Flutter, NestJS, Next.js, AWS, Firebase FCM

▶ 실시간 동기화 소셜 앱 (QR·푸시·Firebase RTDB) (모바일 앱)
- 프로젝트 유형: 크로스플랫폼 앱 / 실시간 동기화
- 핵심 기능: Firebase Realtime DB 실시간 동기화, QR 코드 생성/스캔, 7종 FCM 푸시 + 딥링크
- 유사점: 실시간 위치 동기화(Firebase Realtime DB), 차량 내 QR 출결, 탑승·하차·도착 FCM 푸시 흐름
- 기술 스택: Flutter, Firebase RTDB, FCM, QR 스캔

---

<사용 기술과 툴>

▶ 개발 기술
- 앱: React Native (iOS/Android)
- 웹: React.js (관리자)
- 백엔드: Node.js (REST API)
- DB: MySQL + Firebase Realtime DB(실시간 위치)
- 알림: FCM
- 지도: Google Maps / 지도 SDK
- 인프라: AWS

▶ 개발 도구 및 인프라
- 버전 관리: GitHub
- CI/CD: GitHub Actions
- 클라우드: AWS
- 컨테이너: Docker

▶ 커뮤니케이션
- 일일 진행 공유: Slack 또는 카카오톡
- 주간 미팅: Zoom / Google Meet
- 문서 공유: Notion 또는 Google Docs
- 이슈 트래킹: GitHub Issues

### 관련 포트폴리오 추천
1. 프랜차이즈 통합 관리 앱 — 3권한·출결·CRM·관리자 웹·React Native·다지점 확장
2. 돌봄시설 통합 관리 플랫폼 — 멀티테넌트 SaaS DB·보호자 실시간 푸시·RBAC
3. 실시간 동기화 소셜 앱 — Firebase RTDB 실시간 동기화·QR·FCM 푸시
