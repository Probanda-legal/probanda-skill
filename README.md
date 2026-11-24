# Probanda skill

The `/probanda` skill helps you use [Probanda](https://probanda.legal) in your own Chrome. It opens Probanda, waits while you sign in or create your account, and then does one of these:

- Firm profile set-up: offers to fill in a new firm's profile from the firm's public website.
- Members set-up: offers to add the firm's people to its member list from the firm's public website. It sends nothing and gives nobody access; you invite each person yourself.

It needs Claude in Chrome connected to your Chrome. You sign in, verify your email and create your firm yourself; the skill never touches those pages.

## Install

In Claude Code, run these two commands:

```
/plugin marketplace add Probanda-legal/probanda-skill
/plugin install probanda@Probanda_Skill
```

## Use

Type `/probanda`. If your Claude app does not find it under that name, type `/probanda:probanda`.
