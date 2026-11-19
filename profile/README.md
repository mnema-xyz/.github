<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="mnema-talk-wordmark-dark.svg">
    <img src="mnema-talk-wordmark-light.svg" alt="Mnema Talk" width="240">
  </picture>
</p>

<p align="center"><b>Your crew, on your own server.</b><br>
A self-hosted community chat with text channels, voice and video Talks and screen sharing.<br>
One of you hosts it, everyone else joins with a link.</p>

<p align="center">
  <a href="https://mnema.xyz">Website</a> ·
  <a href="https://mnema.xyz/developers/">Developer docs</a> ·
  <a href="https://github.com/mnema-xyz/talk/releases/latest">Latest release</a>
</p>

---

### What is here

| Project | What it is | License |
|---|---|---|
| [**talk**](https://github.com/mnema-xyz/talk) | The server and web app: one Go binary, PostgreSQL and S3 storage. Text channels, one-click voice and video Talks, screen sharing up to 4K where your hardware can capture it, roles, webhooks, bots, 2FA, Web Push. | AGPL-3.0 |
| [**talk-desktop**](https://github.com/mnema-xyz/talk-desktop) | The desktop app for Windows, macOS and Linux. Holds all your communities side by side and runs a signed web bundle it verifies itself. | AGPL-3.0 |
| [**bot-sdk-js**](https://github.com/mnema-xyz/bot-sdk-js) | The official TypeScript SDK for bots: REST, gateway, slash commands, components and modals. `npm install @mnema-xyz/bot-sdk` | MIT |
| [**bot-sdk-go**](https://github.com/mnema-xyz/bot-sdk-go) | The official Go SDK for bots, with the same REST, gateway and interaction surface. `go get github.com/mnema-xyz/bot-sdk-go` | MIT |
| [**talk-mnemo-bot**](https://github.com/mnema-xyz/talk-mnemo-bot) | Mnemo, a self-hosted helper bot built on the SDK. Bring your own AI provider and key. | MIT |

### What we stand for

- **Your server, your data.** Every community runs on a machine someone in it owns. No hosted version, no paid plan, no company in the middle.
- **Encryption where it fits.** Voice, video and screen sharing are end-to-end encrypted (MLS). Text stays readable by your server, so search and moderation work.
- **No telemetry.** The server and the apps do not phone home.
- **Built in the open.** Releases are signed, and the docs ship with the code.

### Get involved

- Questions or bugs: open an issue in the matching repository.
- Security problems: report them privately, see our [security policy](https://github.com/mnema-xyz/.github/blob/main/SECURITY.md).
- Anything else: [contact@mnema.xyz](mailto:contact@mnema.xyz)
