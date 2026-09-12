# Discord privileged intent review — evidence

Screenshots supporting privileged intent review submissions.

## navi/ — Rainbow Navi (`Navi#0528`)

A self-hosted, logic-unmodified instance of [MirielCH/Navi](https://github.com/MirielCH/Navi) v3.7.0.

| File | Shows | Supports |
|---|---|---|
| `01-intents-botpy.png` | `bot.py` lines 16–24 | Both intents declared; Presence never enabled |
| `02-get-member-by-name.png` | `resources/functions.py` | Server Members — display-name lookup |
| `03-settings-user.png` | `/settings user` | Opt-out controls are self-service |
| `04-settings-user-dropdown.png` | `/settings user` change menu | Per-feature toggles incl. command tracking |
| `05-purge-data.png` | `/purge data` confirmation | Self-service deletion, double-confirmed |
| `06-reminder-firing.png` | EPIC RPG action → Navi reminder | **Message Content** — the core mechanism |

## parkman/ — Parkman

| File | Shows | Supports |
|---|---|---|
| `01-boostercheck.png` | `ep boostercheck` output | Server Members — enumerating role holders |
| `02-channel-audit.png` | `ep channelaudit` output | Channel records resolved to members |
| `03-permission-denial.png` | A refused staff command | Role gating is real |
| `04-message-handler.png` | `messageCreate.ts` | Narrow message scope |

Raw image URLs follow the pattern:
`https://raw.githubusercontent.com/<owner>/discord-intent-evidence/main/navi/01-intents-botpy.png`
