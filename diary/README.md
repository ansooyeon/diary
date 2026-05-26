# Opencode & Cloud-Based Mood Tracker

## 1. Title & Abstract
* **Project Title:** Opencode 자동화 및 로컬 클라우드 연동형 감정 다이어리 (Mood Tracker)
* **Abstract:** 본 프로젝트는 한밭대학교 컴퓨터융합개론 실습 11주차 OpenCode 에이전트 스킬 규격을 준수하여 제작되었습니다. 사용자가 웹 화면에서 기분 점수와 한 줄 다이어리를 남기면 데이터가 브라우저 스토리지에 안전하게 기록되며, OpenCode 에이전트의 `git-push` 스킬 가이드를 통해 소스코드 보존 및 배포 자동화를 지원하는 가젯 응용 프로그램입니다.

---

## 2. Key Features
* **OpenCode Agent Automation:** `.opencode/skills/git-push/SKILL.md` 가이드에 따라 에이전트 지시 기반의 깃 푸시 자동화를 연동했습니다.
* **직관적인 감정 기록:** 5가지 점수화된 이모티콘을 사용하여 사용자의 일일 피드백을 수집합니다.
* **통계 산출 대시보드:** 저장된 다이어리 로그를 추적하여 실시간으로 전체 평균 기분 점수를 환산해 대시보드에 뿌려줍니다.

---

## 3. Getting Started
아래 지시사항에 따라 별도의 패키지 설치 없이 프로그램을 즉시 실행할 수 있습니다.

### Prerequisites (사전 요구사항)
* 인터넷이 지원되는 환경 및 웹 브라우저 (Chrome, Edge, Safari 등)

### Installation & Setup (설치 및 설정)
1. 해당 저장소를 로컬 컴퓨터로 클론합니다.
   ```bash
   git clone [https://github.com/ansooyeon/diary.git](https://github.com/ansooyeon/diary.git)
   cd diary
```
