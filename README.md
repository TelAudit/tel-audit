# TELAUDIT

**Local IPBX documentation and audit tool for Windows.**

TELAUDIT analyzes IPBX backup files and automatically generates professional documentation, audit reports and diagrams.

It is designed to be simple, fast, local and privacy-friendly.

> Current version: **v2.3 beta 3**  
> Contact: **telauditwin@gmail.com**  
> Support the project: https://ko-fi.com/telaudit

[Français](README.fr.md)

---

## What TELAUDIT does

TELAUDIT can generate:

- PDF reports
- HTML reports
- CSV exports
- Automatic audit findings
- IPBX diagrams
- Draw.io / diagrams.net exports
- PNG diagram exports

The current public beta focuses on **Xorcom / Ombutel-style backups**. Additional parsers may be added progressively.

---

## Privacy first

TELAUDIT runs locally on Windows.

- No telemetry
- No tracking
- No advertising
- No online account required
- No data collection
- No IPBX data is sent to the Internet

Your backup files remain on your computer.

---

## Download

Download the latest Windows release from the **Releases** section of this GitHub repository.

The recommended package is the Windows ZIP or executable provided with each release.

---

## Basic usage

1. Start TELAUDIT.
2. Select the interface language.
3. Drag and drop an IPBX backup file, or use the file picker.
4. Select an output folder.
5. Click **Analyze and generate**.
6. Open the generated PDF, HTML, CSV and diagram files.

Supported input formats currently include:

- `.tar`
- `.tar.gz`
- `.tgz`
- `.gz`

---

## Generated files

Depending on the backup content, TELAUDIT may generate:

- Main PDF report
- Standalone HTML report
- CSV exports
- Audit CSV export
- General diagram as PNG
- Editable Draw.io diagram
- Dedicated exports for detected call forwarding rules

---

## Donationware model

TELAUDIT is distributed free of charge as donationware.

Donations are optional. They help support development, maintenance and future improvements, but they do not include guaranteed support or guaranteed updates.

Support page: https://ko-fi.com/telaudit

---

## Support

TELAUDIT is a personal project.

There is no guaranteed support, but bug reports and feedback are welcome.

Contact: telauditwin@gmail.com

Before reporting an issue, please check:

- the backup file is complete;
- the output folder is writable;
- you are using the latest available release;
- sensitive IPBX data has been removed or anonymized if you share files.

---

## Roadmap

Planned directions include:

- more IPBX parsers;
- improved audit rules;
- improved diagrams;
- better report structure;
- cleaner internal architecture;
- future professional features if there is enough interest.

TELAUDIT will remain focused on simplicity, stability and local analysis.

---

## License

See [LICENSE](LICENSE).

TELAUDIT is provided as-is. Use it under your own responsibility, especially when analyzing production systems.

---

## Disclaimer

TELAUDIT is an independent tool. It is not affiliated with, endorsed by, or sponsored by any IPBX vendor.

All trademarks and product names belong to their respective owners.
