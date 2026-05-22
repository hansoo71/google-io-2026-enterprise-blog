# SKILLS.md

Natural-language editing examples:
- “Update the AWS AgentCore section with the latest release notes and refresh the comparison grid.”
- “Add a new image to explain MCP/A2A governance; copy it to all asset directories.”
- “Make the mobile comparison table easier to read while keeping the editorial style.”
- “Regenerate the standalone Telegram HTML after editing.”

Recommended workflow:
1. Update source notes first.
2. Edit `src/` canonical files.
3. Copy to `docs/` for Pages.
4. Rebuild `/opt/data/out/google-io-2026-enterprise-blog.html` with inlined CSS/JS/images.
5. Validate local HTTP and commit.
