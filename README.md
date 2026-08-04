# DagsHub (dagshub)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

DagsHub is a GitHub-like platform for ML and data teams that combines code, data (DVC), experiments (MLflow), and labeling. It exposes a Gitea-compatible REST API for repository operations plus DagsHub-specific endpoints for data and experiments.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/dagshub/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/dagshub/refs/heads/main/apis.yml)

## Tags

- ML
- MLOps
- Data Versioning
- Git
- MLflow

## Timestamps

- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## APIs

### DagsHub REST API

DagsHub's primary REST API mirrors the Gitea API for repositories, issues, pulls, branches, and users, with DagsHub-specific extensions for data, experiments, and annotations. Token-based authentication.

- **Human URL:** [https://dagshub.com/docs/reference/api/](https://dagshub.com/docs/reference/api/)
- **Base URL:** `https://dagshub.com/api/v1`

#### Tags

- REST
- Repos
- Issues
- Branches

#### Properties

- [Documentation](https://dagshub.com/docs/reference/api/)
- [Authentication](https://dagshub.com/docs/reference/api/authentication/)
- [Postman Collection](collections/dagshub.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dagshub.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### DagsHub MLflow Tracking Endpoint

Each DagsHub repo provides a hosted MLflow tracking server endpoint. Point `MLFLOW_TRACKING_URI` at the repo's `.mlflow` URL and authenticate with a token.

- **Human URL:** [https://dagshub.com/docs/integration_guide/mlflow_tracking/](https://dagshub.com/docs/integration_guide/mlflow_tracking/)
- **Base URL:** `https://dagshub.com/{user}/{repo}.mlflow`

#### Tags

- MLflow
- Experiment Tracking

#### Properties

- [Documentation](https://dagshub.com/docs/integration_guide/mlflow_tracking/)
- [Postman Collection](collections/dagshub.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dagshub.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### DagsHub DVC / S3-Compatible Storage

DagsHub provides a DVC remote and S3-compatible storage endpoint per repo for versioned data and model artifacts.

- **Human URL:** [https://dagshub.com/docs/integration_guide/dvc/](https://dagshub.com/docs/integration_guide/dvc/)
- **Base URL:** `https://dagshub.com/{user}/{repo}.dvc`

#### Tags

- DVC
- Storage
- S3 Compatible

#### Properties

- [Documentation](https://dagshub.com/docs/integration_guide/dvc/)
- [Postman Collection](collections/dagshub.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dagshub.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/dagshub)
- [Website](https://dagshub.com/)
- [Portal](https://dagshub.com/docs/)
- [Pricing](https://dagshub.com/pricing)
- [GitHub Organization](https://github.com/DagsHub)
- [Plans](plans/dagshub-plans-pricing.yml)
- [Rate Limits](rate-limits/dagshub-rate-limits.yml)
- [Fin Ops](finops/dagshub-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
