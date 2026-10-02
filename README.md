# dev-skills

Personal cross-agent skills that do not have a suitable third-party home.

The source-of-truth policy is:
- Prefer an existing third-party skill when it covers the use case.
- Fork or adapt upstream only when this repository adds a required workflow contract.
- Create a local skill only when no suitable upstream source exists.

Provenance and local deltas are recorded in SOURCES.md. AgentBrew indexes this repository; it does not copy its content.

Windsurf, Devin, and Augment (Auggie) are deprecated and frozen (owner decision 2026-10-02). Skills that mention them, such as the `devin -p` launch in `grind`, stay as they are. Never add a fix or a feature for these agents. Changes for other agents may still edit these skills.
