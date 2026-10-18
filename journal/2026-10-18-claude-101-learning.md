<!-- ABOUTME: Learning notes from CCAF Claude 101 course -->
<!-- ABOUTME: Covers practical Claude.ai usage — prompting, features, workflows, and collaboration patterns -->

# Claude 101 — Learning Notes

**Date:** 2026-10-18
**Source:** CCAF - Claude 101 (LinkedIn Learning)
**Format:** Video lessons + notes

---

## 1. Getting Started with Claude.ai

This topic covers the practical onboarding to Claude.ai — the interface, prompt structure, and features that make conversations effective.

### The Core Mental Model

Claude is a collaborator, not a search engine. The best approach is to talk to it like a coworker — naturally, concisely, and conversationally. You bring the context and expertise; Claude brings the AI intelligence.

### Prompt Structure

Before prompting, consider three elements:

| Element | What it means | Key question |
|---------|--------------|--------------|
| **Setting the stage** | Your role, objectives, and context | What should Claude know about your situation? |
| **Defining the task** | The specific action you want | What should Claude do — write, analyze, build? |
| **Specifying rules** | Style, tone, format, examples | What should the output look like? |

This maps directly to the **Description** competency from the 4D Framework (AI Foundations):
- Setting the stage = providing context (Product + Process Description)
- Defining the task = defining the output (Product Description)
- Specifying rules = guiding behavior and format (Performance Description)

### Adding Context

Claude can analyze text and visuals in uploaded files (PDF, DOCX, CSV, TXT, PNG, JPEG). Uploading relevant documents is a shortcut — Claude considers that content in its responses.

Practical uses: summarize documents, analyze images/charts, identify data trends, explain or debug code.

Custom preferences (Settings > General) let you set context that applies to every conversation without re-explaining.

### Iteration is the Real Workflow

Conversations are meant to be iterative — chaining bite-sized prompts, not crafting one perfect request.

When Claude's response isn't right:
- **Ask follow-ups** — build on what Claude gave you
- **Provide feedback** — say what worked and what didn't
- **Redirect or restart** — steer back or start fresh

This reinforces the **Description-Discernment loop** from AI Foundations: describe, evaluate, refine, integrate.

### Personalization Features

Two Claude.ai features that reduce the Description burden over time:

- **Memory** — automatically saves key context (role, preferences, decisions, working style) across conversations. Reviewable and editable in Settings.
- **Styles** — customize how Claude communicates (concise, formal, explanatory, or custom). Applies across all conversations.

### Connection to AI Foundations

The prompt framework here is explicitly adapted from the 4D Framework. Claude 101 is the practical application of what AI Foundations taught as theory — same principles, now applied to a specific tool.

---

## 2. Getting Better Results: Common Challenges and How to Fix Them

This topic covers the most common friction points when working with Claude and how to address them. Each challenge maps back to a gap in Description or Discernment.

| Challenge | What's happening | Fix |
|-----------|-----------------|-----|
| **Response is too generic** | Prompt lacked context about your specific situation | Add details — audience, role, constraints. Instead of "Write an email about the project delay," try "Write an email to our enterprise client explaining the software integration will be delayed by two weeks. They've been patient so far but this is the second delay. Keep it professional but apologetic." |
| **Response is too long (or too short)** | Claude is guessing at appropriate length | Be explicit: "Give me a two-paragraph summary" or "Keep this under 100 words" or "I need a comprehensive analysis — length isn't a concern." |
| **Claude didn't follow my format** | Claude understood what you want but not how you want it presented | Show, don't just tell. Provide an example of the format, or describe the structure explicitly: "Use bullet points with bold headers for each section." |
| **Confident-sounding but wrong information** | Claude occasionally generates plausible but incorrect information, especially with specific facts or niche topics | For high-stakes work, verify key facts independently. Ask Claude to cite sources or indicate confidence level. Enable web search to ground responses in current information. |
| **The tone isn't right** | Claude defaults to helpful and professional, which may not match your needs | Describe the tone in plain language: "Make this more conversational" or "This should sound authoritative and formal." Provide an example of writing in the style you want. |

### The Pattern

Every challenge in this list traces back to the same root cause: the human didn't describe something explicitly enough, and Claude filled in the gap with its best guess. The fix is always more specific Description — context, length, format, tone, or verification expectations.

The one exception is hallucination (confident-sounding wrong information). That's not a Description fix — that's **Discernment**. You need to evaluate the output, not just refine the input. This is exactly what AI Foundations warned about: don't blindly accept AI output, especially on specific facts and niche topics.

---

## 3. The Iteration Mindset

The core shift: your first prompt is the start of a conversation, not a one-shot request. A first draft that isn't perfect is normal and expected.

