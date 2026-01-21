# Module 5: Sub-Agents & Parallel Work - Interactive Lesson

Welcome to Module 5! You've mastered commands and automation. Now let's multiply your capabilities with AI sub-agents.

This interactive lesson will take about 30-35 minutes.

STOP: Have you watched the Module 5 video?

USER: Yes / Ready

---

## What Are Sub-Agents?

So far, you've been working with me - Claude, your general assistant.

But what if you could have:
- A **Product Designer** to evaluate UX and design decisions
- A **Trainer Lead** who understands member experience on the gym floor
- An **Executive** who thinks about business metrics and ROI

All working at the same time, each bringing their unique perspective?

That's sub-agents. Different AI personalities with specialized expertise.

STOP: Ready to build your team?

USER: Yes / Ready

---

## Meet Your Team

Let me show you who's already on your team.

ACTION: List files in .claude/agents/

You have three pre-configured agents. Let's meet them.

ACTION: Read .claude/agents/trainer-lead.md and introduce them briefly

ACTION: Read .claude/agents/product-designer.md and introduce them briefly

ACTION: Read .claude/agents/exec.md and introduce them briefly

Each has different expertise, priorities, and ways of thinking.

STOP: Which agent do you think will have the strongest opinions about the app UX issues?

USER: Response (likely Product Designer)

---

## Task 1: Get Multiple Perspectives

Let's test this. You need to make a decision about the FitRewards app redesign.

The question: **Should FitHub simplify the points system or add more earning opportunities?**

Let's ask all three agents at once.

**Ask me: "Get perspectives from the trainer lead, product designer, and exec on whether to simplify the points system or add more earning opportunities."**

STOP: Go ahead.

USER: Asks for multiple perspectives

ACTION: Invoke all three sub-agents with the question, each responding from their unique perspective:
- Trainer Lead: Focuses on member behavior, gym floor experience, trainer feedback
- Product Designer: Focuses on UX, app complexity, user testing
- Exec: Focuses on business metrics, ROI, retention impact

Done! Here's what each agent said:

**Trainer Lead's Perspective:**
[Present their view]

**Product Designer's Perspective:**
[Present their view]

**Exec's Perspective:**
[Present their view]

Notice how different their priorities are?

STOP: Which perspective do you find most compelling?

USER: Response

---

## Task 2: Agent-Specific Deep Dives

Now let's have each agent do deep analysis in their domain.

**Ask the Product Designer: "Analyze all app-related complaints in the customer feedback files. What are the UX issues and how would you fix them?"**

STOP: Go ahead.

USER: Asks product designer question

ACTION: Invoke product-designer agent to:
- Read all customer feedback files
- Extract UX and app-related complaints
- Analyze patterns from a design perspective
- Propose specific UX improvements
- Create analysis/ux-recommendations.md

Here's what the Product Designer found:

[Present UX analysis with design thinking lens]

That's the designer's expertise at work. Now let's ask the Trainer Lead something in their domain.

**Ask the Trainer Lead: "Based on member feedback and old campaigns, what do trainers need to better promote FitRewards on the gym floor?"**

STOP: Your turn.

USER: Asks trainer lead question

ACTION: Invoke trainer-lead agent to:
- Analyze feedback about trainer interactions
- Review campaign materials
- Identify trainer needs and barriers
- Create recommendations from ground-level perspective
- Create organized/trainer-enablement-plan.md

Here's the Trainer Lead's perspective:

[Present trainer-focused analysis]

See how different their lens is? Same data, completely different insights.

STOP: Would you have thought of these trainer needs on your own?

USER: Response

---

## Task 3: Executive Business Case

Now let's use the Exec agent for strategic work.

**Ask the Exec: "Create a business case for investing in FitRewards improvements vs. shutting down the program. Include ROI analysis, risk assessment, and recommendation."**

STOP: Go ahead.

USER: Asks exec question

ACTION: Invoke exec agent to:
- Analyze current metrics
- Project improvement scenarios
- Calculate ROI on potential investments
- Assess risks of shutdown vs. investment
- Create analysis/fitrewards-business-case.md

Here's the Executive's business case:

[Present business-focused analysis with numbers, projections, ROI]

That's executive-level thinking. Numbers, risks, clear recommendation.

STOP: Does this business case feel ready for leadership?

USER: Response

---

## Task 4: Parallel Analysis

Here's where it gets powerful. Let's run all three agents on the same question simultaneously.

**Ask me: "Have the trainer lead, product designer, and exec each analyze the 'Fitness Personality Quiz' concept from the previous manager's notes. Should we pursue it? Each agent should evaluate from their perspective and create a recommendation."**

This is parallel work - three analyses running at once.

STOP: Ready to see parallel processing?

USER: Confirms

USER: Asks the question

ACTION: Invoke all three agents simultaneously, each analyzing the Fitness Personality Quiz from their unique angle:
- Trainer Lead: Member engagement, gym floor applicability, trainer involvement
- Product Designer: UX flow, gamification, app integration
- Exec: Cost, ROI, competitive differentiation

Done! Let me show you what each agent concluded.

**Trainer Lead:**
[Their analysis and recommendation]

**Product Designer:**
[Their analysis and recommendation]

**Exec:**
[Their analysis and recommendation]

Three perspectives, three different priorities, all valuable.

STOP: Do they agree or disagree?

USER: Response

[If they disagree:]
This is the value of multiple perspectives. Now you make the informed decision.

[If they agree:]
When all three align, that's a strong signal to act.

---

## Task 5: Agent Debate

Let's try something advanced. We'll have agents debate each other.

**Ask me: "Have the product designer and exec debate whether FitHub should invest in a major app overhaul or make incremental improvements. Each should make their case and respond to the other's points."**

