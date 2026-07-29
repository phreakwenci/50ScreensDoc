# 50 Screens — Source-of-Truth Index

Live locations the skill reads from and writes to. Prefer these authenticated MCP tools
over web fetches (the docs are private). Confirm before any write.

## Google Drive
Grant application docs, budget, and the Nouveau Roadshow distribution assets. Read with
the Google Drive MCP (`read_file_content`, `search_files`).

- **Grants working folder** (drafts + submitted): parent folder
  `1bnDUh9EQzQnZ47BoiIn4Tch9Ox7chaO9`. Contains:
  - `50Screens_FILab_ApplicationNotes` (reviewer critique — basis of the playbook):
    `1dEEOPzTs57ztKbAq5w9yniceJHJTq3_AxFzMuzcvXnw`
  - `Film Independent Lab Grant` (draft): `11e1uIuczyvJwWYCIeWKJMN4WT4nNErzmBU8rkvgkg9c`
  - `SFFilm Grant` (working doc): `1ogpBFjieBoYfcCYaqqbtFWi2J3rmM8JMNmZh3paVBPo`
  - `Preview application — SFFILM Makers` (submitted, full): `1OD0dbPy3GfEzi5tPGqq3hFMj-stsyUDxypU419srJFE`
  - `Sundance Film Grant`: `1pWvNKokRxJolCCxOdwU0J5E91aj99bfihxoQEfLfxNg`
  - `WEHO Special Arts Grant`: `1ny88z7blps4hpsvkjDLftBdkO5aTztmCL9lNDM6gMsI`
  - `BAVC Media Grant` (stub): `18aw6044Bbf_Jfx03Bdva7P_2Sq3LlLSfPa87VX3ol8Y`
  - `Roy W Dean` (subfolder): `1eWyLfnaNcvGAK-M650iMn-L68DRYFyeX`
  - `Sundance` (subfolder): `1ozGw0cmYDHz2DtOrloGo0sfCkTORlaIQ` — contains the **real**
    current Sundance artifacts: `Sundance Full Application 2027 Doc Fund.pdf`
    (`1CzPCQ1g0gH0H6GFjD5EbP8BNdkmodedU`) and `Proposal-Checklist-2027-Sundance-Institute-
    Documentary-Fund-Application.pdf` (`14uU--tiffKWXjqqJKlDmS4Zydy0vCY8F`) — both dated
    June 15, 2026, both for the **2027** cycle. Supersedes any note about a June 2026
    Sundance submission.
  - `Jan-David_Soutar_Professional_Knowledge_Base.md` — a personal facts doc, viewed as
    recently as **July 27, 2026**: `1D20nmbOQpuIA2xE7Q3mzpLng88nGbUiPV-xZ3-tiXlA`. Not yet
    read into this skill — worth checking for bio/background updates.
- **Budget folder:** `1eaY2XUuCS7xof4kY3K-ZtOmH8dSFnnlK`
  - **CURRENT budget:** "50 Screens Budget" sheet `1FGBzXg6RyewCvGQ5fuxq4N2CULTGbdJBcQQJ2AlEvwA`
    — **the tracking tab of this sheet is the pipeline source of truth.** Grand total
    $614,451. Also submit the **Budget Topsheet as PDF** to funders.
  - Archived budget (do not use): `ARCHIVE_50Screens_Budget`
    `1L02WFUwdeOAtmTwKveahSbWmRiobWf6byzZBXW8jxzg`
  - Budget notes: `50Screens_Budget_Notes` `1c7gq4myVe_dnhF5o61t1iMInm6m6ACgeaFexhCLj_-I`
  - There is (or should be) a **"50 screens budget — minus 500k edition"** for sub-$500K
    funders like Roy W. Dean — search the budget folder to confirm the exact file.
- **Nouveau Roadshow distribution folder:** `1r8xz1hILMRb1942vn5E06hO0ZTQ958GJ`
  - **Cinema distribution database** (theater targets): `Nouveau Roadshow
    Cinema_Distribution_Database_2024.xlsx` `1CxCrLxqwxEohlkrauYpMFUD052TUbdDa`
  - Ashton Legadoé distribution meeting briefs (distribution strategy background).
