# PromptWiki

**AI와 함께 제품을 만드는 과정을 기록하고 공유하는 플랫폼**

> "완성된 프롬프트가 아닌, 진화하는 과정을 아카이브합니다"

---

## PromptWiki란?

PromptWiki는 AI와 대화하며 제품을 개발하는 **전체 과정**을 Markdown으로 기록하고 공유하는 플랫폼입니다.

```
v1: 아이디어 스케치
    ↓
v2: 기능 목록 정의
    ↓
v3: 기술 아키텍처
    ↓
v4: 구현 시작
    ↓
...
```

단순한 프롬프트 팁이 아닌, **아이디어부터 완성까지의 여정**을 버전별로 추적합니다.

---

## 왜 PromptWiki인가?

### 1. 재현 가능한 개발 과정
각 버전에 **Checkpoint**와 **Git 커밋 해시**가 기록되어, 누구나 동일한 단계를 밟아 결과를 재현할 수 있습니다.

### 2. AI 시대의 새로운 학습 방식
"이 프롬프트를 써라"가 아닌 "이렇게 진화시켜라"를 배웁니다.
- 왜 이 방향으로 갔는지
- 어떤 피드백을 반영했는지
- 어떤 시행착오가 있었는지

### 3. 검증 가능한 결과물
각 단계마다 **체크포인트 기준**이 있어, 자신의 결과물이 올바른지 검증할 수 있습니다.

---

## 시작하기

### CLI 설치
```bash
npm install -g @promptwiki/cli
```

### 프로젝트 초기화
```bash
# 현재 폴더에서 시작
promptwiki init

# Git 저장소 연동 (커밋 해시 자동 기록)
promptwiki init --repo https://github.com/your/repo
```

### 변경 추적
```bash
# 파일 변경 자동 감지 및 버전 저장
promptwiki watch

# 저장된 히스토리 확인
promptwiki history
```

---

## 기여하기

### 프로젝트 제출
AI와 함께 만든 프로젝트가 있다면 공유해주세요!

1. [content](https://github.com/promptwiki/content) 레포를 Fork
2. `projects/your-project/` 폴더 생성
3. 버전 파일들 추가 (`v001.md`, `v002.md`, ...)
4. Pull Request 제출

### 기여 가이드라인
- 각 버전에 **왜** 그렇게 했는지 설명 포함
- 가능하면 Checkpoint 기준 추가
- 사용한 AI 모델 명시

---

## 프로젝트 예시

| 프로젝트 | 설명 | 버전 |
|---------|------|------|
| [고객 관리 SaaS](https://pmptwiki.com/ko/projects/sample-saas) | 아이디어부터 MVP까지 | 3 versions |

---

## 링크

- **웹사이트**: [pmptwiki.com](https://pmptwiki.com)
- **콘텐츠 기여**: [promptwiki/content](https://github.com/promptwiki/content)

---

<p align="center">
  <i>AI와 함께 만드는 과정, 그 자체가 가치입니다.</i>
</p>
