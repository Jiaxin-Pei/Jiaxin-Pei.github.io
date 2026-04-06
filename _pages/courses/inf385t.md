---
permalink: /courses/inf385t/
excerpt: "INF 385T - Building Large Language Model Applications"
author_profile: false
---

<style>
.page {
  float: none;
  width: 100%;
  margin-left: auto;
  margin-right: auto;
  padding-left: 0;
  padding-right: 0;
}
.page__inner-wrap {
  max-width: 100%;
}
.course-layout {
  max-width: 1220px;
  margin: 0 auto;
}
.course-page-toc {
  margin: 1.5em auto;
  max-width: 860px;
  background: #fff;
  border: 1px solid #e6e6e6;
  border-radius: 8px;
  box-shadow: 0 2px 12px rgba(0,0,0,0.06);
}
.course-page-toc-title {
  margin: 0;
  padding: 0.75rem 1rem;
  font-size: 0.85rem;
  font-weight: 700;
  letter-spacing: 0.08em;
  text-transform: uppercase;
  color: #fff;
  background: #bf5700;
  border-radius: 8px 8px 0 0;
}
.course-page-toc-list,
.course-page-toc-sublist {
  list-style: none;
  margin: 0;
  padding: 0;
}
.course-page-toc-link {
  display: block;
  padding: 0.6rem 1rem;
  color: #555;
  text-decoration: none;
  border-top: 1px solid #e6e6e6;
  line-height: 1.4;
}
.course-page-toc-link:hover {
  background: #f8f8f8;
  color: #111;
}
.course-page-toc-sublist .course-page-toc-link {
  padding-left: 1.75rem;
  font-size: 0.92em;
}
.course-main {
  max-width: 860px;
  margin: 0 auto;
}
details {
  margin: 4px 0;
}
details summary {
  cursor: pointer;
  font-size: 0.95em;
  color: #555;
}
details summary:hover {
  color: #111;
}
details ul {
  margin-top: 6px;
  padding-left: 1.2em;
}
details li {
  margin-bottom: 3px;
}
@media (min-width: 1024px) {
  .course-layout {
    display: grid;
    grid-template-columns: 270px minmax(0, 860px);
    gap: 2rem;
    justify-content: center;
    align-items: start;
  }
  .course-page-toc {
    position: sticky;
    top: 2rem;
    margin: 0;
    max-width: none;
  }
  .course-main {
    width: min(860px, 100%);
  }
}
</style>
<div style="text-align: center;" markdown="1">
<span style="font-size: 1.6em; font-weight: bold;">INF 385T (Building) Large Language Model Applications</span>

"Build an AI Product in 15 weeks and submit to Y Combinator"

