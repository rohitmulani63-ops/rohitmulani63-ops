<h1 align="center">Rohit Mulani</h1>

<p align="center">
  Small, reviewable open-source fixes, and right-to-left (RTL) support for Arabic and other RTL languages.<br>
  Based in Dubai.
</p>

<p align="center">
  <a href="#arabic-and-right-to-left-rtl-fixes">RTL work</a> ·
  <a href="#fixes-docs-and-tests">Fixes, docs and tests</a> ·
  <a href="https://github.com/rohitmulani63-ops/accepted-open-source-contributions">Proof log</a> ·
  <a href="https://github.com/sponsors/rohitmulani63-ops">Sponsor</a>
</p>

I help open-source maintainers with small, useful work: bug fixes, docs, runbooks, setup notes and tests. Each pull request stays focused, links to its issue and notes how it was checked.

My current focus is right-to-left (RTL) support. Many interfaces still break in Arabic, Hebrew and Persian: long text is cut off on the wrong side, controls ignore `dir="rtl"`, and automated checks misread Arabic script. I find these bugs and send fixes upstream.

> "I really appreciate fixes / feedback on RTL issues."
>
> A Slint maintainer, in a [comment on slint-ui/slint#14595](https://github.com/slint-ui/slint/pull/14595#issuecomment-6506206900)

<!-- rtl-work:start -->
## Arabic and right-to-left (RTL) fixes

Pull requests that improve how apps handle Arabic, Hebrew, Persian and other right-to-left languages.

| Project | Contribution | Status |
| --- | --- | --- |
| [Slint](https://github.com/slint-ui/slint/pull/14595) | Long right-to-left text is cut with its "…" on the correct side | Merged |
| [axe-core](https://github.com/dequelabs/axe-core/pull/5508) | Stops the color-contrast check from treating Arabic text as icon ligatures | In review |
| [Grommet](https://github.com/grommet/grommet/pull/8219) | TextInput inline actions follow `dir="rtl"` | In review |
| [Django Debug Toolbar](https://github.com/django-commons/django-debug-toolbar/pull/2519) | First step toward RTL support: logical CSS properties in the toolbar, plus a lint check for RTL-unsafe CSS | In review |
<!-- rtl-work:end -->

If your project has a right-to-left bug, tag me on the issue.

## Fixes, docs and tests

Mostly in the Stellar, GrantFox and Drips ecosystem, plus a few other projects.

| Project | Contribution | Status |
| --- | --- | --- |
| [Credence Frontend](https://github.com/CredenceOrg/Credence-Frontend) | `.env.example` and `/api` proxy setup docs for faster contributor setup | [Merged via PR #196](https://github.com/CredenceOrg/Credence-Frontend/pull/196) |
| [Remitwise Contracts](https://github.com/Remitwise-Org/Remitwise-Contracts) | Dependency health-check schema and status-code docs | [Merged via PR #785](https://github.com/Remitwise-Org/Remitwise-Contracts/pull/785) |
| [QuickLendX Protocol](https://github.com/QuickLendX/quicklendx-protocol) | Error-code catalog with causes and remediation for integrators | [Merged via PR #1373](https://github.com/QuickLendX/quicklendx-protocol/pull/1373) |
| [Remitwise Frontend](https://github.com/Remitwise-Org/Remitwise-Frontend) | Log-sanitization redaction test coverage to reduce PII leakage risk | [Merged via PR #542](https://github.com/Remitwise-Org/Remitwise-Frontend/pull/542) |
| [Drips / Ignition Pay](https://github.com/Ignition-World/ignition-pay/pull/88) | Database backup strategy contribution | Merged |
| [GrantFox / GuildPass](https://github.com/Adamantine-guild/guildpass-app/pull/56) | Durable webhook idempotency work | Merged |
| [itssimmons/tetris.cpp](https://github.com/itssimmons/tetris.cpp/pull/30) | Hard-drop behavior fix | Merged |
| [Dokploy templates](https://github.com/Dokploy/templates/pulls?q=is%3Apr+is%3Amerged+author%3Arohitmulani63-ops) | Template additions and small fixes | 23 PRs merged |
| Grainlify Stellar Contracts | Deployment and upgrade runbook for safer releases and rollbacks | Merged (PR #105, June 2026; the repository has since been removed) |
| [BonziAssist](https://github.com/dot-Justin/BonziAssist/pull/10) | First-run setup notes | In review |
| [Tailcall](https://github.com/tailcallhq/tailcallhq.github.io/pull/626) | Config generator work | Closed |

## How I work

- Small, reviewable changes, with nothing unrelated mixed in.
- Every pull request links to the issue or the maintainer's request.
- Validation notes when they help the review.
- Quick follow-up when maintainers ask for changes.

## Support this work

Sponsorship funds steady public maintenance: reproducing issues, docs and setup fixes, small bug fixes, tests and RTL fixes. It supports the work in general; it is not a promise to fix a specific issue.

- Sponsor: [github.com/sponsors/rohitmulani63-ops](https://github.com/sponsors/rohitmulani63-ops) (application pending)
- Proof log: [accepted-open-source-contributions](https://github.com/rohitmulani63-ops/accepted-open-source-contributions), a dated list of accepted contributions with issue and PR links
