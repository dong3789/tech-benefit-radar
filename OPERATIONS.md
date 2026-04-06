# Operations

## Goal
동동에게 AI/클라우드/개발자 혜택, 모집, 굿즈, 크레딧 이벤트를 매일 점검하여 중요한 것만 알린다.

## Runtime model
- 기본 감시는 OpenClaw heartbeat를 사용한다.
- heartbeat가 오면 `HEARTBEAT.md` 기준으로 benefit radar를 점검한다.
- 정책 원문은 이 레포의 `README.md`와 상태 파일(`memory/benefit-radar-state.json`)을 기준으로 판단한다.

## Alert policy
- 같은 프로그램은 기본적으로 반복 알리지 않는다.
- 다만 아래는 재알림 가능:
  - 마감 임박
  - 새 시즌 / 새 혜택 / 새 조건
  - 굿즈 / 크레딧 / 무료 플랜 / 참가 보상이 큼
  - 사용자가 놓쳤을 가능성이 큼

## Status model
- `passedPrograms`: 이번 시즌 기준 패스한 항목
- `seenPrograms`: 이미 본 항목
- `lastCheckedAt`: 마지막 점검 시각

## Current limitation
- heartbeat 기반이라 heartbeat가 와야 점검이 돈다.
- 완전 실시간 푸시 시스템은 아님.

## Recommended next step
- heartbeat 빈도 유지 또는 향후 cron 기반 별도 점검 검토
