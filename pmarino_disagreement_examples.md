# MiniProject 3 — Disagreement Examples and Resolutions

**Discussion parties:** Philip (`pmarino`) and Avery (`astubbin`)  
**Source logs:** `pmarino_validation_log.csv` and `astubbin_validation_log.csv`  
**Status:** **Draft for discussion.** Both supplied logs show pre-discussion disagreements, but neither documents an agreed, post-discussion outcome. The resolutions below are **proposed**, not confirmed decisions. Update the final-outcome lines after discussing each example.

## Example 1 — Does an archiving notice count as recovery?

- **WOCProjectID:** `https://github.com/intel-isl/multiobjectiveoptimization`
- **Field:** `HasRecovered`
- **Parties:** Avery (`astubbin`, author) and Philip (`pmarino`, validator)
- **Disagreement:** Avery: `No`; Philip: `Yes`.
- **Evidence:** The only recorded post-gap commit was a September 2024 archiving notice. The repository was subsequently treated as inactive.
- **Proposed resolution:** **`No`**. An archiving notice does not demonstrate resumed or sustained development. Philip would revise the validation value to agree with Avery.
- **Final discussion outcome:** **Pending confirmation by both parties.**

## Example 2 — Irregular activity or a declining trend?

- **WOCProjectID:** `https://github.com/climateglobalchange/tempestremap`
- **Field:** `ActivityPattern`
- **Parties:** Avery (`astubbin`, author) and Philip (`pmarino`, validator)
- **Disagreement:** Avery: `irregular`; Philip: `Declining`.
- **Evidence:** The validation log identifies an eight-month gap followed by bursts of build and mesh development; it does not document a consistent downward trend across the full period.
- **Proposed resolution:** **`irregular`**, pending a review of the full commit-history chart. Isolated bursts and gaps better support irregular activity than an established declining trend.
- **Final discussion outcome:** **Pending confirmation by both parties.**

## Example 3 — Documentation updates or automated bot activity?

- **WOCProjectID:** `https://github.com/lvrcek/gnnome-assembly`
- **Field:** `RecentThemes`
- **Parties:** Avery (`astubbin`, author) and Philip (`pmarino`, validator)
- **Disagreement:** Avery: `Automated bot contributions:Other`; Philip: `Documentation updates:Other`.
- **Evidence:** The two sampled post-gap commits in November 2024 changed README content; the log provides no evidence that they were bot-authored.
- **Proposed resolution:** **`Documentation updates:Other`**. Describe the observed file changes rather than assigning unverified bot authorship.
- **Final discussion outcome:** **Pending confirmation by both parties.**

---

## To finalize after discussion

For each of the **three** examples above, replace **“Pending confirmation by both parties”** with the actual agreed value, whether either person changed their assessment, and a one-sentence explanation of what evidence settled the disagreement. Then reflect the agreed outcomes in the appropriate `AdjudicatedValue`, `ResolutionType`, and `PostDiscussAgreementStatus` columns of the validation log(s), using the assignment's required value conventions.
