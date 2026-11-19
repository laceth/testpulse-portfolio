<p align="center">
  <img src="assets/banner.svg" width="100%" alt="Tarik Riley, BMI2 AI engineering portfolio: Fiduciary, TestPulse, AIM and A&R">
</p>

<p align="center">
  <img alt="Merged PRs built with Claude Code: 1,150" src="https://img.shields.io/badge/merged%20PRs%20with%20Claude%20Code-1%2C150-1C7268">
  <img alt="Automated tests: about 29,000" src="https://img.shields.io/badge/automated%20tests-~29%2C000-1C7268">
  <img alt="AIM built in 41 days" src="https://img.shields.io/badge/AIM%20built%20in-41%20days-1C7268">
  <img alt="MCP tools: 155" src="https://img.shields.io/badge/MCP%20tools-155-1C7268">
  <img alt="Counted 2026-11-17" src="https://img.shields.io/badge/counted-2026--11--17-3F4757">
</p>

<p align="center">
  <a href="https://www.bmi2.com/">bmi2.com</a> ·
  <a href="https://www.bmi2.com/demos/">Watch the demos</a> ·
  <a href="https://www.bmi2.com/engineering/">Engineering approach</a> ·
  <a href="https://www.bmi2.com/work-with-tarik/">Background</a> ·
  <a href="mailto:triley@bmi2.com?subject=Portfolio%20walkthrough">Book a walkthrough</a>
</p>

> [!NOTE]
> The four products' source repositories are private. This page shows what was built, with real screenshots from the
> lab and measurements counted from git. Images load live from bmi2.com, so they always match the site. A live
> walkthrough or time-limited code access is available on request.

<p align="center">
  <a href="https://www.bmi2.com/"><img src="https://bmi2.com/media/two-products-one-rule-20261002.jpg" width="100%" alt="No evidence, no answer: the same rule governs a network outage and a commercial loan"></a>
  <br>
  <sub>▶ <a href="https://www.bmi2.com/">Watch the 2-minute video: <i>Two products. One rule.</i></a></sub>
</p>

## The four products

<table>
  <tr>
    <td width="50%" valign="top">
      <img src="https://bmi2.com/fiduciary/img/live-ask-ai-copilot.png" width="100%" alt="Fiduciary Ask AI copilot answering over a live dashboard of deals">
      <h3>Fiduciary <img alt="private preview" src="https://img.shields.io/badge/-private%20preview-F6E3C4?style=flat-square"></h3>
      Governed AI for capital-investment lending. Agents cite permitted evidence and draft each step from intake to
      payoff; a person signs every step that moves money.
      <br><br><a href="products/fiduciary.md">Read more →</a>
    </td>
    <td width="50%" valign="top">
      <img src="https://bmi2.com/media/poster-copilot.jpg?v=20261021" width="100%" alt="TestPulse copilot: an OpenTelemetry summary and AAA forensic trace beside the chat">
      <h3>TestPulse <img alt="available now" src="https://img.shields.io/badge/-available%20now-D7EFEA?style=flat-square"></h3>
      Evidence-first AI diagnostics for failed network logins. Names the cause, cites the packets behind it, and
      trains vendor-specific models from human-certified runs.
      <br><br><a href="products/testpulse.md">Read more →</a> · <a href="https://www.bmi2.com/demos/">4 demos ↗</a>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <img src="https://bmi2.com/media/aim-ui-overview.png" width="100%" alt="AIM overview: Fiduciary, A&R and TestPulse panels, each endpoint with its own freshness">
      <h3>AIM <img alt="running in the lab" src="https://img.shields.io/badge/-running%20in%20the%20lab-D7EFEA?style=flat-square"></h3>
      Monitoring, business assurance and governance for the AI itself: model runs, spend against ceilings, a
      NIST-mapped risk register, and red-team scans behind a human approval.
      <br><br><a href="products/aim.md">Read more →</a>
    </td>
    <td width="50%" valign="top">
      <img src="https://bmi2.com/media/ask-ai-across-the-roster-20261006b.jpg" width="100%" alt="Ask AI across your roster: plain-English questions answered from your own records, with citations">
      <h3>A&amp;R <img alt="design partner" src="https://img.shields.io/badge/-design%20partner-E5E2DA?style=flat-square"></h3>
      Governed AI for artist development: roster answers with a 90% confidence gate, and drafted Slack, schedule and
      spreadsheet actions that a person approves.
      <br><br><a href="products/ar.md">Read more →</a>
    </td>
  </tr>
