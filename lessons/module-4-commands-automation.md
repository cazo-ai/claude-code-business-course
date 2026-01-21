# Module 4: Commands & Automation - Interactive Lesson

Welcome to Module 4! You've mastered analysis and synthesis. Now let's make your workflows faster with custom commands.

This interactive lesson will take about 25-30 minutes.

STOP: Have you watched the Module 4 video?

USER: Yes / Ready

---

## Why Commands Matter

So far, you've been typing full requests like:
- "Read all customer feedback files and summarize the main themes"
- "Create a competitive analysis comparing these three files"
- "Analyze root causes across these sources"

That works great. But what if you need to run these same analyses:
- Every week?
- On updated data?
- For different projects?

That's where custom commands come in.

STOP: Ready to automate your workflows?

USER: Yes / Ready

---

## Understanding the .claude Directory

Let me show you something.

ACTION: List the contents of the .claude directory

See that? Your project has a `.claude` folder. This is where the magic happens.

Inside `.claude/commands/`, you can create custom commands that run with a simple keyword.

Let's explore what's already there.

STOP: Ready to see how commands work?

USER: Confirms

---

## Your First Command

I'm going to show you a command that already exists. Then you'll create your own.

ACTION: List files in .claude/commands/ directory

Let's look at how these are structured.

ACTION: Read one of the existing command files as an example

See the structure?
- Clear instructions
- Context about what to do
- Expected output format

Now let's create your own.

STOP: Ready to build your first command?

USER: Yes

---

## Task 1: Create a Weekly Summary Command

You're going to need weekly summaries of member feedback as new data comes in.

Let's create a command that automates this.

**Ask me: "Create a command file called 'weekly-feedback-summary' that reads all customer feedback files, identifies top 3 themes, lists notable quotes, and creates a dated summary in the analysis folder."**

STOP: Go ahead.

USER: Asks to create command

ACTION: Create .claude/commands/weekly-feedback-summary with clear instructions for:
- Reading all feedback files
- Identifying top 3 recurring themes
- Extracting 3-5 notable quotes
- Creating analysis/weekly-feedback-[date].md
- Professional formatting for leadership

Done! Now let me show you how to use it.

ACTION: Read the command file to show them what was created

To run this command, you just type:
**`weekly-feedback-summary`**

That's it. Want to try it?

STOP: Type "weekly-feedback-summary" and press Enter.

USER: Runs the command

ACTION: Execute the command - read feedback files, analyze themes, extract quotes, create dated summary file

Done! Let me show you what it created.

ACTION: Read the generated summary file

See how fast that was? One word, instant analysis.

STOP: See the power of custom commands?

USER: Confirms

---

## Task 2: Create a Campaign Analysis Command

Let's create another useful command.

**Ask me: "Create a command called 'analyze-campaign' that takes a campaign name, reads that campaign file, finds related member feedback, analyzes effectiveness, and creates a campaign analysis report."**

This one's more advanced - it will need to search for related feedback.

STOP: Give it a try.

USER: Asks to create campaign analysis command

ACTION: Create .claude/commands/analyze-campaign with instructions for:
- Taking campaign name as input
- Reading campaign file
- Searching feedback files for related mentions
- Analyzing effectiveness
- Creating organized/campaign-analysis-[campaign-name].md

Created! This command is special - it takes an argument.

To use it: `analyze-campaign "double-points-weekend"`

Let's test it.

STOP: Try running: analyze-campaign "double-points-weekend"

USER: Runs command

ACTION: Execute command - read campaign file, search feedback for mentions, analyze, create report

Excellent! Check out the analysis report.

ACTION: Read the generated campaign analysis report

You just automated campaign analysis. Run this on any campaign anytime.

STOP: Can you see using this for future campaigns?

USER: Response

---

## Task 3: Create a Competitive Check Command

One more practical command.

Your job requires keeping tabs on competitors. Let's automate that.

**Ask me: "Create a command called 'competitor-check' that reads all competitor research files and creates a summary of their latest features, pricing, and programs compared to FitHub."**

STOP: Your turn.

USER: Asks to create competitor check command

ACTION: Create .claude/commands/competitor-check with instructions for:
- Reading all competitor research files
- Creating comparison matrix
- Highlighting FitHub gaps and opportunities
- Generating analysis/competitive-landscape-[date].md

Perfect! Now run it.

STOP: Run the command: competitor-check

USER: Runs command

ACTION: Execute command - read competitor files, create comparison, generate summary

Done! Here's your competitive landscape report.

ACTION: Read the competitive landscape report

This is now a repeatable process. Update competitor files, run the command, get fresh insights.

STOP: How much time did this just save you?

USER: Response

---

## Understanding Command Best Practices