### What Effective Claude Users Do

- **Treat first drafts as starting points** — review, identify what works and what doesn't, then refine
- **Give specific feedback** — "Make it shorter" is fine, but "Cut the first two paragraphs and make the conclusion more action-oriented" is better
- **Know when to start fresh** — if a conversation has gone off track, sometimes a new chat with a clearer prompt is faster than redirecting

### The 4D Framework Resurfaces

The course explicitly revisits the 4D Framework here, connecting it to everything taught so far:

- The prompt framework from Topic 1 (setting the stage, defining the task, specifying rules) = **Description**
- The troubleshooting techniques from Topic 2 = **Discernment** and **Diligence**
- Deciding what to hand to Claude vs. what to own yourself = **Delegation**

The 4D Framework isn't a separate course concept — it's the operating system underneath everything in Claude 101.

### Evaluating Claude for Your Workflows (Evals)

**Discernment** applied systematically. Evals are how you build intuition for what Claude is good at *in your specific context*. Claude might excel at one type of task but need heavy guidance for another.

**Why evals matter:**
- Understand where Claude adds the most value in *your* workflow
- Identify tasks that need more context or examples
- Build confidence in Claude's outputs for recurring tasks

**Simple eval approach:**
1. **Gather examples** — collect 5-10 examples of a task you do regularly (emails, reports, analyses)
2. **Create test prompts** — write prompts that would generate similar outputs, with natural context
3. **Compare outputs** — run the prompts and evaluate:
   - Does Claude capture the key information?
   - Is the tone and style appropriate?
   - What's missing or could be improved?
4. **Refine your approach** — adjust prompts, add examples, or identify where human review is essential

### Practical Example: Data Analysis Eval

The course walks through a concrete eval using data analysis:
1. Find a dataset you've already manually analyzed
2. Prompt Claude to do the same analysis
3. Compare Claude's results to your originals
4. Note patterns — maybe Claude gets the right numbers but misses the overall patterns
5. Refine your prompts accordingly

This is Discernment in action: you already know the right answer, so you can objectively measure where Claude adds value and where it falls short.

### Connection to Real Experience

This eval concept is what was missing from my earlier AI workflow. I was using AI on complex tasks without ever systematically checking whether it was actually good at those specific tasks in my domain. I was skipping Discernment entirely — not just on individual outputs, but on the fundamental question of whether AI was the right tool for that particular job (which is also a Delegation question).

### Lesson Reflection

- The common challenges from Topic 2 are all things I've hit — especially generic responses (I wasn't providing enough context about my complex architecture) and blindly trusting confident-sounding output.
- Evals would be valuable for the recurring analysis work in my day job — systematically testing whether AI handles it well rather than assuming.
- The 4D Framework ties everything together: Delegate the right tasks, Describe them well, Discern the output critically, and maintain Diligence throughout.

---

## 4. Navigating the Claude Desktop App: Chat, Cowork, Code

The Claude desktop app provides three distinct modes, each designed around the type of work it serves. Cowork and Code both run on Claude Code underneath — local to your machine, capable of independent work, subagents, and sustained tasks.

### Chat — Conversational AI

The same Claude from claude.ai, enhanced by running natively on your computer.

**Optimized for:** Quick exchanges — exploring ideas, iterative drafting, quick answers, learning through dialogue.

**Desktop-specific features:**
- **Quick entry** — double-tap Option to pull up Claude over any app (Mac)
- **Screenshots and window sharing** — show Claude what you're looking at instead of describing it (Mac)
- **Dictation** — talk through problems instead of typing (Mac)
- **Desktop connectors** — connect local tools and services

**Tools and extensions:** Connectors, Skills, Claude in Chrome.

### Cowork — Agentic Work

Built for work that takes real effort: multi-source research, analysis, and producing finished deliverables. Claude has the scope to draw from more sources and the stamina to see things through.

**Optimized for:** Complex or sustained work — research, analysis, file organization, producing finished documents and deliverables.

**Key capabilities:**
- **Folder access** — reads from and saves back to local folders
- **Scheduled tasks** — recurring work on a schedule (daily briefings, weekly roundups, morning triage)
- **Subagents** — spins up background workers to handle subtasks in parallel
- **Dispatch** — continue Cowork conversations from your phone via the mobile app
- **Projects** — group related tasks into workspaces with their own files, context, instructions, and memory
- **Browser use** — Claude navigates websites in Chrome, interacts with pages, pulls data directly into the task
- **Computer use** — navigates your computer directly when no connector or plugin exists (research preview, Mac only)
- **Plugins** — add capabilities like live financial data, internal knowledge base search, compliance frameworks
- **Protected environment** — runs in a contained space; can only access folders you share

