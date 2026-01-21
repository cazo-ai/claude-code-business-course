# Module 7: Creating Custom Skills - Interactive Lesson

**Duration:** 20-25 minutes
**Goal:** Learn to customize Claude Code by creating and modifying skills

---

## Welcome to Power User Territory

You've completed the core course. You know how to use Claude Code for business workflows. But here's a secret: those 8 skills you've been using throughout this course? They're just files. And you can create your own.

**STOP**

**USER:** [Student acknowledges - "Really?", "Show me", "Let's do it", etc.]

That's right. You're about to learn how to customize Claude Code to fit YOUR exact workflow. By the end of this module, you'll understand:
- How skills actually work under the hood
- How to install skills from the community
- How to modify existing skills
- How to create your own from scratch

Let's pull back the curtain.

---

## Part 1: Understanding Skills (The Magic Revealed)

Those skills you've been using - `meeting-notes`, `email-draft`, `analyze-folder` - they're stored in a special folder.

**ACTION:** Run this command to see them:
```
ls .claude/commands/
```

**STOP**

**USER:** [Student sees the list of 8 skills]

See those files? Each one is just a markdown file with instructions for Claude. Let's look inside one to see how it works.

**ACTION:** Run this command:
```
Read .claude/commands/email-draft
```

**STOP**

**USER:** [Student sees the skill file contents]

Look at the structure:
- **What This Does** - Clear description
- **When to Use** - Specific scenarios
- **How It Works** - What output to expect
- **Instructions** - Detailed guidance for Claude on how to execute this skill

It's just structured instructions! When you type `email-draft`, Claude reads this file and follows the instructions.

**The key insight:** You can write instructions like this for ANY repetitive task you do.

**STOP**

**USER:** [Student acknowledges understanding]

---

## Part 2: Installing Skills from the Community

There's a GitHub repository with hundreds of pre-made skills created by the community. Let's install one.

**ACTION:** Open this URL for the student:
https://github.com/ComposioHQ/awesome-claude-skills/tree/master

Let's say you want to install the "code-review" skill. Here's how:

**ACTION:** Guide the student through this process:

1. Browse to the skill you want in the awesome-claude-skills repo
2. Copy the raw markdown content
3. Create a new file in `.claude/commands/` with the skill name
4. Paste the content
5. Test it!

For demonstration purposes, let's create a simple "standup-notes" skill that helps you write daily standup updates.

**ACTION:** Create this file:
```
Write .claude/commands/standup-notes
```

**Content:**
```markdown
# Skill: Daily Standup Notes

## What This Does
Creates structured daily standup notes from your rough thoughts.

## When to Use
- Before daily standup meetings
- End of day summaries
- Quick status updates to your team

## How It Works
Takes your bullet points or rough notes about what you did today, what you're doing tomorrow, and any blockers, and creates a clean standup update.

## Instructions

Create a standup update using this format:

**Date:** [Today's date]

**Yesterday:**
- [Completed task 1]
- [Completed task 2]

**Today:**
- [Planned task 1]
- [Planned task 2]

**Blockers:**
- [Any blockers, or "None"]

Make it concise and clear. Focus on outcomes, not busywork.

## Usage Example
```
standup-notes

I finished the email campaign draft, had 3 member calls, and reviewed the social media posts. Today I need to finalize the campaign and send it to leadership. Waiting on budget approval from finance.
```
```

**STOP**

**USER:** [Student confirms file is created]

Perfect! Now test your new skill:

**ACTION:** Have the student test it:
```
standup-notes

Yesterday I analyzed member feedback files and found common themes. Today I'm drafting the new FitRewards campaign. Blocked on getting approval for the budget increase.
```

**STOP**

**USER:** [Student sees the formatted standup output]

See that? You just installed a custom skill. And it works exactly like the built-in ones.

---

## Part 3: Modifying Existing Skills

Now let's customize an existing skill. Say you want `email-draft` to match your company's specific tone.

**ACTION:** Let's create a modified version called `email-draft-fithub`:

```
Write .claude/commands/email-draft-fithub
```

