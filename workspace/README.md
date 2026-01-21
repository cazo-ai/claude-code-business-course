# FitHub Wellness - Claude Code Course Project

Welcome to the FitHub Wellness scenario for "Claude Code for Business Professionals"!

## First Time Here?

If this is your first time, run the setup verification to make sure everything is working:

```
start-module-0
```

This quick check (5 minutes) will verify your installation is complete and all course files are in place.

---

## About This Project

You are the new Member Experience Manager at FitHub Wellness, a regional fitness chain with 35 locations across the Southwest. Your mission: turn around the failing FitRewards loyalty program in 90 days.

**The Challenge:**
- 11,800 members signed up for FitRewards
- Only 1,950 are active monthly users (16.5% engagement)
- Target engagement: 35-40%
- Leadership is considering shutting down the program
- You inherited scattered files and notes from the previous manager (Jessica)
- Budget: Limited resources, high expectations

**Your Goal:** Use Claude Code to analyze the situation, find insights, and develop a turnaround strategy.

---

## Folder Structure

```
student-files/
├── company-context/          # Core information about FitHub
│   ├── SCENARIO.md          # Your role and the challenge
│   ├── BRAND-VOICE.md       # FitHub's brand guidelines
│   └── LOYALTY-PROGRAM.md   # FitRewards program structure
│
├── inherited-chaos/         # Files from previous manager Jessica
│   ├── previous-manager-notes.md
│   ├── member-data-summary.csv
│   ├── customer-feedback/   # 4 months of member feedback
│   ├── old-campaigns/       # 8 past campaign files
│   └── competitor-research/ # 5 competitor analysis files
│
├── templates/               # Reusable templates
│   └── leadership-update-template.md
│
├── organized/              # Save organized outputs here
├── analysis/              # Save analysis work here
│
└── .claude/               # Claude Code configuration
    ├── commands/          # Custom commands you create
    ├── agents/           # Specialized AI agents
    └── SCRIPT_INSTRUCTIONS.md
```

---

## Getting Started

### Prerequisites

1. Install Cursor or VS Code
2. Install Claude Code CLI
3. Open this folder in your editor
4. Open terminal (Ctrl+` or Cmd+`)

### Launch Claude Code

In the terminal, type:
```bash
claude
```

Press Enter and start interacting!

### Start the Course

To begin Module 1, type in Claude Code:
```
start-module-1
```

Or simply ask: "Start Module 1" or "Begin the interactive lesson"

---

## Course Modules

### Module 0: Setup Verification (5-10 minutes)
Verify your installation is complete and ready.

**Start:** `start-module-0`

**What it checks:**
- Claude Code is running correctly
- All course files are present
- Commands and agents are available
- File reading and creation work

---

### Module 1: Getting Started (20-25 minutes)
Learn to interact with Claude Code, read files, and explore the FitHub scenario.

**Start:** `start-module-1`

**What you'll learn:**
- Reading files in natural language
- Creating simple files
- Finding specific information
- Exploring your workspace

---

### Module 2: File Exploration (25-30 minutes)
Master multi-file reading, pattern recognition, and creating organized summaries.

**Start:** `start-module-2`

**What you'll learn:**
- Reading multiple files simultaneously
- Searching across all files
- Comparing different sources
- Creating organized inventories
- Extracting patterns from scattered data

---

### Module 3: Deep Analysis & Synthesis (30-35 minutes)
Learn strategic analysis, root cause identification, and executive-level synthesis.

**Start:** `start-module-3`

**What you'll learn:**
- Root cause analysis with evidence
- Synthesizing across multiple sources
- Creating strategic recommendations
- Competitive analysis
- Generating executive deliverables

---

### Module 4: Commands & Automation (25-30 minutes)
Create custom commands to automate recurring analysis tasks.

**Start:** `start-module-4`

**What you'll learn:**
- Creating custom command files
- Building parameterized commands
- Testing and running commands
- Chaining commands together
- Automation mindset

---

### Module 5: Sub-Agents & Parallel Work (30-35 minutes)
Work with specialized AI agents for diverse perspectives and parallel analysis.

**Start:** `start-module-5`

**What you'll learn:**
- Working with specialized agents
- Getting multiple perspectives
- Running parallel analysis
- Creating custom agents
- Orchestrating multi-agent projects

---

### Module 6: Project Memory & Long-Term Context (30-35 minutes)
Build persistent memory systems for continuity across work sessions.

**Start:** `start-module-6`

**What you'll learn:**
- Building project memory files
- Creating decision logs
- Maintaining living documentation
- Session summary systems
- Memory habits for long projects

---

### Module 7: Creating Custom Skills (20-25 minutes) 🎓
**Power User Graduation:** Learn to customize Claude Code by creating your own skills.

**Start:** `start-module-7`

**What you'll learn:**
- How skills work under the hood
- Installing skills from the community
- Modifying existing skills for your needs
- Creating completely new skills from scratch
- Building a personal skills library
- Sharing skills across projects

**Note:** This is a bonus capstone module that transforms you from user to power user!

---

## Working with Custom Commands

Custom commands are shortcuts for complex workflows. They live in `.claude/commands/`.

### Built-in Course Commands

- `start-module-0` - Verify setup (run this first!)
- `start-module-1` through `start-module-7` - Launch interactive lessons

### Business Productivity Skills

The course includes 8 pre-built skills for common business tasks:

