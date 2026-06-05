# DagsHub (dagshub)

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
