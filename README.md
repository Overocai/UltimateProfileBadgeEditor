# Ultimate ProfileBadgeEditor

Add and remove visual profile badges on your own Discord account — **100% client-side**.

Right-click your own profile → **Edit Badges**. This opens an editor with a badge list, click-to-toggle switches, and a live preview.

Every official Discord profile badge is included — see [Included badges](#included-badges) below.

> [!IMPORTANT]
> **Only you can see these badges.** They are purely visual and show up only in your own client.
> The plugin **does not change your account**, **never touches your token**, and **sends nothing** to Discord or any server. Other users never see them.

> [!WARNING]
> **Honestly? I hate this plugin.** I only made it to please people. **If this thing breaks, I'm not fixing it.** No support, no updates. Use it as-is.

## Included badges

All 37 official Discord profile badges that have a real Discord icon:

**Staff & Bug Hunters**
- Discord Staff
- Discord Bug Hunter
- Discord Golden Bug Hunter

**Partner, Mod & Developers**
- Partnered Server Owner
- Moderator Programs Alumni
- Active Developer
- Early Verified Bot Developer
- Early Supporter

**HypeSquad**
- HypeSquad Events
- HypeSquad Bravery
- HypeSquad Brilliance
- HypeSquad Balance

**Nitro**
- Discord Nitro
- Nitro Bronze, Silver, Gold, Platinum, Diamond, Emerald, Ruby, Opal

**Server Booster**
- 1, 2, 3, 6, 9, 12, 15, 18 and 24 months

**Bot**
- Supports Commands
- Premium App
- Uses AutoMod

**Other**
- Discord Quests
- Legacy Username ("Originally Known As")
- Orbs
- A Clown, For a Limited Time

> [!NOTE]
> Server badges, username flairs (Bot / System / AI / OP / Webhook) and clan tags are **not** profile badges, so they can't be shown here.

Badge list verified against:

- [Badges — Discord Wiki (Fandom)](https://discord.fandom.com/wiki/Badges)
- [Official Discord Badges — Discord Resources](https://discordresources.com/resources/official-badges/)
- [mezotv/discord-badges](https://github.com/mezotv/discord-badges)

## Why this plugin exists

I **don't** like the idea of faking things you don't actually have. I made this as an **honest, safe alternative** to what clients like **Nightcord** sell.

Nightcord's whole appeal is making it "look like you have badges you don't" — except it ships that inside a closed-source, pirated client that **has already stolen accounts**:

- **Confirmed token grabber in v1.18.2** — code that **uploaded your Discord token** to Nightcord's server, disguised as "Premium Sync", via a `POST` request to an external VPS (`nightcord.ru`). You can verify it by searching for `x-discord-token` in the archived release's `renderer.js`.
- **Detected as malware** by Kaspersky: `HEUR:Trojan-PSW.Multi.Disco.gen` (Trojan-PSW / Token Grabber). The security analysis was marked "Threat Confirmed".
- **GitHub permanently banned** the project's repositories.
- **Piracy:** the (~1 GB) download bundles **Discord's own binaries** without authorization and violated the GPL licenses of **Vencord** and **Equicord**, which it was forked from.
- One of the main devs was **flagged for fraud/spam** by Discord. Even in the "cleaned" versions, someone who shipped malware once can't be trusted.

This plugin only does the cosmetic part — no token grabber, no network, no binaries to download — on top of open-source, auditable **Equicord**.

### Sources

- [Nightcord is actually malware — gist by Vendicated (Vencord's creator)](https://gist.github.com/Vendicated/bb30cb67878fa682bcee140f56af1531)
- [Nightcord Security Analysis Report — Threat Investigation](https://gist.github.com/ImMayunnaise/4341f7333de34524a0487effc4735ddb)
- [nightcord-cleaned-source (the "cleaned" post-token-grabber version)](https://github.com/luoxthedev/nightcord-cleaned-source)
- [o9ll/nightcord — repository labeled "free malware"](https://github.com/o9ll/nightcord)

## Usage

- Enable the plugin.
- Right-click your own profile and pick **Edit Badges** (or open the plugin settings and click **Open Badge Editor**).
- Toggle the badges you want. Your selection is saved and persists across Discord restarts.
- Profile badges appear/update when you reopen your profile; the editor preview shows the result instantly.

## Author

Made by [overocai](https://discord.com/users/1288832011452153910) (`1288832011452153910`).