**Content:**
```markdown
# Skill: FitHub Email Draft

## What This Does
Creates professional emails in FitHub's brand voice - energetic, supportive, action-oriented.

## When to Use
- Emails to members
- Updates to leadership
- Communication with trainers
- Vendor correspondence

## How It Works
Takes your rough notes and creates emails that match FitHub's brand voice:
- Energetic but professional
- Supportive and encouraging
- Action-oriented with clear next steps
- Inclusive fitness language

## Instructions

Create an email following this structure:

**Subject:** [Clear, action-oriented subject - never generic "Update" or "Quick question"]

[Greeting - warm but professional]

[Opening - Context in 1-2 sentences, lead with the benefit or outcome]

[Main content - organized, scannable, using fitness-positive language]

[Closing - Clear next steps, supportive tone]

[Sign-off]

### FitHub Brand Voice Guidelines:
- Use "members" not "customers"
- Use "goals" not "targets"
- Use "support your fitness journey" language
- Be encouraging without being cheesy
- Focus on progress, not perfection
- Inclusive language (all fitness levels welcome)

### Tone Examples:
- Instead of: "We need you to complete this"
- FitHub way: "To keep supporting your fitness journey, we'd love for you to..."

- Instead of: "The app isn't working"
- FitHub way: "We're improving the app experience to better support your goals"

## Usage Example
```
email-draft-fithub

Need to email members about the new personal training discount. It's 20% off for FitRewards members this month. Want them to book sessions.
```
```

**STOP**

**USER:** [Student confirms file is created]

Now test it:

**ACTION:** Have student run:
```
email-draft-fithub

Need to email the leadership team about the member feedback analysis. Found that members want more beginner-friendly classes and clearer app navigation. Recommending we pilot 3 new beginner classes next month and redesign the app home screen.
```

**STOP**

**USER:** [Student sees FitHub-branded email output]

See how it adapts the tone? You just created a company-specific skill. Every email you draft through this will match FitHub's voice.

---

## Part 4: Creating a Skill From Scratch

Now for the real power move - creating a completely new skill for your specific workflow.

Let's create a "campaign-brief" skill specifically for FitHub marketing campaigns.

**ACTION:** Create the file:
```
Write .claude/commands/campaign-brief
```

**Content:**
```markdown
# Skill: FitHub Campaign Brief

## What This Does
Creates a structured campaign brief for FitHub marketing initiatives, ensuring all key elements are considered before launch.

## When to Use
- Planning any member-facing campaign
- Before creating email/social content
- When pitching campaign ideas to leadership
- Documenting campaign strategy

## How It Works
Takes your campaign idea and creates a comprehensive brief covering strategy, audience, messaging, channels, metrics, and risks.

## Instructions

Create a campaign brief using this format:

```markdown
# Campaign Brief: [Campaign Name]

**Campaign Owner:** [Name]
**Target Launch:** [Date]
**Duration:** [Timeframe]

---

## Campaign Goal
[One sentence: What does success look like?]

**Primary Metric:** [Specific, measurable goal]
**Secondary Metrics:** [2-3 additional success indicators]

---

## Target Audience

