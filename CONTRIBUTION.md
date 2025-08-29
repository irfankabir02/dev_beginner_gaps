CONTRIBUTION GUIDELINES
Project: User‑Centric Development Journey & Registry‑Based Vulnerability Analysis
Version: 1.0.0
Author: Irfan Kabir
License: MIT

1️⃣ Scope of Contributions
Contributions to this repository may include:

Type	Description	How to Contribute
Analysis Enhancements	Additional security insights, deeper registry parsing, updated threat models	Add or modify REPORT.md or create a new Markdown file (analysis-*.md) and reference it in the main report.
Data & Artefacts	Sample registry hives, screenshot collections, scripts to extract .reg files	Place them in the data/ or scripts/ folder. Add a brief description in README.md.
Formatting & Documentation	Markdown styling, layout tweaks, spell‑checking	Update any Markdown file (.md) and ensure consistency.
Issue Reports	Bugs, missing details, typos	Open a GitHub issue and describe the problem clearly.
Pull Requests	Proposed changes following the guidelines below	Fork, branch, commit, push, then open a PR.
Note: Contributions that introduce new code should follow the MIT license and include an LICENSE file at the repository root.

2️⃣ Workflow
Fork the repository.
Create a new branch (e.g., feature/add-regex-analysis).
Make your changes.
Run tests (if any) – none at the moment, but if you add scripts, include a test harness.
Commit with a clear message (git commit -m "Add regex analysis for registry keys").
Push to your fork (git push origin feature/...).
Open a Pull Request (PR) against main.
Review: The maintainer will review within a reasonable timeframe.
Merge: Upon approval, your changes will be merged.
3️⃣ Code of Conduct
We follow the Contributor Covenant.
All contributors must adhere to respectful, inclusive, and professional behavior.

4️⃣ Licensing
All content in this repository is released under the MIT License.
If you add additional code or data, please include the same license or provide a clear statement of licensing.

License Text (MIT):

MIT License

Copyright (c) 2025 Irfan Kabir

Permission is hereby granted, free of charge, to any person obtaining a copy
...
5️⃣ Reporting Issues
Use GitHub Issues to report bugs, missing documentation, or data errors.
Include the exact text or file name if applicable.
If possible, add a small reproducible example.
6️⃣ Acknowledgements
This work builds upon community‑generated insights on Windows security, developer tooling, and user‑experience research.
Special thanks to:

Microsoft’s Windows Insider Program for early feedback.
The OpenAI research community for providing a platform for sharing findings.
All anonymous users who tried out the proposed “Beginner‑Safe” profile and shared their experiences.
