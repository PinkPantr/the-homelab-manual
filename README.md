# The Homelab Manual

A step-by-step guide to build a home server from a spare PC. It is written for people who have never done it.

**Read it online:** https://pinkpantr.github.io/the-homelab-manual/

You start with one old mini-PC or desktop. You end with a server that blocks ads for the whole house, keeps your passwords, backs up your photos, streams your media, and hosts game servers for your friends. Each step says what to click or type, why, and what you should see.

## Why this manual exists

Good help for a beginner homelab is hard to find. The sources are scattered. Most of them are threads where people talk about their own setups. Those threads are fun to read. They do not take a beginner by the hand.

This manual is the missing piece. It is one source, well written, in order, and checked for mistakes. It teaches the ideas as well as the commands. You learn what a container is, how to read a command before you run it, and what to do when something breaks.

## Who it is for

- You are new to homelabs and want a clear path from zero.
- You have a spare computer and a home network.
- You are not afraid to type a command if someone explains it.
- You do not need any Linux experience.

## What is inside

78 chapters in 8 parts, plus a glossary, an index, and a map of the containers.

| Part | What it covers |
| --- | --- |
| A. Read me first | What you need, how the manual works, home networking basics |
| B. Build the server | Install Proxmox, SSH, containers, the build wizard |
| C. The essential six and backups | Notifications, monitoring, ad blocking, reverse proxy, first backup job |
| D. The app catalog | 17 apps: passwords, notes, budgeting, automation, smart home, and more |
| E. Media and personal cloud | Movies, TV, music, books, photos, files |
| F. Game servers | Palworld, Minecraft, Project Zomboid, Valheim, a game download cache, a game-server panel, and a retro game library |
| G. When you outgrow 500 GB | Add drives, check disk health, real backups, off-site copies |
| H. Ops and troubleshooting | First aid, monthly care, update alerts, security, dashboards |

## How it is written

The text follows the rules of ASD-STE100 (Simplified Technical English), to about 80%: short sentences, one action in each step, active voice, plain words, and the same word for the same thing. Every chapter was read by hand. Wrong facts and steps that a beginner would fail were fixed.

Some steps were not tested on a live server. If a step does not work for you, open an issue. Say which chapter and which step.

## Files in this repository

- `index.html` and `img/` — the Manual as a website. GitHub Pages serves these.
- `homelab-manual.html` — the whole Manual in one file. Download it to read offline.

## The example network

The Manual uses a made-up home: a server called `homelab`, a private network `192.168.1.x`, a 500 GB SSD, and 16 GB of RAM. Your own addresses will be different. The chapter on networking shows how to find them.

## License

The text and the images are shared under [Creative Commons Attribution 4.0](LICENSE) (CC BY 4.0). You may share and adapt them. You must give credit.
