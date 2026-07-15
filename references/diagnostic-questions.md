# Diagnostic Questions and Placement Indicators

Evidence beats self-rating. Every question here asks for something the person *did*, not something they *think they are*. The three strongest signals across all columns:

1. **Recency** — "last week" outranks "a while back".
2. **Frequency** — daily habit outranks one impressive experiment.
3. **Dependence** — does anyone else rely on the thing they made? Nothing separates Fluency from Essentials faster.

Ask one question at a time. Follow the thread the person gives you; these are probes, not a script. When an answer is vague ("I use AI a lot"), ask for the last specific instance before moving on.

## Column 1: Augmentation (personal productivity)

### Opening probes

- "Walk me through the last time AI actually saved you real time on something. What was it?"
- "How does AI show up in a normal workday for you — and how often is that, honestly?"
- "Have you ever set up anything reusable — a custom GPT, a Claude project or skill, a saved prompt you return to?"

### Placement indicators

**Approaching Foundations** — Has tried a chatbot a handful of times; no regular habit; can't name a task where AI is now their default. Common blockers to surface gently: fear of doing it wrong, no obvious use case, unclear whether it's allowed at work.

**Foundations** — Can name which tasks in their own work suit AI and picks a sensible tool for each. Uses AI with guidance or templates; recognizes obviously wrong output. Evidence: a few completed real-work tasks, asks "what else can this do?"

**Essentials** — Produces polished, business-ready artifacts (docs, decks, analyses) using structured prompts and deliberate context (examples, source material, constraints). Uses AI most days without help; adapts outputs rather than accepting them; keeps some form of personal prompt library. Evidence: shows you an artifact they shipped, describes *how* they prompted, not just *that* they prompted.

**Fluency** — Has designed and built a custom assistant or tool integrated into how they work: a custom GPT/Gem/Claude skill, a personal chatbot wired to their stack. Evidence: the thing exists, they can describe design choices (instructions, knowledge, context control), and they iterate on it.

**Native** — AI-first is their default operating mode: work starts with "what do I delegate?", automation and agentic delegation are routine, not events. Evidence: they can describe yesterday in those terms without reaching for examples from months ago.

### Level-boundary probes

- Foundations→Essentials: "Show me (or describe) something you made with AI that you actually sent to a colleague or client. How did you get it to that quality?"
- Essentials→Fluency: "Have you built anything reusable that shapes how the AI behaves every time — not a prompt, a *thing*?"
- Fluency→Native: "If I took AI away tomorrow, what breaks in your personal workflow?" (Native: "most of it." Fluency: "a few tools I'd miss.")

## Column 2: Automation (team processes)

### Opening probes

- "Is there a recurring process — yours or your team's — that now runs with less human effort because of something you set up?"
- "Have you ever mapped out a process step-by-step to figure out what could be automated?"
- "Built anything interactive with a no-code platform, or by vibecoding an app into existence?"

### Placement indicators

**Approaching Foundations** — Feels the pain of repetitive processes but hasn't analyzed them; automation is something other people do.

**Foundations** — Can map an existing process, spot the automation opportunities, and think in conditional logic and error handling ("what happens when the input is malformed?"). Evidence: a process map, or a crisp verbal decomposition of one, with branch points named.

**Essentials** — Has built AI-enabled interactive tools on no-code platforms; takes vibecoding seriously as a way to make real things. Evidence: a working tool others can click through, built without a traditional dev team.

**Fluency** — Creates multi-step workflows with agentic nodes and platform integrations (n8n, Make, Zapier-with-AI and kin). Others use the workflow, and it does more than one hop. Evidence: describes the flow's steps, its failure modes, and who depends on it.

**Native** — Deploys production-grade automation infrastructure: versioning, handoff protocols, the discipline that lets someone else operate what they built. Evidence: talks about version control, documentation, monitoring, and handoff unprompted — production reflexes.

### Level-boundary probes

- Foundations→Essentials: "You mapped it — did you build it? What can I click on?"
- Essentials→Fluency: "What happens when step three fails at 2 am? Who finds out, and how?"
- Fluency→Native: "Could you hand this system to a colleague and go on holiday for a month?"

## Column 3: Agentic (system innovation)

Most people have little evidence here. That is expected and fine — say so, don't drag them through every probe.

### Opening probes

- "Have you worked with AI systems that hold context or memory across sessions — designed, not just used?"
- "Any experience giving an AI agent tools or data access — MCP integrations, custom skills, documented decision logic?"
- "Have you shipped an agentic system other people rely on?"

### Placement indicators

**Approaching Foundations** — Uses agentic products others built; hasn't designed one.

**Foundations** — Applies agentic design principles to architect AI-native solutions: thinks deliberately about context management and memory, can explain *why* an agent needs them. Evidence: a design (even on paper) with context strategy articulated.

**Essentials** — Designs organizational knowledge systems: MCP integrations, custom skills, documented decision logic that encodes how the org decides. Evidence: a working system with more than one component, and documentation that exists because others need it.

**Fluency** — Builds production-ready agentic systems with PRD-driven development, testing protocols, and real deployment. Evidence: a spec that preceded the build, tests that gate changes, users who aren't the builder.

**Native** — Scales agentic systems across teams: governance frameworks, organizational memory architecture. Evidence: multiple teams on systems they designed; can talk about governance decisions they made and what those trade off.

### Level-boundary probes

- Foundations→Essentials: "Is there decision logic written down that the system actually follows — or does it live in your head?"
- Essentials→Fluency: "What did you write *before* you built it, and what has to pass before you ship a change?"
- Fluency→Native: "Who besides your team runs on this — and who decides what agents are allowed to do?"

## Cross-cutting: reading blockers as information

When someone stalls at a level, the blocker is diagnostic. Fear of doing it wrong, no sandbox, unclear governance, no time to experiment, tool access — each points to a different next step (psychological safety, access, policy clarity, protected time). Name the blocker back to the person; often the "skill gap" is actually an environment gap, and that reframe alone is worth the conversation.
