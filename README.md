# Paddock feedback

This is where feedback on **Paddock** lives: bugs, things that feel wrong or confusing, and ideas.

Paddock is a native Mac client for [Herdr](https://herdr.dev), the runtime your coding agents run in. It shows every agent in one window, in real terminals, tells you which one is waiting on you, and gets you there in two keys. Paddock is independent and not made by Herdr.

## Send feedback

**From the app (best).** Choose **Help › Send Feedback…** or press `⇧⌘/`. Write what felt off and press Send. Your browser opens a new issue here, already filled in with the details we need: app and Herdr versions, macOS version, what was on screen, and your last few key presses. Check it, then press **Submit new issue**.

If you tick **include screenshot**, Paddock copies a picture of its window to your clipboard. Paste it into the issue with `⌘V`.

**By hand.** [Open a new issue](../../issues/new?template=feedback.md) and fill in the template.

You need a GitHub account to file an issue.

## What helps

- **One thing per issue.** Two problems in one issue tend to get half fixed.
- **What you did, what happened, what you expected.** "I pressed the prefix, the hint strip showed for a second and vanished; I expected it to stay until I pressed a key" is easy to act on. "The hints are weird" is not.
- **A screenshot or short screen recording** when it's about how something looks or moves.
- **Whether it happens every time**, or only sometimes.

## Before you submit: this repository is public

Anyone can read what's posted here. Paddock never adds the contents of your terminals, but a screenshot can show code, file paths or names on screen. Look at it before you paste it, and leave out anything private: code, paths, hostnames, tokens, or keys.

## What happens next

Every issue gets read and sorted with a label:

| Label | Meaning |
|---|---|
| `feedback` | New, not looked at yet |
| `bug` | The app doesn't do what it's designed to do |
| `design` | The design itself needs to change |
| `ready` | Understood, and queued for the next round of work |

When something is fixed or changed, the issue is closed with a short note. If an idea isn't going to happen, it's closed with the reason.
