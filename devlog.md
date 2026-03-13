# 17-mov Development Log

Base resource path: `/home/endless/dev/EDSRP_Dev/resources/[17-mov]/`

This dev log is based on the repository commit history and includes the initial file import plus all follow-up code changes.

## 2026-03-12 — Initial files added
**Commit:** `13de624`  
**Message:** `init commit`

Initial resource packages were added under:
- `/home/endless/dev/EDSRP_Dev/resources/[17-mov]/17mov_BuilderJob/`
- `/home/endless/dev/EDSRP_Dev/resources/[17-mov]/17mov_Deliverer/`
- `/home/endless/dev/EDSRP_Dev/resources/[17-mov]/17mov_Electrician/`
- `/home/endless/dev/EDSRP_Dev/resources/[17-mov]/17mov_FpsBooster/`
- `/home/endless/dev/EDSRP_Dev/resources/[17-mov]/17mov_GarbageCollector/`
- `/home/endless/dev/EDSRP_Dev/resources/[17-mov]/17mov_GruppeSechs/`
- `/home/endless/dev/EDSRP_Dev/resources/[17-mov]/17mov_Lumberjack/`
- `/home/endless/dev/EDSRP_Dev/resources/[17-mov]/17mov_OilRig/`
- `/home/endless/dev/EDSRP_Dev/resources/[17-mov]/17mov_Postman/`
- `/home/endless/dev/EDSRP_Dev/resources/[17-mov]/17mov_TreasureHunter/`
- `/home/endless/dev/EDSRP_Dev/resources/[17-mov]/17mov_WindowCleaning/`

Included file types and content in these folders:
- Core resource files (`fxmanifest.lua`, `Config.lua`, client/server Lua scripts)
- UI files (`web/newui/*`, `web/oldui/*`, `driver.html`)
- Streamed assets (`.yft`, `.ytd`, `.ydr`, `.ytyp`, `vehicles.meta`, etc.)
- Documentation files (e.g., `readme.md`, `instructions.md` where applicable)

---

## 2026-03-12 — Treasure Hunter scuba cleanup logic update
**Commit:** `d8787de`  
**Message:** `Replace scuba cleanup polling thread with state bag handler`

Changed file:
- `/home/endless/dev/EDSRP_Dev/resources/[17-mov]/17mov_TreasureHunter/client/functions.lua`

Summary:
- Reworked scuba gear cleanup behavior to use a state bag handler pattern instead of polling logic.

---

## 2026-03-12 — Merge PR #1
**Commit:** `c6f5d8e`  
**Message:** `Merge pull request #1 from Br0k350n/codex/unequip-scuba-gear-after-job-completion`

Changed files:
- No direct file changes in this merge commit.

---

## 2026-03-12 — Deliverer outfit restoration update
**Commit:** `22f3f2a`  
**Message:** `Restore player's original outfit after job completion`

Changed file:
- `/home/endless/dev/EDSRP_Dev/resources/[17-mov]/17mov_Deliverer/client/functions.lua`

Summary:
- Added logic to restore the player's original outfit when the delivery job is completed.

---

## 2026-03-12 — Merge PR #2
**Commit:** `8eadd14`  
**Message:** `Merge pull request #2 from Br0k350n/codex/refresh-player-skin-after-job-completion`

Changed files:
- No direct file changes in this merge commit.

---

## 2026-03-12 — Treasure Hunter uniform reset fix
**Commit:** `d6eb4f4`  
**Message:** `Fix treasure hunter uniform reset on stop`

Changed file:
- `/home/endless/dev/EDSRP_Dev/resources/[17-mov]/17mov_TreasureHunter/client/functions.lua`

Summary:
- Fixed an issue where the Treasure Hunter job uniform was not properly reset when stopping/quitting.

---

## 2026-03-12 — Merge PR #3
**Commit:** `78375d4`  
**Message:** `Merge pull request #3 from Br0k350n/codex/fix-uniform-not-removing-on-quit`

Changed files:
- No direct file changes in this merge commit.

