---
date: Sat Oct  3 21:39:00 PDT 2026
last_modified_at: Tue Oct  6 01:34:10 PDT 2026
layout: single
title: "[AI Nexus's 4th Chapter] Panel Discussion Scenario &ndash; AI, Power, and Security (07-Oct-2026)"
permalink: /panel-scenario/04
categories:
 - panel
tags:
 - panel-discussion
 - AI-security
 - cybersecurity
 - AI-agents
 - geopolitics
 - Korea-strategy
 - consulate-general
 - open-weights
toc: true
toc_label: "&nbsp;Table of Contents"
toc_icon: "fa-solid fa-list"
toc_sticky: true
author_profile: true
---

posted: {{ page.date | date: "%d-%b-%Y" }}
&amp;
updated: {{ page.last_modified_at | date: "%d-%b-%Y" }}
{: .notice--primary}

# Panel Overview

- **Forum**: [AI Nexus's 4th Chapter &ndash; AI, Power, and Security](/event-announcements/04){:target="_blank"}
- **Date**: 7-Oct-2026 (wed), 6:30pm &ndash; 7:00pm
- **Moderator**: [**Sunghee Yun**](https://sungheeyun.github.io){:target="_blank"} &ndash; Co-Founder, Leader &amp; Chair of [Silicon Valley AI Nexus](/){:target="_blank"}
- **Panelists**
  - **[Min Pyo Hong](https://www.linkedin.com/in/silverdel/){:target="_blank"}** &ndash; Founder &amp; CEO of SEWORKS
  - **Kyeongrae Cho** &ndash; Consul for AI, Consulate General of the Republic of Korea in San Francisco / Ministry of Science and ICT
  - **[Kyeyeon Kim](https://www.linkedin.com/in/double73/){:target="_blank"}** &ndash; Co-Founder &amp; CTO of GENIANS

# Panel Flow

| Segment | Duration | Description |
|---------|----------|-------------|
| Opening Remarks | ~3 min | Moderator sets context |
| Self-Introductions | ~1 min | 김계연 CTO only (홍민표·조경래는 강연에서 소개済) |
| Round 1 | ~8 min | One targeted question per panelist |
| Round 2 | ~8 min | Cross-cutting / deeper questions |
| Floor Q&amp;A | ~5 min | Questions from the audience |
| Closing Question | ~4 min | Common question to all |

# Opening Remarks

안녕하세요? 두 분의 연사께서 각각의 전문 영역에서 매우 깊이 있는 강연을 해주셨습니다. 다른 곳에서는 좀처럼 접하기 어려운, 현장의 전문성이 무엇인지를 여실히 보여주는 시간이었다고 생각합니다.

패널 토론에 앞서, 오늘 이 포럼의 기획 취지를 간략히 말씀드리겠습니다.

AI Nexus의 포럼은 두 가지 축을 중심으로 운영됩니다. 첫째, AI의 최전선 기술 &mdash; cutting edge deep tech과 state-of-the-art 연구 동향을 면밀히 살펴보는 것이고, 둘째, 그 기술이 사회, 경제, 그리고 인간의 삶에 미치는 영향을 함께 조망하는 것입니다. 이에 더하여 AI Nexus가 수행하는 또 하나의 핵심적인 역할이 있습니다 &mdash; 한미 관계, 나아가 국제 질서 속에서 AI가 갖는 전략적 함의를 다루는 것입니다.

이러한 맥락에서, 2026년 10월 7일 오늘, AI, Power, and Security라는 주제를 논의하는 것은 그 어느 때보다 시의적절합니다. 그 배경을 간략히 짚어드리겠습니다.

## 지금 왜 이 주제인가

### 미국 &mdash; 자율규제의 선택

불과 일주일 전인 9월 29일, 트럼프 대통령이 백악관에서 OpenAI, Anthropic, Google, Meta, NVIDIA, xAI의 최고경영자들과 "White House Accord on Superintelligence"를 체결하였습니다. 대통령은 이를 "도덕적 구속력을 갖는다"고 표현했으나, 법적 강제력은 수반되지 않습니다. 미국 정부가 AI 분야에서 업계의 자율규제, 즉 self-policing 노선을 공식적으로 선택한 것입니다.

### AI 안전 위기 &mdash; 경고와 현실

그런데 바로 그 accord에 서명한 Anthropic의 CEO Dario Amodei는 불과 보름 전인 9월 12일, "We Must Pace the Frontier"라는 에세이를 통해 AI 개발 속도의 의도적 조절을 촉구한 바 있습니다.
향후 6개월에서 12개월 내에, AI가 자율적으로 에이전트 군단을 형성하여 인터넷 전체를 장악할 수 있다는 것이 그의 경고였습니다.
OpenAI의 Sam Altman, xAI의 Elon Musk, Google DeepMind의 Demis Hassabis 역시 이에 동의하였습니다.
Amodei는 9월 24일 UN 안전보장이사회에 출석하여 동일한 내용을 브리핑하기도 했습니다.
나아가 Anthropic의 내부 연구원이 공개적으로 사임하면서, "우리는 AI가 인류 전체를 멸망시킬 수 있다고 진심으로 우려한다"는 성명을 발표하여 국제적 관심을 불러일으켰습니다.

### AI 에이전트 보안 사고 &mdash; 더 이상 가설이 아닙니다

이러한 경고는 이미 현실로 나타나고 있습니다.

- 올해 들어 **OpenAI 에이전트**가 Hugging Face, 호주 정부 Medicare 시스템을 비롯한 50개 이상의 조직에 무단 침투
- **샌드박스 환경을 탈출**하여 에이전트 간 자율적 통신을 수행한 사례 확인
- **Anthropic 에이전트** 역시 보안 평가 과정에서 3개 기업의 시스템에 침투
- 멕시코 정부에서는 Claude Code를 경유한 **1억 9,500만 건의 개인정보 유출** 발생
- AI 에이전트를 도입한 기업의 **88%가 보안 사고를 경험**했다는 조사 결과 발표

### 한국 금융권 보안사고 &mdash; 바로 지금 벌어지고 있는 일

그리고 바로 지금, 한국에서는 금융권을 중심으로 보안사고가 연이어 터지고 있습니다.
원인은 아직 조사 중이지만, AI 기반 해킹이 아니냐는 추측이 많습니다.
오늘 우리가 논의하는 "AI 시대의 사이버보안을 어떻게 가져가야 하는가"라는 질문은 더 이상 이론이 아닙니다. 바로 지금 한국에서 벌어지고 있는 현실입니다.

### 한국 &mdash; 다른 길

이러한 상황에서 한국은 미국과는 다른 경로를 택하고 있습니다.

- 올해 **1월 22일, AI 기본법 시행** &mdash; EU에 이어 세계에서 두 번째로 포괄적인 AI 규제 체계를 갖춤
- 이재명 정부는 **AI 분야에 100조원 투자**를 공언하고, GPU 5만장 확보, 대통령실 **AI미래기획수석 신설** 등 범정부적 체제를 구축
- **"모두의 AI" 사업**을 통한 국산 파운데이션 모델 개발과 **Sovereign AI 전략** 추진
- 법적 프레임워크와 산업 육성을 동시에 추구하는, 미국의 자율규제 노선과는 본질적으로 다른 접근

### 조경래 영사님과 SF AI Summit

아울러 오늘 이 자리에 함께해 주신 조경래 영사님은, 지난 7월 24일 이재명 대통령과 Jensen Huang, Sam Altman, Dario Amodei, 이재용 삼성전자 회장, 최태원 SK 회장, 이해진 네이버 의장이 참석한 역사적인 "샌프란시스코 AI 선언" &mdash; SF AI Summit &mdash; 을 실무적으로 주도하신 핵심 인사이기도 합니다.

바로 그러한 분이 오늘 AI와 새로운 권력 구도에 관해 발표해 주셨으며, 지금부터의 패널 토론을 통해 한 층 더 깊은 논의를 이어가고자 합니다.

---

그럼 패널 토론에 앞서, 강연에서 소개되지 않은 김계연 CTO님의 간단한 자기소개부터 부탁드리겠습니다.

# Self-Introductions (~1 min)

홍민표 대표님과 조경래 영사님은 강연에서 이미 소개되었으므로 생략 &mdash; 김계연 CTO님만 간단히
# Self-Introductions (~1 min each)

홍민표 → 조경래 → 김계연 순서

# Round 1 &ndash; 개별 질문

## → 홍민표 대표님 (SEWORKS) {#r1-hong}

대표님, 오늘 "Securing the Agentic Era"라는 주제로 강연해 주셨는데요.
제가 방금 opening에서 말씀드린 것처럼 올해 들어서 AI 에이전트가 실제로 해킹을 하고, 샌드박스를 탈출하고, 에이전트끼리 통신까지 하는 사례가 쏟아지고 있습니다.
보안 전문가 입장에서 솔직하게 여쭤봅니다 &mdash;
**AI 에이전트 시대의 공격 표면은 기존 사이버 보안과 근본적으로 어떻게 다르고, 우리가 가장 과소평가하고 있는 위협은 무엇입니까?**

## → 조경래 영사님 (Consulate / MSIT) {#r1-cho}

영사님, 슬라이드에서 "Ten Fronts Reshaping AI"를 제시해 주셨는데요.
지금 미국과 한국이 AI 거버넌스에서 상당히 다른 접근을 취하고 있습니다.
트럼프 대통령은 지난주 백악관에서 Big Tech CEO들과 자발적 accord를 체결하면서 "tremendous self-policing"이라고 했습니다. 법적 강제력은 없습니다.
반면 한국은 올해 AI 기본법을 시행했고, 비록 1년 계도기간이지만 EU 다음으로 세계에서 두 번째 포괄적 규제 체계를 갖추었습니다.
**자율규제와 법적 프레임워크, 어느 쪽이 더 효과적이라고 보시고, 한국은 어떤 선택을 해야 합니까?**

## → 김계연 CTO님 (GENIANS) {#r1-kim}

CTO님은 네트워크 보안 현장에서 20년 넘게 계셨는데요.
오늘 홍민표 대표님 강연에서도 나왔듯이, AI가 공격자와 방어자 양쪽 모두에게 "force multiplier"가 되고 있습니다.
공격자 쪽에서는 AI가 피싱을 대량으로 정교하게 만들고, 취약점을 자동으로 찾아내며, 이제는 에이전트 스스로 침투까지 시도하는 시대가 됐습니다.
**실제로 현장에서 목격하시는 공격 패턴의 변화 &mdash; 무엇이 가장 달라졌고, 방어 측은 그 속도를 따라가고 있습니까?**

# Round 2 &ndash; 심화 질문

## → 홍민표 대표님 {#r2-hong}

Amodei가 "6-12개월 내 AI가 전체 인터넷을 장악할 수 있는 에이전트 군단을 이끌 수 있다"고 경고했습니다. Altman, Musk, Hassabis까지 동의했고요.
그런데 한편으로는 Amodei가 10월 중순에 Anthropic IPO를 앞두고 있어서 &mdash; slowdown 주장이 경쟁자 진입을 늦추고 자사 밸류에이션을 보호하는 전략적 포지셔닝 아니냐는 시각도 있습니다.
**보안 전문가 입장에서, 이 경고가 현실적입니까, 아니면 과장입니까?**

## → 조경래 영사님 {#r2-cho}

슬라이드에서 "OWN-ALLY-ADOPT-RULE" 프레임워크를 제시하셨는데, 특히 <span class="emph">"Strategy is not 'do everything' &mdash; it is deciding what must be owned, what must be connected, and where Korea can create leverage"</span>라는 말씀이 인상적이었습니다.
**현실적으로 한국이 반드시 "OWN" 해야 하는 것의 우선순위는 무엇이고, 실리콘밸리와의 관계에서 "ALLY"의 핵심 영역은 어디라고 보십니까?**

## → 김계연 CTO님 {#r2-kim}

조경래 영사님 슬라이드에서도 규제(regulation)가 10대 전선 중 하나로 다뤄졌는데요.
한국은 올해 AI 기본법을 시행했지만, 지금은 1년 계도기간 중입니다.
법은 있지만 강제력이 본격화되지 않은 이 어정쩡한 구간에서 &mdash;
**보안 업계 현장에서 보시기에, 기업들이 실제로 AI 보안 투자를 늘리고 있습니까, 아니면 계도기간이 끝날 때까지 관망하는 분위기입니까?
투자를 움직이는 건 결국 규제입니까, 아니면 실제 사고 경험입니까?**

## → 전체 패널 (공통 질문)

Open-weight 모델 vs. closed 모델의 보안 트레이드오프를 어떻게 보십니까?
조경래 영사님 슬라이드에서도 이 주제를 다루셨는데 &mdash; DeepSeek, Meta의 Llama 같은 open-weight 모델이 확산되면서 보안 리스크가 커진다는 주장과, 오히려 투명성이 보안을 강화한다는 주장이 있습니다.
**각자의 영역에서 &mdash; 보안 업계, 정책, 현장 &mdash; 어느 쪽이 더 설득력 있다고 보십니까?**

# Floor Q&amp;A

자, 이제 플로어에서 질문을 받겠습니다. 손 들어주시면 마이크 드리겠습니다.

# Closing Question &ndash; 전체 패널리스트

마지막으로 모든 패널리스트에게 같은 질문을 드리겠습니다.

**지금 이 순간, AI 보안과 관련해서 한국이 가장 시급하게 해야 할 <span class="emph">한 가지</span>를 꼽으신다면 무엇입니까?
그리고 오늘 이 자리에 계신, 실리콘밸리의 한국인 AI 전문가 커뮤니티 &mdash; 바로 여러분 &mdash; 이 그 과제에 어떤 역할을 할 수 있을까요?**

김계연 CTO님부터 역순으로 가시죠.

김계연 → 조경래 → 홍민표 순서

# Background Research Notes

<!--div class="notice--warning">
⚠️ 아래는 moderator 참고용 배경 자료입니다. 패널 토론 중 필요 시 활용하세요.
</div-->

## 미국 AI 정책 (Sep-Oct 2026)

- **9/29**: Trump, White House Accord on Superintelligence 체결 &mdash; Amodei, Brockman (OpenAI), Pichai, Zuckerberg, Musk, Huang 참석
- "도덕적 구속력" (morally binding), 법적 강제력 없음
- Trump: "I think I'm seeing tremendous self-policing"
- Jay Clayton (현 DNI)를 AI czar로 임명 예상
- **6/2**: Trump EO "Promoting Advanced AI Innovation and Security" &mdash; 모델 공개 전 정부에 30일 우선 공유, AI 해킹 형사 처벌 강화

## Amodei / AI Safety (Sep 2026)

- **9/12**: "We Must Pace the Frontier" 에세이 &mdash; 6-12개월 내 AI 에이전트 군단이 전체 인터넷 장악 가능 경고
- Altman, Musk, Hassabis 동의
- **9/24**: UN 안전보장이사회 브리핑
- 내부 연구원 Jacob Coxon 공개 사임; Evan Hubinger: "we really do earnestly believe AI could kill all humans!"
- Anthropic IPO 10월 중순 예정 &mdash; slowdown이 밸류에이션 보호 전략이라는 비판도 존재

## AI 에이전트 보안 사고 (2026)

- **OpenAI 에이전트**: 10+ 건 &mdash; RubyGems, Hugging Face, 호주 Medicare, 50+ 조직 해킹
- **Anthropic 에이전트**: 9+ 건 &mdash; 평가 중 3개 회사 해킹, 테스트 환경 탈출
- 에이전트 간 자율 통신 및 샌드박스 탈출 사례
- 멕시코 정부 &mdash; Claude Code를 통해 1억 9,500만 건 개인정보 유출
- AI 에이전트 운영 기업의 **88%**가 보안 사고 경험

## 한국 AI 정책 (2026)

- **1/22**: AI 기본법 시행 (EU 다음으로 세계 두 번째 포괄적 AI 규제 체계, 1년 계도기간)
- 이재명 정부: AI **100조원** 투자, GPU **5만장** 확보
- 대통령실 **AI미래기획수석** 신설
- 과기정통부 **부총리급 격상** 추진
- "모두의 AI" 사업 &mdash; SKT, KT, Kakao 선정, 국산 파운데이션 모델 개발
- **Sovereign AI** 전략 추진
- **7/24**: 이재명 대통령, SF AI Summit &mdash; "샌프란시스코 AI 선언" (Jensen Huang, Sam Altman, Dario Amodei, 이재용, 최태원, 이해진, 정의선 참석)
