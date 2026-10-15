<p align="center">
  <img src="assets/feature-graphic.png" alt="MuchiLife product artwork" width="100%" />
</p>

<h1 align="center">MuchiLife</h1>

<p align="center">
  <strong>Choose the time. Choose the apps. Protect the boundary you set.</strong>
</p>

<p align="center">
  <a href="https://muchiworks.com/products/muchilife">Product website</a> ·
  <a href="PRODUCT_CASE_STUDY.md">Product case study</a> ·
  <a href="ENGINEERING_CASE_STUDY.md">Engineering case study</a> ·
  <a href="ARCHITECTURE.md">Technical overview</a> ·
  <a href="SHIPPING_LOG.md">Shipping log</a>
</p>

## Product at a glance

MuchiLife is an Android product for setting a deliberate boundary around selected
apps during a Focus session. A person chooses a duration between 15 minutes and
8 hours, selects the apps to keep closed, and follows the remaining time until
the session ends.

The product does not depend on advertising or engagement loops. Its job is to
support a decision, keep the chosen boundary visible, and get out of the way when
the session is complete.

**Current status:** Google Play closed testing.

## Product flow

| Decide why | See how it works | Configure Focus |
| --- | --- | --- |
| <img src="assets/screenshots/01-focus-intro-park.png" alt="MuchiLife introduction" /> | <img src="assets/screenshots/02-how-focus-works-park.png" alt="How MuchiLife Focus works" /> | <img src="assets/screenshots/03-focus-setup-park.png" alt="Configure a Focus session" /> |

| Stay with the timer | Focus Shield |
| --- | --- |
| <img src="assets/screenshots/04-active-focus-park.png" alt="Active Focus timer" /> | <img src="assets/screenshots/05-shield-overlay-park.png" alt="Focus Shield over a selected app" /> |

## Engineering scope

- React Native and TypeScript application with Android native integrations
- Android API 24+ support across phones and tablets
- Managed cloud services for application data and supported sign-in methods
- Google Play commerce integration
- Resilient product behavior across common device and network interruptions
- Separate development and production delivery environments
- Twelve localized application experiences and synchronized Android resources
- Testing, monitoring, account controls, and release validation

## Technical overview

```mermaid
flowchart LR
    App[Android application] <--> Services[Managed application services]
    App <--> Store[Google Play services]
```

The public overview intentionally stays at product-boundary level. Non-public
design and implementation details are omitted.

## Ownership

MuchiLife is designed and engineered by **Metin Cetin**, founder of
**MuchiWorks**. The work spans product direction, mobile engineering, backend
services, commerce, quality, testing, documentation, and Google Play delivery.

## Source availability

The application and backend source code are private and proprietary. This public
repository is a product and engineering case study. It contains no production
credentials, user data, or deployable application source.