STOP: Ready for some AI debate?

USER: Confirms and asks

ACTION: Create a structured debate:
- Product Designer makes opening argument for major overhaul
- Exec makes opening argument for incremental improvements
- Product Designer responds to Exec's points
- Exec responds to Product Designer's points
- Present both sides clearly

Here's the debate:

[Present structured back-and-forth]

**Product Designer's Case:**
[Opening argument and responses]

**Exec's Case:**
[Opening argument and responses]

This is like having your team in a strategy meeting.

STOP: Who won the debate?

USER: Response

---

## Creating Your Own Agent

Now you're going to create a custom agent.

Think about FitHub Wellness. What perspective is missing?

Some ideas:
- Marketing Specialist (campaign effectiveness, brand messaging)
- Data Analyst (numbers, trends, statistical insights)
- Member Advocate (pure member perspective)
- Tech Lead (app architecture, technical feasibility)

**Pick a role and ask me: "Create a new agent called [role] with expertise in [domain]. They should focus on [key priorities] when analyzing FitHub challenges."**

STOP: What agent would you find useful? Design it and ask me to create it.

USER: Describes custom agent

ACTION: Create .claude/agents/[agent-name].md with:
- Role and expertise
- Key priorities and perspective
- How they approach problems
- Types of questions they excel at

Created! Let me show you.

ACTION: Read the new agent file

Now let's test your new agent.

**Ask your new agent a question relevant to their expertise about FitHub.**

STOP: Give your agent something to analyze.

USER: Asks new agent a question

ACTION: Invoke the custom agent and generate response from their unique perspective

[Present agent's response]

How'd they do?

STOP: Does this agent add value to your team?

USER: Response

---

## Orchestrating Multiple Agents

Final advanced technique: Agent orchestration.

This is when you coordinate multiple agents on a complex project.

**Ask me: "I need to create a comprehensive FitRewards improvement plan. Have the trainer lead identify gym floor opportunities, the product designer create UX improvements, the exec build a budget and timeline, and then synthesize all three into one implementation plan."**

This is project management with AI agents.

STOP: Ready for full orchestration?

USER: Confirms and asks

ACTION:
1. Invoke trainer-lead for gym floor opportunities → create output
2. Invoke product-designer for UX improvements → create output
3. Invoke exec for budget and timeline → create output
4. Synthesize all three into organized/comprehensive-improvement-plan.md

Done! Let me show you the comprehensive plan.

ACTION: Read comprehensive-improvement-plan.md

This is agent orchestration - dividing a complex project among specialists, then synthesizing their work.

STOP: Can you imagine using this for real projects?

USER: Response

---

## Practice: Your Own Multi-Agent Project

Now you try. Choose a complex question about FitHub and orchestrate multiple agents to answer it.

Some ideas:
- Create a 90-day turnaround plan (use all agents)
- Design a new member onboarding experience
- Evaluate whether to expand to a new market
- Build a crisis communication plan for low engagement

**Pick a complex challenge, decide which agents should work on it, and orchestrate them to create a comprehensive deliverable.**

STOP: What challenge do you want to tackle? Design the multi-agent approach.

USER: Describes project and agent assignments

ACTION: Orchestrate agents as requested, create comprehensive output

[Present results]

Excellent orchestration!

STOP: How does this multi-agent output compare to single-perspective analysis?

USER: Response

---

## Managing Agent Perspectives

Let's talk about when to use which agent.

**Use single agent when:**
- Question is clearly in their domain
- You need deep expertise
- Speed matters

**Use multiple agents when:**
- Decision has multiple stakeholders
- You need diverse perspectives
- Risk of blind spots

**Use agent orchestration when:**
- Project is complex and multi-faceted
- Different deliverables needed
- Building comprehensive plans

STOP: Make sense?

USER: Confirms

---

## Reflection: From Solo to Team

Think about your workflow evolution:

**Module 1-3:** You + Claude analyzing files

**Module 4:** You + Claude + custom commands

**Module 5:** You orchestrating a team of specialized AI agents

You've gone from single-player to team manager.

STOP: How does having specialist agents change your approach to complex problems?

USER: Response

[Acknowledge]

That's the power of sub-agents. Specialized expertise on demand.

---

## Module 5 Complete! ✅

You've completed Module 5. Here's what you can now do:

✅ Work with multiple specialized AI agents
✅ Get diverse perspectives on decisions
✅ Run parallel analysis with different agents
✅ Create custom agents for specific domains
✅ Orchestrate multi-agent projects
✅ Synthesize multiple agent outputs
✅ Choose appropriate agents for different tasks

**What you created:**
- Multiple agent-specific analysis documents
- UX recommendations from Product Designer
- Trainer enablement plan from Trainer Lead
- Business case from Exec
- Your custom agent
- Comprehensive multi-agent improvement plan

**Next up:** Module 6 - Project Memory & Long-Term Context

In Module 6, you'll learn to build persistent project memory so Claude remembers your work across sessions and builds cumulative knowledge.

STOP: Any questions before we wrap?

USER: Questions or confirms done

[Answer any questions]

Fantastic work! When you're ready for Module 6:
1. Watch the Module 6 video (8-10 minutes)
2. Then run: `start-module-6`

This is the final module - let's finish strong!

---

## Success Criteria

By completing this module, you should be able to:
- [x] Understand and use pre-configured sub-agents
- [x] Request perspectives from multiple agents
- [x] Have agents do domain-specific deep dives
- [x] Run parallel analysis across agents
- [x] Create custom agents for your needs
- [x] Orchestrate multi-agent projects
- [x] Synthesize multi-perspective outputs

If you want more practice, create agents for other roles (marketing, data, operations) and have them analyze FitHub challenges!