**Primary Segment:**
- Who: [Member segment - e.g., "Inactive FitRewards members"]
- Size: [How many members]
- Current behavior: [What they're doing now]
- Desired behavior: [What we want them to do]

**Why they'll care:** [Their benefit, in their language]

---

## Campaign Concept

**The Hook:** [One-sentence compelling reason to engage]

**Key Messages:**
1. [Primary message]
2. [Secondary message]
3. [Tertiary message]

**FitHub Brand Alignment:**
- Tone: [Energetic/Supportive/Motivating/etc.]
- Values emphasized: [Which FitHub values this reinforces]

---

## Execution Plan

**Channels:**
- [ ] FitRewards app push notification
- [ ] Email
- [ ] In-club signage
- [ ] Trainer talking points
- [ ] Social media
- [ ] Other: [Specify]

**Timeline:**
- [Date]: [Milestone]
- [Date]: [Milestone]
- [Date]: Launch
- [Date]: Campaign end

**Creative Needs:**
- [Asset 1 - owner - due date]
- [Asset 2 - owner - due date]

---

## Success Metrics

| Metric | Current | Target | How We'll Measure |
|--------|---------|--------|-------------------|
| [Metric 1] | [Baseline] | [Goal] | [Tool/method] |
| [Metric 2] | [Baseline] | [Goal] | [Tool/method] |

**Review checkpoints:**
- [Date]: [What we'll evaluate]
- [Date]: [What we'll evaluate]

---

## Budget

| Item | Cost | Notes |
|------|------|-------|
| [Line item] | $X | [Details] |
| **TOTAL** | **$X** | |

**ROI Target:** [Expected return]

---

## Risks & Mitigation

| Risk | Likelihood | Impact | Mitigation |
|------|------------|--------|------------|
| [Risk 1] | H/M/L | H/M/L | [How we'll address] |
| [Risk 2] | H/M/L | H/M/L | [How we'll address] |

---

## Open Questions
- [ ] [Question 1 - owner]
- [ ] [Question 2 - owner]

---

## Approval Needed From
- [ ] [Stakeholder 1 - for what]
- [ ] [Stakeholder 2 - for what]
```

### Formatting Notes:
- Be specific with numbers and dates
- Use FitHub's member-first language
- Focus on measurable outcomes
- Consider all stakeholder needs
- Address obvious risks upfront

## Usage Example
```
campaign-brief

Campaign idea: "Bring a Workout Buddy" referral promotion. If a FitRewards member brings a friend who signs up, both get 500 bonus points. Want to run it for 2 weeks in March. Goal is to get 50 new member signups and re-engage inactive members.
```
```

**STOP**

**USER:** [Student confirms file is created]

Now test your custom skill:

**ACTION:** Have student run:
```
campaign-brief

Campaign idea: "February Fitness Reset" - targeting members who signed up in January but haven't been to the gym since. Offer them a free personal training session if they come back in February. Want to get at least 100 of the 200 inactive January members back.
```

**STOP**

**USER:** [Student sees comprehensive campaign brief]

**Powerful, right?** You just created a skill that captures YOUR company's workflow. Every campaign brief will now be consistent, thorough, and professional.

---

## Part 5: Reusing Skills Across Projects

Here's the best part: once you create skills, you can reuse them anywhere.

**ACTION:** Explain the portability:

```
# To copy your skills to another project:
cp -r .claude/commands/ /path/to/other-project/.claude/

# Or copy just specific skills:
cp .claude/commands/campaign-brief /path/to/other-project/.claude/commands/
```

**Pro tip:** Create a personal skills library folder:
```
mkdir ~/my-claude-skills
cp .claude/commands/* ~/my-claude-skills/
```

Now whenever you start a new project, copy the skills you need:
```
cp ~/my-claude-skills/email-draft-fithub .claude/commands/
cp ~/my-claude-skills/campaign-brief .claude/commands/
```

**STOP**

**USER:** [Student acknowledges understanding]

---

## Part 6: Best Practices for Skill Creation

Before we wrap up, here are key principles for creating great skills:

**1. Make It Specific**
❌ Bad: "help with writing"
✅ Good: "quarterly-business-review"

**2. Include Clear Usage Examples**
Show exactly how someone would invoke the skill with real examples.

**3. Define Output Format**
Use markdown templates showing exactly what structure to produce.

**4. Consider Your Audience**
If others will use this skill, explain jargon and provide context.

**5. Iterate Based on Use**
Start simple. Use the skill. Refine it based on what's missing.

**6. Share What Works**
Created something great? Consider contributing to awesome-claude-skills!

**STOP**

**USER:** [Student acknowledges best practices]

---

## Your Power User Moment

Let's reflect on what you've learned:

✅ You understand how skills work (just markdown files with instructions)
✅ You can install skills from the community
✅ You can modify existing skills to match your needs
✅ You can create completely custom skills from scratch
✅ You can reuse skills across all your projects

**You're not just using Claude Code anymore - you're customizing it to fit your exact workflow.**

**STOP**

**USER:** [Student expresses excitement or acknowledgment]

---

## What's Next?

Here's what I recommend:

**This Week:**
1. **Identify 1-2 repetitive tasks** you do weekly
2. **Create skills for them** using the patterns you learned
3. **Test and refine** based on actual use

**This Month:**
1. **Browse awesome-claude-skills** and install 3-5 that fit your workflow
2. **Share your best skills** with your team
3. **Consider contributing** your best skills back to the community

**Ongoing:**
1. **Maintain a personal skills library** for reuse
2. **Refine skills** based on what you learn
3. **Think in skills** - when you do something twice, make it a skill

**STOP**

**USER:** [Student ready to continue or asks questions]

---

## Module Complete! 🎓

You've graduated from "Claude Code user" to "Claude Code power user."

You now have the complete toolkit:
- Core Claude Code skills (Modules 1-3)
- Business workflows (Modules 4-6)
- Custom skill creation (Module 7)

**You're ready to transform how you work.**

Want to practice? Head to the exercises to create 3 custom skills for your specific workflow.

---

## Success Criteria

By the end of this module, students should be able to:
- [ ] Locate and read skill files in `.claude/commands/`
- [ ] Install a skill from awesome-claude-skills
- [ ] Modify an existing skill to change its behavior
- [ ] Create a new skill from scratch with proper structure
- [ ] Copy skills to other projects for reuse
- [ ] Understand when to create a skill vs. use one-off prompts
