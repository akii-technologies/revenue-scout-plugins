# Revenue Scout

Connect your Revenue Scout account to work with saved social media leads and their source evidence. The plugin supplies the hosted connection, and your client opens the Revenue Scout sign-in and permission screen. Choose your brands, permissions and connection expiry before allowing access.

The same hosted service supports Codex, Claude Desktop and Claude Code. Each client has a separate connection. Account permissions, credit terms and individual action approvals still apply. Revoke a connection in Revenue Scout Account settings, API & MCP. Existing API-key integrations continue to work.

## Gmail outreach and opt-outs

Gmail outreach requires your approval of each message and its recipient. Give each recipient a clear way to opt out, such as replying to the sender. Check replies in Gmail. If a recipient opts out, an authorized team member can use **Block this recipient** in Revenue Scout to stop pending and future Revenue Scout email to that address across the account. Revenue Scout does not read Gmail replies or add an unsubscribe link automatically.

This source folder contains OpenAI and Claude manifests. Build the platform-specific packages using `python3 scripts/package-mcp-plugins.py --output /absolute/output/path` from the Revenue Scout repository root. Directory publication requires verified OAuth acceptance and the submission checklist in `docs/operations/mcp-oauth-plugin-submissions.md`.

Support: https://revenuescout.ai/contact

Privacy: https://revenuescout.ai/privacy

Terms: https://revenuescout.ai/terms
