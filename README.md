# Academy Manager MCP plugins

Release candidate for connecting ChatGPT and Claude to the Academy Manager MCP service. Each academy signs in with its own account and selects the academies and read permissions to authorize.

## Release status

The packages are prepared for public directory review. The standalone production MCP gateway, publisher verification, policy approval, reviewer access and directory reviews are still in progress. This repository is currently a private publication staging area.

## Packages

- `plugins/chatgpt`: ChatGPT plugin manifest, remote MCP configuration and shared connection guidance.
- `plugins/claude`: Claude web plugin manifest, remote connector reference and the same guidance.

The target MCP endpoint is `https://mcp.academy-manager.app/mcp`. The Academy Manager website is `https://academy-manager.app`. Current capabilities cover read-only student, attendance, class, stored lesson, makeup, billing, invoice and stored counseling-summary queries. An approved owner or administrator membership is required.

## Connect

After publication, install Academy Manager from the relevant official directory. Complete the normal account login, select your academies and permissions, and confirm the connection. Passwords, API keys and tokens belong in the service connection flow; do not paste them into chat or issues.

## Support

Use repository issues for package installation and technical questions. Keep student and guardian information, counseling content, billing records and credentials out of public reports.

## License

Each package includes a draft proprietary integration license for owner review. It permits unmodified distribution through the official repository and OpenAI/Anthropic directories, and authorized installation/use.
