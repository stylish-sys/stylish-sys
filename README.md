<!-- ============================================================== -->
<!--              stylish-sys · GitHub Profile                     -->
<!-- ============================================================== -->

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=26&duration=2800&pause=900&color=58A6FF&center=true&vCenter=true&multiline=true&repeat=true&width=820&height=110&lines=Sunyong+Lee+%E2%80%94+Build+Anything+with+AI;Backend+%C2%B7+Infra+%C2%B7+SaaS+%C2%B7+Payments+%C2%B7+Automation;%EB%A7%8C%EB%8A%A5%ED%98%95+%EC%97%94%EC%A7%80%EB%8B%88%EC%96%B4+%2B+AI+%EC%98%A4%EC%BC%80%EC%8A%A4%ED%8A%B8%EB%A0%88%EC%9D%B4%ED%84%B0)](https://git.io/typing-svg)

`Feb 2020 ~` · 7년차 · Daejeon, Korea

[![Profile Views](https://komarev.com/ghpvc/?username=stylish-sys&color=58A6FF&style=flat-square&label=VIEWS)]()
[![Followers](https://img.shields.io/github/followers/stylish-sys?style=flat-square&color=58A6FF&labelColor=0d1117)](https://github.com/stylish-sys)

</div>

---

## `> whoami`

```ts
const me = {
  name:  "Sunyong Lee",
  alias: "stylish-sys / slecs / jorney1015",
  base:  "Daejeon, KR",
  role:  "Full-Stack Engineer · Tech Lead · AI Orchestrator",
  range: "PG 결제 서버 ←→ Flutter 앱 ←→ 인프라 자동화 ←→ AI 콘텐츠 파이프라인",
  motto: [
    "혼자서 PG부터 모바일까지 — 한 명이 한 회사를 굴리는 풀스택",
    "AI 와 함께 코딩하는 것이 아니라, AI 를 오케스트레이션해서 시스템을 짓는다",
    "설계 → 개발 → 배포 → 운영 → 자동화 → SaaS 전환까지 손수",
  ],
  current: "결제 시스템 + 멀티테넌트 SaaS + 멀티에이전트 AI 워크플로우 운영",
};
```

> **TL;DR** — 결제 / 커머스 / SaaS / 인프라 / AI 오케스트레이션 / 콘텐츠 자동화.
> **전부 직접 만들고 직접 굴립니다.** 공통점은 하나 — **AI 를 무기처럼 다룬다.**

---

## `> ls ~/in-production/`

> 현재 **실제 운영 중인** 시스템들. 매일 트래픽이 흐르고, 매일 코드를 고친다.

### 💳 Payment & Settlement
| | Project | Stack | What |
|:-:|---|---|---|
| 🔐 | **티켓나라 결제 시스템** | `Spring Boot` `MariaDB` | WAS 이중화 · 가상계좌/카드 결제 · 멀티계층 파트너 수수료 정산 (PENDING → CONFIRMED 홀딩) |
| 🔐 | **pg-solution** | `Spring Boot` `Java` | 자체 PG 게이트웨이 — 결제/송금/입금 감지 API |
| 🔐 | **pay-monitor** | `Android` `Kotlin` | 결제 알림 실시간 캡처 + Webhook 송출 |

### 🏪 Commerce & SaaS
| | Project | Stack | What |
|:-:|---|---|---|
| 🔐 | **온더몰 (Onthemall)** | `Spring Boot` `MyBatis` `MariaDB` | 운영 중 커머스 플랫폼 |
| 🔐 | **slecs (Weaver Kit)** | `Spring Boot` `MyBatis` | 멀티테넌트 SaaS — 한 코드베이스로 N개 쇼핑몰 운영 |
| 🔐 | **slecs_app** | `Flutter` `Dart` | 멀티테넌트 쇼핑몰 모바일 앱 (iOS/Android) |
| 🔐 | **404_pjt** | `Spring Boot` `Thymeleaf` | 운영 통합 백오피스 / 어드민 |

### 🤖 AI-Native Tooling (Open Source)
| | Project | Stack | What |
|:-:|---|---|---|
| 🌐 | **[claude-monitor](https://github.com/stylish-sys/claude-monitor)** | `Node.js` `React` | Claude 멀티 에이전트 실시간 모니터링 대시보드 |
| 🌐 | **oh-my-claudecode (OMC)** | `TypeScript` `Claude SDK` | 자체 운영용 멀티 에이전트 오케스트레이션 레이어 |

### 📺 Content Automation (Built with AI)
| | Project | Stack | What |
|:-:|---|---|---|
| 🔐 | **YouTube Shorts Pipeline** | `Python` `DALL·E` `TTS` `ffmpeg` | 주제 → 스크립트 → 이미지 → TTS → 자막 → 업로드 풀 자동화 |
| 🔐 | **Kling AI Fitness Shorts** | `Python` `Kling API` | text2video 자동 생성 파이프라인 |
| 🔐 | **telegram-news-bot** | `Python` `Telegram API` | 뉴스 큐레이션 자동 송출 봇 |

<sub>🔐 Private · 🌐 Public</sub>

---

## `> cat super-power.md`

```yaml
range:        "PG 백엔드 ←→ 모바일 앱 ←→ 인프라 ←→ AI 파이프라인"
working_mode: "혼자서 한 회사 시스템을 통째로 굴림"
weapon:       "Claude Code + 멀티 에이전트 (OMC) — 1인 = 5인 팀"
specialty:
  - "결제/정산 도메인 깊이 (PG 서버부터 파트너 수수료 정산까지)"
  - "멀티테넌트 SaaS 설계"
  - "AI 워크플로우로 반복 작업을 0 으로 수렴"
  - "레거시 운영 시스템에서도 매일 안정 배포"
philosophy:
  - "테스트 우선, 자동화 우선, 단순함 우선"
  - "붙여놓은 복잡도는 제거 대상이다"
  - "AI 는 도구가 아니라 동료다 — 어떻게 쓰느냐가 곧 실력"
```

---

## `> ls ~/tech-stack/`

<div align="center">

**Backend & Languages**
<br/>
<a href="#"><img src="https://skillicons.dev/icons?i=java,spring,kotlin,python,nodejs,ts,js,dart&theme=dark" /></a>

**Mobile · Frontend**
<br/>
<a href="#"><img src="https://skillicons.dev/icons?i=flutter,react,html,css&theme=dark" /></a>

**Infra · DevOps · DB**
<br/>
<a href="#"><img src="https://skillicons.dev/icons?i=docker,linux,aws,nginx,githubactions,gitlab,mysql,redis,postgres&theme=dark" /></a>

**AI · Automation**
<br/>
<a href="#"><img src="https://skillicons.dev/icons?i=anthropic,openai,bash&theme=dark" /></a>

</div>

<details>
<summary><b>📋 전체 스택 상세 보기</b></summary>
<br/>

```yaml
languages:   [ Java, Kotlin, JavaScript, TypeScript, Python, Dart, C++ ]
backend:     [ Spring Boot 3.x, MyBatis, JPA, eGovFrame, Node.js, Express ]
mobile:      [ Flutter, React Native, Android (Kotlin) ]
frontend:    [ React, Thymeleaf, Vanilla JS ]
devops:      [ Docker, GitHub Actions, GitLab CI, Pulumi, CloudFormation ]
infra:       [ Linux, AWS, Naver Cloud, JEUS, Nginx, ELK ]
databases:   [ MariaDB, MySQL, PostgreSQL, Redis ]
ai:          [ Claude Code, ChatGPT API, DALL·E, Kling AI, Multi-Agent Orchestration ]
automation:  [ ffmpeg pipeline, Telegram bots, YouTube auto-publish, scheduled crons ]
```

</details>

---

## `> git log --graph --since="2020-02"`

```
◉  2026  결제 운영 + 커머스 SaaS + AI 오케스트레이션 풀 파이프라인
│
◉  2025  AI-Augmented Engineering — Claude Code · OMC 자체 멀티 에이전트 프레임워크
│
◉  2024  결제 시스템 깊이 — PG 서버, 가상계좌/카드 정산, 결제 모니터링
│
◉  2023  SaaS 아키텍처 설계 — 멀티테넌트 구조 전환
│
◉  2022  DevOps & 인프라 — Docker, CI/CD, 서버 운영
│
◉  2021  첫 회사 풀입 — 실무 프로젝트 & 팀 리드
│
◉  2020  웹 개발 입문 — Java, Spring, JSP
│
◉  2020.02  개발 시작 — 첫 번째 코드 🚀
```

---

## `> echo $STATS`

<div align="center">

<img width="49%" src="https://github-readme-stats.vercel.app/api?username=stylish-sys&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&bg_color=0d1117&title_color=58A6FF&icon_color=58A6FF&text_color=c9d1d9" />
<img width="49%" src="https://github-readme-streak-stats.herokuapp.com/?user=stylish-sys&theme=tokyonight&hide_border=true&background=0d1117&ring=58A6FF&fire=FF6B6B&currStreakLabel=58A6FF" />

<br/><br/>

<img width="70%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=stylish-sys&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=58A6FF&text_color=c9d1d9&langs_count=8&count_private=true" />

<br/><br/>

[![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=stylish-sys&theme=tokyo-night&hide_border=true&bg_color=0d1117&color=58A6FF&line=58A6FF&point=FF6B6B&area=true&area_color=58A6FF)](https://github.com/ashutosh00710/github-readme-activity-graph)

<br/>

![Snake animation](https://raw.githubusercontent.com/stylish-sys/stylish-sys/output/github-snake-dark.svg)

</div>

---

<div align="center">

**`dev.slecs@gmail.com`** · **[GitHub](https://github.com/stylish-sys)** · **Daejeon, KR**

> _"가장 많은 일을 가장 적은 사람으로. AI 와 함께라면 가능합니다."_

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer&animation=twinkling" width="100%"/>

</div>
