# Install Lexful Documentation

## Install in Lexful

Lexful Documentation is packaged as a native Lexful Skill Kit. Once installed, its slash commands are available in Ask Lex without adding the skills one by one.

Use the repository URL `https://github.com/Lexful-ai/doc-skills` as the source for a Lexful Skill Kits importer that can read the private repository. The `skill-kit.json` manifest lists the complete kit. Preview and install the manifest and its listed skills from the same resolved commit. Record that commit so the installed version is reproducible.

## Install in another agent host

For manual installation, add every Markdown file listed in the manifest to your agent host under its frontmatter name. Install the complete kit for routing. If your host cannot load another skill during a turn, invoke the selected specialist directly.

Connect an authenticated Lexful session to read tenant evidence and save documents when requested. You can draft from supplied notes without a connection. Start with `/lexful-docs` and describe the situation. To check routing without a write, ask for a draft of a one-time switch replacement plan. The result should use the change plan skill and include an observable rollback trigger and verification checks.

Run `python3 scripts/validate-skills.py` before shipping changes.
