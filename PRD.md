# AI 콘텐츠 프롬프트 자동화 시스템

## 문제
> SNS 바이럴 AI 동영상 필터 프롬프트를 매번 처음부터 수작업으로 만들어 품질이 들쭉날쭉하고, 반복 작업에 시간이 낭비된다.

- **현재 상태**: 프롬프트 1개 제작 시 베이스 작성 + 레퍼런스 5-10개 수동 배열로 20-30분 소요. 매번 품질이 달라져 재작업 발생.
- **원하는 상태**: "어떤 스타일로?" 같은 질문 5개에 답하면 일관된 품질의 프롬프트 파일이 자동 생성된다.
- **성공 기준**: 프롬프트 생성 시간 20분 → 5분 이내 단축 / 동일 스타일 요청 시 품질 편차 없음

## 스킬

| # | 스킬명 | 한 줄 설명 | 상태 |
|---|--------|-----------|------|
| 1 | `my-context-sync` | Slack·Notion·Linear·Google 4개 소스를 병렬 수집 → 하나의 브리핑 문서로 정리 | ✅ 동작 |
| 2 | `my-clarify` | 모호한 콘텐츠/프롬프트 요청을 AskUserQuestion으로 clarify → Before/After 스펙 생성 | ✅ 동작 |

## 변화 기록

- **Day 1**: "Claude Code가 뭔지도 모르겠다" → 7가지 핵심 기능(Memory, Skill, MCP, Subagent, Agent Teams, Hook, Plugin) 체험
- **Day 2**: "MCP가 뭔지 몰랐다" → Connector/mcp add/Plugin/커뮤니티 Plugin 4가지 연결 방법으로 Context Sync 스킬 직접 구축
- **Day 3**: "요구사항이 모호한 채로 작업했다" → Clarify로 Before/After 변환 체험, 나만의 Clarify 스킬 제작
- **가장 크게 달라진 점**: "AI를 쓰는 사람"에서 "AI 워크플로우를 설계하는 사람"으로 관점 전환. 특히 Unknown Unknown 분석에서 미적 감각 + 프롬프트 설계 + AI 바이럴 영상 특화가 희소한 조합임을 발견.

---

*AI Native Camp 2기 — jaylawrtn*
*작성일: 2026-03-23*

---
*Submitted: 2026-03-23*