</table>

## See it working

**An honest refusal, with the reason.** Fiduciary's Ask AI, signed in as a junior analyst who isn't authorized for the
diagnosis lens: no search, no model call, and the reason on screen.

<img src="https://bmi2.com/media/ask-ai-three-identities-20261002.jpg" width="100%" alt="Fiduciary Ask AI refusing a junior analyst, showing the purpose gate that blocked the request">

**A dashboard that won't pretend.** AIM when Fiduciary stops answering: the panel turns red with the cause and the last
success time, and it's never shown as healthy.

<img src="https://bmi2.com/media/aim-ui-fault-unreachable.png" width="100%" alt="AIM with Fiduciary unreachable, showing timeouts per endpoint">

<table>
  <tr>
    <td width="50%" valign="top">
      <b>A&amp;R, the whole artist lifecycle.</b> A 10-artist roster, the AI lenses and the human approval layer on one page.
      <br><br>
      <img src="https://bmi2.com/media/ar-artist-development-dashboard.png" width="100%" alt="A&R artist development operating layer dashboard">
    </td>
    <td width="50%" valign="top">
      <b>Nothing trains without a human seal.</b> TestPulse's teaching cell: graded blind, signed by an expert, then
      QLoRA-trained on Amazon SageMaker.
      <br><br>
      <img src="https://bmi2.com/media/poster-teachingcell.jpg" width="100%" alt="TestPulse curriculum trainer report card">
    </td>
  </tr>
</table>

## Velocity, measured from git

| 1,150 | 41 days | 842 | ~29,000 |
|:---:|:---:|:---:|:---:|
| merged PRs built with Claude Code, Apr–Nov 2026 | AIM, from design decision to 100 merged PRs | Fiduciary PRs in 16 weeks | test functions, Python and TypeScript |

All counted from GitHub on 2026-11-17; every merged PR was authored by me. Per-repository figures and method:
[ENGINEERING.md](ENGINEERING.md).

## How I work

Speed only matters if the code is right. Every change, docs included, goes through the same loop:

```mermaid
flowchart LR
    A[Decision record] --> B[Build with Claude Code]
    B --> C[Tests fail without the fix]
    C --> D[Independent AI review]
    D --> E[Merge the reviewed commit]
    E --> F[Verify live]
```

A real catch: a review found a calendar route that let any authorized user read any mailbox the shared credential
could reach. I fixed it the same day, with the allowlist enforced at the route and again in both executors.
[More in ENGINEERING.md →](ENGINEERING.md)

## Stack

![Python](https://img.shields.io/badge/Python%203.12-3776AB?logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript%20%C2%B7%20React-3178C6?logo=typescript&logoColor=white)
![Postgres](https://img.shields.io/badge/Postgres%20%C2%B7%20RLS%20%C2%B7%20pgvector-336791?logo=postgresql&logoColor=white)
![AWS](https://img.shields.io/badge/AWS%20Bedrock%20%C2%B7%20SageMaker-232F3E?logo=amazonwebservices&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes%20%C2%B7%20Argo%20CD-326CE5?logo=kubernetes&logoColor=white)
![Keycloak](https://img.shields.io/badge/Keycloak%20%C2%B7%20OPA-4D4D4D?logo=keycloak&logoColor=white)
![NATS](https://img.shields.io/badge/NATS%20JetStream-27AAE1?logo=natsdotio&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?logo=playwright&logoColor=white)
![MCP](https://img.shields.io/badge/MCP%20servers-6E40C9)

## Background

Twenty years in telecom automation and test engineering at AT&T, Verizon, Spirent, Viasat and DISH, before founding
BMI2 in Round Rock, Texas. [Full background →](https://www.bmi2.com/work-with-tarik/)

---

<sub>Copyright © 2025–2026 Tarik Riley / BMI2. All rights reserved. Portfolio review only; no license is granted to
copy, modify, redistribute, reverse engineer, or use the products, branding, designs, or documentation except as
permitted in writing by BMI2. See <a href="NOTICE.md">NOTICE.md</a>.</sub>