**Tools and extensions:** Connectors (local and remote), Skills, Claude in Chrome, Plugins, Computer Use.

**Priority order for actions:** Connectors first, then Chrome, then screen interaction — always picks the fastest, most reliable path.

### Code — Software Development

Full development environment powered by Claude Code, running directly in the desktop app.

**Optimized for:** Building software — writing, testing, running, and deploying code.

**Key capabilities:**
- Works directly in your codebase — reads, writes, modifies code, runs commands
- Visual diffs show what changed
- Built-in terminal shows commands as they run
- Git tracks every version for rollback
- **Local or Remote** environments (remote uses GitHub repos in the cloud, sessions persist even if app closes)

**Three interaction modes:**
| Mode | Behavior |
|------|----------|
| **Ask** | Claude proposes every change, waits for approval via visual diff |
| **Code** | Claude applies file changes automatically, checks before terminal commands |
| **Plan** | Claude outlines full approach first; dedicated plan viewer for review |

**Tools and extensions:** Connectors, Skills, Claude in Chrome, Plugins, Hooks.

**Key difference from Cowork:** Code runs directly in your project with full access to file system, terminal, and dev tools. Cowork runs in a contained workspace limited to shared folders.

### Comparison Summary

| | Chat | Cowork | Code |
|---|---|---|---|
| **Optimized for** | Quick exchanges, dialogue | Complex research, finished deliverables | Building software |
| **Key features** | Quick entry, dictation | Local folders, plugins, subagents, scheduled tasks | Ask/Code/Plan modes, visual diffs, git, local + remote |
| **Tools** | Connectors, Skills, Chrome | Connectors, Skills, Chrome, Plugins, Computer Use | Connectors, Skills, Chrome, Plugins, Hooks |

### Connection to the 4D Framework

This topic maps directly to **Delegation** — specifically **Platform Awareness**. Knowing which mode to use for which task is a Delegation decision. You're not just deciding "should I use AI?" — you're deciding "which *form* of AI collaboration fits this work?"

- Quick question about a concept? Chat.
- Need to research across 10 sources and produce a brief? Cowork.
- Need to build or modify software? Code.

Choosing wrong doesn't mean failure, but it means friction — like using a screwdriver when you need a drill. The tool works, but it's not optimized for the job.

---

## 5. Introduction to Projects

Projects are self-contained workspaces in Claude.ai — each with its own memory, chat histories, knowledge base, and customized instructions. Think of them as dedicated environments for specific work streams.

### When to Use Projects

Projects make sense when work is **ongoing**, not one-off:
- Reference materials you'll use repeatedly
- Consistent requirements for how Claude should respond
- Team collaboration where multiple people need the same context

### Setting Up a Project

**Step 1: Create the project** — descriptive name, brief description, visibility settings (private or shared for Claude for Work users).

**Step 2: Add project instructions** — tell Claude how to behave across all conversations in this project:
- Context about the work
- Process instructions (e.g., "First consider blog structure, then write the draft")
- Tone and style preferences
- Specific requirements (e.g., "Always include a call-to-action")

Instructions can also automate workflows: "When I upload a meeting transcript, create a structured summary using this template."

**Step 3: Build the knowledge base** — upload documents Claude should reference (PDFs, DOCX, CSV, TXT, HTML, Google Drive links).

Best practice: name files descriptively. Claude uses filenames to understand and retrieve the right information. "Q4-2024-Brand-Guidelines.pdf" beats "document1.pdf."

### How Projects Handle Scale (RAG)

When the knowledge base approaches context limits, Claude automatically enables **Retrieval Augmented Generation (RAG)** — instead of loading all content into memory, it intelligently searches and retrieves only the most relevant information. This expands capacity by up to 10x while maintaining quality.

A visual indicator appears when RAG is active, but the experience feels the same.

### Collaboration (Claude for Work)

Three permission levels:
| Level | Access |
|-------|--------|
| **Can view** | See contents, access knowledge, chat — but can't modify |
| **Can edit** | Full collaboration — modify instructions, update knowledge, manage members |
| **Owner** | Full control including sharing and visibility |

### Best Practices

- **Start focused, then expand** — one specific use case per project, not everything in one place
- **Keep knowledge current** — outdated documents produce outdated responses
- **Write clear instructions** — vague instructions lead to inconsistent results
- **Name documents descriptively** and group related files together
- **Reference documents by name** in conversations to help Claude focus its search

### Connection to the 4D Framework

Projects are the **infrastructure for Description**. Instead of re-describing your context, role, and preferences every conversation, you set it once and it persists. This is what the Personalization features (Memory, Styles) do at the user level — Projects do it at the work-stream level.

