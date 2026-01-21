# Module 6: Project Memory & Long-Term Context - Interactive Lesson

Welcome to Module 6 - the final module! You've mastered file exploration, analysis, commands, and sub-agents. Now let's build persistent memory.

This interactive lesson will take about 30-35 minutes.

STOP: Have you watched the Module 6 video?

USER: Yes / Ready

---

## The Memory Problem

Here's a challenge you've probably noticed:

Every time you start a new Claude Code session, I start fresh. I can see your files, but I don't remember:
- What you analyzed yesterday
- Decisions you've made
- Insights you've uncovered
- Context you've built

That's where project memory comes in.

STOP: Has this been frustrating? Starting over each session?

USER: Response

---

## What is Project Memory?

Project memory is documentation that preserves:
- **Project context** - What you're working on and why
- **Decisions made** - What you've decided and the reasoning
- **Key insights** - Important discoveries from your analysis
- **Next steps** - Where you're headed
- **Working knowledge** - Information you reference frequently

It's not just notes. It's structured memory that I can read to instantly understand your project state.

STOP: Ready to build your project memory?

USER: Yes / Ready

---

## The Memory Files

Let me show you what exists already.

ACTION: List files in company-context/ folder

These are permanent context files:
- SCENARIO.md - The FitHub situation
- BRAND-VOICE.md - Brand guidelines
- LOYALTY-PROGRAM.md - Program structure

These give me instant context every session.

But we need more. We need memory of YOUR work.

STOP: Ready to create your first memory file?

USER: Confirms

---

## Task 1: Create a Decision Log

You've made decisions throughout this course. Let's capture them.

**Ask me: "Create a decision-log.md file in the organized folder that documents key decisions I've made about FitRewards, including: the root causes I identified, which campaigns to learn from, strategic priorities, and recommendations I've chosen to pursue."**

STOP: Go ahead.

USER: Asks to create decision log

ACTION: Create organized/decision-log.md reviewing past analysis work and documenting decisions made:
- Root causes identified in Module 3
- Successful vs. unsuccessful campaigns
- Strategic priorities chosen
- Recommendations selected
- Rationale for each decision
- Date of decision

Done! Let me show you.

ACTION: Read decision-log.md

This is now permanent memory. Next session, I can read this and know what you've decided.

STOP: See how this creates continuity?

USER: Confirms

---

## Task 2: Create a Project Brief

Every project needs a living brief that captures current state.

**Ask me: "Create a project-brief.md file that includes: project goal, current status, key metrics, major insights discovered, work completed so far, and immediate next steps."**

STOP: Your turn.

USER: Asks for project brief

ACTION: Create organized/project-brief.md synthesizing:
- FitHub Wellness overview
- FitRewards goal (turn around the program)
- Current metrics (11,800 members, 1,950 active, 16.5% engagement)
- Major insights from Modules 1-5 analysis
- Work completed (analysis docs, commands created, agent perspectives)
- Next steps

Here's your project brief.

ACTION: Read project-brief.md

This is your single source of truth. Update it as the project evolves.

STOP: If someone new joined this project, could they read this and get oriented?

USER: Response

---

## Task 3: Create a Knowledge Base

You've uncovered lots of information. Let's organize it into a searchable knowledge base.

**Ask me: "Create a knowledge-base.md file that organizes everything I've learned about FitHub into categories: Member Insights, Competitive Intelligence, Campaign Learnings, App/UX Issues, and Trainer Feedback."**

STOP: Go ahead.

USER: Asks for knowledge base

