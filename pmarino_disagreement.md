# MiniProject 3 — Disagreement Examples and Resolutions

**Discussion parties:** Philip (`pmarino`, validator) and Avery (`astubbin`, project owner/author)  
**Source:** Updated `pmarino_validation_log(1).numbers`  
**Scope:** Three documented pre-discussion disagreements and their recorded adjudications.

## Example 1 — Is an archiving notice evidence of recovery?

- **WOCProjectID:** `https://github.com/intel-isl/multiobjectiveoptimization`
- **Field:** `HasRecovered`
- **Parties:** Avery (`astubbin`, author); Philip (`pmarino`, validator)
- **Original disagreement:** Avery: `No`; Philip: `Yes`.
- **Key evidence:** The only post-gap commit was a September 2024 archiving notice.
- **Adjudicated value:** `No`
- **Resolution type:** `AuthorKept`
- **Post-discussion agreement:** `Yes`
- **Resolution:** The recorded decision is that an archiving notice does not demonstrate meaningful project recovery, so Avery's original `No` was kept.

## Example 2 — How should TempestRemap's activity be classified?

- **WOCProjectID:** `https://github.com/climateglobalchange/tempestremap`
- **Field:** `ActivityPattern`
- **Parties:** Avery (`astubbin`, author); Philip (`pmarino`, validator)
- **Original disagreement:** Avery: `irregular`; Philip: `Declining`.
- **Key evidence:** Eight-month gap followed by intermittent bursts of build and mesh work.
- **Adjudicated value:** `Declining`
- **Resolution type:** `ValidatorKept`
- **Post-discussion agreement:** `Yes`
- **Resolution:** The discussion record selects Philip's `Declining` classification. The brief evidence note alone describes bursts rather than an overall trend, so a full-series commit graph should be used to support this classification if requested.

## Example 3 — What best describes recent GNNOME activity?

- **WOCProjectID:** `https://github.com/lvrcek/gnnome-assembly`
- **Field:** `RecentThemes`
- **Parties:** Avery (`astubbin`, author); Philip (`pmarino`, validator)
- **Original disagreement:** Avery: `Automated bot contributions:Other`; Philip: `Documentation updates:Other`.
- **Key evidence:** Both sampled November 2024 post-gap commits edit README documentation; no bot author is established in the log.
- **Adjudicated value:** `Doc updates`
- **Resolution type:** `ValidatorKept` (as recorded in the Numbers file)
- **Post-discussion agreement:** `Yes`
- **Resolution:** The agreed shorthand `Doc updates` retains Philip's documentation theme rather than Avery's bot-activity interpretation.

---

**Consistency note:** In the Numbers file, Example 1 was labeled `ValidatorKept`, although the adjudicated `No` matches Avery's author value. The resolution CSV corrects that label to `AuthorKept` without changing the recorded adjudicated value.
