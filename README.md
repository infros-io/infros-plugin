# InfrOS plugin

InfrOS designs cloud architectures from your requirements and generates the Terraform to deploy them. This plugin connects your AI coding assistant to InfrOS, so the assistant can work in InfrOS as you: create Systems and specifications, run designs, review the proposals, and read the generated Terraform.

You need an InfrOS account at [app.infros.io](https://app.infros.io).

## Install

### Claude Code

Run these two commands inside Claude Code:

```text
/plugin marketplace add infros-io/infros-plugin
/plugin install infros@infros
```

### Kiro

[![Add to Kiro](https://kiro.dev/images/add-to-kiro.svg)](https://kiro.dev/launch/mcp/add?name=infros&config=%7B%22url%22%3A%22https%3A%2F%2Fapi.app.infros.io%2Fassistant%2Fmcp%22%2C%22disabled%22%3Afalse%2C%22autoApprove%22%3A%5B%5D%7D)

Or install it as a power:

1. Open the Powers panel and select **Add Custom Power**.
2. Select **Import power from a repository URL**.
3. Enter `https://github.com/infros-io/infros-plugin` and click **Install**.

### VS Code

1. Run **Chat: Install Plugin from Source** from the Command Palette.
2. Enter `https://github.com/infros-io/infros-plugin`.

### Cursor

Install **InfrOS** from the Cursor Marketplace. Its listing is at [infros-io/cursor-plugin](https://github.com/infros-io/cursor-plugin).

## Sign in

The first time your assistant uses InfrOS, your browser opens the InfrOS sign-in. After you sign in, InfrOS shows what the assistant is asking for and where the sign-in returns. Nothing is shared until you click **Allow**. The assistant then works as you: it sees and does only what your role in your organization allows.

## What your assistant can do

| Permission | What it allows |
| --- | --- |
| Read | See your Systems, versions, landing zones, proposals and generated Terraform, and get the price of a design run or a Terraform generation |
| Write | Create Systems and versions, and edit your drafts |
| Spend credits | Start a design run or a Terraform generation |
| Admin (organization admins only) | Manage your organization's landing zones, standing constraints and GitHub repository analyses |

## Credits

Design runs and Terraform generation use your organization's InfrOS credits. InfrOS gives the price first, and a start goes through only at that exact price. InfrOS tells your assistant to ask you before it spends.

## Stop access

In InfrOS, open your profile, find **Connected Assistants**, and click **Revoke** next to the assistant. It loses access within five minutes.

## Privacy and support

- Privacy policy: https://app.infros.io/privacy-policy
- Terms of service: https://app.infros.io/terms-of-service
- Support: support@infros.io