Projects also support **Delegation** — by organizing different work streams into separate projects, you're making deliberate decisions about what context Claude needs for each type of task. This prevents the "everything in one conversation" problem that leads to context pollution and generic responses.

---

## 6. Creating with Artifacts

Artifacts are standalone, interactive outputs that Claude creates in a dedicated window alongside the conversation. Instead of content buried in chat, you get rendered, usable output — a working website, an interactive chart, or a downloadable document.

### When Claude Creates Artifacts

Claude automatically creates an artifact when content:
- Is significant and self-contained (typically 15+ lines)
- Is something you'd want to edit, iterate on, or reuse
- Represents complex content that stands on its own
- Is content you'll want to reference later

If Claude doesn't create an artifact automatically, you can ask: "Create this as an artifact" or "Show me this in an artifact."

### Artifact Types

| Type | Use cases |
|------|-----------|
| **Documents** (markdown/plain text) | Meeting notes, reports, project plans, blog posts |
| **Code snippets** | Working code in any language — view, copy, or download |
| **HTML pages** | Complete web pages (HTML/CSS/JS) — landing pages, forms, prototypes |
| **SVG images** | Logos, icons, illustrations — rendered directly in the artifact window |
| **Mermaid diagrams** | Flowcharts, sequence diagrams, Gantt charts, org charts |
| **React components** | Interactive UI with real logic — calculators, dashboards, games, data visualizations |

**Note:** Word docs, Excel spreadsheets, PowerPoint, and PDFs are created through a separate file creation capability, not as artifacts — they come back as downloadable files.

### Working with Artifacts

When generated, artifacts appear in a dedicated window to the right of the conversation:
- **Preview vs. code** — toggle between how it looks and the underlying code
- **Copy** — grab content for use elsewhere
- **Download** — save as a file
- **View code** — see exactly what Claude generated

### Sharing and Publishing

- **Copy/download** — for personal use or sharing via other channels
- **Share within organization** (Claude for Work) — stays internal, requires team authentication
- **Publish publicly** (Free, Pro, Max) — accessible to anyone with the link, no Claude account needed
  - Only the selected version becomes public (chat stays private)
  - Others can "remix" — open it in their own Claude conversation to modify
  - Not indexed by search engines
  - Can unpublish at any time

### Best Practices

- **Be specific** — "Build a monthly budget tracker with expense categories, pie chart breakdown, and over-budget warnings" beats "Build a budget tracker"
- **Describe the end user** — helps Claude make appropriate design choices
- **Iterate incrementally** — one feature or change at a time
- **Request artifacts when needed** — ask explicitly if Claude responds in chat instead

### Connection to the 4D Framework

Artifacts shift the collaboration from "Claude gives me text" to "Claude builds me something usable." This is a **Delegation** evolution — you're not just delegating writing or analysis, you're delegating creation of functional tools and visual outputs.

The Description skills matter even more here: the more precisely you describe what you want (audience, features, format, behavior), the closer the first artifact is to what you need. And Discernment applies to evaluating whether the artifact actually works as intended — not just whether it reads well, but whether it functions correctly.

**Key distinction:** Artifacts range from **finished outputs** (SVGs, diagrams, markdown docs — usable as-is) to **starting points** (HTML pages, React components — get you 70-80% there, then you refine in a real codebase). The line is blurry — depends on the use case, not the type.

---

## 7. Working with Skills

Skills are folders of instructions, scripts, and resources that Claude loads dynamically to perform specialized tasks. Think of them as expertise packages — they teach Claude how to complete specific tasks in a repeatable way.

**Plan availability:** Feature preview for Pro, Max, Team, and Enterprise plans.

### How Skills Work

Skills run behind the scenes. When you ask Claude to create an Excel spreadsheet or a PowerPoint, that's a Skill executing. You don't need to invoke them explicitly — Claude selects the right Skill based on your request.

### Two Types of Skills

| Type | What it is | Examples |
|------|-----------|----------|
| **Anthropic Skills** | Created and maintained by Anthropic. Available to all paid users, invoked automatically. | Excel, Word, PowerPoint, PDF file creation |
| **Custom Skills** | Created by you or your organization for specialized workflows. | Brand guideline enforcement, meeting note templates, data analysis workflows, compliance checklists |

### What Makes Skills Powerful

Skills go beyond document creation. Custom Skills can codify **entire repeatable workflows** — a quarterly variance analysis methodology, a brand voice review process, a compliance checklist — so Claude follows the same rigorous steps every time.

This is the difference between:
- "Help me analyze this quarter's variance" (Claude improvises an approach each time)
- A Skill that enforces: gather data, apply specific formulas, compare against thresholds, flag outliers, format report to template (same rigorous process every time)

