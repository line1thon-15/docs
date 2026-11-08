# 1호선톤 15조 — docs

경계선지능 청소년을 위한 AI 생활 판단 연습 서비스의 **팀 공용 문서 저장소**입니다.
프론트·백엔드·AI·디자인이 함께 참조하는 문서만 여기에 둡니다.

## 레포 구성

| 레포 | 내용 |
| --- | --- |
| `frontend` | 웹 화면 (React + Tailwind) |
| `backend` | API 서버 |
| `ai` | LLM 기반 생활 판단 연습·피드백 로직 |
| `docs` | 팀 공용 문서 (여기) |

## 문서

| 문서 | 내용 |
| --- | --- |
| [`conventions/`](./conventions) | 팀 공용 컨벤션 — 브랜치·PR·커밋 |
| [`planning/PRD.md`](./planning/PRD.md) | 기획서 (PRD) — 기능·승인 기준·화면 목록·열린 질문 |
| [`architecture/Architecture.md`](./architecture/Architecture.md) | 아키텍처 — 공개 API(`/api/v1`)·AI 내부 API(`/internal/v1`) 규격, 데이터 모델, 파트별 요청 |

> 기획서·아키텍처는 backend 저장소 `docs/`가 원본이고, 여기에는 사본을 올립니다(각 문서 맨 위에 원본 커밋 표시).

## 문서 배치 규칙

> **여러 역할이 함께 보는 문서만 이 레포에 둡니다. 역할 전용 문서는 해당 역할 레포에 둡니다.**

| 성격 | 위치 |
| --- | --- |
| 팀 공용 (기획·아키텍처·API) | **`docs`** (여기) |
| 프론트/디자인 구현 상세 | `frontend/docs` |
| 백엔드 구현 상세 | `backend/docs` |
| AI 구현 상세 | `ai/docs` |

## 협업

- **브랜치 전략: `main`(최종 데모) / `dev`(통합) / `feature/*`(작업).** PR base는 `dev`입니다.
- 상세 → [`conventions/브랜치-PR-커밋.md`](./conventions/브랜치-PR-커밋.md)
