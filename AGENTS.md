# AGENTS.md

Notes for AI assistants working in this repo (a personal website served by GitHub Pages from `main`).

## Branch before big changes

`main` is the live site: anything pushed to it is public within a minute or two.

When we discuss a large decision or a major change, remind the user to work on a branch before making any edits. Do this at the start of the discussion, before touching files, not after.

Treat these as large or major:
- A redesign or a change of visual style
- Restructuring the page, or adding or removing whole sections or pages
- Changing the headline, positioning, or how the user is branded
- Adding a framework, build step, or dependency
- Changing the domain, repo name, or GitHub Pages settings
- Anything the user might want to undo or compare against the current live version

How to remind:
- Say it in one line, for example: "This is a big change, so I'd suggest a branch first. Want me to create one?"
- Suggest a short descriptive branch name, such as `redesign-hero` or `add-playbook-page`.
- Merge to `main` only after the user has reviewed the change, ideally from a preview of the branch.

Small edits (typos, wording tweaks, a color adjustment) can go straight to `main` once the user approves the push.

## Other conventions

- Ask before pushing: pushing to `main` publishes the site.
- Don't name clients or the user's employer on the site; use generic descriptions like "national fiber infrastructure provider".
- Keep the user's phone number and email off the public pages unless they ask.