### Requirements

- Code execution and file creation must be enabled (Settings > Capabilities)
- Skills run in Claude's secure sandboxed computing environment
- Enterprise: Owners must enable in Admin settings first
- Team: enabled by default at org level

### Connection to the 4D Framework

Skills are **codified Description**. Instead of re-describing a complex workflow every time, you package it once as a Skill and Claude follows it consistently. This is the same principle as Project Instructions but at a deeper level — Project Instructions guide tone and context, Skills guide entire methodologies.

This also has a **Delegation** angle: by creating a Skill, you're making a deliberate decision about which parts of a process AI should own and exactly how it should execute them. You're encoding your expertise into a repeatable system.

---

## 8. File Execution and Custom Skills

### File Execution

Claude can work directly with actual files — slides, spreadsheets, contracts (.xlsx, .pptx, .docx, .pdf). Upload them and Claude creates updated versions: building slides, performing analyses, adding suggested edits. Download the results or open them in Drive.

In Chat mode, Claude creates a **new version** rather than editing the original in place.

Requires "Allow limited network access" toggle — this lets Claude install packages and libraries for advanced data analysis, custom visualizations, and specialized file processing.

### Security Considerations for Skills

- Only install custom Skills from trusted sources
- Anthropic's built-in Skills are tested and maintained by Anthropic
- Custom Skills you upload are private to your individual account
- Review external Skills before installing — they can include executable code

### Creating Custom Skills

The easiest way: **have a conversation with Claude about it.** No code writing needed.

1. **Start a chat** — tell Claude what you want ("I want a skill for writing quarterly business reviews")
2. **Answer Claude's questions** — it interviews you about the workflow, what good output looks like, when you'd use it
3. **Upload reference materials** — templates, style guides, brand assets, examples of good work
4. **Save the skill** — Claude generates the properly structured skill file
5. **Find your skills** — Customize tab in the left sidebar; edit manually or by chatting with Claude

Once saved, Claude **automatically invokes** the skill when you work on relevant tasks. Improve through iteration — ask Claude to edit and it updates the files.

### Skills vs. Projects — The Key Distinction

**Projects store knowledge. Skills perform tasks.**

| | Projects | Skills |
|---|---|---|
| **Purpose** | Store knowledge Claude references | Define processes Claude executes |
| **Best for** | Long-term context, reference materials, team collaboration | Repeatable workflows, multi-step tasks, consistent methodology |
| **Example** | Customer hub, research buddy, feedback generator | Process guidelines (brand/legal), blog drafting, PDF creation |
| **Persistence** | Knowledge available across all chats in the project | Instructions applied when the skill is invoked |

They complement each other: a Skill can reference knowledge stored in a Project. The Project provides the **what** (information), the Skill provides the **how** (process).

### Connection to What We're Doing Right Now

This distinction maps exactly to how we work in Claude Code:
- Our **memory files and journal entries** = Project knowledge (the what)
- Our **CLAUDE.md rules and workflows** = Skills (the how)

The concepts are the same. The surface is different.

---

## 9. Connecting Your Tools (Connectors)

Connectors transform Claude from an assistant into an informed collaborator by giving it access to the same tools, data, and context you use every day. Instead of starting from scratch, Claude works directly with your actual information.

### What Connectors Do

Depending on the connector and permissions granted, Claude can:
- Search files and retrieve documents
- Analyze data and create new content
- Update records and execute tasks across connected apps
- Both **read information** and **perform actions** on your behalf

### MCP — The Universal Standard

Connectors are powered by the **Model Context Protocol (MCP)** — think of it like USB-C for AI. A universal standard that lets Claude connect to many different applications through one consistent interface. Open standard, so developers can build connectors for any tool.

### Two Types of Connectors

| Type | Where it runs | Examples |
|------|--------------|----------|
| **Web connectors** | Cloud services via claude.ai | Google Drive, Notion, Slack, Asana, Linear, Stripe, Gmail |
| **Desktop extensions** | Locally via Claude Desktop app | Local file access, browser control, native app integration (Figma, etc.) |

### Setting Up Web Connectors

1. Find the connector at claude.ai/directory or via + > Connectors in chat
2. Click Connect and authenticate with the service's login
3. Review and grant specific permissions
4. Test with a simple request ("Can you access my [tool name]?")

### Practical Usage Examples

- **Project management** (Asana, Linear, Jira) — "What are my highest priority tasks due this week?"
- **Communication** (Slack, Gmail) — "Find the email thread about the vendor contract"
- **Documentation** (Notion, Drive, Confluence) — "Search our docs for brand voice guidelines"
- **Business tools** (Stripe, Salesforce) — "Show me revenue trends for the past quarter"

