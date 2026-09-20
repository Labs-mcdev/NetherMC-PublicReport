# NetherMC player reports and appeals

**English** · [中文](docs/i18n/README.zh.md) · [日本語](docs/i18n/README.ja-JP.md) · [हिन्दी](docs/i18n/README.hi-IN.md)

> If language versions differ or are ambiguous, the English version governs the interpretation of NetherMC rules. Report wording or translation issues through **Report a vulnerability** under [Security and quality](https://github.com/SchemaFoxLabs/NetherMC/security).

## Purpose

Use this repository to report player misconduct while staff are offline or to appeal a restriction you believe was applied by mistake. Use in-game reporting first when staff are online. Skin reports are accepted only in-game.

Server and website bugs, questions, and feature requests belong in the [main repository](https://github.com/SchemaFoxLabs/NetherMC/issues/new/choose). Report vulnerabilities through the main repository’s [private security route](https://github.com/SchemaFoxLabs/NetherMC/security).

## Quick navigation

- **[Server and community rules](https://github.com/SchemaFoxLabs/NetherMC/blob/main/docs/SERVER_RULES.md)**
- **[Submit a player report](https://github.com/Labs-mcdev/NetherMC-PublicReport/issues/new?template=player_report.yml)**
- **[Submit a report without media](https://github.com/Labs-mcdev/NetherMC-PublicReport/issues/new?template=player_report_no_media.yml)** — CSAM Content or Illegal PlayerID
- **[Submit a sanction appeal](https://github.com/Labs-mcdev/NetherMC-PublicReport/issues/new?template=appeal.yml)**
- **[Main repository](https://github.com/SchemaFoxLabs/NetherMC)**

## Player reports

A player report requires a valid in-game **Report-ID**. Staff use the associated game record to check the reporter and reported player; the ID alone is not identity verification.

Streamer Mode hides the relevant chat display. View your report records with:

```minecraft-command
/report-mylist
```

Old records are periodically cleared. If the original ID is unavailable, go to the subserver where the incident occurred and obtain a new ID with:

```minecraft-command
/inforeport
```

State the original incident time and events accurately. A new ID does not restore cleared records.

Organize the submission as **Report-ID → incident context → confidence and its basis → redacted evidence**. Higher confidence requires clearer and more complete evidence. Confidence is the reporter’s assessment and does not determine a penalty.

For CSAM Content or Illegal PlayerID, use the no-media form. Do not download, copy, upload, forward, or link to CSAM. Provide only non-graphic locating information.

## Sanction appeals

### Join Block

You cannot join the main lobby or any subserver while the restriction is active. An authorized `Author` can lift it. The connection screen displays:

- block reason
- block-ID

### SubServer Block

You cannot join the affected subserver while the restriction is active. An authorized `Author`, `Staff`, or `Admin` can lift it. Chat displays:

- block reason
- block-ID
- block-duration

### Feature Block

You cannot use the affected feature while the restriction is active. This may include Ranked, public chat, private messages, or cross-subserver chat. An authorized `Author`, `Staff`, or `Admin` can lift it. Chat displays:

- disable reason
- `disable-duration`

Restriction durations follow the [server and community rules](https://github.com/SchemaFoxLabs/NetherMC/blob/main/docs/SERVER_RULES.md).

In an appeal, provide the restriction type, optional **Player ID**, affected subserver or feature, approximate time in **UTC−8**, displayed reason, grounds for appeal, and any redacted supporting material. If you leave the Player ID blank, request a private contact method (PM if available) in the public Issue and provide the ID only through that private method.

## Privacy and handling

Do not publish real names, private contact details, credentials, private account information, sensitive identifiers, or unrelated personal information. Redact screenshots while retaining the context needed for review.

Staff review submissions as time and available evidence allow. The usual **1–7 days**, or **8–30 days** during busy periods, are reference estimates for initial handling or a first reply.

Ask about a suitable method before sending sensitive evidence.
