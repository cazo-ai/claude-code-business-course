# Module 1: Getting Started - Interactive Lesson

Welcome! You've watched the video, now let's get your hands dirty.

This interactive lesson will take about 20-25 minutes. I'll guide you through every step.

STOP: Ready to begin?

USER: Yes / Ready / Let's go

---

## Your First Claude Command

Great! You're already here in Claude Code, so you've mastered the first step: launching Claude.

Let me check where we are.

ACTION: Run `pwd` to show current directory

We're in the course folder. Perfect.

STOP: Can you see the path to the student-files folder?

USER: Yes / Confirms

---

## Understanding the Workspace

Let's get oriented. I'm going to show you what files exist in this project.

ACTION: List all folders and files in the current directory with a simple tree structure

See all those folders?
- `company-context/` - Information about FitHub Wellness
- `inherited-chaos/` - The mess you inherited from the previous manager
- `.claude/` - Commands and sub-agents
- `organized/` - Where you'll save organized outputs
- `analysis/` - Where you'll save analysis work

STOP: Which folder sounds most interesting to you?

USER: Any response

---

## The FitHub Wellness Scenario

[Regardless of answer]

Good choice! But first, let me tell you about your new job.

You're the new Member Experience Manager at FitHub Wellness. They launched "FitRewards" six months ago, invested $40,000, and... it's failing.

Let me show you the details.

ACTION: Read company-context/SCENARIO.md and summarize the key points conversationally (your role, the problem, the timeline)

So here's the situation:
- 11,800 members signed up
- Only 1,950 are active monthly (that's just 16.5% engagement!)
- Leadership is considering shutting down the program
- You have 3 months to turn it around

STOP: Feeling the pressure yet? 😅

USER: Response

---

## Your First File Read

Perfect. Now let's see what the previous manager left you.

Ask me to read the previous manager's notes. Use natural language - say something like "Read the previous manager notes" or "Show me what the previous manager left behind."

STOP: Go ahead, ask me.

USER: Asks to read previous-manager-notes.md

ACTION: Read inherited-chaos/previous-manager-notes.md and give a conversational summary

Yikes. That's... messy. Scattered thoughts, half-finished ideas, no clear plan.

But there's information in there we can use. We'll come back to this in Module 3.

STOP: Did you notice how I understood your natural language request? You don't need to be technical with me.

USER: Confirms

---

## Task 1: Create Your First File

Now let's create something. I'm going to help you create a simple file to capture your first thoughts about this project.

Here's what I want you to do:

**Ask me to create a file called `my-first-notes.md` with three bullet points about what you've learned so far about FitHub Wellness.**

Use your own words. Don't worry about being perfect.

STOP: Give it a try.

USER: Asks Claude to create the file

ACTION: Create the file in the student-files directory with three bullet points based on what we discussed

Done! Let me show you what we created.

ACTION: Read the file back to them

STOP: Look good? You can always ask me to change it.

USER: Confirms or asks for changes

[If changes requested: Make them and confirm]
[If confirmed: Continue]

---

## Task 2: Find Specific Information

Now let's practice finding information. The rewards program has some key metrics.

**Ask me: "What are the current engagement metrics for FitRewards?"**

STOP: Go ahead.

USER: Asks about metrics

ACTION: Search through files (member-data-summary.csv and SCENARIO.md) to find and present the metrics clearly

Here's what matters:
- Total members: 11,800
- Monthly active users: 1,950
- Engagement rate: 16.5%
- Target engagement: 35-40%

Those are the numbers you need to improve.

STOP: Make sense?

USER: Confirms

---

## Task 3: Explore a Folder

Let's look at what member feedback exists.

**Ask me: "What member feedback files do we have?"**

STOP: Your turn.

USER: Asks about member feedback

ACTION: List files in inherited-chaos/customer-feedback/ folder and briefly describe what's there

Four months of feedback: January through April.

Here's a preview of what members are saying...

ACTION: Read one file (April feedback) and share 2-3 notable quotes

Notice a theme? We'll analyze all of this in Module 3.

STOP: Starting to see patterns?

USER: Response

---

## Practice: Free Exploration

Now you try. Take 5 minutes to explore on your own.

Some ideas:
- Ask me about the brand voice
- Look at the competitor research
- Check out the old campaigns folder
- Read the loyalty program details

**Just ask me questions naturally, like you would ask a colleague.**

STOP: Go explore! Ask me anything about the files. When you're ready to move on, say "I'm done exploring" or "What's next?"

USER: Asks various questions, explores, then indicates they're done

[Answer questions naturally as they come]

[When done exploring, continue:]

---

## Reflection

Nice work exploring! Let's capture what you learned.

STOP: What's the biggest problem you see with FitRewards so far?

USER: Their answer

[Acknowledge their response]

Good observation. As we go through the next modules, we'll do deep analysis to find the real root cause.

---

## Module 1 Complete! ✅

You've completed Module 1. Here's what you can now do:

✅ Launch Claude Code and navigate your workspace
✅ Ask me to read files in natural language
✅ Create files and documents
✅ Find specific information across files
✅ Explore folders and their contents

**What you created:**
- `my-first-notes.md` - Your first Claude Code deliverable

**Next up:** Module 2 - File Exploration

In Module 2, you'll learn advanced file navigation, how to search across multiple files at once, and create your first comprehensive summary.

STOP: Any questions before we wrap up?

USER: Questions or confirms done

[Answer any questions]

Excellent! When you're ready for Module 2:
1. Watch the Module 2 video (6-8 minutes)
2. Then come back and run: `start-module-2` (or just ask me to start Module 2)

Great work today! 🎉

---

## Success Criteria

By completing this module, you should be able to:
- [x] Successfully interact with Claude Code via natural language
- [x] Ask Claude to read files
- [x] Create simple files
- [x] Find specific information
- [x] Explore the FitHub Wellness scenario

If you struggled with any of these, feel free to practice more before moving on!
