# Awesome-Feature-Experimentation

# Top Feature Experimentation Platforms Ecosystem
**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on A/B Testing, Feature Flags, Experimentation Stats, Warehouse-Native Analysis & Progressive Delivery*
**Last updated: September 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Feature Experimentation**. These systems enable A/B and multivariate testing, feature flag-driven experiments, statistical analysis, and warehouse-native metrics so product teams can measure impact and ship with confidence.

**Examples** include Statsig, Eppo, Optimizely, VWO, AB Tasty, Kameleoon, GrowthBook, LaunchDarkly Experiments, Convert Experiences, and Dynamic Yield (the category leaders).

**Open-source emphasis**: Feature experimentation has a strong open-source leader in **GrowthBook** (feature flags + experimentation + warehouse-native stats). Related open feature-flag platforms (Unleash, Flagsmith) also support experimentation workflows. This section is heavily expanded.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms
- **[Statsig](https://www.statsig.com/)**  
  Product experimentation and feature-management platform with advanced stats (CUPED, sequential, Bayesian), feature flags, and high-volume event infrastructure.

- **[Eppo](https://www.geteppo.com/)**  
  Warehouse-native experimentation platform focused on statistical rigor, CUPED, sequential testing, and deep integration with data warehouses for mature data teams.

- **[Optimizely](https://www.optimizely.com/)**  
  Enterprise experimentation and feature-management platform with visual editing, server-side testing, and full-stack experimentation capabilities.

- **[VWO](https://vwo.com/)**  
  Conversion optimization and experimentation platform with A/B testing, visual editor, and insights for web and product teams.

- **[AB Tasty](https://www.abtasty.com/)**  
  Experimentation and personalization platform for A/B testing, feature experimentation, and customer experience optimization.

- **[Kameleoon](https://www.kameleoon.com/)**  
  AI-driven experimentation and personalization platform for A/B testing and feature experimentation across web and apps.

- **[GrowthBook Cloud](https://www.growthbook.io/)**  
  Managed offering of the open-source GrowthBook platform—feature flags, experimentation, and warehouse-native analysis.

- **[LaunchDarkly (Experiments)](https://launchdarkly.com/)**  
  Feature management platform with experimentation capabilities layered on top of robust feature-flag infrastructure.

- **[Convert Experiences](https://www.convert.com/)**  
  A/B testing and experimentation platform with visual editor and targeting for conversion optimization.

- **[Dynamic Yield](https://www.dynamicyield.com/)**  
  Personalization and experimentation platform used for A/B testing, recommendations, and experience optimization at scale.

## Open-Source GitHub Projects
- **[GrowthBook](https://github.com/growthbook/growthbook)**  
  Leading open-source platform for feature flags, experimentation, and product analytics—warehouse-native metrics, advanced stats engine, and full self-hosting (MIT).

- **[Unleash](https://github.com/Unleash/unleash)**  
  Open-source feature flag and experimentation platform with strategies, gradual rollouts, and SDKs for progressive delivery.

- **[Flagsmith](https://github.com/Flagsmith/flagsmith)**  
  Open-source feature flag and remote config platform that supports experimentation and targeting workflows.

- **[PostHog (experiments / flags)](https://github.com/PostHog/posthog)**  
  Open-source product analytics platform with feature flags and experimentation capabilities.

- **[Experiment stats and analysis open libraries](https://github.com/)**  
  Open statistical libraries and notebooks implementing CUPED, sequential testing, Bayesian methods, and SRM checks.

- **[Feature-flag open SDKs and evaluators](https://github.com/)**  
  Client and server SDKs used to evaluate flags and assign experiment variations locally.

- **[Warehouse-native metric open connectors](https://github.com/)**  
  SQL and connector patterns for defining experiment metrics directly on BigQuery, Snowflake, Redshift, and similar warehouses.

- **[Visual editor and front-end experiment open tools](https://github.com/)**  
  Community tools for client-side A/B testing and visual variation management.

- **[Progressive delivery open controllers](https://github.com/)**  
  Kubernetes and application-level tools (e.g., Flagger, Argo Rollouts) that complement feature experimentation with traffic shifting.

- **[Awesome feature-flag and experimentation lists](https://github.com/)**  
  Curated collections of open tools and best practices for flags and experiments.

### Additional Strong Open-Source Options
- Self-hosting **GrowthBook** for full control of flags, experiments, and warehouse-native analysis.
- Using **Unleash** or **Flagsmith** when feature flags are the primary need and experiments are secondary.
- Combining open flags with commercial stats engines (or vice versa) in hybrid setups.
- Accepting that polished visual editors, global edge evaluation, advanced enterprise governance, and managed stats infrastructure still favor commercial platforms (Statsig, Eppo, Optimizely, VWO, LaunchDarkly, etc.).
- Focusing open-source efforts on data ownership, transparent stats, and avoiding vendor lock-in for experiment results.

**Frameworks for building custom systems**: Define flags and experiments in GrowthBook (or Unleash) → assign variations via SDKs → log events to your warehouse → compute metrics with warehouse-native SQL or GrowthBook’s engine → decide and roll out. Suitable for engineering-led product teams. Many organizations run GrowthBook self-hosted or use commercial platforms for higher-touch stats and support.

## How to Contribute
1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer
- This is a **community-curated** list — not exhaustive and not an endorsement.
- Experimentation systems influence user experience and product decisions. Proper statistical practice, privacy compliance, and change control are required. This list is not statistical or product advice.

---
**Made for product engineers, data scientists, and growth teams running rigorous experiments.**
Let's keep experimentation transparent, warehouse-native, and as open as practical.
