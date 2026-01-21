# Module 7 Exercises: Creating Custom Skills

**Goal:** Practice creating, modifying, and installing custom Claude Code skills

---

## Exercise 1: Explore Existing Skills (Beginner)

**Objective:** Understand skill structure by examining the 8 skills you've been using.

**Tasks:**
1. Navigate to `.claude/commands/` folder
2. Open and read through 3 different skill files:
   - `meeting-notes`
   - `analyze-folder`
   - `competitive-analysis`
3. Identify the common structure in all three
4. Note how instructions differ based on complexity

**Success Criteria:**
- [ ] You can explain the purpose of each section (What This Does, When to Use, Instructions)
- [ ] You understand why some skills have more detailed instructions than others
- [ ] You can describe what makes a skill effective

**Bonus Challenge:**
Pick your favorite skill and explain why it's well-designed. What makes its instructions clear?

---

## Exercise 2: Install a Community Skill (Beginner)

**Objective:** Practice installing a skill from the awesome-claude-skills repository.

**Tasks:**
1. Browse to: https://github.com/ComposioHQ/awesome-claude-skills/tree/master
2. Find a skill that would be useful for your work
3. Copy the skill content (click "Raw" to get clean markdown)
4. Create a new file in `.claude/commands/` with the skill name
5. Paste the content and save
6. Test the skill with a real example

**Recommended Skills to Try:**
- `code-review` - If you review code
- `sql-query` - If you work with databases
- `blog-post` - If you write content
- `data-analysis` - If you work with data

**Success Criteria:**
- [ ] Skill file created in correct location
- [ ] Skill executes successfully when called
- [ ] You understand what the skill does and when to use it

**Bonus Challenge:**
Install 3 different skills and create a personal "Skills Cheat Sheet" document listing what each one does.

---

## Exercise 3: Modify an Existing Skill (Intermediate)

**Objective:** Customize a skill to match your specific needs.

**Scenario:** You want the `email-draft` skill to match your personal communication style.

**Tasks:**
1. Copy `email-draft` to a new file called `email-draft-personal`
2. Modify the instructions to match YOUR preferences:
   - Your typical greeting style
   - Your communication tone
   - Your sign-off preference
   - Any phrases you commonly use
   - Any phrases you avoid
3. Add 2-3 examples of your communication style
4. Test it with a real email you need to write

**Example Customizations:**
- "Always use 'Hope this helps!' as closing"
- "Keep paragraphs under 3 sentences"
- "Never use corporate jargon like 'circle back' or 'touch base'"
- "Include emojis when appropriate for internal emails"
- "Always offer to schedule a call if the topic is complex"

**Success Criteria:**
- [ ] New skill file created with custom name
- [ ] Instructions modified to reflect your style
- [ ] Skill generates emails that sound like you wrote them
- [ ] Original `email-draft` skill still works unchanged

**Bonus Challenge:**
Create three variants: `email-draft-formal` (for executives), `email-draft-casual` (for teammates), and `email-draft-client` (for external stakeholders).

---

## Exercise 4: Create a Simple Skill From Scratch (Intermediate)

**Objective:** Build a brand new skill for a task you do regularly.

**Task:** Create a "weekly-update" skill that helps you write status updates for your manager.

**Your Skill Should:**
1. Ask for this week's accomplishments
2. Ask for next week's priorities
3. Ask for any blockers or help needed
4. Format it in a clean, consistent structure
5. Use professional but concise language

**Template to Start With:**
```markdown
# Skill: Weekly Update

## What This Does
[Your description]

## When to Use
[Your scenarios]

## How It Works
[What output it creates]

## Instructions

Create a weekly update using this format:

**Week of [Date]**

**This Week's Accomplishments:**
- [Item with outcome/impact]
- [Item with outcome/impact]

**Next Week's Priorities:**
- [Item with expected outcome]
- [Item with expected outcome]

**Blockers / Help Needed:**
- [Blocker or help request, or "None"]

**Notes:**
[Any additional context worth mentioning]

[Add your specific formatting and tone preferences]

## Usage Example
```
weekly-update

This week I finished the FitRewards campaign analysis and started drafting the new member onboarding email. Next week I'm finalizing the campaign and presenting to leadership. Need feedback on the campaign budget by Wednesday.
```
```

**Success Criteria:**
- [ ] Skill file created at `.claude/commands/weekly-update`
- [ ] Clear instructions with output format
- [ ] Usage example included
- [ ] Skill works when tested with your real weekly update

**Bonus Challenge:**
Add a section that automatically suggests metrics or data points based on the type of work mentioned.

---

## Exercise 5: Create a Role-Specific Skill (Advanced)

**Objective:** Build a sophisticated skill for a complex task specific to your role.

**Choose ONE of these scenarios** (or create your own):

### Option A: "client-proposal" Skill
Creates client proposals with:
- Executive summary
- Problem statement
- Proposed solution
- Timeline and deliverables
- Pricing breakdown
- Terms and conditions
- Next steps

### Option B: "product-spec" Skill
Creates product specifications with:
- Feature description
- User stories
- Acceptance criteria
- Technical requirements
- Design considerations
- Success metrics
- Open questions

### Option C: "performance-review" Skill
Creates performance review drafts with:
- Achievement highlights
- Growth areas
- Specific examples
- Goals for next period
- Development plan
- Rating justification

