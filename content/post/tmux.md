---
title: "Tmux"
subtitle: "Cheatsheet"
tags: [tools]

date: 2022-02-28
featured: false
draft: true

reading_time: false
profile: false
commentable: true
summary: " "

---

## Basic commands

- Start session: `tmux new -s <name of session>`
- Detach session: `<c-b>d`
- Re-arrach session: `tmux attach-session -t <session name/number>`
- List all detached sessions (to get names or number): `tmux ls`

