<div align="center">

<a href="https://osxninja.github.io/operation-black-veil/">
<img src="operation-black-veil-room-icon.png" alt="Operation Black Veil dossier icon" width="180" />
</a>

# OPERATION BLACK VEIL
### CASE BV-17 · OFFLINE OSINT INVESTIGATION

**A missing analyst. A fractured trail. Your evidence-led assessment.**

[◈ OPEN THE INTERACTIVE 3D CASE DASHBOARD](https://osxninja.github.io/operation-black-veil/)

[⬇ DOWNLOAD THE PLAYER EVIDENCE ZIP](https://github.com/Osxninja/operation-black-veil/raw/refs/heads/main/operation-black-veil.zip)

FICTIONAL CASE　·　OFFLINE　·　30-HOUR TARGET

</div>

---

## Mission Brief

At 06:20 UTC on 14 October 2025, analyst Mara Venn missed a scheduled check-in after sending a cryptic fragment. Your task is to reconstruct the trail from synthetic accounts, archived records, a schematic map, conflicting timestamps, and a disputed contract.

The GitHub Pages dashboard is the animated 3D entry point. The downloadable ZIP contains the actual case materials and the answer sheet. GitHub does not run 3D JavaScript inside the rendered README.

> **Fiction notice:** every person, organization, account, record, domain, and location in this exercise is invented. The .test domains are for training. Do not search for real people or contact real services.

## Start the Investigation

1. Download the [player evidence ZIP](https://github.com/Osxninja/operation-black-veil/raw/refs/heads/main/operation-black-veil.zip).
2. Extract the ZIP on your computer.
3. Open the extracted folder named operation-black-veil.
4. Read its README.md for the case rules and evidence index.
5. Begin with evidence/case_brief.txt.
6. Verify files against evidence/SHA256SUMS.txt.
7. Use ANSWER-SHEET.md to record all eight answers and the evidence supporting each one.

You can use local text, spreadsheet, JSON, and image viewers. No internet connection is required to solve the evidence.

## Investigation Questions

Open a question when you are ready. Each answer should include the requested finding **and** citations to the evidence file and record, row, or post ID you used. Do not copy a guess without showing how the records support it.

<details>
<summary><strong>01 · Identity trace</strong> — Which recovered account handle is linked to the “glass orchard” clue?</summary>

**Write in your answer sheet:** the handle, the evidence references, and why the competing account records are weaker.

**Start with:** fieldnote.txt, account_registry.csv, and profile_archive.json.

</details>

<details>
<summary><strong>02 · Archive pivot</strong> — Which archived domain is connected to that account’s routing label?</summary>

**Write in your answer sheet:** the complete domain and the profile/DNS fields that connect them.

**Start with:** profile_archive.json, domain_records.csv, and archive_index.txt.

</details>

<details>
<summary><strong>03 · Entity link</strong> — What supplier code connects the archive record to the supplier register?</summary>

**Write in your answer sheet:** the code and the matching cross-reference in both records.

**Start with:** archive_index.txt and supplier_register.csv.

</details>

<details>
<summary><strong>04 · Print record</strong> — Which print-run record matches the recovery hint?</summary>

**Write in your answer sheet:** the print-run ID and how the catalog fields satisfy the hint.

**Start with:** archive_index.txt and print_run_catalog.csv.

</details>

<details>
<summary><strong>05 · Grid fix</strong> — What grid and cell identify the relevant meeting feature?</summary>

**Write in your answer sheet:** both the grid and cell, plus the mapped feature and evidence references.

**Start with:** photo_manifest.csv, proof_03.svg, and grid_legend.csv.

</details>

<details>
<summary><strong>06 · UTC window</strong> — What is the estimated planned meeting time in UTC?</summary>

**Write in your answer sheet:** the UTC timestamp and the conversion/reconciliation steps. Use the supplied offset; do not assume a time zone.

**Start with:** message_fragments.json, civic_clock_notices.csv, and transit_timetable.csv.

</details>

<details>
<summary><strong>07 · Contract review</strong> — Which contract and disputed amount are relevant to the investigation?</summary>

**Write in your answer sheet:** the contract reference, disputed amount, and why it differs from the total award.

**Start with:** procurement_extract.csv and acceptance_log.csv.

</details>

<details>
<summary><strong>08 · Final assessment</strong> — Who was the intended recipient, where and when was the planned meeting, and what was its likely purpose?</summary>

**Write in your answer sheet:** a short report that names the recipient, planned location, planned UTC time, and likely purpose. Cite independent sources for each key claim.

Also include one alternative hypothesis, confidence levels, and what the evidence does not establish. A planned meeting is not proof of attendance; a procurement discrepancy is not proof of fraud.

**Start with:** identity_crosswalk.csv and all source records relevant to your earlier findings.

</details>

## Write-up Format

Complete the ANSWER-SHEET.md included in the ZIP. For every question, provide:

- Your answer.
- Evidence filename plus row, post, record, or message ID.
- A brief explanation showing how the evidence supports the answer.

For the final assessment, add:

1. Recipient, location, planned time, and likely purpose.
2. A short timeline with times normalized to UTC.
3. Confidence for each major conclusion.
4. One plausible alternative explanation.
5. Limitations: what the evidence cannot prove.

### Submitting answers

- **TryHackMe:** submit each checkpoint in its matching room question, then use the answer sheet for the written assessment.
- **GitHub download:** save your completed answer sheet locally. This repository has no automatic answer checker and the ZIP contains no flag strings.

## Evidence and Integrity

The ZIP includes synthetic case records in CSV, JSON, TXT, and SVG formats. SHA256SUMS.txt lists evidence hashes so you can check that the supplied files have not changed. The included EVIDENCE-INDEX.md describes the files and the limits of each source.

Use multiple independent sources for attribution. Separate direct observations from inferences. Treat a username match as a lead, not proof of identity.

## Case Parameters

| Item | Detail |
|---|---|
| Target effort | 30 hours |
| Environment | Offline |
| Evidence | Synthetic and deterministic |
| Internet research | Not needed |
| Answer key | Not included in the player ZIP |

## Spoiler Policy

This repository is the player release. Keep the instructor solution and accepted flags private. If you share a write-up publicly, consider waiting until other players have had a chance to solve the case.

---

<div align="center">

**CASE BV-17 · FICTIONAL TRAINING MATERIAL**

*Observe carefully. Corroborate independently. Report with restraint.*

</div>
