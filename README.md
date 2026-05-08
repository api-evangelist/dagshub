# DagsHub (dagshub)

DagsHub is a GitHub-like platform for ML and data teams that combines code, data (DVC), experiments (MLflow), and labeling. It exposes a Gitea-compatible REST API for repository operations plus DagsHub-specific endpoints for data and experiments.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/dagshub/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=dagshub-api-evangelist&utm_content=repo)

## Type
- **x-type:** company

## APIs
- **DagsHub REST API** - Gitea-compatible REST at `https://dagshub.com/api/v1` for repos/issues/pulls/branches plus DagsHub extensions for data, experiments, annotations.
- **DagsHub MLflow Tracking Endpoint** - Per-repo MLflow tracking server at `https://dagshub.com/{user}/{repo}.mlflow`.
- **DagsHub DVC / S3-Compatible Storage** - Per-repo DVC remote and S3-compatible storage at `.dvc` URL.

## Tags
- ML, MLOps, Data Versioning, Git, MLflow

## Timestamps
- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## Common Properties
- [Website](https://dagshub.com/)
- [Documentation](https://dagshub.com/docs/)
- [Pricing](https://dagshub.com/pricing)
- [GitHub](https://github.com/DagsHub)
- [Plans](plans/dagshub-plans-pricing.yml)
- [RateLimits](rate-limits/dagshub-rate-limits.yml)
- [FinOps](finops/dagshub-finops.yml)

## Notes
- Pricing reconciled (research): Individual free (20 GB, 100 tracked experiments, 2 collaborators on private); Team $99-119/mo (1 TB or 2M files, 10 members); Enterprise petabyte-scale, VPC/air-gap, SSO/LDAP/OIDC.
- Unusual breadth: bundles Git API + MLflow + DVC remote + S3 + labeling under one product.

## Maintainers
**FN:** Kin Lane

**Email:** kin@apievangelist.com
