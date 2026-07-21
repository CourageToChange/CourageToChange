# Noorun Nobi

**CompTIA Security+ | Entry-Level Cybersecurity and IT Support | London**

I built a server in my house and now my wife and four of my friends won't get off it.

That's most of what I do outside work. It started because I didn't want to keep paying
Google and Apple to hold our photos, and it turned into the thing I learn on — six
isolated services on Proxmox, locked down properly, hosting everything I build. I'm a
Security Officer at the British Museum at the moment and I'm looking for my first role in
cybersecurity or IT: SOC Tier 1, junior analyst, or a service desk.

## Things I've built

**Home server and security lab** — Six isolated containers on Proxmox: media, network-wide
DNS filtering, private photo backup, e-books, a reverse proxy, and a read-only operations
console I built with an AI coding agent. Key-only SSH, default-deny
firewall, fail2ban, 2FA, TLS, and backups that get checked nightly to make sure they'd
actually restore. My portfolio is served off it, so if you can read this page, it's
working: <https://noor.noorfamily.uk/>

**[Patchwork](https://github.com/CourageToChange/patchwork)** — A mood board my wife uses
for her knitting and clothes-making ideas. Her idea, her direction. I built it by running
a team of AI coding agents: I wrote the specs, split the work between them, made them
review each other, and reviewed and browser-tested every change myself before it shipped.
The agents wrote most of the code. Deciding what was correct and what was safe didn't
leave me.

**Retro Snake Arena** — A multiplayer browser game I deployed on my own server, then
reviewed for security. The review found a score endpoint anyone could call, an uncapped
WebSocket payload, and a rate-limit that was counting the CDN instead of the visitor.
<https://snake.noorfamily.uk/>

**Bloom** — A daily-puzzle app built for one person who uses it every day. No timers, no streaks, nothing that
guilts you into coming back. Runs privately on my server, invite-only.

**Photo and file migration** — Thousands of photos moved off iCloud and Google onto
hardware I own, de-duplicated, metadata intact.

Smaller things are in the repo list — including
[my first ever program](https://github.com/CourageToChange/password-strength-checker), a
password checker in C, which sat here as an empty repo for years because my first `git
push` silently failed and I never checked.

---

📫 nnobi.inbox@hotmail.com · [LinkedIn](https://www.linkedin.com/in/noorun-nobi-6b76a3217) · <https://noor.noorfamily.uk/>
