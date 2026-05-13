[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/vanderbilt-data-science/ai-summer-2025)

# AI Summer
> Summary repository for AI Summer 2026. Introduction to generative AI, with practical applications for inferencing and training
> May 5-30, 2026

Presented by Vanderbilt Data Science Institute data scientists:
* Dr. Jesse Spencer-Smith, Chief Data Scientist
* Umang Chaudhry, Senior Data Scientist
* Myranda Shirk, Senior Data Scientist

## Overview
The objective of these workshops is to develop foundational skills in understanding, inferencing and training generative AI models and other transformer models.  

## Getting Ready for AI Summer


### Getting Accounts

You’ll want to use the most advanced AI chat model that you can get access to. To get a headstart, please create an account with https://claude.ai/ .  We will be spending a signficant time using Claude, Claude Cowork and Claude Code. Please sign up for a paid Claude account to gain access to these tools. 


### Decide on a Project (recommended)

Think about any data you might want to bring to the workshop. Also begin thinking about any projects you might want to accomplish during our month. We’ll have office hours for you to work with us to get your first project off the ground!

## Workshop Schedule and Recordings

Session will run live from 11am-1pm, with an office hour from 1pm to 2pm (all times Central). 

### Week 1

#### Day 1 — Tuesday, May 5, 2026

**Topics covered:**
- Working with secure data: Vanderbilt's data classification levels (1–4) and the AI tool that fits each one
- Opting out of training, ChatGPT EDU, Vanderbilt's Amplify, and where Claude / Cowork / Code fall in the framework
- Working locally: open-source models, quantization, distillation, and PEFT
- Demo: LM Studio for fully-local model use
- Tour of Claude Chat vs. Claude Cowork vs. Claude Code (desktop and CLI)
- What separates a chat from an agent: planning, task files, sub-agents, evaluation
- How LLMs actually work: tokens, embeddings, attention, MLP, temperature
- Context as the central problem: tools, MCPs, RAG, and context rot
- Skills and the agent harness ("Agent 2.0"); progressive disclosure
- Live build: co-creating a "sensitive field detector" skill in Claude Cowork

