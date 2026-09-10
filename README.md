<p align="center">
  <img src="assets/zyroshift-wordmark.png" alt="ZyroShift" width="760" />
</p>

<p align="center"><strong>A crypto swap web application built around the SideShift.ai API.</strong></p>
<p align="center">Next.js · React · TypeScript · Tailwind CSS</p>
<p align="center"><a href="mailto:support@zyroshift.com?subject=ZyroShift%20project%20enquiry">Discuss the project</a> · <a href="docs/architecture.md">Architecture</a> · <a href="docs/commercial-options.md">Commercial options</a></p>

ZyroShift brings asset selection, network selection, swap quotes and order tracking into one branded web experience. I built the project over approximately three months, working across interface design, application logic, API integration and search-oriented content architecture.

This repository is the product showcase. Screenshots, documentation and any future code samples describe a defined project version; the scope of a source delivery is agreed separately.

## Product capabilities

| Area | Implementation |
| --- | --- |
| Swap interface | Token and network selection, amount entry and destination address input |
| Quotes and orders | Variable-rate shifts and fixed-rate quotes/orders through SideShift |
| Tracking | Dedicated shift pages, status polling, deposit QR codes and cancellation flow |
| Product experience | Responsive layouts and light/dark themes |
| Discovery | Swap-pair pages, token and network directories, guides and price pages |
| Search architecture | Structured metadata, internal linking, sitemaps and staged indexability rules |

The local development version also contains an affiliate portal with registration, referral tracking, dashboard/admin interfaces and Neon/Postgres-backed settlement accounting. This extension is separate from the earlier source revision and has not been revalidated for this showcase release.

## Engineering focus

- Keep provider integration behind application server routes.
- Turn token/network metadata into a usable route-selection experience.
- Handle the journey from a quote to deposit instructions and order status.
- Structure a large family of discovery pages with explicit publishing rules.
- Support provider affiliate attribution as part of order creation.

SideShift supplies exchange execution. The commercial model supports affiliate commissions subject to provider terms and attribution; revenue depends on actual completed activity. No revenue or traffic figures are asserted here. See the provider's [integration documentation](https://docs.sideshift.ai/) and [monetization documentation](https://docs.sideshift.ai/api-intro/monetization/).

## Availability

The hosted demo is currently offline. A walkthrough can be arranged using the project locally. This showcase does not claim a current live-service test or an independent security audit.

## Work with me

I am open to discussing:

- **Project acquisition:** a negotiated handover of agreed code, documentation and project assets.
- **Source licensing:** a defined version for an agreed deployment or business use.
- **Custom implementation:** branding, interface changes, integration work and related web applications.

Email **[support@zyroshift.com](mailto:support@zyroshift.com?subject=ZyroShift%20project%20enquiry)** with your intended use, preferred scope and timeline. See [commercial options](docs/commercial-options.md) for the handover boundaries.

The showcase does not grant a software license. Commercial rights and delivery terms are agreed separately, subject to applicable third-party rights.

Built by [furydu](https://github.com/furydu).
