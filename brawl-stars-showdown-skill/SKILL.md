---
name: brawl-stars-showdown
description: 브롤스타즈 게임에서 쇼다운 모드를 자동으로 플레이합니다. 현금 결제 없이 무료 플레이만 진행합니다.
metadata:
  homepage: https://github.com/mkseo1012-pixel/mkseo/tree/main/brawl-stars-showdown-skill
---

# 브롤스타즈 쇼다운 자동 플레이 AI

## 🎮 기능 설명

이 스킬은 브롤스타즈(Brawl Stars) 게임에서 **쇼다운(Showdown) 모드**를 자동으로 플레이합니다.

### 핵심 기능
- ✅ 브롤스타즈 앱 자동 실행
- ✅ 무료 쇼다운 모드 자동 선택
- ✅ 현금 결제 완전 우회
- ✅ AI 기반 자동 플레이
- ✅ 스마트 이동 및 전투 시스템
- ✅ 플레이 결과 리포트 생성

---

## 📊 지원하는 액션(Action)

### 1. 게임 실행 및 모드 선택

Call the `run_js` tool with:
- script name: index.html
- data: {"action": "launch_game"}

### 2. 완전 자동 플레이

Call the `run_js` tool with:
- script name: index.html
- data: {"action": "auto_play", "difficulty": "normal", "duration": 180, "strategy": "aggressive"}

### 3. 게임 상태 모니터링

Call the `run_js` tool with:
- script name: index.html
- data: {"action": "check_status"}

### 4. 플레이 결과 리포트

Call the `run_js` tool with:
- script name: index.html
- data: {"action": "get_report"}

### 5. 다중 세션 플레이

Call the `run_js` tool with:
- script name: index.html
- data: {"action": "multi_play", "sessions": 5, "strategy": "balanced"}

---

## 🎯 사용 예시

- "브롤스타즈를 실행하고 쇼다운을 플레이해줘"
- "자동으로 5게임 연속 플레이해줘"
- "어려운 난이도로 게임을 진행해줘"
- "현재 게임 상태를 확인해줘"
- "게임 결과 리포트를 보여줘"
- "공격적인 전략으로 게임해줘"