Let's talk about what makes a good command.

A good command is:
1. **Specific** - Clear about what files to read and what to analyze
2. **Consistent** - Produces reliable output every time
3. **Documented** - Someone else could understand it
4. **Parameterized** - Can handle variables (like campaign names)
5. **Output-focused** - Creates files in predictable locations

Bad command: "analyze stuff"
Good command: "Read Q1 feedback files, identify top 3 issues, create timestamped report in analysis folder"

STOP: Make sense?

USER: Confirms

---

## Task 4: Create Your Own Command

Now you design one. Think about your workflow.

What analysis or task do you find yourself repeating?

Some ideas:
- Brand voice checker (analyzes content against brand guidelines)
- Member segment analyzer (categorizes feedback by member type)
- Monthly KPI report (pulls metrics from data files)
- Quick win finder (identifies easy improvements from feedback)

**Pick one and ask me to create a custom command for it.**

STOP: What command would help your workflow? Design it and ask me to create it.

USER: Describes and asks for custom command

ACTION: Create the custom command based on their specification, with clear instructions and expected outputs

Created! Let me show you what I built.

ACTION: Read the command file

Now test it!

STOP: Run your new command and see what it produces.

USER: Runs their custom command

ACTION: Execute the command and generate output

[Show results]

How'd it work?

STOP: Does the output match what you wanted? Any adjustments needed?

USER: Response / requests changes

[If changes needed, update the command and re-run]

---

## Task 5: Command Chaining

Here's an advanced technique: running multiple commands in sequence.

For example, you might want to:
1. Run weekly-feedback-summary
2. Then run competitor-check
3. Then create an exec summary combining both

You can ask me: "Run weekly-feedback-summary, then competitor-check, then create an executive summary combining insights from both reports."

STOP: Want to try command chaining?

USER: Response

[If yes:]

USER: Asks to chain commands

ACTION: Run commands in sequence, then create synthesis document

[Show final output]

This is workflow automation at its finest.

---

## Building a Command Library

Let's see what you've built.

ACTION: List all commands in .claude/commands/

You now have a command library for the FitHub project.

Imagine in 3 months you have:
- 15 custom commands
- All your repetitive analyses automated
- One-word shortcuts for complex tasks

That's the compound effect of building commands as you work.

STOP: What other commands can you imagine creating?

USER: Ideas

[Acknowledge ideas]

Great thinking! You can create any of those as you need them.

---

## Practice: Document Your Commands

Create a command reference guide.

**Ask me: "Create a file called command-reference.md in the organized folder that lists all available commands with descriptions of what they do and example usage."**

STOP: Go ahead.

USER: Asks for command reference

ACTION: Create organized/command-reference.md with:
- List of all commands
- Description of each
- Usage examples
- Expected outputs
- Last updated date

Done! This is your command documentation.

ACTION: Read command-reference.md

Keep this updated as you add new commands.

STOP: Helpful reference?

USER: Confirms

---

## Reflection: Automation Mindset

Think about your work before this module vs. now.

Before:
- Manually reading files each time
- Typing long requests repeatedly
- Starting from scratch for recurring tasks

Now:
- One-word commands for complex analysis
- Automated workflows
- Repeatable, consistent outputs

This is the automation mindset: if you do it twice, automate it.

STOP: What's the first thing you'll automate in your real work?

USER: Response

[Acknowledge]

That's the right thinking. Commands = leverage.

---

## Module 4 Complete! ✅

You've completed Module 4. Here's what you can now do:

✅ Create custom commands for recurring tasks
✅ Build parameterized commands that take input
✅ Chain multiple commands together
✅ Automate analysis workflows
✅ Build a command library for your project
✅ Document your automation

**What you created:**
- `weekly-feedback-summary` command
- `analyze-campaign` command
- `competitor-check` command
- Your own custom command
- `command-reference.md` documentation
- Multiple automated analysis reports

**Next up:** Module 5 - Sub-Agents & Parallel Work

In Module 5, you'll learn to run multiple AI agents simultaneously, each with different expertise and perspectives.

STOP: Any questions before we wrap?

USER: Questions or confirms done

[Answer any questions]

Great work! When you're ready for Module 5:
1. Watch the Module 5 video (7-9 minutes)
2. Then run: `start-module-5`

You're building serious AI productivity skills!

---

## Success Criteria

By completing this module, you should be able to:
- [x] Create custom command files in .claude/commands/
- [x] Build commands with clear instructions and outputs
- [x] Create parameterized commands that accept input
- [x] Chain multiple commands in sequence
- [x] Document your command library
- [x] Apply automation mindset to recurring tasks

If you want more practice, create commands for other repetitive tasks in the FitHub project!
