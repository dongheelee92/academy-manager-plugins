# Academy Manager for Claude

Read academy records available to your own Academy Manager account from Claude. After installing the plugin, open its Connectors tab, connect Academy Manager, and complete the normal OAuth sign-in and academy consent screen. Team and Enterprise organizations may need an Owner to add the connector first. Every member then connects with their own account.

Ask about students, attendance, classes, stored lessons, makeup lessons, billing summaries, invoices, and saved counseling summaries. Choose the academy when more than one is available. The plugin cannot edit records, collect payments, send messages, or recover raw counseling content. Never put passwords, session credentials, or API keys into a conversation.

![Academy Manager](./assets/icon.svg)

- Website: https://academy-manager.app
- Privacy: https://academy-manager.app/legal/privacy
- Terms: https://academy-manager.app/legal/terms
- Planned support: https://github.com/dongheelee92/academy-manager-plugins/issues

This is a submission draft. Public publication requires the production MCP server, a separate connector listing, this bundle's public GitHub repository, verified ownership, final legal review, and a populated synthetic reviewer account. The planned support repository is not verified by a local build.

The bundle declares only the server URL. The separate directory connector's authentication configuration uses the planned confidential client academy-manager-claude-directory-v1 in Anthropic's portal; its secret must never be placed in this package. This is a hosted Claude configuration, not proof of Claude Code authentication. Host validation and the actual sign-in flow remain launch gates.