### Security and Permissions

- **Scoped access** — permissions are specific to what the connector needs; individual permissions can be toggled
- **Claude sees what you see** — connecting your email doesn't give Claude access to anyone else's inbox
- **Revocable at any time** — disconnect through Claude's settings or the third-party service's security settings
- Same caution as Skills: only install connectors from trusted sources

### Connection to the 4D Framework

Connectors are a **Delegation multiplier**. Without connectors, you're the bottleneck — copying data from Slack, pasting into Claude, copying results back. With connectors, Claude reaches into your tools directly, which changes what you can realistically delegate.

But this also raises the **Diligence** bar. More access means more responsibility — scoping permissions thoughtfully, understanding what Claude can see and modify, and being deliberate about what you connect. The ease of connection doesn't reduce the need for oversight.

MCP is also worth noting as a concept beyond Claude — it's an open standard, meaning the same connector architecture works across AI tools. Another reason AI Fluency matters more than tool-specific knowledge.

---

## 10. Enterprise Search

**Plan availability:** Team and Enterprise plans only, must be enabled by a workspace admin.

### What It Is

A dedicated "Ask {Your Org Name}" option in the sidebar — a pre-built Project for the entire organization. The company's knowledge base is already loaded across connected tools (SharePoint, Slack, Gmail, Google Drive, etc.). Claude searches across all connected sources and synthesizes information into a unified response with cited sources.

Unlike regular chats with connectors, Enterprise Search is specifically designed for **information gathering** using custom instructions configured by Anthropic.

### Common Use Cases

- **Getting up to speed** — "What happened yesterday while I was out?"
- **Policy and process** — "What is our remote work policy?" / "How do I submit an expense report?"
- **Research and analysis** — "What are the main reasons customers cite for choosing competitors?"
- **Onboarding** — "How does our authentication system work?" / "Who should I talk to about the billing system?"
- **Project tracking** — "What were the key decisions from last week's leadership meetings?"

### Security

- Only shows what you already have permission to access in the original tools
- Conversations remain private
- Connected data isn't indexed or stored separately

### Connection to the Learning Path

Enterprise Search is essentially **Connectors + Projects at organizational scale**. It combines the knowledge-base concept (Projects) with the tool-access concept (Connectors) and wraps it in a ready-to-use package for the whole org. This is the pattern: individual features compose into larger capabilities.

---

## 11. Research Mode for Deep Dives

Research transforms Claude from a conversational assistant into a systematic investigator. Instead of a single search, Claude operates **agentically** — conducting multiple searches that build on each other, determining what to investigate next, exploring different angles automatically.

### How Research Works

1. **Plans its approach** — extended thinking activates automatically; Claude breaks down the request, identifies what information it needs, plans investigation angles
2. **Conducts multiple searches** — not one search but many, building on each other; pursues leads and fills gaps autonomously
3. **Synthesizes findings** — compiles information from web + connected integrations into a comprehensive, organized report
4. **Provides citations** — every claim links back to its source for verification

Most reports complete in **5-15 minutes**, complex ones up to 45 minutes — replacing hours of manual research.

### When to Use Research vs. Other Capabilities

| Need | Use |
|------|-----|
| Comprehensive multi-source reports with citations | **Research** |
| Quick specific fact (stock price, address) | **Web Search** |
| Deep reasoning without external info (math, code, logic) | **Extended Thinking** |
| Answers from internal org knowledge (policies, past decisions) | **Enterprise Search** |

### Research Use Cases

- Market analysis and competitive research
- Complex project planning (offsites, product launches)
- Synthesizing information across email, calendar, and documents
- Technical documentation from multiple sources
- Briefings requiring current, verified information

### Effective Research Prompts

- **Be specific about goals** — "Analyze the EV battery market — key players, technology trends, supply chain challenges affecting investment" beats "Tell me about the EV market"
- **Specify structure** — tell Claude what sections you want in the report
- **Include constraints** — budget, timelines, geography to focus the research
- **Ask Claude to help refine the prompt** — before enabling Research, have Claude help you frame the question

### Research + Connected Integrations

When connected to tools like Google Workspace, Research pulls context from emails, calendar, and docs alongside web research. Can also turn off web search for **internal-only research** across connected tools.

### Connection to the 4D Framework

Research is where **Delegation** reaches its fullest expression so far in this course. You're not delegating a single task — you're delegating an entire investigation process. Claude plans, searches, evaluates, and synthesizes autonomously.

But this also means **Discernment** becomes critical at the output level. You're not reviewing one response — you're reviewing a comprehensive report. The citations help, but the judgment about whether the synthesis is sound, the right angles were explored, and no important perspective was missed — that's still yours.

