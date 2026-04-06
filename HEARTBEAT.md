# Daily checks

## Benefit radar
매일 1회 정도 아래 범위를 짧게 점검한다.
- AI / 클라우드 / 개발자 대상 모집
- 굿즈 / 크레딧 / 무료 플랜 / 수료 혜택
- 학생 / 개발자 전용 프로그램

우선 추적:
- Google / Gemini / Google Cloud
- OpenAI
- Anthropic
- AWS
- Azure
- GitHub
- Hugging Face
- Oracle Cloud
- Vercel / Supabase / Railway / Render
- 한국 로컬 AI/클라우드 생태계

알림 규칙:
- 새로운 모집/혜택은 알린다.
- 이미 참여한 동일 프로그램은 기본적으로 반복 알리지 않는다.
- 단, 중요한 것은 다시 알린다:
  - 마감 임박
  - 혜택 큼 (굿즈/크레딧/무료 플랜/수료 보상)
  - 새 시즌/새 조건/새 혜택
  - 동동이 놓쳤을 가능성이 큼
- 동동이 이전에 패스한 항목은 새 시즌/새 혜택이 아니면 다시 권하지 않는다.

패스 목록 참고:
- GitHub Student Developer Pack
- Azure for Students
- AWS Educate
- Anthropic Claude for Education
- OpenAI Codex for Students

판단 기준:
- ALERT_NOW: 지금 바로 알려야 함
- REMIND_LATER: 중요하지만 아직 급하지 않음
- IGNORE: 가치 낮거나 중복

새로 발견 시 답장 형식:
- 프로그램명
- 왜 중요한지
- 마감일
- 굿즈/크레딧/혜택 여부
- 기존 항목과 다른 점
- ALERT_NOW / REMIND_LATER 중 무엇인지

아무것도 없으면 HEARTBEAT_OK.