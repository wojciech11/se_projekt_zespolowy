# Projektowanie i Wdrażanie

Projektowanie:

- Design doc,
- Estimations,
- Horizontal vs Vertical scalling,
- Traceable bullet approach,
- lightweigh diagrams - lucid, yEd, ...,
- patterns (queues),
- DDD.

Wdrażanie:

- envs,
- [Continoues Deployment](https://github.com/wojciech11/se_continuous_delivery_and_deployment)
- Infrastructure-as-a-Code (about [Terraform](https://github.com/wojciech12/talk_best_practices_for_infra_as_a_code_with_Terraform)),
- Deployment strategies (examples for [k8s](https://github.com/wojciech12/talk_zero_downtime_deployment_with_kubernetes)), goal - zero downtime:

  - **feature flags**,
  - rolling,
  - blue/green,
  - canary,
  - shadow deployment.

- observability - monitoring, logging, APM, tracing (see [the course on cloud app administration and dev](https://github.com/wojciech11/se_cloud_app_administration_and_development)),
- error budget.

```mermaid
flowchart LR
    CI(Continuous\nIntegration) --> CDel(Continuous\nDelivery) --> CD(Continuous\nDeployment)
```

Automatyzacja:

- effective != efficient

## References

- [Practice of Cloud System Administration, The: DevOps and SRE Practices for Web Services, Volume 2](https://www.amazon.com/Practice-Cloud-System-Administration-Practices/dp/032194318X),
- [The DevOps Handbook: How to Create World-Class Agility, Reliability, & Security in Technology Organizations](https://www.amazon.com/DevOps-Handbook-World-Class-Reliability-Organizations/dp/1950508404/ref=d_pd_sbs_sccl_2_11/132-3064294-1858128).