This maps to the AI Fluency principle: the more you delegate, the more your Discernment skills matter. Power and responsibility scale together.

---

## 12. Other Ways to Work with Claude: Claude Code

Claude is an intelligence. Claude.ai is just one way of working with it. Claude Code is another — an agentic coding tool that works where you work: terminal, IDE, browser, or Slack.

### What Claude Code Does

- Understands your codebase, executes commands, handles entire development workflows through natural language
- **Build features** — describe what you need in plain English; Claude writes code, runs tests, creates commits
- **Debug issues** — paste error messages; Claude analyzes the codebase to identify and fix problems
- **Navigate unfamiliar codebases** — ask questions about how different parts work together
- **Automate tedious tasks** — fix lint errors, resolve merge conflicts, write release notes
- Works alongside your existing IDE and dev tools — no context switching

### Connection to Real Experience

This is what we're using right now. Every topic in this course has been documented, committed, and organized through Claude Code. The learning notes, the memory system, the git workflow — all happening in the terminal.

The course positions Claude Code as "another way to work with Claude," but for a developer it's arguably the most natural way. It meets you in the environment you already live in.

### Where Claude Code Sits in the Three Modes

From Topic 4: Chat is for conversation, Cowork is for complex research and deliverables, Code is for building software. Claude Code (terminal) is the engine underneath the Code tab in the desktop app. Same power, different surface.

---

## 13. Claude in Action: Use Cases by Role

A reference-style topic linking practical use cases organized by role, each with detailed guides in Anthropic's Use Case Gallery.

### Use Cases by Role

| Role | Key use cases |
|------|--------------|
| **General professional** | Project status reports, user feedback analysis, brand guideline skills |
| **Sales** | Battle card libraries, deal preparation, sales reports |
| **Marketing** | Campaign performance analysis, cross-platform content adaptation |
| **Finance** | Financial models, investment memos, inherited spreadsheet analysis |
| **HR** | New hire onboarding guides |
| **Legal** | Discovery timeline tracking, pattern analysis in legal documents |
| **Research** | Literature review planning, statistical verification from raw data |

### What This Means

This topic is less about new concepts and more about seeing the **breadth of Delegation possibilities**. Every role has recurring tasks that fit the AI collaboration model. The 4D Framework applies universally — only the domain context changes.

For someone working across multiple roles or functions (like a consultant), the value multiplies — you're not locked into one use-case category.

---

## 14. Other Ways to Work with Claude: @Claude and Claude Design

### @Claude (Slack Integration)

Brings Claude directly into Slack — tag @Claude in any thread to get help without leaving the conversation.

**Use cases:**
- Draft responses, summarize threads, break down complex discussions
- Prepare for meetings by pulling together relevant conversations and shared docs
- Onboard to a new team by reviewing channel history
- Hand off coding tasks from bug reports or feature discussions — Claude can spin up a Code session from Slack context
- Quick answers on industry trends, technical concepts, or company info mid-conversation

### Claude Design

A dedicated space for turning ideas into working interfaces. Describe what you want in plain language — or start from a sketch/screenshot — and Claude builds an interactive prototype you can refine through conversation.

**Use cases:**
- Go from a brief, sketch, or screenshot to a working UI prototype without code
- Explore design directions — generate and compare variations quickly
- Iterate on layout, copy, or interactions by describing changes
- Build prototypes using your team's design system so handoff matches what engineering builds

### The Bigger Picture

The course keeps expanding the surface area of where Claude lives:

1. **claude.ai** — web chat (Topics 1-3)
2. **Desktop app** — Chat, Cowork, Code (Topic 4)
3. **Projects, Artifacts, Skills** — persistent context and outputs (Topics 5-8)
4. **Connectors, Enterprise Search, Research** — reaching into external data (Topics 9-11)
5. **Claude Code** — terminal/IDE (Topic 12)
6. **@Claude** — inside Slack (this topic)
7. **Claude Design** — UI prototyping (this topic)

The intelligence is the same. The surfaces multiply. This is why **AI Fluency matters more than tool-specific knowledge** — the 4D Framework applies identically whether you're in claude.ai, Slack, a terminal, or a design tool.

---

## 15. Claude for Microsoft 365: Excel, PowerPoint, Word, and Outlook

Claude integrates directly into Microsoft 365 apps as a sidebar — bringing AI collaboration into the tools where work already happens.

