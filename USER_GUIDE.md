# TELAUDIT User Guide

## 1. Overview

TELAUDIT is a Windows application that transforms IPBX backup files into professional documentation.

It can generate PDF reports, HTML reports, CSV exports, diagrams and automatic audit findings.

The analysis is performed locally. No IPBX data is sent to the Internet.

## 2. First use

1. Start TELAUDIT.
2. Select the language.
3. Drag and drop a backup file or click the backup selection button.
4. Select the output folder if needed.
5. Click **Analyze and generate**.

Supported formats currently include `.tar`, `.tar.gz`, `.tgz` and `.gz`.

## 3. Results

After analysis, TELAUDIT creates files in the selected output folder.

Common outputs include:

- PDF report;
- HTML report;
- CSV exports;
- audit CSV;
- PNG diagram;
- Draw.io diagram.

## 4. Understanding the PDF report

The PDF report may include:

- cover page;
- detected IPBX information;
- general diagram;
- inbound routes;
- queues;
- extensions;
- call forwarding information;
- automatic audit findings.

## 5. Understanding the audit

The audit highlights useful points to review.

Examples:

- empty queue;
- unused trunk;
- route without clear destination;
- IVR with unknown destination;
- referenced but missing extension.

Possible severity levels:

- critical;
- important;
- warning;
- information.

## 6. Comparing two backups

Enable the comparison option and select a second backup.

TELAUDIT can detect additions, removals and changes when enough information is available.

## 7. About and support

The **About** menu displays:

- application version;
- project name;
- official contact;
- local-analysis reminder.

The system information copy button can help prepare a support request.

Support page: https://ko-fi.com/telaudit  
Contact: telauditwin@gmail.com

## 8. Security notes

TELAUDIT does not execute scripts from the backup file.

Analysis is local.

No Internet connection is required for the analysis.

## 9. Troubleshooting

If something fails, check:

- the backup is complete;
- the file extension is supported;
- the output folder is writable;
- antivirus software did not block the executable;
- the latest TELAUDIT version is being used.

When reporting an issue, anonymize sensitive files before sharing them.
