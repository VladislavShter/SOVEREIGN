# Your phone spies on you — and it stopped being about the flashlight long ago

*A year ago I opened my phone's settings and scrolled through the app list. And it hit me: I'm not the one using these apps — they're using me. Here's what I did about it.*

## The surveillance you never see

The classic example is a flashlight app that somehow wants your location and your Wi-Fi map. But let's be honest: **not every flashlight spies, and not on every phone.** This stopped being about a specific icon a long time ago.

By 2026, manufacturers and ad networks learned something far subtler. Data collection moved into **invisible system apps and background services — many of which don't even have an icon on your home screen.** You don't know about them, you never opened them, and you can't delete them. Yet they quietly harvest your location, the map of devices around you, your identifiers, the pattern of your movements. That builds a digital model of you — one you never agreed to — and it lives not in your pocket, but on someone else's servers.

We treat this like the weather. But one thought stuck with me. In a kitchen there's an iron rule: raw meat doesn't share a shelf with cooked food. That's not paranoia — it's hygiene. In the digital world we threw everything onto one shelf: government services, banking, private messages, photos of our kids, a crypto wallet. Any app can potentially see its neighbor. The digital world forgot about hygiene. I decided to bring it back.

## Why antivirus and "incognito" won't save you

The first instinct is an antivirus or incognito mode. It doesn't work. Antivirus catches viruses, not the legal data collection you tapped "Allow" on yourself. Incognito hides your browser history from your family, not from the sites.

The second idea — "I'll just quit apps." Also a miss. Try living in 2026 without a banking app, government services and a marketplace. That's not freedom, that's self-exile from reality.

The third — custom ROMs and root. It works, but it's a path for the 0.1% of geeks. A normal person won't reflash their phone and void the warranty. I wanted a solution for normal people: **let every app work as usual, but stop them from seeing each other. No root. On the phone already in your pocket.**

## Three identities in one phone

That's how **Sovereign** was born — an app that splits one phone into three isolated spaces.

**Citizen.** The public-facing side: government services, banks, marketplaces, and mass messengers such as MAX and Telegram. Everything works in full. The state sees an ordinary citizen with an ordinary phone. Sovereign simply shows you what these apps are doing.

**Human.** Your private life. Messengers for private conversation (such as Signal), crypto wallets, torrent hubs, personal photos and mail. Its own storage, its own keys. Citizen cannot read a single file from here.

**Sovereign.** An encrypted enclave for what matters most. It isn't shown in the app list. To an ordinary inspection of the phone, there's simply nothing there to open.

The key point: this is **not a sandbox and not a clone**. Isolation runs at the operating-system level — through standard Android mechanisms (work profile and enclave). So **no root** is needed, no custom ROM. It installs like an ordinary app.

## What's inside

I won't hide the features behind vague words — here's what v1.0 actually does:

- **Sovereign X-Ray** — an X-ray of surveillance. A live map of which app sends what data, where, right now. You see the "invisible" service pinging analytics, and the bank firing dozens of requests an hour even while locked. Plus a weekly plain-language report.
- **Sovereign Compass** — a one-glance threat light: green / yellow / red in the status bar, from analysis of hundreds of on-device signals. No internet needed.
- **Encrypted vault with post-quantum protection** — the Android hardware module plus the Kyber and Dilithium algorithms on top of AES. Honestly: the post-quantum part protects the key, against "store now, decrypt later" attacks.
- **Sovereign Whisper** — an AI that runs offline, right on the phone: translate, summarize, search your vault. Without a single outgoing packet to the cloud.
- **The Veil** — a hidden vault. When veiled, there's no visible vault — no folder, no icon. Plus a duress wipe: enter a decoy password and a hollow shell opens.
- **Mesh, Air Gap, separate DNS** — phone-to-phone file transfer with no server, fully cutting a profile off the network, isolating network traffic.

## Honestly, what Sovereign does NOT do

Marketing "absolute protection" is a lie, and I don't sell that. Sovereign is digital hygiene, **not an invisibility cloak against state agencies**.

The hidden vault gives plausible deniability at an **everyday level** — real protection against someone who picked up your phone, but not a mathematical guarantee against a state forensic lab. Without root, the operating system imposes limits, and I don't bypass them or promise to. My goal is simpler and more honest: to separate the state and banks from your private life the way a kitchen separates raw from cooked.

## Why solo

I have no team and no funding round. I have a phone, a laptop and stubbornness. I wrote and tested every feature myself, on a real device. It's slow and hard — but solo development has one advantage: **there's no one for me to sell your data to.** The app has no cloud, no servers, no subscription. It can't leak — it has nowhere to.

Hence the philosophy I built into the project: **you are a subject, not a function.** A tool should work for you, not you for the tool.

## How to try it

Sovereign is finished, tested and packaged as an installable **.apk**. The license is one-time, lifetime, no subscriptions. Payment in USDT/USDC; after payment your key, the download link and the full manual arrive by email.

- **Sovereign page (demo & buy):** https://s0vereign.pw/sovereign.html
- **Watch the demo on YouTube:** https://youtu.be/cvy4_lwi-TI

## The ecosystem

Sovereign is part of the digital ecosystem of solo developer **Vladislav Shter**:

- **Sovereign** — personal data protection on your phone (this article).
- **Egregor** — a desktop multi-AI consilium, **already on sale**.
- **SovereignWeb3 Browser** — a unique Web3 browser, **coming soon**.
- **SovereignBank-Web3** — non-custodial on-chain banking.

Links:

- Ecosystem site — https://s0vereign.pw/
- GitHub — https://github.com/VladislavShter/SOVEREIGN
- GitVerse (mirror) — https://gitverse.ru/wadyas/SOVEREIGN
- SovereignBank-Web3 — https://github.com/VladislavShter/SovereignBank-Web3
- Demo — https://youtu.be/cvy4_lwi-TI

*Created solo, against inevitability. — Vladislav Shter*