The University of Texas at Austin, Fall 2026  
**M 9:00 a.m.–12:00 p.m. · UTA 1.208**  
[Jiaxin Pei](https://jiaxin-pei.github.io/), jiaxinpei@utexas.edu  

[Syllabus](#syllabus) • [Schedule](#schedule) • Project • Canvas

<p style="margin: 1.25em 0 0;">
  <a href="https://forms.gle/ELXDCPe4AuWyaH2E9" rel="noopener noreferrer" style="display: inline-block; background: #bf5700; color: #fff !important; padding: 0.65em 1.75em; border-radius: 8px; font-weight: 600; text-decoration: none; box-shadow: 0 1px 3px rgba(0,0,0,0.15);">Apply for enrollment</a>
</p>

</div>

<div class="course-layout">
<aside class="course-page-toc">
  <nav aria-label="Course table of contents">
    <h2 class="course-page-toc-title">On This Page</h2>
    <ul class="course-page-toc-list">
      <li><a class="course-page-toc-link" href="#class-philosophy">Class Philosophy</a></li>
      <li><a class="course-page-toc-link" href="#syllabus">Syllabus</a></li>
      <li><a class="course-page-toc-link" href="#prerequisites">Prerequisites</a></li>
      <li><a class="course-page-toc-link" href="#course-materials">Course materials</a></li>
      <li><a class="course-page-toc-link" href="#course-overview-and-objectives">Course overview and objectives</a></li>
      <li>
        <a class="course-page-toc-link" href="#schedule">Schedule</a>
        <ul class="course-page-toc-sublist">
          <li><a class="course-page-toc-link" href="#week-1">Week 1: The AI application landscape</a></li>
          <li><a class="course-page-toc-link" href="#week-2">Week 2: Coding agents</a></li>
          <li><a class="course-page-toc-link" href="#week-3">Week 3: Labor Day week</a></li>
          <li><a class="course-page-toc-link" href="#week-4">Week 4: Personal agents &amp; the agentic web</a></li>
          <li><a class="course-page-toc-link" href="#week-5">Week 5: Lightweight demo day</a></li>
          <li><a class="course-page-toc-link" href="#week-6">Week 6: AI for vertical domains</a></li>
          <li><a class="course-page-toc-link" href="#week-7">Week 7: Evaluation, testing &amp; red-teaming</a></li>
          <li><a class="course-page-toc-link" href="#week-8">Week 8: Generative engine optimization &amp; AI-native distribution</a></li>
          <li><a class="course-page-toc-link" href="#week-9">Week 9: Safety, guardrails, and product design</a></li>
          <li><a class="course-page-toc-link" href="#week-10">Week 10: Demo day &amp; beta test</a></li>
          <li><a class="course-page-toc-link" href="#week-11">Week 11: Multi-modal applications &amp; world models</a></li>
          <li><a class="course-page-toc-link" href="#week-12">Week 12: Cost optimization and deployment</a></li>
          <li><a class="course-page-toc-link" href="#week-13">Week 13: AI economics, moats, and go-to-market</a></li>
          <li><a class="course-page-toc-link" href="#week-14">Week 14: Thanksgiving break</a></li>
          <li><a class="course-page-toc-link" href="#week-15">Week 15: Final guest lecture &amp; pitch practice</a></li>
          <li><a class="course-page-toc-link" href="#week-16">Week 16: Public demo day</a></li>
        </ul>
      </li>
    </ul>
  </nav>
</aside>

<div class="course-main" markdown="1">

## Class Philosophy {#class-philosophy}

This is not a lecture-and-exam course. It is a **builder course**. You will spend the semester designing, building, and shipping a real AI product—one good enough to put in front of real users.

We cover LLM fundamentals not as an end in themselves, but as tools you need to build something great. The best way to learn what LLMs can and cannot do is to push them to their limits on a problem you care about.

We welcome students with diverse backgrounds—science, engineering, design, business—as long as you are strongly motivated to build something great. **We especially welcome PhD students from all areas** who want to apply LLMs to their own research domains. The strongest teams combine people who can code, people who can design experiences, and people who have deep understanding of a specific domain.

We hold ourselves and our students to the highest standard. This course is fast-paced and demanding—expect to invest serious time and energy every week. But if you are passionate about building with AI and ready to put in the work, you will leave with a product you are proud of, skills that transfer directly to industry, a portfolio piece that speaks for itself—and, ultimately, an opportunity that changes your life.

The semester culminates in a public demo day with investors from top venture capital firms. Standout teams will have fast-track access to leading accelerator programs to continue building beyond the classroom.

<div style="background: #f0f0f0; padding: 14px 18px; margin: 1.5em 0;">
<strong>Interested in sponsoring or collaborating?</strong><br>
We welcome partnerships with investors, accelerators, and industry sponsors who want to connect with the next generation of AI builders. Reach out at <a href="mailto:jiaxinpei@utexas.edu">jiaxinpei@utexas.edu</a>.
</div>

## Syllabus {#syllabus}

### Prerequisites {#prerequisites}

Comfortable writing Python applications, using APIs, and working in a terminal. Prior experience with machine learning or natural language processing is also required.

### Course materials {#course-materials}

* Readings and resources will be provided via hyperlinks under Schedule.
* Exercises, code, etc. will be posted on Canvas.

### Course overview and objectives {#course-overview-and-objectives}

This course explores the design and development of practical applications powered by large language models (LLMs), with an emphasis on frontier application categories such as coding agents, personal agents, vertical AI, AI-native distribution, and multi-modal systems. Core technical concepts such as prompting, retrieval-augmented generation, embeddings, structured outputs, orchestration, safety, and evaluation are taught in the context of building products rather than as isolated abstractions, with additional technical foundations provided as a Canvas reference page. The course is project-driven: students rapidly prototype individual demos, form teams around the strongest ideas, and then build, test, and pitch an LLM-based application with guidance from founders, investors, and researchers.

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

@media (max-width: 768px) {
  .course-timeline {
    font-size: 0.68em;
  }
  .course-timeline .phase {
    padding: 10px 4px;
  }
  .course-timeline .phase-icon {
    font-size: 1.3em;
    margin-bottom: 3px;
  }
  .course-timeline .phase-title {
    font-size: 0.78em;
  }
  .course-timeline .phase-weeks {
    font-size: 0.68em;
  }
  .course-timeline .phase-desc {
    display: none;
  }
}

@media (max-width: 480px) {
  .course-timeline {
    font-size: 0.58em;
  }
  .course-timeline .phase {
    padding: 8px 2px;
  }
  .course-timeline .phase-icon {
    font-size: 1.1em;
    margin-bottom: 2px;
  }
  .course-timeline .phase-title {
    font-size: 0.72em;
  }
  .course-timeline .phase-weeks {
    font-size: 0.62em;
  }
}
</style>

<div class="course-timeline">
  <div class="phase phase-ideate">
    <div class="phase-icon">💡</div>
    <div class="phase-title">Landscape</div>
    <div class="phase-weeks">Week 1</div>
    <div class="phase-desc">Survey frontier AI products and opportunities</div>
  </div>
  <div class="phase phase-basics">
    <div class="phase-icon">🧱</div>
    <div class="phase-title">Ideate &amp; Build</div>
    <div class="phase-weeks">Weeks 2–4</div>
    <div class="phase-desc">Coding agents, personal agents, 3 demos</div>
  </div>
  <div class="phase phase-demo1">
    <div class="phase-icon">🎤</div>
    <div class="phase-title">Lightweight Demo Day</div>
    <div class="phase-weeks">Week 5</div>
    <div class="phase-desc">Present, vote, form teams</div>
  </div>
  <div class="phase phase-build">
    <div class="phase-icon">🔨</div>
    <div class="phase-title">Team Build</div>
    <div class="phase-weeks">Weeks 6–9</div>
    <div class="phase-desc">Vertical AI, evals, GEO, safety</div>
  </div>
  <div class="phase phase-beta">
    <div class="phase-icon">🧪</div>
    <div class="phase-title">Beta Test</div>
    <div class="phase-weeks">Week 10</div>
    <div class="phase-desc">Demo &amp; real user testing</div>
  </div>
  <div class="phase phase-iterate">
    <div class="phase-icon">🔄</div>
    <div class="phase-title">Iterate &amp; Ship</div>
    <div class="phase-weeks">Weeks 11–15</div>
    <div class="phase-desc">Multi-modal, costs, moats, pitch practice</div>
  </div>
  <div class="phase phase-launch">
    <div class="phase-icon">🚀</div>
    <div class="phase-title">Public Demo Day</div>
    <div class="phase-weeks">Week 16</div>
    <div class="phase-desc">Pitch to investors</div>
  </div>
</div>

**Schedule is tentative and subject to change.** Guest speakers are distributed throughout the semester rather than concentrated in standalone guest-lecture weeks.

### Week 1 (8/24–8/28) – The AI application landscape {#week-1}

* Course introduction. Rapid-fire tour of frontier application areas: coding agents, personal agents, vertical AI, generative engine optimization, agentic web, and world models. The goal is to help students see what exists, who is building it, and where ambitious project ideas may come from.
* Guest speaker: [TBD] (30 min)
* <details><summary>Readings</summary><ul>
    <li><a href="https://www.ycombinator.com/rfs">Y Combinator, Requests for Startups (RFS)</a></li>
    <li><a href="https://www.ycombinator.com/techno-industrialist">Y Combinator, Techno-Industrialist</a></li>
    <li><a href="https://a16z.com/newsletter/big-ideas-2026-part-1/">a16z, Big Ideas 2026 (Part 1)</a></li>
    <li><a href="https://a16z.com/geo-over-seo/">a16z, GEO over SEO</a></li>
    <li><a href="https://greylock.com/idea-map/">Greylock, Idea Map</a></li>
    <li><a href="https://www.bvp.com/atlas">Bessemer Venture Partners, Atlas</a></li>
    <li><a href="https://sequoiacap.com/article/ai-in-2025/">Sequoia, AI in 2025</a></li>
    <li><a href="https://www.nfx.com/post/generative-ai-tech-market-map">NFX, Generative AI Tech Market Map</a></li>
    </ul></details>
* **Homework:** Write four one-pagers: (1) a cool AI startup product that you tried, and (2–4) three AI applications you want to build

### Week 2 (8/31–9/4) – Coding agents {#week-2}

* How AI coding agents work, from autocomplete to autonomous multi-file editing. Architecture of Cursor, Claude Code, Devin, and Windsurf. Agentic loops, tool use, function calling, structured outputs, and MCP basics. This is also a practical skills week: students will use coding agents to build all their demos.
* Product to explore: Cursor or Claude Code (hands-on in class)
* Guest speaker: [TBD] (30 min)
* <details><summary>Readings</summary><ul>
    <li><a href="https://www.anthropic.com/research/building-effective-agents">Anthropic, Building Effective Agents</a></li>
    <li><a href="https://www.anthropic.com/engineering/writing-tools-for-agents">Anthropic, Writing Effective Tools for AI Agents</a></li>
    <li><a href="https://platform.openai.com/docs/guides/function-calling">OpenAI, Function Calling</a></li>
    <li><a href="https://platform.openai.com/docs/guides/structured-outputs">OpenAI, Structured Outputs</a></li>
    <li><a href="https://www.lennysnewsletter.com/p/the-rise-of-cursor-michael-truell">Lenny's Newsletter, The Rise of Cursor — Michael Truell</a></li>
    <li><a href="https://fortune.com/2026/03/21/cursor-ceo-michael-truell-ai-coding-claude-anthropic-venture-capital/">Fortune, Cursor's Crossroads</a></li>
    </ul></details>
* **Homework:** Use a coding agent to build the **first** demo of the LLM application you want to build

### Week 3 (9/7–9/11) – Labor Day week {#week-3}

* Labor Day 9/7; no class.
* Product to explore: [TBD]
* **Homework:** Use a coding agent to build the **second** demo of the LLM application you want to build

### Week 4 (9/14–9/18) – Personal agents & the agentic web {#week-4}

* Agents that operate on your behalf: browsing the web, managing email, booking travel, and filling forms. Key technical concepts are taught through this lens, including multi-step planning, error recovery, permission models, RAG for context retrieval, embeddings for memory, MCP as the "USB-C for AI," and multi-agent orchestration patterns.
* Product to explore: Claude Cowork / Computer Use (hands-on)
* Guest speaker: [TBD] (30 min)
* <details><summary>Readings</summary><ul>
    <li><a href="https://platform.claude.com/docs/en/agents-and-tools/tool-use/computer-use-tool">Anthropic, Computer Use Tool Documentation</a></li>
    <li><a href="https://www.anthropic.com/news/model-context-protocol">Anthropic, Introducing the Model Context Protocol</a></li>
    <li><a href="https://www.anthropic.com/engineering/code-execution-with-mcp">Anthropic, Code Execution with MCP</a></li>
    <li><a href="https://docs.anthropic.com/en/docs/mcp">Model Context Protocol Documentation</a></li>
    <li><a href="https://lilianweng.github.io/posts/2023-06-23-agent/">Lilian Weng, LLM Powered Autonomous Agents</a></li>
    <li><a href="https://langchain-ai.github.io/langgraph/tutorials/workflows/">LangChain, Workflows and Agents</a></li>
    </ul></details>
* **Homework:** Use a coding agent to build the **third** demo of the LLM application you want to build

### Week 5 (9/21–9/25) – Lightweight demo day {#week-5}

* Students present their demos, review products others built, vote on the most promising ideas, and form teams for the class project.

### Week 6 (9/28–10/2) – AI for vertical domains: law, finance, healthcare {#week-6}

* How LLM applications win in specific industries. Deep dive into products such as Harvey, Abridge, and Ramp. We will examine domain expertise, enterprise sales, compliance, trust-building with professional users, and why the "wrapper" framing missed what makes vertical AI defensible.
* Product to explore: Harvey or a legal/healthcare AI tool
* Guest speaker: [TBD] (30 min)
* <details><summary>Readings</summary><ul>
    <li><a href="https://sequoiacap.com/podcast/training-data-winston-weinberg/">Sequoia, Training Data: Harvey's Winston Weinberg</a></li>
    <li><a href="https://techcrunch.com/2025/11/14/inside-harvey-how-a-first-year-legal-associate-built-one-of-silicon-valleys-hottest-startups/">TechCrunch, Inside Harvey</a></li>
    <li><a href="https://www.hbs.edu/faculty/Pages/item.aspx?num=67121">Harvard Business School, Harvey: AI for Lawyers (case study)</a></li>
    <li><a href="https://sequoiacap.com/article/ai-retail-opportunity/">Sequoia, AI Retail Opportunity</a></li>
    </ul></details>
* **Homework:** Build application in teams

### Week 7 (10/5–10/9) – Evaluation, testing & red-teaming {#week-7}

* Automated evals, human evals, LLM-as-judge, and regression testing, reframed for the agentic era: evaluating multi-step autonomous systems rather than only single-turn chatbots. We will also cover prompt injection via observed content, tool misuse, and cascading failures in multi-agent systems.
* Product to explore: Promptfoo or Braintrust (eval tooling)
* Guest speaker: [TBD] (30 min)
* <details><summary>Readings</summary><ul>
    <li><a href="https://hamel.dev/blog/posts/evals/index.html">Hamel Husain, Your AI Product Needs Evals</a></li>
    <li><a href="https://www.anthropic.com/engineering/demystifying-evals-for-ai-agents">Anthropic, Demystifying Evals for AI Agents</a></li>
    <li><a href="https://evidentlyai.com/llm-guide/llm-as-a-judge">Evidently AI, LLM-as-a-Judge: A Complete Guide</a></li>
    <li><a href="https://simonwillison.net/2025/Jun/16/the-lethal-trifecta/">Simon Willison, The Lethal Trifecta for AI Agents</a></li>
    <li><a href="https://genai.owasp.org/resource/owasp-top-10-for-llm-applications-2025/">OWASP, Top 10 for LLM Applications 2025</a></li>
    </ul></details>
* **Homework:** Build application in teams. Set up evals for your project

### Week 8 (10/12–10/16) – Generative engine optimization & AI-native distribution {#week-8}

* How users discover products when AI mediates information. GEO, optimizing to get cited by ChatGPT, Perplexity, and Google AI Overviews, is increasingly replacing classic SEO. We will cover reference rates, click-through behavior, and practical tactics for AI-native go-to-market.
* Product to explore: Perplexity (study how it cites sources)
* Guest speaker: [TBD] (30 min)
* <details><summary>Readings</summary><ul>
    <li><a href="https://a16z.com/geo-over-seo/">a16z, GEO over SEO</a></li>
    <li><a href="https://arxiv.org/pdf/2311.09735">Princeton et al., GEO: Generative Engine Optimization</a></li>
    <li><a href="https://searchengineland.com/what-is-generative-engine-optimization-geo-444418">Search Engine Land, Generative Engine Optimization: How to Win AI Mentions</a></li>
    <li><a href="https://www.frase.io/blog/what-is-generative-engine-optimization-geo">Frase.io, What is GEO? 2026 Guide</a></li>
    </ul></details>
* **Homework:** Build application in teams

### Week 9 (10/19–10/23) – Safety, guardrails, and product design {#week-9}

* Prompt injection, hallucination mitigation, content filtering, error recovery; UX patterns, latency vs quality tradeoffs, human-in-the-loop design.
* Product to explore: [TBD]
* Guest speaker: [TBD] (30 min)
* <details><summary>Readings</summary><ul>
    <li><a href="https://genai.owasp.org/resource/owasp-top-10-for-llm-applications-2025/">OWASP, Top 10 for LLM Applications 2025</a></li>
    <li><a href="https://www.promptfoo.dev/docs/red-team/">Promptfoo, Red Teaming LLM Guide</a></li>
    <li><a href="https://pair.withgoogle.com/guidebook/patterns">Google PAIR, People + AI Guidebook</a></li>
    <li><a href="https://www.nngroup.com/articles/designing-ai-study-guide/">Nielsen Norman Group, Designing AI Products and Features</a></li>
    </ul></details>
* **Homework:** Build application in teams. Red-team another team's product

### Week 10 (10/26–10/30) – Demo day & beta test {#week-10}

* Teams present their applications and run beta testing with real users.

### Week 11 (11/2–11/6) – Multi-modal applications & world models {#week-11}

* Vision, audio, and video models; integrating multi-modal capabilities into products. We then zoom out to frontier research: why some researchers are betting against pure LLMs, what world models are, and how they connect to robotics, simulation, and physical reasoning.
* Product to explore: [TBD — a multi-modal product like ElevenLabs, Sora, or Runway]
* Guest speaker: [TBD] (30 min)
* <details><summary>Readings</summary><ul>
    <li><a href="https://platform.openai.com/docs/guides/vision">OpenAI, Vision Guide</a></li>
    <li><a href="https://ai.google.dev/gemini-api/docs/vision">Google, Gemini Multi-Modal Capabilities</a></li>
    <li><a href="https://docs.anthropic.com/en/docs/build-with-claude/vision">Anthropic, Vision with Claude</a></li>
    <li><a href="https://tech-insider.org/yann-lecun-ami-labs-1-billion-world-models-2026/">Tech Insider, LeCun's AMI Labs Raises $1B for World Models</a></li>
    <li><a href="https://blog.bytebytego.com/p/whats-next-in-ai-five-trends-to-watch">ByteByteGo, What's Next in AI: Five Trends to Watch in 2026</a></li>
    </ul></details>
* **Homework:** Iterate based on real user feedback

### Week 12 (11/9–11/13) – Cost optimization and deployment {#week-12}

* Caching, model selection and routing, latency optimization, serving infrastructure, and the economics of running an LLM application. We will focus on token budgeting, model sizing, and when smaller models are sufficient.
* Product to explore: [TBD]
* Guest speaker: [TBD] (30 min)
* <details><summary>Readings</summary><ul>
    <li><a href="https://enricopiovano.com/blog/llm-cost-optimization-caching-strategies">Enrico Piovano, LLM Cost Engineering: Token Budgeting, Caching, and Model Routing</a></li>
    <li><a href="https://redis.io/blog/large-language-model-operations-guide/">Redis, LLMOps Guide: Build Fast, Cost-Effective LLM Apps</a></li>
    <li><a href="https://blog.gopenai.com/optimizing-large-language-model-infrastructure-a-practitioners-guide-to-latency-cost-and-46f9002152bc">GoPenAI, Optimizing LLM Infrastructure: Latency, Cost, and Quality Trade-offs</a></li>
    </ul></details>
* **Homework:** Iterate based on real user feedback

### Week 13 (11/16–11/20) – AI economics, moats, and go-to-market {#week-13}

* What makes an LLM application defensible when models keep getting better and cheaper? We will cover data flywheels, workflow lock-in, vertical vs. horizontal strategy, pricing, and how to pitch to investors. Students will also draft a YC application for their project.
* Product to explore: [TBD]
* Guest speaker: [TBD] (30 min)
* <details><summary>Readings</summary><ul>
    <li><a href="https://sequoiacap.com/podcast/training-data-winston-weinberg/">Sequoia, Training Data: Harvey's Winston Weinberg</a></li>
    <li><a href="https://www.lennysnewsletter.com/p/the-rise-of-cursor-michael-truell">Lenny's Newsletter, The Rise of Cursor — Michael Truell</a></li>
    <li><a href="https://www.ycombinator.com/howtoapply">Y Combinator, How to Apply to YC</a></li>
    </ul></details>
* **Homework:** Iterate based on real user feedback. Draft a YC application for your project

### Week 14 (11/23–11/27) – Thanksgiving break {#week-14}

* No classes.

### Week 15 (11/30–12/4) – Final guest lecture & pitch practice {#week-15}

* Final guest lecture from a researcher or founder on what is next, followed by in-class pitch practice and feedback.
* Guest speaker: [TBD] (30 min)
* **Homework:** Final iteration. Polish demo day presentation

### Week 16 (12/7) – Public demo day {#week-16}

* Last class day.

### Technical foundations (Canvas reference page) {: .no_toc }

These materials are not lectured as standalone units, but are available for students to consult as needed while building.

* **How LLMs work**
  * <a href="https://www.deeplearning.ai/short-courses/how-transformer-llms-work/">DeepLearning.AI, How Transformer LLMs Work</a>
* **Prompting**
  * <a href="https://docs.anthropic.com/en/docs/build-with-claude/prompt-engineering/overview">Anthropic, Prompt Engineering Overview</a>
  * <a href="https://cookbook.openai.com/examples/gpt-5/gpt-5_prompting_guide">OpenAI, GPT Prompting Guide</a>
  * <a href="https://learnprompting.org/docs/basics/few_shot">Learn Prompting, Shot-Based Prompting</a>
* **RAG and embeddings**
  * <a href="https://python.langchain.com/docs/tutorials/rag/">LangChain, Build a RAG Agent</a>
  * <a href="https://ashutosh.dev/the-complete-guide-to-retrieval-augmented-generation-rag-in-2025/">Ashutosh, The Complete Guide to RAG in 2025</a>
  * <a href="https://platform.openai.com/docs/guides/embeddings">OpenAI, Embeddings Guide</a>
* **Agent frameworks**
  * <a href="https://langchain-tutorials.github.io/langgraph-tutorial-2026-beginners-guide/">LangGraph Tutorial: Building AI Agents</a>
  * <a href="https://anthropic.skilljar.com/introduction-to-model-context-protocol">Anthropic, Introduction to MCP (Course)</a>
  * <a href="https://anthropic.skilljar.com/model-context-protocol-advanced-topics">Anthropic, MCP Advanced Topics (Course)</a>


### Course requirements and grading policy {: .no_toc }

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

### Academic integrity and AI tools {: .no_toc }

This course *requires* you to use AI tools — ChatGPT, Copilot, Cursor, and whatever else helps you build. Building on the shoulders of AI is a core skill this class teaches.

That said, using AI tools does not remove your responsibility to understand what you submit. You must be able to explain every piece of your work — how it works, why you made the choices you did, and what the tradeoffs are. If your only answer is "the AI told me to do it," that is not your own work.

You are encouraged to discuss ideas with classmates, consult external resources, and use open-source code. However, you must cite any substantial external code or resources you incorporate. For individual assignments, the work you submit must reflect your own understanding. For team projects, all team members are expected to contribute meaningfully and be able to speak to the full scope of the project.

### Notice about students with disabilities {: .no_toc }

The University of Texas at Austin provides upon request appropriate academic accommodations for qualified students with disabilities. Please contact the [Division of Diversity and Community Engagement, Services for Students with Disabilities](https://ddce.utexas.edu/disability/), 512-471-6259.

### Notice about missed work due to religious holy days {: .no_toc }

A student who cannot meet an assignment deadline due to the observance of a religious holy day may submit the assignment up to 24 hours late without penalty, if proper notice of the planned absence has been given. Notice must be given at least 14 days prior to the due date. For religious holy days that fall within the first 2 weeks of the semester, notice should be given on the first day of the semester. Notice should be emailed to the instructor and course staff.


</div>
</div>