### Claude for Excel
- Analyze, understand, and modify spreadsheets through conversation
- Understand formula flows across multi-tab workbooks
- Update assumptions while preserving formula dependencies
- Debug errors (#REF!, #VALUE!, circular references) — Claude traces to source and suggests fixes
- Create spreadsheets, populate templates, build pivot tables and charts

### Claude for PowerPoint
- Draft, edit, and restructure presentations through conversation
- Turn outlines/notes into first-draft slide decks
- Rewrite slide copy, add speaker notes, adjust tone
- Restructure decks — reorder, split dense slides, merge overlapping ones
- Apply consistent formatting across the deck
- Suggest layouts and chart types for specific points

### Claude for Word
- Draft, revise, and restructure documents in the sidebar
- Turn outlines into structured first drafts in your team's template
- Revise sections — tighten writing, adjust tone, rework structure
- Respond to tracked changes and reviewer comments in place
- Ground drafts in connected source material with traceability

### Claude for Outlook (Beta)
- Triage mail, draft replies with context from related threads and calendar
- Turn long email chains into clear summaries or next steps
- Installed separately from other Microsoft 365 add-ins

### The Pattern

Same story as the rest of this course: Claude meets you where you work. The sidebar pattern across Excel, PowerPoint, Word, and Outlook means you don't context-switch to a separate AI tool — the collaboration happens inside the document you're already editing.

Each integration is a different **Delegation surface** for the same intelligence. The 4D skills (describe clearly, evaluate critically, delegate thoughtfully, stay responsible) apply identically in every one.

---

## 16. Claude in Chrome

A browser extension that adds Claude as a sidebar in Google Chrome. It can observe what you're working on and take actions directly within the browser.

**Use cases:**
- Summarize articles, research papers, or web pages while browsing
- Draft email responses and manage inbox
- Automate filling out repetitive forms
- Test website features or navigate multi-step workflows
- Maintain context as you move between tabs — useful for pulling context from internal tools, CRMs, and dashboards

**Important:** Currently in public beta. Recommended for low-risk tasks on trusted websites. Asks permission before high-risk actions (purchasing, sharing personal data). Financial services and adult content sites blocked by default.

**Diligence note:** The permission model here is a practical example of Deployment Diligence — the tool has built-in guardrails (blocked categories, permission prompts for high-risk actions), but the user still needs to exercise judgment about when and where to use it.

---

## 17. Summary: All the Ways to Work with Claude

The full landscape of Claude's surfaces:

| Tool | Best for | Where it runs |
|------|----------|---------------|
| **Claude.ai** | General tasks, research, writing, analysis, file creation | Web, desktop, and mobile apps |
| **Claude Code** | Software development, codebase navigation, git workflows | Terminal/command line, IDE, or browser |
| **Claude Cowork** | Complex multi-step tasks: research briefs, document creation, file organization, data analysis | Desktop (and mobile via Dispatch) |
| **@Claude** | Team collaboration, meeting prep, quick answers in context | Slack workspace |
| **Claude Design** | UI prototypes, design exploration, design-system-aware mockups | Web |
| **Claude for Microsoft 365** | Editing in place and carrying context across documents | Excel, PowerPoint, Word, and Outlook sidebars |
| **Claude in Chrome** | Web research, email management, browser automation | Chrome browser sidebar |

### The Takeaway

One intelligence, many surfaces. The course started with "Claude is an intelligence, claude.ai is just one way of working with it" — and this table is the proof. Each surface is optimized for a specific context, but the underlying capabilities (and the 4D skills needed to use them well) are the same everywhere.

---

## 18. Course Wrap-Up: What's Next

### What Claude 101 Covered

The course built understanding in four layers:

**Layer 1 — Getting Started (Topics 1-3):** How to prompt effectively, common challenges and fixes, the iteration mindset. All rooted in the 4D Framework from AI Foundations.

**Layer 2 — Organizing Your Work (Topics 4-8):** Desktop app modes (Chat/Cowork/Code), Projects for persistent context, Artifacts for standalone outputs, Skills for repeatable workflows. The infrastructure for sustained AI collaboration.

**Layer 3 — Expanding Reach (Topics 9-11):** Connectors for tool access, Enterprise Search for org knowledge, Research mode for deep investigations. Claude goes from answering questions to actively gathering and synthesizing information.

**Layer 4 — Claude Everywhere (Topics 12-17):** Claude Code, @Claude in Slack, Claude Design, Microsoft 365 sidebars, Chrome extension. One intelligence across every surface where work happens.

### Key Principles Reinforced Throughout

- Claude is a **collaborator**, not a replacement — best results come from combining your expertise with AI capabilities
- **AI Fluency (4D Framework)** is the operating system underneath everything — Delegation, Description, Discernment, Diligence
- **Iteration** is the workflow — first responses are starting points, not final answers
- The **skills are tool-agnostic** — they apply whether you're in claude.ai, a terminal, Slack, or Excel
- **Start simple**, pick one recurring task, try it, iterate, build from there
