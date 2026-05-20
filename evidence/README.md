# Evidence

Every gate in this repo requires proof. A gate is not done because someone said it is done. A gate is done when the evidence file says it is done.

---

## Required proof per gate

Depending on the gate, evidence may include:

- **Screenshots** — UI state, page state, registration form, Facebook post.
- **Command outputs** — `git log`, `tree`, build output, deployment output.
- **Commit SHA** — the exact commit that completes the gate.
- **File tree** — snapshot of `tree` or `ls -R` showing required files exist.
- **Sample content** — actual lesson text, actual post copy, actual video script.
- **Registration test evidence** — a real or test registration that flowed end to end.
- **Links** — where a public artifact exists (Facebook post URL, landing page URL, form URL).

## How to file evidence

- Create a subdirectory per gate: `evidence/<GATE-NAME>/`.
- Put artifacts inside, named clearly (e.g. `commit_sha.txt`, `file_tree.txt`, `screenshot_registration.png`).
- Add a short `evidence/<GATE-NAME>/README.md` listing each artifact and what it proves.

## Rule

If the evidence is not in this folder, the gate is not closed — no matter what anyone says in chat.
