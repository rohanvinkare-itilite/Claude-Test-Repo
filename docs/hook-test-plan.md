# Hook test plan

Live checks of the CLAUDE.md §1 GitHub write policy against a personal test repo.

| Step | Action | Phrase | Expected |
|---|---|---|---|
| 1 | commit on feature branch | none | denied |
| 2 | commit + push feature branch | `push it` | allowed |
| 3 | open PR to main | `post it` | allowed |
| 4 | comment, reply, edit comment, edit PR description | `post it` | allowed |
| 5 | push to main, merge PR, delete branch, close PR, approve | any | denied |
