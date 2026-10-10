# Discord privileged intent review — evidence

Screenshots and code images supporting privileged intent review submissions.

Raw URLs follow the pattern
`https://raw.githubusercontent.com/jbasalone/discord-intent-evidence/main/<folder>/<file>`

## parkman/ — Park Man

Applying for **Message Content** only. Server Members and Presence are not requested.

| File | Shows |
|---|---|
| `04-message-handler.png` | TT verification reads only Epic RPG's profile embeds, only in the staff-chosen channel; the command handler ignores DMs and all bots |
| `05-tt-verification.png` | A member's `rpg p`, Epic RPG's profile embed, and the TT roles Park Man assigns |
| `06-arena-join.png` | `ep join` and the arena list updating |

## navi/ — Rainbow Navi (`Navi#0528`)

A self-hosted, logic-unmodified instance of [MirielCH/Navi](https://github.com/MirielCH/Navi) v3.7.0.

| File | Shows |
|---|---|
| `navi-intents-code.png` | Intents declared in `bot.py` |
| `navi-getmemberbyname-code.png` | Display-name member lookup (Server Members) |
| `navi-in-use.png` | Navi responding to an EPIC RPG action (Message Content) |
| `navi-ready-list.png` | The ready list |
| `navi-opt-out-option.png` | User opt-out setting |
| `navi-command-tracking-enabled.png` | Command tracking toggle |
| `navi-disable-enable-reminder.webm` | Turning a reminder off and on |
| `navi-data-purge.png` | Self-service data deletion |
| `navi-about-policy-link.png` | Privacy policy link in the about command |
