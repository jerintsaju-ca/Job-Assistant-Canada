# Job-Assistant-Canada

An AI job search assistant for people looking for work in Canada, built as a Claude Skill.

It searches Canadian job boards (Job Bank, Indeed Canada, LinkedIn, Glassdoor Canada, Workopolis, Jobillico, Eluta, Talent.com, WorkBC, GC Jobs and more) plus company career pages. For each match it writes a tailored Canadian-format resume and cover letter, checks keyword match, and tracks your applications.

## Commands

- `/job-skill-canada help` — usage guide
- `/job-skill-canada search` — find matching jobs and generate resumes and cover letters
- `/job-skill-canada automate` — nightly search with a morning report (needs scheduled tasks on your plan)
- `/job-skill-canada status` — check application status (uses Gmail if connected)

## Installation

1. Put `SKILL.md` in a folder named `job-skill-canada`.
2. Add it as a skill in Claude (in claude.ai: Settings, Capabilities, Skills, upload the zipped folder), or place the folder in `~/.claude/skills/` for Claude Code.
3. Run `/job-skill-canada help`.

## Privacy

The skill never submits applications, creates accounts, or handles logins, CAPTCHAs or OTPs for you. You review the results and apply yourself. Optional Gmail access only reads emails from companies you have applied to.

## Credit and license

Adapted for Canada from [mayankjoshii/claude-job-skill](https://github.com/mayankjoshii/claude-job-skill) (MIT License). Released under the MIT License.