- **Reference:** IDA "2025 Documentary Budgeting & Scheduling" article PDF
  `1CJY7y7fBJUkIV4m4HifjY1Lx6Fm3ZFBo` (the budget template's source).

> Note: some files are owned by `richardbrown.filmmaker@gmail.com` and shared; both JD's
> and Richard's Drives hold pieces of the pipeline.

## Notion — 50 Screens Production Bible
Read/query with the Notion MCP (`notion-fetch`, `notion-search`, `notion-query-data-sources`).
The Bible holds meeting notes, funding strategy, budget summary, theater subjects, and
key relationships — the freshest project state.

- **Production Bible (page):** `35636b1a59968127961cc2ffb7ec5363`
- **Development Bible (child page — origin/theme material):** `35536b1a599680398146e58fcb8b88a9`
- **Meeting Notes DB:** data source `collection://a11eab1e-4d00-421d-b43d-4b6e9efbc707`
- **Production Tasks DB:** data source `collection://35536b1a-5996-81a8-96fd-000b5123013a`
- Film Independent Lab submission portal (from Bible):
  https://filmindependent1.submittable.com/submit/8b3afc26-3144-4a42-94e2-708d1fa7cedf

When the Bible and a Drive doc conflict, the **Bible is usually the fresher state** for
logistics/status — but confirm with the user for anything going into a live application.
See the conflict list in `project-facts.md`.

## Gmail
- **Connected inbox:** `mdlafilms@gmail.com` (Jan-David) — searchable via the Gmail MCP
  for funder correspondence, deadlines, confirmations.
- **Dedicated project inbox:** the team referenced a separate 50 Screens / Nouveau
  Roadshow email. **If it is not the connected account above, it must be connected
  separately** before the skill can search it — ask the user for the address and to add
  the connector. Until then, use `mdlafilms@gmail.com` and anything the user pastes.

## Airtable
No dedicated 50 Screens grants base exists (closest: a generic "Indie Film Production"
base). The pipeline tracker is the **Google Sheet tracking tab**, not Airtable — do not
create an Airtable tracker unless the user asks.

## Fiscal sponsor (updated 2026-07-29)
The plan changed after this file was first written: **From the Heart Productions** (the
Roy W. Dean people) is now the team's leading fiscal-sponsor candidate — ~$80, no
nonprofit status required, faster than IDA/Fractured Atlas. A Jotform-based sponsorship
inquiry is confirmed in Gmail (July 8, 2026: "Ready for Fiscal Sponsorship?"). **Still not
finalized** as of the last check — this is the top blocking dependency in the pipeline.
`mdlafilms@gmail.com` also receives their monthly "Art of Film Funding" newsletter
(`info@fromtheheartproductions.com`), which sometimes references grant opportunities and
finalist announcements — worth a skim periodically.

## Submission portals (fill locally; never final-submit without confirmation)
- SFFilm: sffilm.grantplatform.com  ·  Film Independent: filmindependent1.submittable.com
- Roy W. Dean / From the Heart Productions: via Jotform (application-received
  confirmation on file, July 1, 2026).
- Others (Sundance 2027 cycle, NEH/Grants.gov) — capture each portal URL in the tracker as
  applications open.

## Verified-via-Gmail status (as of 2026-07-29 — see grant skill for full detail)
- **Roy W. Dean:** confirmed submitted (Jotform receipt, July 1, 2026).
- **No decision/acceptance emails found** for SFFilm, Sundance, or Film Independent Doc
  Lab in the connected inbox as of this sync — absence of a rejection ≠ confirmation of
  submission; see the conflict notes in `project-facts.md` for SFFilm and NEH specifically.
- Daily-brief automation (`mdlafilms+cc@gmail.com`) flagged **Film Independent Project
  Involve 2027** and **Film Independent Fast Track** as live decisions in early-to-mid
  July; no follow-through found in Drive. Both may have been missed — confirm with the
  user.
