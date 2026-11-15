# songjogfoundation.org

[songjogfoundation.org](https://songjogfoundation.org) is the international website of Songjog Foundation, the US 501(c)(3) side of the organization. It tells donors and partners abroad about Songjog's work in Bangladesh: digital education, healthcare, skill development and disaster resilience.

![songjogfoundation.org home page](screenshots/home.jpg)

## What changed

The site used to be a single static page. I rebuilt it as a dynamic WordPress site so the team can publish projects and updates on their own, and redesigned it.

```mermaid
flowchart LR
  v[Visitor] --> about[About]
  v --> work[Our work and projects]
  v --> inv[Get involved]
  v --> up[Updates]
  v --> don[Make a donation]
  team[Songjog team] -->|publishes| wp[(WordPress)]
  about & work & inv & up --> wp
```

## Built with

WordPress

## Status

Live at [songjogfoundation.org](https://songjogfoundation.org).
