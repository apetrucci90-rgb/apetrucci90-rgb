# Andrea Petrucci

**Software Developer** *(transitioning from 10 years as Head Chef)* · **deltaX — Developing Systems** · Vicenza, Italy

I spent ten years running professional restaurant kitchens across Veneto and Trentino-Alto Adige. A kitchen in service is a concurrent system under real load: inputs arrive out of order, equipment degrades, and mistakes compound fast — you verify every figure before it goes out and fix the process rather than patching symptoms.

Now I apply that same discipline to building offline-first, verifiable software in **Java**, **Kotlin/Android**, **JavaScript/HTML/CSS**, and **Python** — designing domain models, deterministic architectures, and automated test suites while using AI tools critically as implementation accelerators under strict verification constraints.

---

## Shipped Production Work

### [KitchenMetrics](https://github.com/apetrucci90-rgb/kitchenmetrics-public) — Food Science, Costing &amp; HACCP Suite (`v1.9.8`)

Offline-first suite for professional kitchens, live on [**Google Play**](https://play.google.com/store/apps/details?id=com.kitchenmetrics.app) (`~4 MB`, native Kotlin WebView) and the [**App Store (iOS)**](https://apps.apple.com/app/id6802054330) (`~7 MB`, Capacitor wrapper sharing the exact same engine core).

- **Analytical Physics &amp; Nutrition:** Closed-form transient heat transfer (`Fourier` series + radiative/convective surface balance), sequential 2-stage finite-difference double cooking, `Bigelow` 6.0-log pasteurisation, `Pham (1986)` / `Cleland (2011)` freezing time (`1,108` food profiles), `148`-entry Lipid Science DB, deep-fat frying TPC degradation kinetics, USAR Prime Cost / recipe repricing, and double-entry HACCP Stock &amp; Lot traceability across `23` panels (`EN / IT / ES`).
- **Privacy by Subtraction:** Zero Android OS permissions (`allowBackup="false"`, no `INTERNET`), zero external servers, zero telemetry.
- **Automated Verification (`2026-11-15`):** **`98` test suites (`95` Node + `3` browser stub), `28,712` assertions passing, `0` failures** checking physics parity, i18n keys, regulatory bounds (`50` tracked source documents), backup/restore, and manifest privacy guards.
- **Open Research &amp; ASHRAE Table Audit:**
  - Deposited the plane-sections &amp; hollow-cavity cooking/freezing method on **Zenodo** ([`doi:10.5281/zenodo.22747922`](https://doi.org/10.5281/zenodo.22747922)) with companion repositories ([EN](https://github.com/apetrucci90-rgb/kitchenmetrics-plane-sections-en) · [IT](https://github.com/apetrucci90-rgb/kitchenmetrics-plane-sections-it)).
  - While validating Choi–Okos coefficients against *ASHRAE Handbook — Refrigeration (ch. 9)*, identified a published table discrepancy on water density and reported it to ASHRAE (`2026-07-31`), formally confirmed by the responsible technical committee.
- **Try Online:** [**Live Lipid Science Database Demo**](https://apetrucci90-rgb.github.io/kitchenmetrics-public/lipid-database.html) · [**Technical &amp; Verification Notes**](https://github.com/apetrucci90-rgb/kitchenmetrics-public/blob/main/TECHNICAL.md)

### Commissioned Client Software — *BE Service Energy* *(Private Repo · Delivered &amp; In Production)*

Standalone Windows desktop management suite built and delivered for an energy brokerage client: tariff/service comparison, client &amp; agent directory, operational dashboard, and contract expiry tracking.

- **Stack:** **Java 25**, Maven, zero external runtime dependencies, embedded local HTTP server (`com.sun.net.httpserver` on `127.0.0.1`), atomic file persistence (`Decorator` pattern on TSV storage), covered by **`52` JUnit 5 test suites**, packaged as a native Windows installer.

---

## Stack &amp; Continuous Training

- **Languages &amp; Core Tech:** Java (`Java 25`, OOP, NIO, HTTP server) · JavaScript (`ES6+`) · HTML5 / CSS3 · Kotlin (`Android`) · Python (foundations)
- **Tooling &amp; Architecture:** Git / GitHub · Maven · Gradle · Capacitor (`iOS`) · Automated Unit &amp; Integrity Testing (`JUnit 5`, Node suites) · Offline-First Architectures · Linux (basic)
- **Certifications:**
  - *In progress:* **Oracle Java Foundations (`1Z0-811`)** · **Developing Secure Software (`LFD121` — OpenSSF / Linux Foundation)**
  - *Completed:* **Python Essentials 1** (Cisco Networking Academy) · **Google Android Studio User / Developers Learning Pathway / Introduction to Programming in Kotlin** · **HACCP Certification**

---

📍 Vicenza, Italy · 💼 [LinkedIn](https://www.linkedin.com/in/andrea-petrucci-17a080128) · ✉️ KitchenMetrics support: `uncuocoatavola@gmail.com`
