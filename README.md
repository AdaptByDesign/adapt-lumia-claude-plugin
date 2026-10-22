# Adapt Lumia

Explore and summarise organisational data in Adapt Lumia with Claude. This plugin
bundles the Lumia skill and a remote MCP connector. Available information and
features depend on your account and organisation permissions. Authorised Nimbus
users can also review account risk and billing tiers.

## Setup and authentication

Install the complete plugin folder in a Claude client that supports plugins.
Connect the Lumia MCP server and complete the OAuth sign-in and consent flow with
your Adapt account. Use an account for the environment selected by this package.
The server URL is declared in the root `.mcp.json`; staging packages connect to
staging, and production packages connect to production.

You need an existing Adapt account with access to the requested data and enabled
features. Credentials and tokens are not bundled with this plugin.

## Example requests

- Which organisations am I connected to?
- Summarise our objectives this quarter.
- How does Career Valuation work?
- Run the culture sentiment Preset Prompt.

See [workflow examples](skills/use-lumia/references/workflows.md) for more requests.

## Data access and privacy

Claude sends tool requests and their parameters to the configured Lumia MCP
server. The server returns permitted organisational records, reports, support
guidance and requested Preset Prompt material to Claude for your task. Returned
records may include personal information where your permissions allow it.
The connector provides read-only access and does not change Lumia records.

This package contains Markdown guidance, a logo and connector configuration.
It does not bundle a local server, executable scripts or dependencies to install.

Read the [Adapt privacy policy](https://theadaptway.com/privacy-policy) and
[terms of service](https://theadaptway.com/terms/).

## Troubleshooting and support

If connection or authentication fails, confirm that your Claude client supports
the plugin and that you are signing in to the package's environment. Reconnect
the connector if necessary. For missing data, check your account's organisation
access and feature permissions. Contact [Adapt support](https://support.theadaptway.com)
with the operation and error message, without sharing passwords or access tokens.

## License

Use of the Application is subject to the [Adapt End User Licence Agreement](LICENSE).
