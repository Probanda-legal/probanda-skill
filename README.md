# Probanda skill

The `/probanda` skill helps you use [Probanda](https://probanda.legal) in your own Chrome. It opens Probanda, waits while you sign in or create your account, and then does one of these:

- Firm profile set-up: fills in a new firm's profile from the firm's public website, then lists each value it filled so you can change any of them.
- Members set-up: adds the firm's people to its member list from the firm's public website, then lists who it added. It sends nothing and gives nobody access; you invite each person yourself.
- New matter: when you ask it to add a new matter and give the path of the client's folder on your computer, it reads the folder, asks you once about anything it is unsure of, fills New Matter, creates the matter and lists each value with the document it came from. Reading a folder on your computer needs Claude Code on that computer, or a folder you connected in Cowork.

The skill does these without asking first, because you can correct or undo each one on the page. It never does a step that cannot be undone or that leaves your firm, such as sending an invitation or changing a person's access: those stay with you.

It needs Claude in Chrome connected to your Chrome. You sign in, verify your email and create your firm yourself; the skill never touches those pages.

## Install

In Claude Code, run these two commands:

```
/plugin marketplace add Probanda-legal/probanda-skill
/plugin install probanda@Probanda_Skill
```

## Use

Type `/probanda`. If your Claude app does not find it under that name, type `/probanda:probanda`.
