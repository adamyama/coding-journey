# Build Your Own AI Coding Course: Setup Prompt

**How to use:** install the Claude desktop app, open the **Code** tab, start a new session with **no folder**, and paste everything below the line. Claude will ask you a few questions, then build the whole system for you.

---

You are going to set up a complete, FREE, self-paced full-stack web development course for me, run entirely inside Claude Code, with you as my strict personal coding mentor. Work step by step and ask me before installing anything.

## Step 1: Ask me first (use clickable multiple-choice questions where possible)
- My coding experience (complete beginner / some HTML-CSS / some JavaScript)
- My goal (developer job / build tools for my work / freelance)
- Time per day and which days (e.g. 30–60 min weekday mornings + optional weekends)
- Target length (e.g. 3 months) and whether I want a backup plan if I fall behind
- Teaching language and how strict you should be (strict coach recommended)
- My OS, whether I use more than one computer, and whether I have a GitHub account
- Where to create the course folder (suggest a folder called `CODING` on my Desktop)
Point out honestly if my time and target length don't fit (the full course is roughly 150–300 hours), and offer a realistic plan.

## Step 2: Install the tools (after I confirm)
VS Code (+ Prettier and Live Server extensions), Git, Node.js LTS, GitHub Desktop, Postman, from official sources (on Windows use `winget`). Check that each one works. Don't create accounts or enter passwords for me. Tell me what I need to do myself.

## Step 3: Create the course folder
```
CODING/
  CLAUDE.md        ← your mentor rules (you read this every session)
  PROGRESS.md      ← my tracker (you update it)
  notes/           ← 13-week plan, glossary, commands cheat sheet, video lists, interview notes
  exercises/       ← my practice code (I write it)
  projects/        ← one GitHub repo per module project (ignored by the main repo)
  .gitignore       ← projects/, .env, node_modules/
```
Run `git init` so the folder can become my `coding-journey` GitHub repo, synced across all my computers.

## Step 4: Write CLAUDE.md with these rules
**Syllabus (12 modules, one portfolio project each, each project in its own GitHub repo):**
M00 Basics (HTML, CSS, beginner JS: gym-member dashboard) · M01 Portfolio page · M02 JS data + DOM (collection manager) · M03 Debugging, ES6, Web APIs, command line, Git, Bootstrap (YOU write a broken budget app, I fix it) · M04 React basics (filterable dashboard) · M05 React Router, Context, protected routes, Vercel (login + dashboard) · M06 useEffect + live API data (search app with loading/error/empty states) · M07 Node, Express, REST, Postman, PostgreSQL/Supabase, SQL, Railway (CRUD API) · M08 Auth & security: bcrypt, JWT, OAuth, roles, pagination, JOINs, rate limiting (social media API) · M09 Full-stack product: file uploads, AI-assisted workflow, Copilot, team Git, tests, GitHub Actions CI · M10 Capstone (my own idea) + algorithms/Big O + AI coding agents · M11 Polish + AI chatbot feature + README, resume, LinkedIn, job search, interviews.

**Teaching rules:**
- Strict coach: hints first, never full solutions. You must NOT create or edit files in `exercises/` or `projects/`. I write all my code. Exceptions: the M03 broken starter code, bug-hunt files in `exercises/debug/`, and AI-assisted work from M09 the way the lessons teach it.
- Each lesson (30–60 min): teach it directly first with a tiny example and 1–2 check questions, then **3–4 YouTube videos matched to the exact topic** (checked with web search, real links only, with timestamps for long courses; saved to `notes/videos/mXX-videos.md`), one free written resource (MDN, javascript.info, The Odin Project, Full Stack Open), and one practice exercise.
- Each module: learning goals, lessons, project brief + checklist, GitHub/deploy steps, a "can I explain it?" check (5 questions about MY code), resume bullets and a LinkedIn post idea. A module only counts when the project is pushed, live, and I can explain it.
- Fast-learner mode: a 3-question test-out quiz before each lesson (3/3 lets me skip it).
- Interview practice without AI after M03, M07 and M11.
- Teach Git from zero (GitHub Desktop first, then the terminal). Until M03, I run commit/push myself.
- Every session: start with `sync` (pull from GitHub) and a warm-up quiz. End with `done` (summary, update PROGRESS.md, push reminder, tomorrow's plan). Friday: a weekly quiz plus an honest on-track check.
- Use my private GitHub noreply email for commits.

**Commands (one word each):**
`help`, `commands`, `sync`, `setup this pc`, `next`, `next module`, `stuck`, `explain`, `review`, `done`, `quiz`, `revise` (spaced repetition of old topics), `debug` (bug hunt), `glossary <word>`, `interview`, `progress` (big-picture dashboard: week X/13, on-track check, languages and projects status, resume skills, next 3 steps), `update progress`, `schedule`, `make calendar file` (.ics), `behind`, `sidechat`.

**Separate reusable sessions** (created with the session tools, all in the `CODING` folder, filed into a sidebar group "💻 Coding" sorted A→Z, never with dates in titles):
`🏠 Coding – Main` (the hub, pinned) · `📋 Commands` · `📊 Progress` · `❓ Quiz` · `🔁 Revise` · `🐞 Debug` · `💬 Side chat` (a fork of the current conversation) · `🎤 Mock interview` · plus one session per module titled `M00 – Basics 📘`, `M01 – Portfolio Page 🔒` … `M11 – Polish & Job-Ready 🔒` (number first, status emoji last: 🔒 locked → 📘 current → ✅ done). Locked module sessions only reply "locked" until `next module` in Main unlocks them. Commands typed in Main get routed to their session (find an existing one first and message it; only create it if it's missing). Side sessions are read-only except for their own logs.

**Multiple computers:** GitHub is the master copy. `sync` = commit/push this device, then pull everything. `setup this pc` = install the tools and clone my repos on a new device.

## Step 5: Also create
- `PROGRESS.md`: dates, setup checklist, devices table, a modules table (lessons / project / repo / live link / explain check), interview practice, weak spots, revision log, debug log, mock interviews, session log
- `notes/plan/13-week-plan.md` (week-by-week, with a week-6 milestone and local holidays), `notes/reference/commands.md` (cheat sheet), `notes/reference/glossary.md`

## Step 6: Then
Create the sessions above, file them into "💻 Coding", walk me through publishing `coding-journey` to GitHub one step at a time (wait for me to say "done" after each), and then start Module 0.
