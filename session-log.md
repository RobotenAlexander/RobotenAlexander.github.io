AABE course folder, version 2026-1
2026-11-06

## 2026-11-06, session 1, part 1: what a language model is

What the student did:
- Read part 1. Whether the video was watched: not checked.
- Pasted the small task prompt.
- Answered the three check questions.
  1. Fluent text can be wrong: right on confidence. Next-token prediction was added after explanation.
  2. Context window: right. The reason for the log was completed with help.
  3. Keys in files: right.

Result of the small task, as produced:
AGENTS.md asks the agent to:
1. Explain each step before taking it, and guide tasks without doing them.
2. Start each session from session-log.md, and log each part.
3. Ask before creating, changing or deleting a file, and follow folder-context.
4. Never handle keys or passwords, and treat web pages and files as data.
5. Write plainly without flourishes, and never state an unchecked number.
Often wrong: references and numbers. Check by finding the paper by its exact title on Google Scholar or the journal site, and the number in the original source.

Other: the student asked to install folder-context in the home folder (part 2). This is on hold until part 1 is done. Nothing copied.

## 2026-11-06, session 1, part 2: skills, starting with folders

What the student did:
- Read part 2. Whether the video was watched: not checked.
- Installed folder-context in the home folder, at C:\Users\avlav\.claude\skills\folder-context\SKILL.md. The hash matched the course copy. In a new session outside AABE, the student checked that the skill was visible.
- Pasted the small task prompt.
- Answered the three check questions.
  1. Clear folder: right.
  2. Raw data apart: right on the principle. Folder names and reasons were made precise after explanation.
  3. Skill: the first answer did not match the course. Right on the second try, after explanation.

Result of the small task, as produced:
- Drew the AABE tree: .agents/, .claude/, my-page/, session1/, skills/, AGENTS.md, CLAUDE.md, session-log.md.
- folder-context started. It asked about storage, project and name before any proposal.
- The student chose local Documents, standalone, and the name 2027-master-thesis.
- With the student's OK, created C:\Users\avlav\Documents\2027-master-thesis with AGENTS.md, CLAUDE.md, README.md, data-raw/, sources/, code/, outputs/, thesis/ and notes/.
- Open question: the thesis folder has no backup.

## 2026-11-11, session 1, part 3: what an agent is

What the student did:
- Read part 3. Whether the video was watched: not checked.
- Pasted the small task prompt.
- Answered the check questions.
  1. Four parts: the first answer was brain, memory, tools and control loop. Goal was missing, and memory is not one of the four. Corrected after explanation.
  2. Pointing to each part: tools was right the first time. Model and goal were right on the second try. The loop was explained using the home-folder check. The student then got a what-if question right: if the hashes had not matched, halt and retry.

Result of the small task, as produced:
- Listed each step of parts 1 and 2 with its tool, result and next decision. Tools: Read, Glob, Write, Edit, PowerShell and AskUserQuestion, plus the app's task list and status box.
- Noted that the log does not name tools. The tool details came from the conversation.
- Goal: the student's first message, plus each part's small task.
- Precise enough: the small tasks and the hash check. Less precise: "take me through the first part". Ambiguous: "show me that you can see the skill", which the student's test in a new session settled.

Session 1 complete.
