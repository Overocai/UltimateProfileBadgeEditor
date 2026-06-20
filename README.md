# Ultimate ProfileBadgeEditor

Add and remove visual profile badges on your own Discord account — **100% client-side**.

Right-click your own profile → **Edit Badges**. This opens an editor with a badge list, click-to-toggle switches, and a live preview.

Every badge is available: Discord Staff, Partnered Server Owner, Moderator Programs Alumni, Early Supporter, Active Developer, Early Verified Bot Developer, Bug Hunter (and Golden), all four HypeSquad badges, Quests, Legacy Username, Orbs, the limited-time Clown, Supports Commands, Premium App, Uses AutoMod, every Nitro tier (Bronze through Opal), and every Server Booster level (1 month to 24 months).

> [!IMPORTANT]
> **Only you can see these badges.** They are purely visual and show up only in your own client.
> The plugin **does not change your account**, **never touches your token**, and **sends nothing** to Discord or any server. Other users never see them.

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