**Communication & Documentation:**
- `meeting-notes` - Convert messy notes to organized action items
- `email-draft` - Create professional emails from bullet points

**Analysis & Research:**
- `analyze-folder` - Deep analysis of folder contents
- `web-synthesis` - Web research with structured summaries
- `compare-docs` - Side-by-side document comparison

**Strategic Work:**
- `executive-summary` - Leadership-ready summaries
- `decision-matrix` - Structured decision framework
- `competitive-analysis` - Comprehensive competitive landscape analysis

**Usage Example:**
```
meeting-notes @my-meeting-notes.md
email-draft @bullet-points.md
analyze-folder @inherited-chaos/
```

### Creating Your Own Skills

Ask Claude: "Create a command called [name] that [does something]"

Example:
```
Create a command called weekly-summary that reads all feedback files
and creates a dated summary in the analysis folder
```

### Running Commands

Just type the command name:
```
weekly-summary
```

### Listing Commands

Ask Claude: "What commands do I have?" or "List my custom commands"

---

## Working with Sub-Agents

Sub-agents are specialized AI personalities with domain expertise.

### Available Agents

**Trainer Lead** (`.claude/agents/trainer-lead.md`)
- 10+ years gym floor experience
- Focuses on member experience and trainer enablement
- Thinks about practical implementation

**Product Designer** (`.claude/agents/product-designer.md`)
- UX and app design expert
- Focuses on user experience and interface
- Thinks about simplicity and usability

**Executive** (`.claude/agents/exec.md`)
- Business strategist
- Focuses on ROI, metrics, and risk
- Thinks about business impact and timeline

### Using Agents

Ask specific agents questions:
```
Product Designer: Analyze the app UX issues in customer feedback
```

Or get multiple perspectives:
```
Get perspectives from trainer lead, product designer, and exec
on whether to simplify the points system
```

### Creating Custom Agents

Ask Claude:
```
Create a new agent called Marketing Specialist with expertise
in campaign effectiveness and brand messaging
```

---

## Best Practices

### File Organization

- Save analysis work in `analysis/` folder
- Save organized outputs in `organized/` folder
- Use descriptive file names with dates
- Keep source files in `inherited-chaos/` untouched

### Asking Good Questions

**Instead of:** "Summarize this"
**Try:** "What are the root causes of low engagement based on these files?"

**Instead of:** "Read feedback"
**Try:** "Read all feedback files and identify the top 3 complaints with supporting quotes"

**Instead of:** "Help"
**Try:** "What should I focus on next to improve FitRewards engagement?"

### Building Memory

For longer projects, create these files:
- `project-brief.md` - Current status and goals
- `decision-log.md` - Track important decisions
- `knowledge-base.md` - Organized learnings
- `session-summary-[date].md` - Work history

Ask Claude to read these at the start of each session for instant context.

---

## Common Workflows

### Starting a Work Session

1. Launch Claude Code: `claude`
2. Get oriented: "Read my project brief and latest session summary. What should I focus on today?"
3. Start work with full context

### During Work

- Save useful outputs to organized folders
- Update decision log when making choices
- Add insights to knowledge base as you discover them

### Ending a Work Session

1. Create session summary: "Create a session summary for today's work"
2. Update project brief if status changed
3. Note next session priorities

---

## Troubleshooting

**Claude doesn't remember previous conversations:**
- This is normal! Build project memory files
- At session start, ask Claude to read your project brief

**Can't find a file:**
- Ask Claude: "Where is the [filename] file?"
- Check folder structure in this README

**Command not working:**
- Ask Claude: "Show me the [command-name] command file"
- Verify the command file exists in `.claude/commands/`

**Agent giving generic responses:**
- Give them context: "Read agent-context.md first, then [question]"
- Be specific about what perspective you want

---

## Course Resources

### Exercise Files
Practice exercises for each module are in `/course-content/exercises/`

### Video Scripts
Video transcripts are in `/course-content/video-scripts/`

### Interactive Lessons
Full lesson scripts are in `/course-content/interactive-lessons/`

---

## Tips for Success

1. **Follow the modules in order** - Each builds on previous skills
2. **Complete the exercises** - Practice reinforces learning
3. **Experiment freely** - You can't break anything
4. **Ask natural questions** - Claude understands plain English
5. **Build as you go** - Create commands and memory files during the course
6. **Apply to real work** - Think about how to use these skills in your job

---

## Project Goals

By the end of this course, you will:

✅ Analyze the FitRewards situation comprehensively
✅ Identify root causes of low engagement
✅ Generate strategic recommendations
✅ Create custom commands for recurring analysis
✅ Work with specialized AI agents
✅ Build a complete turnaround plan
✅ Develop project memory systems
✅ Create and customize your own Claude Code skills
✅ Build a personal productivity toolkit

**And most importantly:** Gain professional AI productivity skills you can use in any business context, with the ability to customize Claude Code for your exact workflow.

---

## Support

Stuck? Ask Claude:
- "What should I do next?"
- "How do I create a command?"
- "What files should I analyze?"
- "Show me an example of [something]"

Claude is your instructor, colleague, and AI assistant all in one.

---

## Ready to Begin?

**First time?** Verify your setup:
```
start-module-0
```

**Setup already verified?** Start Module 1:
```
start-module-1
```

Good luck turning around FitRewards!

**You've got this.**