ACTION: Create organized/knowledge-base.md pulling from all analysis done across modules:
- Member Insights (from feedback analysis)
- Competitive Intelligence (from competitor research)
- Campaign Learnings (what worked/didn't work)
- App/UX Issues (product designer findings)
- Trainer Feedback (trainer lead insights)
- Each with key points and sources

Done! Here's your knowledge base.

ACTION: Read knowledge-base.md

This is your quick reference for any FitHub question.

STOP: How useful would this be in a real 3-month project?

USER: Response

---

## Task 4: Create Context for Sub-Agents

Your sub-agents need memory too. Let's give them project context.

**Ask me: "Create a file called agent-context.md that each sub-agent should read when they start work. Include FitHub background, current challenges, decisions made so far, and work-in-progress."**

STOP: Your turn.

USER: Asks for agent context

ACTION: Create organized/agent-context.md designed for sub-agents:
- FitHub Wellness background
- FitRewards challenge summary
- Key decisions logged
- Current project phase
- Important constraints (timeline, budget)
- Work already completed
- What's still needed

Perfect! Now agents can read this for instant context.

ACTION: Read agent-context.md

Let's test it. Ask an agent to read this context first, then analyze something.

**Ask the Product Designer: "Read agent-context.md first, then recommend top 3 UX priorities for the next sprint."**

STOP: Go ahead.

USER: Asks product designer with context

ACTION: Have product designer read agent-context.md, then provide recommendations based on full project awareness

Here's what the Product Designer recommended:

[Present context-aware recommendations]

See the difference? They're building on previous work, not starting from scratch.

STOP: Notice how context improved their recommendations?

USER: Response

---

## Task 5: Create a Session Summary Template

At the end of each work session, you should capture what you did.

**Ask me: "Create a template called session-summary-template.md that I can fill out after each work session. Include: date, what I analyzed, key findings, decisions made, files created, and next session priorities."**

STOP: Your turn.

USER: Asks for template

ACTION: Create organized/session-summary-template.md with clear sections for capturing session work

Here's the template.

ACTION: Read session-summary-template.md

Now let's use it. **Ask me: "Fill out a session summary for today's Module 6 work using the template."**

STOP: Go ahead.

USER: Asks to fill out session summary

ACTION: Create organized/session-summary-[date].md documenting Module 6 work

Done! Here's today's session summary.

ACTION: Read the session summary

Do this after every work session. You'll build a complete project history.

STOP: Can you see yourself doing this in real projects?

USER: Response

---

## Task 6: Build a Living README

Every project needs a README that explains the project and how to navigate it.

**Ask me: "Create a comprehensive README.md for the FitHub student-files folder that explains: what this project is, how the folders are organized, how to use commands, how to work with agents, where key documents are located, and how to get started."**

STOP: Your turn.

USER: Asks for README

ACTION: Create README.md in student-files root with:
- Project overview
- Folder structure explanation
- How to use custom commands
- How to work with sub-agents
- Where to find key documents
- Getting started guide
- Tips for effective work

Perfect! Let me show you.

ACTION: Read README.md

This is the entry point for anyone (including future you) working on this project.

STOP: Would this help you if you came back to this project in 3 months?

USER: Response

---

## Task 7: Create a Progress Tracker

You're managing a 3-month turnaround. Let's track progress.

**Ask me: "Create a progress-tracker.md that shows the 90-day timeline with phases, milestones, work completed, current status, and what's blocking progress."**

STOP: Go ahead.

USER: Asks for progress tracker

ACTION: Create organized/progress-tracker.md with:
- 90-day timeline breakdown (Month 1: Analysis, Month 2: Implementation, Month 3: Optimization)
- Key milestones
- Work completed (check marks)
- Current phase and status
- Blockers or risks
- Success metrics tracking

Here's your progress tracker.

ACTION: Read progress-tracker.md

Update this weekly. It keeps you focused and shows leadership you're on track.

STOP: Could you share this with executives?

USER: Response

---

## The Power of Cumulative Memory

Let's test the full memory system.

Close this Claude Code session (or imagine you did). Then start fresh tomorrow.

When you start tomorrow's session, ask me:
"Read my project brief, decision log, and latest session summary. What should I focus on today?"

Let's simulate that.

STOP: Ask me that question.

USER: Asks what to focus on today based on memory files

ACTION: Read project-brief.md, decision-log.md, and latest session summary, then provide context-aware recommendations for next priorities

Based on your project memory:

[Present next priorities with full context of past work]

See? Instant continuity. No "what was I doing?" No starting over.

STOP: Feel the power of project memory?

USER: Response

---

## Practice: Memory Maintenance

Memory needs maintenance. Let's practice updating.

Something changed: Leadership just approved a $15,000 budget for FitRewards improvements.

**Update your project brief, decision log, and progress tracker to reflect this new development.**

STOP: Ask me to update the relevant files.

USER: Asks to update files with new budget info

ACTION: Update:
- project-brief.md with budget allocation
- decision-log.md with budget decision and date
- progress-tracker.md with budget milestone

Updated! Let me show you the changes.

ACTION: Show updated sections of relevant files

This is living documentation. It evolves with your project.

STOP: See how memory files stay current?

USER: Response

---

## Building Memory Habits

Here's the memory habit to build:

**Start of each session:**
1. Ask Claude to read project-brief.md and latest session-summary.md
2. Get oriented on current status and priorities
3. Start work with full context

**During session:**
4. Update decision-log.md when you make decisions
5. Add to knowledge-base.md when you discover insights

**End of session:**
6. Fill out session-summary.md
7. Update progress-tracker.md
8. Update project-brief.md if status changed

5 minutes of memory work saves hours of reconstruction.

STOP: Willing to commit to this habit?

USER: Response

---

## Real-World Application

Let's talk about using this in your actual work.

For any project, create:
- **Project Brief** - Living document of current state
- **Decision Log** - Track what you decided and why
- **Knowledge Base** - Organized learnings
- **Session Summaries** - Work history
- **Progress Tracker** - Timeline and milestones
- **README** - How the project is organized

This works for:
- Product launches
- Marketing campaigns
- Business analysis
- Strategic planning
- Research projects
- Client work

STOP: What project could you apply this to right now?

USER: Response

[Acknowledge]

Start building memory from day one. Your future self will thank you.

---

## The Final Challenge

One last task. Create your graduation deliverable.

**Ask me: "Create a comprehensive FitRewards Turnaround Plan that synthesizes all my work from Modules 1-6. Include executive summary, situation analysis, strategic recommendations, implementation timeline, success metrics, and resource requirements. Make it presentation-ready for FitHub leadership. Save it as final-turnaround-plan.md"**

This is everything you've learned in one deliverable.

STOP: Ready for the final challenge?

USER: Confirms and asks

ACTION: Create organized/final-turnaround-plan.md synthesizing all work:
- Executive Summary
- Situation Analysis (from Module 2-3 work)
- Root Causes (from Module 3)
- Strategic Approach (from all modules)
- Specific Recommendations (from agent perspectives)
- Implementation Timeline (90 days)
- Success Metrics (tracking engagement growth)
- Resource Requirements (budget, team, tools)
- Risk Mitigation
- Appendices (linking to supporting analysis)

Done! This is your magnum opus.

ACTION: Read final-turnaround-plan.md

STOP: Does this feel like professional consulting work?

USER: Response

[Acknowledge]

You just created a plan that could actually turn around a loyalty program. That's the power of everything you've learned.

---

## Reflection: From Beginner to Expert

Think about where you started:

**Module 1:** Learning to read a single file

**Module 6:** Orchestrating AI agents, building project memory, creating executive strategies

You've learned to:
- Explore and analyze complex file structures
- Synthesize information from multiple sources
- Automate workflows with custom commands
- Manage teams of specialized AI agents
- Build persistent project memory
- Create professional deliverables

STOP: What surprised you most about what you can do with Claude Code?

USER: Response

[Acknowledge response]

---

## Module 6 Complete! ✅

You've completed Module 6 and the entire course!

Here's what you can now do:

✅ Build project memory that persists across sessions
✅ Create decision logs and knowledge bases
✅ Maintain living project documentation
✅ Give sub-agents project context
✅ Track progress and milestones
✅ Create session summaries
✅ Build comprehensive project briefs
✅ Apply memory systems to real-world projects

**What you created:**
- `decision-log.md` - All decisions tracked
- `project-brief.md` - Living project overview
- `knowledge-base.md` - Organized learnings
- `agent-context.md` - Context for sub-agents
- `session-summary-template.md` - Reusable template
- `progress-tracker.md` - 90-day timeline
- `README.md` - Project guide
- `final-turnaround-plan.md` - Complete strategy

**You've completed the entire course!**

STOP: Congratulations! How do you feel?

USER: Response

[Celebrate with them]

---

## What's Next?

You now have professional-grade AI productivity skills.

**Immediate next steps:**
1. Apply these techniques to a real project at work
2. Build your own command library for recurring tasks
3. Create custom agents for your domain
4. Start every project with memory files

**Keep learning:**
- Experiment with advanced prompting techniques
- Build more sophisticated agent orchestration
- Create project templates for common work
- Share your knowledge with colleagues

**Stay connected:**
- Join the Claude Code community
- Share your use cases and learnings
- Help others get started

STOP: What's the first real project you'll use Claude Code for?

USER: Response

[Acknowledge and encourage]

Perfect! Go build something amazing.

---

## Course Complete!

**You've finished Claude Code for Business Professionals!**

You've learned:
✅ Module 1 - Getting Started
✅ Module 2 - File Exploration
✅ Module 3 - Deep Analysis & Synthesis
✅ Module 4 - Commands & Automation
✅ Module 5 - Sub-Agents & Parallel Work
✅ Module 6 - Project Memory & Long-Term Context

**You created:**
- Comprehensive analysis documents
- Strategic recommendations
- Custom commands
- Specialized AI agents
- Project memory system
- Professional deliverables

You're now equipped to use Claude Code as a powerful business tool.

Thank you for taking this course. Now go turn some real-world chaos into clarity.

---

## Success Criteria

By completing this module, you should be able to:
- [x] Create and maintain project memory files
- [x] Build decision logs and knowledge bases
- [x] Write session summaries
- [x] Create living project documentation
- [x] Give agents project context
- [x] Track project progress and milestones
- [x] Build comprehensive project briefs
- [x] Apply memory systems to real projects
- [x] Maintain continuity across work sessions

**You've mastered Claude Code for business productivity. Well done!**
