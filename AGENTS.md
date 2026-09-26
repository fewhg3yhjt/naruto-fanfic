# Project instructions

## Commit and push completed changes

- For a task that changes project files, finish the requested work and the relevant verification, then create one commit for the completed task and push the current branch to its configured upstream. If the branch has no upstream, push it to `origin` and set the upstream.
- Do not create a commit for read-only answers, reviews, or tasks that make no file changes.
- Before editing, inspect `git status` and treat every pre-existing change as user-owned. Do not stage, commit, revert, or otherwise alter those changes unless the user explicitly includes them in the task.
- Before committing, review the staged diff and stage only the explicit paths changed for the current task. Do not use `git add -A` or a blanket `git add .` when unrelated or pre-existing changes are present.
- Use a concise Chinese Conventional Commit-style message that describes the actual change.
- This repository is public. Check the files being committed for credentials, tokens, private keys, local environment files, and other sensitive data; never publish those files.
- If the branch is in a merge, rebase, cherry-pick, or conflict state, or if the remote has diverged, stop before committing or pushing and explain what needs attention.
- Never force-push, rewrite published history, or discard user changes. If authentication or network access prevents a push, keep the local commit and report the exact blocker without claiming the push succeeded.
- After pushing, verify that the current commit is on the configured upstream and report the commit, branch, and push result.
