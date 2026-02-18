---
permalink: /courses/inf385t/
title: "INF 385T Large Language Model Applications"
excerpt: "INF 385T - MSIS course at UT-Austin"
author_profile: true
---

{% include base_path %}

The University of Texas at Austin  
School of Information  
Fall 2026  
Instructor: [Jiaxin Pei](https://jiaxin-pei.github.io/)

[Syllabus](#syllabus) • [Schedule](#schedule) • Project • Canvas

## Syllabus {#syllabus}

* **Course**: INF 385T Large Language Model Applications (MSIS)
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
  * Readings:
    * [DeepLearning.AI, How Transformer LLMs Work](https://www.deeplearning.ai/short-courses/how-transformer-llms-work/) (short course)
    * [Anthropic, Prompt Engineering Overview](https://docs.anthropic.com/en/docs/build-with-claude/prompt-engineering/overview)
    * [OpenAI, GPT Prompting Guide](https://cookbook.openai.com/examples/gpt-5/gpt-5_prompting_guide)
    * [Learn Prompting, Shot-Based Prompting: Zero-Shot, One-Shot, and Few-Shot](https://learnprompting.org/docs/basics/few_shot)
  * **Homework:** Use AI tools to build the **first** demo of the LLM application you want to build
* **Week 3 (9/7–9/11) – LLM basics II** *(Labor Day 9/7; no class)*
  * Retrieval-augmented generation (RAG); embeddings and semantic search; grounding LLM outputs.
  * Readings:
    * [LangChain, Build a RAG Agent](https://python.langchain.com/docs/tutorials/rag/)
    * [Ashutosh, The Complete Guide to RAG in 2025](https://ashutosh.dev/the-complete-guide-to-retrieval-augmented-generation-rag-in-2025/)
    * [OpenAI, Embeddings Guide](https://platform.openai.com/docs/guides/embeddings)
  * **Homework:** Use AI tools to build the **second** demo of the LLM application you want to build
* **Week 4 (9/14–9/18) – LLM basics III**
  * Orchestration and composing LLM calls; chaining; structured outputs; key patterns for building applications.
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
  * Readings:
    * [Anthropic, Building Effective Agents](https://www.anthropic.com/research/building-effective-agents)
    * [Anthropic, Writing Effective Tools for AI Agents](https://www.anthropic.com/engineering/writing-tools-for-agents)
    * [Lilian Weng, LLM Powered Autonomous Agents](https://lilianweng.github.io/posts/2023-06-23-agent/)
    * [LangGraph Tutorial: Building AI Agents](https://langchain-tutorials.github.io/langgraph-tutorial-2026-beginners-guide/)
  * **Homework:** Build application in teams
* **Week 7 (10/5–10/9) – Evaluation and testing**
  * Automated evals, human evals, LLM-as-judge, regression testing.
  * Readings:
    * [Hamel Husain, Your AI Product Needs Evals](https://hamel.dev/blog/posts/evals/index.html)
    * [Anthropic, Demystifying Evals for AI Agents](https://www.anthropic.com/engineering/demystifying-evals-for-ai-agents)
    * [Evidently AI, LLM-as-a-Judge: A Complete Guide](https://evidentlyai.com/llm-guide/llm-as-a-judge)
  * **Homework:** Build application in teams
* **Week 8 (10/12–10/16) – Multi-modal applications**
  * Vision, audio, and video models; integrating multi-modal capabilities into LLM applications; use cases and design patterns.
  * Readings:
    * [OpenAI, Vision Guide](https://platform.openai.com/docs/guides/vision)
    * [Google, Gemini Multi-Modal Capabilities](https://ai.google.dev/gemini-api/docs/vision)
    * [Anthropic, Vision with Claude](https://docs.anthropic.com/en/docs/build-with-claude/vision)
  * **Homework:** Build application in teams
* **Week 9 (10/19–10/23) – Safety, guardrails, and product design**
  * Prompt injection, hallucination mitigation, content filtering, error recovery; UX patterns, latency vs quality tradeoffs, human-in-the-loop design.
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
  * Readings:
    * [Enrico Piovano, LLM Cost Engineering: Token Budgeting, Caching, and Model Routing](https://enricopiovano.com/blog/llm-cost-optimization-caching-strategies)
    * [Redis, LLMOps Guide: Build Fast, Cost-Effective LLM Apps](https://redis.io/blog/large-language-model-operations-guide/)
    * [GoPenAI, Optimizing LLM Infrastructure: Latency, Cost, and Quality Trade-offs](https://blog.gopenai.com/optimizing-large-language-model-infrastructure-a-practitioners-guide-to-latency-cost-and-46f9002152bc)
  * **Homework:** Iterate based on real user feedback
* **Week 12 (11/9–11/13) – Guest lecture: Founders**
  * Founder perspective on building and shipping AI products.
  * **Homework:** Iterate based on real user feedback
* **Week 13 (11/16–11/20) – Guest lecture: Investors**
  * Investor perspective on evaluating AI startups, moats, and go-to-market.
  * **Homework:** Iterate based on real user feedback
* **Week 14 (11/23–11/27) – Thanksgiving break; no classes**
* **Week 15 (11/30–12/4) – Guest lecture: Researchers**
  * Researcher perspective on frontier AI and what's next.
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


