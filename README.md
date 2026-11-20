# Probanda skill

The `/probanda` skill opens [Probanda](https://probanda.web.app) in your own Chrome, waits while you sign in or create your account, and offers to fill in a new firm's profile from the firm's public website.

It needs Claude in Chrome connected to your Chrome. You sign in, verify your email and create your firm yourself; the skill never touches those pages.

## Install

In Claude Code, run these two commands:

```
/plugin marketplace add Probanda-legal/probanda-skill
/plugin install probanda@Probanda_Skill
```

## Use

Type `/probanda`. If your Claude app does not find it under that name, type `/probanda:probanda`.
