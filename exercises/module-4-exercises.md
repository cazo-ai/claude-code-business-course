# Module 4: Commands & Automation - Exercises

Complete these exercises to master custom commands and workflow automation.

---

## Exercise 1: Create a Feedback Summary Command

**Objective:** Create a reusable command for recurring analysis.

**Tasks:**
1. Create a command called `feedback-summary`
2. The command should:
   - Read all customer feedback files
   - Identify top 3 recurring themes
   - Extract 3-5 notable member quotes
   - Create a dated summary file in the analysis folder
3. Test the command to ensure it works

**Success Criteria:**
- Command file exists in `.claude/commands/`
- Running the command produces consistent, useful output
- Output file is automatically dated

---

## Exercise 2: Create a Campaign Analyzer Command

**Objective:** Create a parameterized command that accepts input.

**Tasks:**
1. Create a command called `analyze-campaign`
2. The command should:
   - Accept a campaign name as input
   - Read that specific campaign file
   - Search feedback files for related mentions
   - Analyze effectiveness
   - Create a campaign analysis report in organized folder
3. Test with at least 2 different campaigns

**Success Criteria:**
- Command works with different campaign names
- Analysis includes both campaign details and member feedback
- Reports are saved with campaign name in filename

---

## Exercise 3: Create a Competitor Intelligence Command

**Objective:** Automate competitive research synthesis.

**Tasks:**
1. Create a command called `competitor-intel`
2. The command should:
   - Read all competitor research files
   - Create comparison matrix of key features
   - Highlight gaps in FitHub's offerings
   - Identify opportunities for differentiation
   - Save as dated competitive-intelligence report
3. Run the command and review output

**Success Criteria:**
- All competitors are analyzed
- Clear comparison structure
- Actionable insights for FitHub
- Report is dated for tracking changes over time

---

## Exercise 4: Create a Quick Wins Command

**Objective:** Create a command that identifies easy improvements.

**Tasks:**
1. Create a command called `find-quick-wins`
2. The command should:
   - Analyze all feedback for easy-to-fix issues
   - Prioritize by frequency of complaint and implementation effort
   - List top 5 quick wins with expected impact
   - Save to organized folder
3. Test the command

**Success Criteria:**
- Quick wins are genuinely easy to implement
- Prioritization makes business sense
- Expected impact is clearly stated

---

## Exercise 5: Create a Brand Voice Checker Command

**Objective:** Create a quality assurance command.

**Tasks:**
1. Create a command called `brand-check`
2. The command should:
   - Read BRAND-VOICE.md to understand FitHub's voice
   - Accept a file or text to check
   - Analyze alignment with brand guidelines
   - Provide specific feedback on tone, language, style
3. Test with one of the old campaign files

**Success Criteria:**
- Command correctly interprets brand guidelines
- Feedback is specific and actionable
- Can identify on-brand vs. off-brand content

---

## Exercise 6: Create a Weekly Status Command

**Objective:** Automate recurring status reporting.

**Tasks:**
1. Create a command called `weekly-status`
2. The command should:
   - Review recent work (check analysis and organized folders)
   - Summarize work completed this week
   - Identify key insights discovered
   - List next week's priorities
   - Create dated weekly status report
3. Run the command

**Success Criteria:**
- Report captures meaningful progress
- Format is consistent and professional
- Could be shared with stakeholders

---

## Exercise 7: Document Your Commands

**Objective:** Create command library documentation.

**Tasks:**
1. Create a file called `command-library.md` in organized folder
2. List all commands you've created
3. For each command, include:
   - Command name
   - What it does
   - How to use it (including parameters)
   - Example usage
   - Where output is saved
4. Add a "Quick Start" section for common workflows

**Success Criteria:**
- All commands are documented
- Documentation is clear enough for someone else to use
- Examples are specific and helpful

---

## Exercise 8: Command Chaining

**Objective:** Practice running multiple commands in sequence.

**Tasks:**
1. Run `feedback-summary`
2. Then run `competitor-intel`
3. Then ask Claude to create an executive brief combining insights from both reports
4. Save as `weekly-exec-brief.md`

**Success Criteria:**
- Commands run successfully in sequence
- Executive brief synthesizes both reports
- Output is polished and concise

---

## Bonus Challenge

**Create Your Own Custom Command:**

Think about your actual work. What analysis do you do repeatedly?

Create a custom command for your real work that:
- Solves a recurring need
- Saves you significant time
- Produces consistent output
- Could be shared with colleagues

Document it in your command library.

---

## Self-Assessment

After completing these exercises, you should be able to:
- [ ] Create custom command files in `.claude/commands/`
- [ ] Build commands with clear, consistent instructions
- [ ] Create parameterized commands that accept input
- [ ] Test commands to ensure reliability
- [ ] Chain multiple commands together
- [ ] Document your command library
- [ ] Apply automation mindset to recurring work

**If you struggled with any exercise, review the Module 4 interactive lesson and study the structure of successful commands. Automation gets easier with practice!**
