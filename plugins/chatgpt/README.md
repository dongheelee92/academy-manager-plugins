# Academy Manager for ChatGPT

Read academy records available to your own Academy Manager account from ChatGPT. Connect through the host's OAuth sign-in screen, select the academies and read permissions you intend to share, then choose the academy for your question. Never paste passwords, session credentials, or API keys into a chat.

The integration reads students, attendance, classes, stored lessons, makeup lessons, billing summaries, invoices, and saved counseling summaries. It cannot edit records, collect payments, send messages, or recover raw counseling content. Each customer's existing account permissions still apply. Incomplete data and missing saved summaries are reported rather than invented.

![Academy Manager](./assets/icon.svg)

- Website: https://academy-manager.app
- Privacy: https://academy-manager.app/legal/privacy
- Terms: https://academy-manager.app/legal/terms
- Planned support: https://github.com/dongheelee92/academy-manager-plugins/issues

This is a submission draft. The production MCP endpoint, planned support repository, verified publisher identity, final legal text, host validation, and public directory publication remain separate launch gates. A local package build does not verify any of them. The review cases describe synthetic review data that must be prepared and tested in a dedicated reviewer account. No reviewer credentials or demo recording are included in this package.

The OAuth declaration follows OpenAI's documented host extension. Its server-level extension is not accepted by the unmodified Agent Plugins MCP 1.0.0 schema; the builder checks the portable projection and the OpenAI host contract separately. Portal validation is still required.
