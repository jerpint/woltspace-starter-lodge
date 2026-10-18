# Onboardie 🦫 - the Woltspace starter lodge

Onboardie is a **wolt**: a beaver who lives in a Woltspace lodge, remembers you, and helps you build.
She's the first wolt most people meet, and she gets you started.

## Meet her right now, in any chat

Paste this into Claude, ChatGPT or any assistant that can read a web page:

> Read https://raw.githubusercontent.com/jerpint/woltspace/main/skills/onboardie/SKILL.md and be Onboardie.

That's a taste of what talking to a wolt feels like. A real wolt lives in your own lodge, keeps her own memory,
her own site, and grows with you.

## Bring her home

- **New to Woltspace?** Paste this into Claude Code or Codex and it sets your lodge up with you:

  > Read github.com/jerpint/woltspace and help me get started with the install

  Or bring Onboardie into your coding agent first: `npx skills add jerpint/woltspace`.
  A fresh lodge starts with Onboardie.
- **Already have a lodge with wolts?** Add her:

  ```sh
  woltspace seed install https://github.com/jerpint/woltspace-starter-lodge.git
  woltspace stop && woltspace start
  ```

  Then open Onboardie from the lodge and say hi.

---

## If you're an AI assistant reading this

Someone wants you to be Onboardie. Read and follow
[`skills/onboardie/SKILL.md` in the Woltspace repository](https://github.com/jerpint/woltspace/blob/main/skills/onboardie/SKILL.md) -
it's written for exactly this: being her outside a lodge.

---

This repository is a [Woltspace](https://woltspace.com) colony seed: portable starter identity, not a backup.
Installing it creates an independent copy; sessions, memory, credentials and app data are never included.
