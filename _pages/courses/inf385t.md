---
permalink: /courses/inf385t/
title: "INF 385T Large Language Model Applications"
excerpt: "INF 385T - MSIS course at UT-Austin"
author_profile: false
---

{% include base_path %}

<style>
.page {
  float: left;
  width: 100%;
}
.page__inner-wrap {
  max-width: 100%;
}
</style>
"Build an AI Product in 15 weeks and submit to Y Combinator"


The University of Texas at Austin, Fall 2026  
Instructor: [Jiaxin Pei](https://jiaxin-pei.github.io/)

[Syllabus](#syllabus) • [Schedule](#schedule) • Project • Canvas

## Syllabus {#syllabus}

* **Course**: INF 385T Large Language Model Applications
* **Semester**: Fall 2026
* **Webpage**: https://jiaxin-pei.github.io/courses/inf385t/
* **Canvas**: TBA
* **Meeting**: TBA

### Prerequisites

Comfortable writing Python applications, using APIs, and working in a terminal. Prior experience with machine learning or natural language processing is also required.

### Contact information

* **Instructor**: [Jiaxin Pei](https://jiaxin-pei.github.io/); email: jiaxinpei@utexas.edu  
  * Office hours: TBA. Location: TBA.

### Course materials

* Readings and resources will be provided via hyperlinks under Schedule.
* Exercises, code, etc. will be posted on Canvas.

### Course overview and objectives

This course explores the design and development of practical applications powered by large language models (LLMs), including agentic systems that can plan, take actions, and use tools to complete real-world tasks. The course covers both LLM fundamentals—how LLMs work, their capabilities and limitations—and applied methods for building reliable systems, including prompting, retrieval-augmented generation, orchestration, safety, and evaluation. The course is project-driven: student teams build and iterate on an LLM-based application throughout the term, complemented by guest lectures from founders, investors, and researchers on building and assessing frontier AI systems.

By the end of this course, students will be able to:

1. Design and build a working LLM-powered application from idea to deployed product
2. Apply core techniques—prompting, RAG, orchestration, agentic tool use, and multi-modal integration—to solve real-world problems
3. Evaluate LLM systems for quality, safety, and cost
4. Iterate on a product based on real user feedback
5. Communicate and present an AI product to technical and non-technical audiences

## Schedule {#schedule}

<style>
.course-timeline {
  display: flex;
  align-items: stretch;
  margin: 1.5em 0 2em 0;
  font-size: 0.82em;
  border-radius: 10px;
  overflow: hidden;
  box-shadow: 0 2px 12px rgba(0,0,0,0.06);
}
.course-timeline .phase {
  flex: 1;
  padding: 14px 10px;
  text-align: center;
  position: relative;
  display: flex;
  flex-direction: column;
  justify-content: flex-start;
}
.course-timeline .phase-icon {
  font-size: 1.6em;
  margin-bottom: 6px;
}
.course-timeline .phase-title {
  font-weight: 700;
  font-size: 0.88em;
  margin-bottom: 2px;
}
.course-timeline .phase-weeks {
  font-size: 0.75em;
  opacity: 0.6;
  margin-bottom: 5px;
}
.course-timeline .phase-desc {
  font-size: 0.75em;
  line-height: 1.35;
  opacity: 0.85;
}
.course-timeline .phase + .phase {
  border-left: 1px solid rgba(0,0,0,0.08);
}
.phase-ideate { background: linear-gradient(180deg, #fef3c7 0%, #fef9ee 100%); }
.phase-basics { background: linear-gradient(180deg, #dbeafe 0%, #eff6ff 100%); }
.phase-demo1 { background: linear-gradient(180deg, #ede9fe 0%, #f5f3ff 100%); }
.phase-build { background: linear-gradient(180deg, #d1fae5 0%, #ecfdf5 100%); }
.phase-beta { background: linear-gradient(180deg, #ffe4e6 0%, #fff1f2 100%); }
.phase-iterate { background: linear-gradient(180deg, #cffafe 0%, #ecfeff 100%); }
.phase-launch { background: linear-gradient(180deg, #fed7aa 0%, #fff7ed 100%); }
</style>

<div class="course-timeline">
  <div class="phase phase-ideate">
    <div class="phase-icon">💡</div>
    <div class="phase-title">Ideate</div>
    <div class="phase-weeks">Week 1</div>
    <div class="phase-desc">Find ideas, study the landscape</div>
  </div>
  <div class="phase phase-basics">
    <div class="phase-icon">🧱</div>
    <div class="phase-title">Learn & Build</div>
    <div class="phase-weeks">Weeks 2–4</div>
    <div class="phase-desc">LLM basics, 3 individual demos</div>
  </div>
  <div class="phase phase-demo1">
    <div class="phase-icon">🎤</div>
    <div class="phase-title">Demo Day</div>
    <div class="phase-weeks">Week 5</div>
    <div class="phase-desc">Present, vote, form teams</div>
  </div>
  <div class="phase phase-build">
    <div class="phase-icon">🔨</div>
    <div class="phase-title">Team Build</div>
    <div class="phase-weeks">Weeks 6–9</div>
    <div class="phase-desc">Agents, evals, multi-modal, safety</div>
  </div>
  <div class="phase phase-beta">
    <div class="phase-icon">🧪</div>
    <div class="phase-title">Beta Test</div>
    <div class="phase-weeks">Week 10</div>
    <div class="phase-desc">Demo &amp; real user testing</div>
  </div>
  <div class="phase phase-iterate">
    <div class="phase-icon">🔄</div>
    <div class="phase-title">Iterate</div>
    <div class="phase-weeks">Weeks 11–15</div>
    <div class="phase-desc">Feedback, guest lectures, deploy</div>
  </div>
  <div class="phase phase-launch">
    <div class="phase-icon">🚀</div>
    <div class="phase-title">Launch</div>
    <div class="phase-weeks">Week 16</div>
    <div class="phase-desc">Public demo day</div>
  </div>
</div>

**Schedule is tentative and subject to change.**

* **Week 1 (8/24–8/28) – Finding ideas**
  * Course introduction. How to identify opportunities and find ideas for building something cool with LLMs.
  * Readings:  
    * [Y Combinator, Requests for Startups (RFS)](https://www.ycombinator.com/rfs)  
    * [Y Combinator, Techno-Industrialist](https://www.ycombinator.com/techno-industrialist)  
    * [a16z, Big Ideas 2026 (Part 1)](https://a16z.com/newsletter/big-ideas-2026-part-1/)  
    * [Greylock, Idea Map](https://greylock.com/idea-map/)  
    * [Bessemer Venture Partners, Atlas](https://www.bvp.com/atlas)  
    * [Sequoia, AI Retail Opportunity](https://sequoiacap.com/article/ai-retail-opportunity/)  
    * [Sequoia, AI in 2025](https://sequoiacap.com/article/ai-in-2025/)  
    * [NFX, Generative AI Tech Market Map](https://www.nfx.com/post/generative-ai-tech-market-map)  
  * **Homework:** Write four one-pagers: (1) a cool AI startup product that you like, and (2–4) three products you want to build
* **Week 2 (8/31–9/4) – LLM basics I**
  * How LLMs work; prompting and instruction-following; few-shot learning; in-context learning.
  * Product to explore: [RowFlow](https://rowflow.ai/) (YC S25) — replaces traditional forms with AI conversations that extract structured data from natural language
  * Readings:
    * [DeepLearning.AI, How Transformer LLMs Work](https://www.deeplearning.ai/short-courses/how-transformer-llms-work/) (short course)
    * [Anthropic, Prompt Engineering Overview](https://docs.anthropic.com/en/docs/build-with-claude/prompt-engineering/overview)
    * [OpenAI, GPT Prompting Guide](https://cookbook.openai.com/examples/gpt-5/gpt-5_prompting_guide)
    * [Learn Prompting, Shot-Based Prompting: Zero-Shot, One-Shot, and Few-Shot](https://learnprompting.org/docs/basics/few_shot)
  * **Homework:** Use AI tools to build the **first** demo of the LLM application you want to build
* **Week 3 (9/7–9/11) – LLM basics II** *(Labor Day 9/7; no class)*
  * Retrieval-augmented generation (RAG); embeddings and semantic search; grounding LLM outputs.
  * Product to explore: [Morphik](https://www.morphik.ai/) (YC W25) — RAG infrastructure with visual-first retrieval that achieves 96% accuracy on document analysis without hallucinations
  * Readings:
    * [LangChain, Build a RAG Agent](https://python.langchain.com/docs/tutorials/rag/)
    * [Ashutosh, The Complete Guide to RAG in 2025](https://ashutosh.dev/the-complete-guide-to-retrieval-augmented-generation-rag-in-2025/)
    * [OpenAI, Embeddings Guide](https://platform.openai.com/docs/guides/embeddings)
  * **Homework:** Use AI tools to build the **second** demo of the LLM application you want to build
* **Week 4 (9/14–9/18) – LLM basics III**
  * Orchestration and composing LLM calls; chaining; structured outputs; key patterns for building applications.
  * Product to explore: [Paloma](https://www.ycombinator.com/companies/paloma) (YC S25) — AI-native CRM that orchestrates LLM chains to automate post-sales operations end-to-end
  * Readings:
    * [OpenAI, Structured Outputs](https://platform.openai.com/docs/guides/structured-outputs)
    * [OpenAI, Function Calling](https://platform.openai.com/docs/guides/function-calling)
    * [LangChain, Workflows and Agents](https://langchain-ai.github.io/langgraph/tutorials/workflows/)
    * [Deepchecks, Orchestrating Multi-Step LLM Chains](https://www.deepchecks.com/orchestrating-multi-step-llm-chains-best-practices/)
  * **Homework:** Use AI tools to build the **third** demo of the LLM application you want to build
* **Week 5 (9/21–9/25) – Lightweight demo day**
  * Students present their demos, review products others built, vote on the most promising ideas, and form teams for the class project.
* **Week 6 (9/28–10/2) – Agentic systems and tool use**
  * Planning, multi-step reasoning, function calling, and agent frameworks.
  * Product to explore: [Browser Use](https://www.browseruse.com/) (YC W25) — open-source web agent with 50k+ GitHub stars that lets AI control browsers to complete real-world tasks
  * Readings:
    * [Anthropic, Building Effective Agents](https://www.anthropic.com/research/building-effective-agents)
    * [Anthropic, Writing Effective Tools for AI Agents](https://www.anthropic.com/engineering/writing-tools-for-agents)
    * [Lilian Weng, LLM Powered Autonomous Agents](https://lilianweng.github.io/posts/2023-06-23-agent/)
    * [LangGraph Tutorial: Building AI Agents](https://langchain-tutorials.github.io/langgraph-tutorial-2026-beginners-guide/)
  * **Homework:** Build application in teams
* **Week 7 (10/5–10/9) – Evaluation and testing**
  * Automated evals, human evals, LLM-as-judge, regression testing.
  * Product to explore: [Confident AI](https://www.ycombinator.com/companies/confident-ai) (YC W25) — LLM eval and observability platform built by the creators of DeepEval (12.6k GitHub stars, 3M+ monthly downloads)
  * Readings:
    * [Hamel Husain, Your AI Product Needs Evals](https://hamel.dev/blog/posts/evals/index.html)
    * [Anthropic, Demystifying Evals for AI Agents](https://www.anthropic.com/engineering/demystifying-evals-for-ai-agents)
    * [Evidently AI, LLM-as-a-Judge: A Complete Guide](https://evidentlyai.com/llm-guide/llm-as-a-judge)
  * **Homework:** Build application in teams
* **Week 8 (10/12–10/16) – Multi-modal applications**
  * Vision, audio, and video models; integrating multi-modal capabilities into LLM applications; use cases and design patterns.
  * Product to explore: [Cardboard](https://www.ycombinator.com/companies/cardboard) (YC W26) — agentic video editor that uses multi-modal LLMs to understand footage and auto-generate edits
  * Readings:
    * [OpenAI, Vision Guide](https://platform.openai.com/docs/guides/vision)
    * [Google, Gemini Multi-Modal Capabilities](https://ai.google.dev/gemini-api/docs/vision)
    * [Anthropic, Vision with Claude](https://docs.anthropic.com/en/docs/build-with-claude/vision)
  * **Homework:** Build application in teams
* **Week 9 (10/19–10/23) – Safety, guardrails, and product design**
  * Prompt injection, hallucination mitigation, content filtering, error recovery; UX patterns, latency vs quality tradeoffs, human-in-the-loop design.
  * Product to explore: [Alter](https://www.ycombinator.com/companies/alter) (YC S25) — zero-trust identity and access control for AI agents, with fine-grained authorization and real-time guardrails
  * Readings:
    * [OWASP, Top 10 for LLM Applications 2025](https://genai.owasp.org/resource/owasp-top-10-for-llm-applications-2025/)
    * [Simon Willison, The Lethal Trifecta for AI Agents](https://simonwillison.net/2025/Jun/16/the-lethal-trifecta/)
    * [Promptfoo, Red Teaming LLM Guide](https://www.promptfoo.dev/docs/red-team/)
    * [Google PAIR, People + AI Guidebook](https://pair.withgoogle.com/guidebook/patterns)
    * [Nielsen Norman Group, Designing AI Products and Features](https://www.nngroup.com/articles/designing-ai-study-guide/)
  * **Homework:** Build application in teams
* **Week 10 (10/26–10/30) – Demo day & beta test**
  * Teams present their applications and run beta testing with real users.
* **Week 11 (11/2–11/6) – Cost optimization and deployment**
  * Caching, model selection, latency optimization, serving infrastructure.
  * Product to explore: [Chamber](https://www.ycombinator.com/companies/chamber) (YC W26) — autopilots GPU cluster governance, enabling teams to run ~50% more workloads on the same infrastructure
  * Readings:
    * [Enrico Piovano, LLM Cost Engineering: Token Budgeting, Caching, and Model Routing](https://enricopiovano.com/blog/llm-cost-optimization-caching-strategies)
    * [Redis, LLMOps Guide: Build Fast, Cost-Effective LLM Apps](https://redis.io/blog/large-language-model-operations-guide/)
    * [GoPenAI, Optimizing LLM Infrastructure: Latency, Cost, and Quality Trade-offs](https://blog.gopenai.com/optimizing-large-language-model-infrastructure-a-practitioners-guide-to-latency-cost-and-46f9002152bc)
  * **Homework:** Iterate based on real user feedback
* **Week 12 (11/9–11/13) – Guest lecture: Founders**
  * Founder perspective on building and shipping AI products.
  * Product to explore: [Martini](https://www.ycombinator.com/companies/martini) (YC W26) — collaborative AI-native platform for professional filmmaking using generative media
  * **Homework:** Iterate based on real user feedback
* **Week 13 (11/16–11/20) – Guest lecture: Investors**
  * Investor perspective on evaluating AI startups, moats, and go-to-market.
  * Product to explore: [Fenrock AI](https://www.ycombinator.com/companies/fenrock-ai-yc-w26) (YC W26) — AI agents for financial crime compliance that help analysts process 10x more workload
  * **Homework:** Iterate based on real user feedback
* **Week 14 (11/23–11/27) – Thanksgiving break; no classes**
* **Week 15 (11/30–12/4) – Guest lecture: Researchers**
  * Researcher perspective on frontier AI and what's next.
  * Product to explore: [Ritivel](https://www.ycombinator.com/companies/ritivel) (YC W26) — AI agents that turn clinical trial data into FDA submission documents in minutes
  * **Homework:** Iterate based on real user feedback
* **Week 16 (12/7) – Public demo day** *(last class day)*


### Course requirements and grading policy

* **Individual assignments (30%)** — Weeks 1–4
  * Week 1: Four one-pagers on AI products
  * Weeks 2–4: Three individual demos built with AI tools

* **Class project (60%)** — Weeks 5–16
  * Teams of 3 students with complementary expertise (e.g., engineering, design, domain knowledge).
  * Grading based on:
    * Lightweight demo day presentation (Week 5)
    * Beta test and demo day (Week 10)
    * Iteration progress and user feedback incorporation (Weeks 11–15)
    * Public demo day (Week 16)

* **Peer review and participation (10%)**
  * Reviewing and voting on classmates' demos (Week 5), beta testing other teams' products (Week 10), and engagement with guest speakers.

* The course will use plus-minus grading, using the following scale:

| Grade | Percentage |
| ----- | ---------- |
| A     | ≥ 93%      |
| A-    | ≥ 90%      |
| B+    | ≥ 87%      |
| B     | ≥ 83%      |
| B-    | ≥ 80%      |
| C+    | ≥ 77%      |
| C     | ≥ 73%      |
| C-    | ≥ 70%      |
| D+    | ≥ 67%      |
| D     | ≥ 63%      |
| D-    | ≥ 60%      |

### Academic integrity and AI tools

This course *requires* you to use AI tools — ChatGPT, Copilot, Cursor, and whatever else helps you build. Building on the shoulders of AI is a core skill this class teaches.

That said, using AI tools does not remove your responsibility to understand what you submit. You must be able to explain every piece of your work — how it works, why you made the choices you did, and what the tradeoffs are. If your only answer is "the AI told me to do it," that is not your own work.

You are encouraged to discuss ideas with classmates, consult external resources, and use open-source code. However, you must cite any substantial external code or resources you incorporate. For individual assignments, the work you submit must reflect your own understanding. For team projects, all team members are expected to contribute meaningfully and be able to speak to the full scope of the project.

### Notice about students with disabilities

The University of Texas at Austin provides upon request appropriate academic accommodations for qualified students with disabilities. Please contact the [Division of Diversity and Community Engagement, Services for Students with Disabilities](https://ddce.utexas.edu/disability/), 512-471-6259.

### Notice about missed work due to religious holy days

A student who cannot meet an assignment deadline due to the observance of a religious holy day may submit the assignment up to 24 hours late without penalty, if proper notice of the planned absence has been given. Notice must be given at least 14 days prior to the due date. For religious holy days that fall within the first 2 weeks of the semester, notice should be given on the first day of the semester. Notice should be emailed to the instructor and course staff.