**Resources:**
- [Lecture notes](Lecture-Notes/week1-day1/week1-day1-lecture-notes.md)
- [Zoom recording](https://vanderbilt.zoom.us/rec/share/8jCW_cYAo8RbyeqBRKQkG_Br5FuSPyUp0Daq4Uokj4gQeF94tIM9kHFui827Ui2C.C8Y4xumD1BjVobtV)

#### Day 2 — Thursday, May 7, 2026

**Topics covered:**
- Recap: chat vs. agent (replay), and what "Agent 2.0" means
- Walkthroughs of two real skills: the sensitive-field detector and the lecture-recording-to-lecture-notes skill that produced these notes
- Three surfaces for creating skills — Chat, Cowork, Claude Code — and how to match the surface to the skill
- Anatomy of a SKILL.md: YAML frontmatter, body, `$ARGUMENTS`, and the lesser-known flags (`disable-model-invocation`, `user-invocable`, `allowed-tools`)
- Progressive disclosure: how metadata / body / bundled-files load in three levels
- Where skills live: Enterprise vs. Personal/Global (`~/.claude/skills/`) vs. Project (`<project>/.claude/skills/`)
- Writing skill descriptions that actually trigger
- Case study: the three-step composable accessible-housing research pipeline (programs → housing → audit)
- Four design patterns from the pipeline: canonical taxonomies, do/not-do tables, confidence ratings, cross-skill references
- Skill-building framework and when to reach for the Skill Creator Skill
- Model Context Protocol (MCP): what it is, how to set up a server, and how skills layer on top of MCPs
- Claude Code modes (plan / accept-edits / ask), effort levels, and routines

**Resources:**
- [Lecture notes](Lecture-Notes/week1-day2/week1-day2-lecture-notes.md)
- [Zoom recording](https://vanderbilt.zoom.us/rec/share/anhF20gurjZiab-ErYiOJ1t1cBV8bhEy6CMkXOdoA5XfBpRHukSim--LTaBN-zwM.6KpavNU327NcOWBX?startTime=1778169302000)

### Week 2

#### Day 1 — Tuesday, May 12, 2026

**Topics covered:**
- Recap of the agent framework with three zoom levels: the LLM, the harness, and the working space
- Where a skill actually lives on disk — global vs. project vs. session vs. Anthropic-bundled
- Anatomy of a skill folder: SKILL.md (required), scripts/, references/, evals/, LICENSE
- How to tell if Claude actually used your skill (and the slash-command trick to force it)
- One-verb rule for deciding when a task is one skill vs. many
- Two skill composition patterns: linear chain and fan-out / fan-in
- Spec-driven development: writing a precise, testable specification before you build
- Anatomy of a good spec: Goal, Inputs/Outputs, Constraints, Acceptance Criteria
- Three levels of tests: smoke, correctness, and edge cases
- Live demos: skill that didn't trigger (vague prompt), the Customize → Skills panel, dissecting a real skill in breakout rooms
- Office hours: vetting third-party skills, prototyping security middleware, Level-3 Claude on AWS update

**Resources:**
- [Lecture notes](Lecture-Notes/week2-day1/week2-day1-lecture-notes.md)
- [Zoom recording](https://vanderbilt.zoom.us/rec/share/zxaHNDHPrwJn0YUDb5UInvvDgnWmeGOJS-L5YoSZa6gFeu6TRgwDcz21nRvnXW2M.fb9kXCmzyHvB_SEt?startTime=1778601193000)

### Week 3, 

### Week 4, 


## Breakout Rooms

### How to Breakout

Remember we are all learning and exploring
- Please share your video upon entering the room and unmute
- Share your screens--someone volunteer to share their screen upon entering, and everyone be ready to share your screen to show what you’ve found
- Make notes of what you’ve discussed in the Response Reports below
- Everyone be ready to report out (random)
- Make some friends
- Breakout Rooms Worksheets

### Report Documents
Google Docs has a limit of 100 people viewing/editing a document at one time. 


### Special Breakout Room Groups

Please be sure your display name is set in Zoom. If you are in one of the following special groups, please pre-pend your name with one of the following qualifiers. 
- Data Science for Social Good: DSSG
- If you are in a lab and would like your own breakout room: Labname (keep it short, please!)
- If you are faculty and would like to be in a breakout room with other faculty: Faculty

For example, I might be *DSSG-Jesse Spencer-Smith*


## Workshop Video Recordings
Video recordings of these workshops can be found on our YouTube [channel](https://www.youtube.com/@VUDataScience/playlists)

Looking for the code resources for Summer 2025? See the archive folder.

## Course Resources

- Visual overview of Generative AI from 3Blue1Brown: https://www.youtube.com/watch?v=wjZofJX0v4M 
- Semester-long course on transformer models, DS 5690. Graduate students and advanced undergraduates can register by contacting Jesse Spencer-Smith. We welcome auditing by a select number of postdoctoral fellows, and drop-ins from faculty! 

## Other Resources

### Compute Grants for Vanderbilt Faculty and Students

DGX A100 Compute Grant: [https://forms.gle/2mGfEy9DB4JU2GpZ8](https://forms.gle/EKUNHnUSVPPCh9qX6)

### Python

### Transformers
-  Natural Language Processing with Transformers by Lewis Tunstall, Leandro von Werra and Thomas Wolf. If you are affiliated with Vanderbilt University, you can access this pre-print book (and any book by O’Reilly) free by logging into O'Reilly Media using your Vanderbilt email address. Vanderbilt licenses all content from O’Reilly. The book covers Transformers for purposes beyond text. 

### Getting the Most out of this Course
To get the most out of this workshop:
* Open Colab (workbook) notebooks and actively write code along with the instructor
* Actively participate in discussions
* Actively participate in breakout rooms
* Work on homework assignments before coming to class
* Relax your mind and ask questions
