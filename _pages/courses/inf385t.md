---
permalink: /courses/inf385t/
title: "INF 385T Large Language Model Applications"
excerpt: "INF 385T - MSIS course at UT-Austin"
author_profile: false
---

{% include base_path %}

<style>
/* ── Page-wide layout ── */
.page { float: left; width: 100%; }
.page__inner-wrap { max-width: 100%; }
.page__content { font-size: 0.92em; line-height: 1.7; }
.page__content h2 { border-bottom: 2px solid #e5e7eb; padding-bottom: 6px; margin-top: 2.2em; }
.page__content h3 { margin-top: 1.6em; }

/* ── Hero banner ── */
.course-hero {
  background: linear-gradient(135deg, #0f172a 0%, #1e3a5f 50%, #0f172a 100%);
  color: #fff;
  padding: 48px 40px;
  border-radius: 14px;
  margin-bottom: 2em;
  position: relative;
  overflow: hidden;
}
.course-hero::before {
  content: "";
  position: absolute;
  top: -50%;
  right: -20%;
  width: 500px;
  height: 500px;
  background: radial-gradient(circle, rgba(99,102,241,0.15) 0%, transparent 70%);
  pointer-events: none;
}
.course-hero .hero-tagline {
  font-size: 0.95em;
  opacity: 0.7;
  margin-bottom: 8px;
  letter-spacing: 0.5px;
  text-transform: uppercase;
}
.course-hero h1 {
  font-size: 2.2em;
  margin: 0 0 8px 0;
  font-weight: 800;
  letter-spacing: -0.5px;
}
.course-hero .hero-subtitle {
  font-size: 1.15em;
  opacity: 0.85;
  margin-bottom: 16px;
  font-style: italic;
}
.course-hero .hero-meta {
  font-size: 0.88em;
  opacity: 0.7;
}
.course-hero .hero-meta a { color: #93c5fd; }

/* ── Quick nav pills ── */
.quick-nav {
  display: flex;
  gap: 10px;
  flex-wrap: wrap;
  margin-bottom: 2em;
}
.quick-nav a {
  display: inline-block;
  padding: 8px 18px;
  border-radius: 20px;
  background: #f1f5f9;
  color: #334155;
  font-size: 0.88em;
  font-weight: 600;
  text-decoration: none;
  transition: all 0.15s;
}
.quick-nav a:hover { background: #e2e8f0; color: #1e293b; }

/* ── Info grid ── */
.info-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  gap: 14px;
  margin-bottom: 2em;
}
.info-card {
  background: #f8fafc;
  border: 1px solid #e2e8f0;
  border-radius: 10px;
  padding: 16px 18px;
}
.info-card .info-label {
  font-size: 0.72em;
  text-transform: uppercase;
  letter-spacing: 0.8px;
  color: #94a3b8;
  font-weight: 600;
  margin-bottom: 4px;
}
.info-card .info-value {
  font-size: 0.92em;
  font-weight: 600;
  color: #1e293b;
}
.info-card .info-value a { color: #3b82f6; }

/* ── Learning outcomes ── */
.outcomes {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 12px;
  margin: 1em 0 1.5em 0;
}
.outcome {
  display: flex;
  align-items: flex-start;
  gap: 10px;
  background: #f0fdf4;
  border-left: 3px solid #22c55e;
  padding: 12px 14px;
  border-radius: 0 8px 8px 0;
  font-size: 0.88em;
  line-height: 1.45;
}
.outcome-num {
  font-weight: 800;
  color: #16a34a;
  font-size: 1em;
  min-width: 18px;
}

/* ── Timeline ── */
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
  display: flex;
  flex-direction: column;
  justify-content: flex-start;
}
.course-timeline .phase-icon { font-size: 1.6em; margin-bottom: 6px; }
.course-timeline .phase-title { font-weight: 700; font-size: 0.88em; margin-bottom: 2px; }
.course-timeline .phase-weeks { font-size: 0.75em; opacity: 0.6; margin-bottom: 5px; }
.course-timeline .phase-desc { font-size: 0.75em; line-height: 1.35; opacity: 0.85; }
.course-timeline .phase + .phase { border-left: 1px solid rgba(0,0,0,0.08); }
.phase-ideate { background: linear-gradient(180deg, #fef3c7 0%, #fef9ee 100%); }
.phase-basics { background: linear-gradient(180deg, #dbeafe 0%, #eff6ff 100%); }
.phase-demo1 { background: linear-gradient(180deg, #ede9fe 0%, #f5f3ff 100%); }
.phase-build { background: linear-gradient(180deg, #d1fae5 0%, #ecfdf5 100%); }
.phase-beta { background: linear-gradient(180deg, #ffe4e6 0%, #fff1f2 100%); }
.phase-iterate { background: linear-gradient(180deg, #cffafe 0%, #ecfeff 100%); }
.phase-launch { background: linear-gradient(180deg, #fed7aa 0%, #fff7ed 100%); }

/* ── Week cards ── */
.week-card {
  background: #fff;
  border: 1px solid #e5e7eb;
  border-radius: 12px;
  padding: 20px 24px;
  margin-bottom: 16px;
  transition: box-shadow 0.15s;
}
.week-card:hover { box-shadow: 0 4px 16px rgba(0,0,0,0.06); }
.week-card.week-milestone {
  border-left: 4px solid #8b5cf6;
  background: #faf5ff;
}
.week-card.week-break {
  border-left: 4px solid #94a3b8;
  background: #f8fafc;
  opacity: 0.75;
}
.week-header {
  display: flex;
  justify-content: space-between;
  align-items: baseline;
  margin-bottom: 8px;
}
.week-title { font-weight: 700; font-size: 1.05em; color: #1e293b; }
.week-dates { font-size: 0.8em; color: #94a3b8; font-weight: 500; }
.week-desc { font-size: 0.9em; color: #475569; margin-bottom: 10px; line-height: 1.55; }
.week-product {
  display: inline-flex;
  align-items: center;
  gap: 6px;
  background: #eef2ff;
  border: 1px solid #c7d2fe;
  border-radius: 6px;
  padding: 6px 12px;
  font-size: 0.82em;
  margin-bottom: 8px;
  color: #4338ca;
}
.week-product a { color: #4338ca; font-weight: 600; }
.week-readings { font-size: 0.85em; color: #64748b; }
.week-readings summary { cursor: pointer; font-weight: 600; color: #475569; margin-bottom: 4px; }
.week-readings ul { margin: 6px 0 0 0; padding-left: 18px; }
.week-readings li { margin-bottom: 3px; }
.week-readings a { color: #3b82f6; }
.week-hw {
  margin-top: 10px;
  padding: 8px 14px;
  background: #fffbeb;
  border-left: 3px solid #f59e0b;
  border-radius: 0 6px 6px 0;
  font-size: 0.85em;
  color: #92400e;
}
.week-hw strong { color: #78350f; }

/* ── Grading bars ── */
.grade-bars { margin: 1em 0 1.5em 0; }
.grade-bar-row {
  display: flex;
  align-items: center;
  margin-bottom: 10px;
  font-size: 0.9em;
}
.grade-bar-label { width: 220px; font-weight: 600; color: #334155; }
.grade-bar-track {
  flex: 1;
  height: 28px;
  background: #f1f5f9;
  border-radius: 6px;
  overflow: hidden;
  position: relative;
}
.grade-bar-fill {
  height: 100%;
  border-radius: 6px;
  display: flex;
  align-items: center;
  padding-left: 12px;
  font-size: 0.82em;
  font-weight: 700;
  color: #fff;
}
.grade-bar-fill.bar-individual { background: linear-gradient(90deg, #3b82f6, #60a5fa); width: 30%; }
.grade-bar-fill.bar-project { background: linear-gradient(90deg, #8b5cf6, #a78bfa); width: 60%; }
.grade-bar-fill.bar-peer { background: linear-gradient(90deg, #f59e0b, #fbbf24); width: 10%; }
.grade-bar-detail { font-size: 0.82em; color: #64748b; margin: -4px 0 12px 220px; }

/* ── Policy cards ── */
.policy-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 16px;
  margin-top: 1em;
}
.policy-card {
  background: #f8fafc;
  border: 1px solid #e2e8f0;
  border-radius: 10px;
  padding: 18px 20px;
}
.policy-card h4 {
  margin: 0 0 8px 0;
  font-size: 0.95em;
  color: #1e293b;
}
.policy-card p {
  font-size: 0.85em;
  color: #475569;
  line-height: 1.55;
  margin: 0;
}
.policy-card a { color: #3b82f6; }
</style>

<!-- ════════ HERO ════════ -->
<div class="course-hero">
  <div class="hero-tagline">INF 385T · MSIS · UT-Austin School of Information</div>
  <h1>Large Language Model Applications</h1>
  <div class="hero-subtitle">"Build an AI product in 16 weeks"</div>
  <div class="hero-meta">Fall 2026 · Instructor: <a href="https://jiaxin-pei.github.io/">Jiaxin Pei</a></div>
</div>

<!-- ════════ QUICK NAV ════════ -->
<div class="quick-nav">
  <a href="#overview">Overview</a>
  <a href="#schedule">Schedule</a>
  <a href="#grading">Grading</a>
  <a href="#policies">Policies</a>
  <a href="#">Canvas (TBA)</a>
</div>

<!-- ════════ INFO GRID ════════ -->
<div class="info-grid">
  <div class="info-card">
    <div class="info-label">Course</div>
    <div class="info-value">INF 385T</div>
  </div>
  <div class="info-card">
    <div class="info-label">Semester</div>
    <div class="info-value">Fall 2026</div>
  </div>
  <div class="info-card">
    <div class="info-label">Meeting</div>
    <div class="info-value">TBA</div>
  </div>
  <div class="info-card">
    <div class="info-label">Office Hours</div>
    <div class="info-value">TBA</div>
  </div>
  <div class="info-card">
    <div class="info-label">Contact</div>
    <div class="info-value"><a href="mailto:jiaxinpei@utexas.edu">jiaxinpei@utexas.edu</a></div>
  </div>
  <div class="info-card">
    <div class="info-label">Prerequisites</div>
    <div class="info-value">Python, APIs, terminal</div>
  </div>
</div>

## Overview {#overview}

This course explores the design and development of practical applications powered by large language models (LLMs), including agentic systems that can plan, take actions, and use tools to complete real-world tasks. The course covers both LLM fundamentals—how LLMs work, their capabilities and limitations—and applied methods for building reliable systems, including prompting, retrieval-augmented generation, orchestration, safety, and evaluation. The course is project-driven: student teams build and iterate on an LLM-based application throughout the term, complemented by guest lectures from founders, investors, and researchers on building and assessing frontier AI systems.

### Learning outcomes

<div class="outcomes">
  <div class="outcome"><span class="outcome-num">1</span> Design and build a working LLM-powered application from idea to deployed product</div>
  <div class="outcome"><span class="outcome-num">2</span> Apply core techniques — prompting, RAG, orchestration, agentic tool use, and multi-modal integration</div>
  <div class="outcome"><span class="outcome-num">3</span> Evaluate LLM systems for quality, safety, and cost</div>
  <div class="outcome"><span class="outcome-num">4</span> Iterate on a product based on real user feedback</div>
  <div class="outcome"><span class="outcome-num">5</span> Communicate and present an AI product to technical and non-technical audiences</div>
</div>

## Schedule {#schedule}

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

*Schedule is tentative and subject to change.*

<!-- Week 1 -->
<div class="week-card">
  <div class="week-header">
    <span class="week-title">Week 1 — Finding Ideas</span>
    <span class="week-dates">8/24–8/28</span>
  </div>
  <div class="week-desc">Course introduction. How to identify opportunities and find ideas for building something cool with LLMs.</div>
  <div class="week-readings">
    <details><summary>Readings</summary>
    <ul>
      <li><a href="https://www.ycombinator.com/rfs">Y Combinator, Requests for Startups (RFS)</a></li>
      <li><a href="https://www.ycombinator.com/techno-industrialist">Y Combinator, Techno-Industrialist</a></li>
      <li><a href="https://a16z.com/newsletter/big-ideas-2026-part-1/">a16z, Big Ideas 2026 (Part 1)</a></li>
      <li><a href="https://greylock.com/idea-map/">Greylock, Idea Map</a></li>
      <li><a href="https://www.bvp.com/atlas">Bessemer Venture Partners, Atlas</a></li>
      <li><a href="https://sequoiacap.com/article/ai-retail-opportunity/">Sequoia, AI Retail Opportunity</a></li>
      <li><a href="https://sequoiacap.com/article/ai-in-2025/">Sequoia, AI in 2025</a></li>
      <li><a href="https://www.nfx.com/post/generative-ai-tech-market-map">NFX, Generative AI Tech Market Map</a></li>
    </ul>
    </details>
  </div>
  <div class="week-hw"><strong>Homework:</strong> Write four one-pagers: (1) a cool AI startup product that you like, and (2–4) three products you want to build</div>
</div>

<!-- Week 2 -->
<div class="week-card">
  <div class="week-header">
    <span class="week-title">Week 2 — LLM Basics I</span>
    <span class="week-dates">8/31–9/4</span>
  </div>
  <div class="week-desc">How LLMs work; prompting and instruction-following; few-shot learning; in-context learning.</div>
  <div class="week-product">🔍 Explore: <a href="https://rowflow.ai/">RowFlow</a> (YC S25) — replaces forms with AI conversations</div>
  <div class="week-readings">
    <details><summary>Readings</summary>
    <ul>
      <li><a href="https://www.deeplearning.ai/short-courses/how-transformer-llms-work/">DeepLearning.AI, How Transformer LLMs Work</a> (short course)</li>
      <li><a href="https://docs.anthropic.com/en/docs/build-with-claude/prompt-engineering/overview">Anthropic, Prompt Engineering Overview</a></li>
      <li><a href="https://cookbook.openai.com/examples/gpt-5/gpt-5_prompting_guide">OpenAI, GPT Prompting Guide</a></li>
      <li><a href="https://learnprompting.org/docs/basics/few_shot">Learn Prompting, Shot-Based Prompting</a></li>
    </ul>
    </details>
  </div>
  <div class="week-hw"><strong>Homework:</strong> Use AI tools to build the <strong>first</strong> demo of the LLM application you want to build</div>
</div>

<!-- Week 3 -->
<div class="week-card">
  <div class="week-header">
    <span class="week-title">Week 3 — LLM Basics II</span>
    <span class="week-dates">9/7–9/11 · <em>Labor Day 9/7; no class</em></span>
  </div>
  <div class="week-desc">Retrieval-augmented generation (RAG); embeddings and semantic search; grounding LLM outputs.</div>
  <div class="week-product">🔍 Explore: <a href="https://www.morphik.ai/">Morphik</a> (YC W25) — visual-first RAG with 96% accuracy</div>
  <div class="week-readings">
    <details><summary>Readings</summary>
    <ul>
      <li><a href="https://python.langchain.com/docs/tutorials/rag/">LangChain, Build a RAG Agent</a></li>
      <li><a href="https://ashutosh.dev/the-complete-guide-to-retrieval-augmented-generation-rag-in-2025/">The Complete Guide to RAG in 2025</a></li>
      <li><a href="https://platform.openai.com/docs/guides/embeddings">OpenAI, Embeddings Guide</a></li>
    </ul>
    </details>
  </div>
  <div class="week-hw"><strong>Homework:</strong> Use AI tools to build the <strong>second</strong> demo of the LLM application you want to build</div>
</div>

<!-- Week 4 -->
<div class="week-card">
  <div class="week-header">
    <span class="week-title">Week 4 — LLM Basics III</span>
    <span class="week-dates">9/14–9/18</span>
  </div>
  <div class="week-desc">Orchestration and composing LLM calls; chaining; structured outputs; key patterns for building applications.</div>
  <div class="week-product">🔍 Explore: <a href="https://www.ycombinator.com/companies/paloma">Paloma</a> (YC S25) — AI-native CRM orchestrating LLM chains</div>
  <div class="week-readings">
    <details><summary>Readings</summary>
    <ul>
      <li><a href="https://platform.openai.com/docs/guides/structured-outputs">OpenAI, Structured Outputs</a></li>
      <li><a href="https://platform.openai.com/docs/guides/function-calling">OpenAI, Function Calling</a></li>
      <li><a href="https://langchain-ai.github.io/langgraph/tutorials/workflows/">LangChain, Workflows and Agents</a></li>
      <li><a href="https://www.deepchecks.com/orchestrating-multi-step-llm-chains-best-practices/">Deepchecks, Orchestrating Multi-Step LLM Chains</a></li>
    </ul>
    </details>
  </div>
  <div class="week-hw"><strong>Homework:</strong> Use AI tools to build the <strong>third</strong> demo of the LLM application you want to build</div>
</div>

<!-- Week 5 -->
<div class="week-card week-milestone">
  <div class="week-header">
    <span class="week-title">🎤 Week 5 — Lightweight Demo Day</span>
    <span class="week-dates">9/21–9/25</span>
  </div>
  <div class="week-desc">Students present their demos, review products others built, vote on the most promising ideas, and form teams of 3 for the class project.</div>
</div>

<!-- Week 6 -->
<div class="week-card">
  <div class="week-header">
    <span class="week-title">Week 6 — Agentic Systems and Tool Use</span>
    <span class="week-dates">9/28–10/2</span>
  </div>
  <div class="week-desc">Planning, multi-step reasoning, function calling, and agent frameworks.</div>
  <div class="week-product">🔍 Explore: <a href="https://www.browseruse.com/">Browser Use</a> (YC W25) — open-source web agent, 50k+ GitHub stars</div>
  <div class="week-readings">
    <details><summary>Readings</summary>
    <ul>
      <li><a href="https://www.anthropic.com/research/building-effective-agents">Anthropic, Building Effective Agents</a></li>
      <li><a href="https://www.anthropic.com/engineering/writing-tools-for-agents">Anthropic, Writing Effective Tools for AI Agents</a></li>
      <li><a href="https://lilianweng.github.io/posts/2023-06-23-agent/">Lilian Weng, LLM Powered Autonomous Agents</a></li>
      <li><a href="https://langchain-tutorials.github.io/langgraph-tutorial-2026-beginners-guide/">LangGraph Tutorial: Building AI Agents</a></li>
    </ul>
    </details>
  </div>
  <div class="week-hw"><strong>Homework:</strong> Build application in teams</div>
</div>

<!-- Week 7 -->
<div class="week-card">
  <div class="week-header">
    <span class="week-title">Week 7 — Evaluation and Testing</span>
    <span class="week-dates">10/5–10/9</span>
  </div>
  <div class="week-desc">Automated evals, human evals, LLM-as-judge, regression testing.</div>
  <div class="week-product">🔍 Explore: <a href="https://www.ycombinator.com/companies/confident-ai">Confident AI</a> (YC W25) — LLM eval platform by creators of DeepEval</div>
  <div class="week-readings">
    <details><summary>Readings</summary>
    <ul>
      <li><a href="https://hamel.dev/blog/posts/evals/index.html">Hamel Husain, Your AI Product Needs Evals</a></li>
      <li><a href="https://www.anthropic.com/engineering/demystifying-evals-for-ai-agents">Anthropic, Demystifying Evals for AI Agents</a></li>
      <li><a href="https://evidentlyai.com/llm-guide/llm-as-a-judge">Evidently AI, LLM-as-a-Judge: A Complete Guide</a></li>
    </ul>
    </details>
  </div>
  <div class="week-hw"><strong>Homework:</strong> Build application in teams</div>
</div>

<!-- Week 8 -->
<div class="week-card">
  <div class="week-header">
    <span class="week-title">Week 8 — Multi-Modal Applications</span>
    <span class="week-dates">10/12–10/16</span>
  </div>
  <div class="week-desc">Vision, audio, and video models; integrating multi-modal capabilities into LLM applications; use cases and design patterns.</div>
  <div class="week-product">🔍 Explore: <a href="https://www.ycombinator.com/companies/cardboard">Cardboard</a> (YC W26) — agentic video editor with multi-modal LLMs</div>
  <div class="week-readings">
    <details><summary>Readings</summary>
    <ul>
      <li><a href="https://platform.openai.com/docs/guides/vision">OpenAI, Vision Guide</a></li>
      <li><a href="https://ai.google.dev/gemini-api/docs/vision">Google, Gemini Multi-Modal Capabilities</a></li>
      <li><a href="https://docs.anthropic.com/en/docs/build-with-claude/vision">Anthropic, Vision with Claude</a></li>
    </ul>
    </details>
  </div>
  <div class="week-hw"><strong>Homework:</strong> Build application in teams</div>
</div>

<!-- Week 9 -->
<div class="week-card">
  <div class="week-header">
    <span class="week-title">Week 9 — Safety, Guardrails, and Product Design</span>
    <span class="week-dates">10/19–10/23</span>
  </div>
  <div class="week-desc">Prompt injection, hallucination mitigation, content filtering, error recovery; UX patterns, latency vs quality tradeoffs, human-in-the-loop design.</div>
  <div class="week-product">🔍 Explore: <a href="https://www.ycombinator.com/companies/alter">Alter</a> (YC S25) — zero-trust auth and guardrails for AI agents</div>
  <div class="week-readings">
    <details><summary>Readings</summary>
    <ul>
      <li><a href="https://genai.owasp.org/resource/owasp-top-10-for-llm-applications-2025/">OWASP, Top 10 for LLM Applications 2025</a></li>
      <li><a href="https://simonwillison.net/2025/Jun/16/the-lethal-trifecta/">Simon Willison, The Lethal Trifecta for AI Agents</a></li>
      <li><a href="https://www.promptfoo.dev/docs/red-team/">Promptfoo, Red Teaming LLM Guide</a></li>
      <li><a href="https://pair.withgoogle.com/guidebook/patterns">Google PAIR, People + AI Guidebook</a></li>
      <li><a href="https://www.nngroup.com/articles/designing-ai-study-guide/">Nielsen Norman Group, Designing AI Products and Features</a></li>
    </ul>
    </details>
  </div>
  <div class="week-hw"><strong>Homework:</strong> Build application in teams</div>
</div>

<!-- Week 10 -->
<div class="week-card week-milestone">
  <div class="week-header">
    <span class="week-title">🧪 Week 10 — Demo Day &amp; Beta Test</span>
    <span class="week-dates">10/26–10/30</span>
  </div>
  <div class="week-desc">Teams present their applications and run beta testing with real users.</div>
</div>

<!-- Week 11 -->
<div class="week-card">
  <div class="week-header">
    <span class="week-title">Week 11 — Cost Optimization and Deployment</span>
    <span class="week-dates">11/2–11/6</span>
  </div>
  <div class="week-desc">Caching, model selection, latency optimization, serving infrastructure.</div>
  <div class="week-product">🔍 Explore: <a href="https://www.ycombinator.com/companies/chamber">Chamber</a> (YC W26) — GPU cluster optimization, ~50% more workloads</div>
  <div class="week-readings">
    <details><summary>Readings</summary>
    <ul>
      <li><a href="https://enricopiovano.com/blog/llm-cost-optimization-caching-strategies">LLM Cost Engineering: Token Budgeting, Caching, and Model Routing</a></li>
      <li><a href="https://redis.io/blog/large-language-model-operations-guide/">Redis, LLMOps Guide</a></li>
      <li><a href="https://blog.gopenai.com/optimizing-large-language-model-infrastructure-a-practitioners-guide-to-latency-cost-and-46f9002152bc">Optimizing LLM Infrastructure</a></li>
    </ul>
    </details>
  </div>
  <div class="week-hw"><strong>Homework:</strong> Iterate based on real user feedback</div>
</div>

<!-- Week 12 -->
<div class="week-card">
  <div class="week-header">
    <span class="week-title">Week 12 — Guest Lecture: Founders</span>
    <span class="week-dates">11/9–11/13</span>
  </div>
  <div class="week-desc">Founder perspective on building and shipping AI products.</div>
  <div class="week-product">🔍 Explore: <a href="https://www.ycombinator.com/companies/martini">Martini</a> (YC W26) — AI-native collaborative filmmaking</div>
  <div class="week-hw"><strong>Homework:</strong> Iterate based on real user feedback</div>
</div>

<!-- Week 13 -->
<div class="week-card">
  <div class="week-header">
    <span class="week-title">Week 13 — Guest Lecture: Investors</span>
    <span class="week-dates">11/16–11/20</span>
  </div>
  <div class="week-desc">Investor perspective on evaluating AI startups, moats, and go-to-market.</div>
  <div class="week-product">🔍 Explore: <a href="https://www.ycombinator.com/companies/fenrock-ai-yc-w26">Fenrock AI</a> (YC W26) — AI agents for financial crime compliance</div>
  <div class="week-hw"><strong>Homework:</strong> Iterate based on real user feedback</div>
</div>

<!-- Week 14 -->
<div class="week-card week-break">
  <div class="week-header">
    <span class="week-title">Week 14 — Thanksgiving Break</span>
    <span class="week-dates">11/23–11/27</span>
  </div>
  <div class="week-desc">No classes. Recharge and keep building.</div>
</div>

<!-- Week 15 -->
<div class="week-card">
  <div class="week-header">
    <span class="week-title">Week 15 — Guest Lecture: Researchers</span>
    <span class="week-dates">11/30–12/4</span>
  </div>
  <div class="week-desc">Researcher perspective on frontier AI and what's next.</div>
  <div class="week-product">🔍 Explore: <a href="https://www.ycombinator.com/companies/ritivel">Ritivel</a> (YC W26) — AI agents for FDA submissions</div>
  <div class="week-hw"><strong>Homework:</strong> Iterate based on real user feedback</div>
</div>

<!-- Week 16 -->
<div class="week-card week-milestone">
  <div class="week-header">
    <span class="week-title">🚀 Week 16 — Public Demo Day</span>
    <span class="week-dates">12/7 · <em>Last class day</em></span>
  </div>
  <div class="week-desc">Teams present their final products to the public. Ship it.</div>
</div>

## Grading {#grading}

<div class="grade-bars">
  <div class="grade-bar-row">
    <span class="grade-bar-label">Individual Assignments</span>
    <div class="grade-bar-track"><div class="grade-bar-fill bar-individual">30%</div></div>
  </div>
  <div class="grade-bar-detail">Week 1: four one-pagers · Weeks 2–4: three individual demos</div>
  <div class="grade-bar-row">
    <span class="grade-bar-label">Class Project</span>
    <div class="grade-bar-track"><div class="grade-bar-fill bar-project">60%</div></div>
  </div>
  <div class="grade-bar-detail">Teams of 3 · Demo days (Weeks 5, 10, 16) · Iteration progress (Weeks 11–15)</div>
  <div class="grade-bar-row">
    <span class="grade-bar-label">Peer Review & Participation</span>
    <div class="grade-bar-track"><div class="grade-bar-fill bar-peer">10%</div></div>
  </div>
  <div class="grade-bar-detail">Reviewing demos · Beta testing others' products · Guest speaker engagement</div>
</div>

Plus-minus grading scale: A ≥ 93%, A- ≥ 90%, B+ ≥ 87%, B ≥ 83%, B- ≥ 80%, C+ ≥ 77%, C ≥ 73%, C- ≥ 70%, D+ ≥ 67%, D ≥ 63%, D- ≥ 60%.

## Policies {#policies}

<div class="policy-grid">
  <div class="policy-card">
    <h4>🤖 Academic Integrity & AI Tools</h4>
    <p>This course <em>requires</em> you to use AI tools — ChatGPT, Copilot, Cursor, and whatever else helps you build. Building on the shoulders of AI is a core skill this class teaches.</p>
    <p style="margin-top:8px;">You must be able to explain every piece of your work — how it works, why you made the choices you did, and what the tradeoffs are. If your only answer is "the AI told me to do it," that is not your own work. Cite any substantial external code or resources you incorporate.</p>
  </div>
  <div class="policy-card">
    <h4>♿ Students with Disabilities</h4>
    <p>The University of Texas at Austin provides upon request appropriate academic accommodations for qualified students with disabilities. Contact <a href="https://ddce.utexas.edu/disability/">Services for Students with Disabilities</a>, 512-471-6259.</p>
  </div>
  <div class="policy-card">
    <h4>🙏 Religious Holy Days</h4>
    <p>A student who cannot meet a deadline due to a religious holy day may submit work up to 24 hours late without penalty with at least 14 days' prior notice to the instructor.</p>
  </div>
</div>