### Option D: Your Own Complex Workflow
Think of something you do monthly/quarterly that takes 1-2 hours and has a consistent structure.

**Requirements:**
1. Comprehensive instructions covering all sections
2. Output format with markdown template
3. At least 3 usage examples showing different scenarios
4. Clear guidelines for tone and style
5. Tips for best results

**Success Criteria:**
- [ ] Skill addresses a real, time-consuming task
- [ ] Instructions are detailed enough for consistent results
- [ ] Output format is professional and complete
- [ ] Skill saves you meaningful time (30+ minutes per use)
- [ ] You'd actually use this skill in your real work

**Bonus Challenge:**
Share your skill with a colleague and get their feedback. Refine based on their suggestions.

---

## Exercise 6: Build a Personal Skills Library (Advanced)

**Objective:** Create a reusable library of skills for your workflow.

**Tasks:**
1. Identify 5-7 repetitive tasks you do weekly/monthly
2. Create a skill for each one
3. Organize them in a personal library folder: `~/my-claude-skills/`
4. Document each skill in a master "Skills Index" file
5. Test each skill with real examples
6. Refine based on actual use

**Example Skills Library for a Product Manager:**
- `feature-brief` - Product feature documentation
- `user-story` - User story creation
- `release-notes` - Release note generation
- `roadmap-update` - Quarterly roadmap updates
- `stakeholder-update` - Executive stakeholder updates
- `sprint-planning` - Sprint planning preparation
- `competitive-analysis` - Quick competitor analysis

**Your Skills Index Should Include:**
```markdown
# My Claude Skills Library

## Email & Communication
- `email-draft-formal` - Executive/formal emails
- `email-draft-casual` - Internal team emails
- `meeting-notes` - Convert meeting notes to action items

## [Your Category]
- `skill-name` - Brief description
- `skill-name` - Brief description

[Continue for all categories]

## Quick Reference
**Most Used:** [Your top 3 skills]
**Time Savers:** [Skills that save the most time]
**Specialized:** [Role-specific skills]
```

**Success Criteria:**
- [ ] 5-7 custom skills created
- [ ] Skills organized in dedicated folder
- [ ] Skills Index document created
- [ ] Each skill tested with real examples
- [ ] At least 3 skills actively used in your work this week

**Bonus Challenge:**
Calculate time saved: For each skill, estimate how long the task takes manually vs. with the skill. Project your monthly/yearly time savings.

---

## Exercise 7: Contribute to the Community (Advanced)

**Objective:** Share your best skill with the awesome-claude-skills community.

**Tasks:**
1. Choose your best, most polished skill
2. Review the awesome-claude-skills contribution guidelines
3. Ensure your skill follows the repository's format
4. Add comprehensive usage examples
5. Consider submitting a pull request (optional but encouraged!)

**What Makes a Good Community Contribution:**
- ✅ Solves a common problem many people face
- ✅ Clear, detailed instructions
- ✅ Multiple usage examples
- ✅ Well-organized output format
- ✅ Professional tone and formatting
- ✅ Includes tips for best results

**Skills Worth Sharing:**
- Industry-specific workflows (finance, healthcare, legal, etc.)
- Role-specific tasks (PM, marketing, sales, etc.)
- Universal business needs (reporting, analysis, communication)

**Success Criteria:**
- [ ] Skill is polished and professional
- [ ] Instructions are clear enough for strangers to use
- [ ] Multiple examples demonstrate versatility
- [ ] You'd be proud to have your name on it

**Bonus Challenge:**
Actually submit the skill to awesome-claude-skills via pull request and see if it gets accepted!

---

## Reflection Questions

After completing these exercises, reflect on:

1. **What surprised you most about skill creation?**

2. **Which skill you created will save you the most time?**

3. **What repetitive task haven't you turned into a skill yet, but should?**

4. **How does understanding skill creation change how you think about using Claude Code?**

5. **What skill would be valuable for your entire team? How would you introduce it to them?**

---

## Next Steps

**This Week:**
- [ ] Create 2-3 skills for your most repetitive tasks
- [ ] Use them in your real work and refine based on results
- [ ] Share one skill with a colleague

**This Month:**
- [ ] Build a personal skills library with 10+ skills
- [ ] Install 5+ skills from awesome-claude-skills
- [ ] Track time saved and calculate ROI of your skills

**Ongoing:**
- [ ] When you do something twice, ask: "Should this be a skill?"
- [ ] Continuously refine skills based on actual use
- [ ] Share great skills with your team
- [ ] Consider contributing your best skills to the community

---

## Resources

**awesome-claude-skills Repository:**
https://github.com/ComposioHQ/awesome-claude-skills/tree/master

**Your Course Skills (Examples to Study):**
- `.claude/commands/meeting-notes`
- `.claude/commands/email-draft`
- `.claude/commands/analyze-folder`
- `.claude/commands/web-synthesis`
- `.claude/commands/compare-docs`
- `.claude/commands/executive-summary`
- `.claude/commands/decision-matrix`
- `.claude/commands/competitive-analysis`

**Skill Creation Template:**
See Module 7 interactive lesson for the full template structure.

---

## Congratulations! 🎓

You've completed the entire Claude Code for Business Professionals course. You're now equipped to:
- Use Claude Code for real business workflows
- Create custom automation for your specific needs
- Share skills and best practices with your team
- Continuously improve your productivity toolkit

**You're a Claude Code power user. Now go save some time!**
