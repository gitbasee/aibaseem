# Release Notes — AI Instruction Files Project

---

## [2026-06-01] — Initial Project Setup

### Prompt Given
> "I want to create a generic instruction files for my project for both front end and back end, which will have below items for now just create folders and empty files as below, we will start putting the actual instructions later. this instruction file should work for any kind of AI model for example Claude code, Co-pilot etc etc
>
> Folders: Rules, Commands, hooks, Agents, Skills
>
> under this location - F:\aibaseem"

### Activities
- Created folder structure under `F:\aibaseem` with the following folders and empty placeholder files:
  - `Rules/frontend.md`
  - `Rules/backend.md`
  - `Commands/frontend.md`
  - `Commands/backend.md`
  - `hooks/frontend.md`
  - `hooks/backend.md`
  - `Agents/frontend.md`
  - `Agents/backend.md`
  - `Skills/frontend.md`
  - `Skills/backend.md`

### Commit ID
> `1780ee6` — feat: initial project structure - add Rules, Commands, hooks, Agents, Skills, and Release notes folders with frontend/backend placeholder files

---

## [2026-06-01] — Release Notes Setup

### Prompt Given
> "Create a folder called 'Release notes' which will have a md file - in that write file write down all the activities done on that folder with commit ids and messages. also capture the prompt given."

### Activities
- Created `Release notes/` folder under `F:\aibaseem`
- Created `Release notes/release-notes.md` to track all project activities, prompts, and commit history

### Commit ID
> `1780ee6` — feat: initial project structure _(included in the same initial commit above)_

---

## [2026-06-01] — GitHub Repository Created & Pushed

### Prompt Given
> "Create a Repo for aibaseem and push the changes to github remote"

### Activities
- Initialized local Git repository in `F:\aibaseem`
- Created initial commit with all 11 placeholder files
- Created public GitHub repository: https://github.com/gitbasee/aibaseem
- Set remote `origin` to `https://github.com/gitbasee/aibaseem.git`
- Pushed `main` branch to GitHub remote

### Commit ID
> `1780ee6` — feat: initial project structure - add Rules, Commands, hooks, Agents, Skills, and Release notes folders with frontend/backend placeholder files

---

## [2026-06-01] — Release Notes Rule Added to Rules Files

### Prompt Given
> "create a instruction under rules md file after every prompt make a entry into release notes"

### Activities
- Added **Rule 1: Release Notes Entry Required** to `Rules/frontend.md`
- Added **Rule 1: Release Notes Entry Required** to `Rules/backend.md`
- Rule mandates that after every prompt, an entry is made in `Release notes/release-notes.md` with prompt, activities, and commit ID

### Commit ID
> `8171a0f` — feat(rules): add release notes entry rule to frontend and backend rules files

---

## [2026-06-01] — Rule 1 Updated in Rules Files

### Prompt Given
> "modify Rule 1 - make entry when the code is committed"

### Activities
- Updated Rule 1 in `Rules/frontend.md` — trigger changed from "after every prompt" to "when code is committed"
- Updated Rule 1 in `Rules/backend.md` — same change

### Commit ID
> `110d639` — feat(rules): update Rule 1 - release notes entry triggered on commit not every prompt

---

## [2026-06-01] — Published to npmjs

### Prompt Given
> "i want to publish this instruction folder into npmjs"
> "i have created a new token by-passing 2factor authentication"

### Activities
- Created `package.json` with package name `@baseeem/aibaseem@1.0.0`
- Created `.npmignore` to exclude `.git` from the npm package
- Fixed `repository.url` field in `package.json` via `npm pkg fix`
- Published `@baseeem/aibaseem@1.0.0` to https://www.npmjs.com/package/@baseeem/aibaseem

### Commit ID
> _Pending_

---

## Notes
- Commit IDs will be updated once a Git repository is initialized (`git init`) and commits are made.
- Each future change should be logged here with the corresponding prompt, activities, and commit ID/message.
