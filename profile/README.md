<div align="center">

# PromptWiki

**5개 질문에 답하면, 바이브 코딩이 시작됩니다**

**[한국어](#한국어) | [English](#english)**

</div>

---

# 한국어

**AI와 함께 제품을 만드는 과정을 기록하고 공유하는 도구**

> "완성된 프롬프트가 아닌, 진화하는 과정을 아카이브합니다"

## PromptWiki란?

PromptWiki는 AI와 대화하며 제품을 개발하는 **전체 과정**을 기록하고 공유하는 CLI 도구입니다.

```
pmpt plan → 5개 질문 답변 → AI 프롬프트 자동 생성 → 클립보드 복사
    ↓
AI와 대화하며 개발
    ↓
pmpt save → 버전 저장
    ↓
pmpt export → zip으로 공유
```

## 왜 PromptWiki인가?

| | |
|---|---|
| **간단한 시작** | 5개 질문만 답하면 AI 프롬프트 자동 생성 |
| **재현 가능** | export/import로 누구나 동일하게 재현 |
| **학습 방식** | "프롬프트 써라" → "이 과정 따라해봐" |

## 사용법

```bash
# 1. CLI 설치 (30초)
npm install -g pmpt-cli

# 2. 프로젝트 시작
pmpt init
pmpt plan          # 5개 질문 → AI 프롬프트 생성

# 3. AI와 작업하며 버전 저장
pmpt save          # 수동 저장
pmpt watch         # 자동 감지

# 4. 히스토리 확인
pmpt history

# 5. 공유하기
pmpt export        # zip으로 내보내기
pmpt import <zip>  # 다른 사람 프로젝트 가져오기
```

## 링크

| | |
|---|---|
| **웹사이트** | [pmptwiki.com](https://pmptwiki.com) |
| **npm** | [pmpt-cli](https://www.npmjs.com/package/pmpt-cli) |

---

# English

**Answer 5 questions. Start vibe coding.**

**A CLI tool to document and share the process of building products with AI**

> "We archive the evolving process, not just the final prompts"

## What is PromptWiki?

PromptWiki is a CLI tool that documents and shares the **entire journey** of developing products through AI conversations.

```
pmpt plan → Answer 5 questions → Auto-generate AI prompt → Copy to clipboard
    ↓
Build with AI
    ↓
pmpt save → Save version
    ↓
pmpt export → Share as zip
```

## Why PromptWiki?

| | |
|---|---|
| **Easy Start** | Answer 5 questions, get AI prompt automatically |
| **Reproducible** | Export/import for exact reproduction |
| **Learning** | "Use this prompt" → "Follow this journey" |

## Usage

```bash
# 1. Install CLI (30 sec)
npm install -g pmpt-cli

# 2. Start project
pmpt init
pmpt plan          # 5 questions → AI prompt

# 3. Save versions while working with AI
pmpt save          # Manual save
pmpt watch         # Auto-detect

# 4. View history
pmpt history

# 5. Share
pmpt export        # Export as zip
pmpt import <zip>  # Import someone's project
```

## Links

| | |
|---|---|
| **Website** | [pmptwiki.com](https://pmptwiki.com) |
| **npm** | [pmpt-cli](https://www.npmjs.com/package/pmpt-cli) |

---

<p align="center">
  <i>The process of building with AI is valuable in itself.</i>
  <br>
  <i>AI와 함께 만드는 과정, 그 자체가 가치입니다.</i>
</p>
