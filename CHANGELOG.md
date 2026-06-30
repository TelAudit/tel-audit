# Changelog

## v2.3 beta 3

Human-readable code edition and call forwarding improvements.

- Added simplified developer documentation.
- Added simplified architecture notes.
- Added explanatory comments in the main code files and audit rules.
- Improved active call forwarding detection for Xorcom / Ombutel backups.
- Detects call forwarding data from `ombu_diversions` and `ombu_forwarding_diversions` when available.
- Disabled forwarding entries with an old stored destination are not displayed as active.
- Automatic audit remains visible in PDF and HTML reports even when no issue is detected.
- Added a clear message when current audit rules do not detect any issue.
- No intentional functional change in the human-readable code edition, apart from the documented beta corrections.

## v2.3 beta

- Added detection of active CFI/CF, CFN/CFNA, CFB and CFU call forwarding rules when present in the backup.
- Added a PDF page dedicated to detected call forwarding rules.
- Added HTML section and dedicated CSV export for active forwarding rules.
- Added dedicated Draw.io export for active forwarding rules when detected.
- Prepared the model to display associated conditions when the backup provides them.

## v2.2 beta donationware

- Removed personal developer information.
- Added official contact address: telauditwin@gmail.com.
- Added Ko-fi support link: https://ko-fi.com/telaudit.
- Added a discreet "Support the project" menu.
- Added a discreet donation reminder after successful analysis.
- Added a "Do not show again" option for the donation reminder.
- Added a license file clarifying the donationware distribution model.

## v2.2 beta

- Added final TELAUDIT branding with logo and icon.
- Logo included in the interface and generated reports.
- Added PNG export of the general diagram.
- Added editable Draw.io / diagrams.net export.
