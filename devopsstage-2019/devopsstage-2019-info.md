# DevOpsStage 2019 - Kubernetes Navigation Stories

[Talk slides](./DevOpsStage-2019-slides.pdf)

## Talk descrption

thredUP is the largest online consignment store for women’s and children’s clothes. thredUP was launched in 2009 as a monolithic application running on Amazon Web Services. Since then it has evolved into a fully containerized distributed system powered by Kubernetes

We have started Kubernetes evaluation in 2017 and within a year migrated all production services on it. Now we are 100% in Kubernetes for 1.5 years. Migration has enabled faster releases with a cycle time under 20 minutes, decreased hardware cost by 60% while a number of services has doubled, unified infrastructure automation, decreased new service rollout time from weeks to minutes/hours.

Was our Kubernetes journey finished after the migration? Definitely not. thredUP team will share key learnings from after-migration processes about what technologies and solutions worked best for us and where we spent time troubleshooting and improving. In particular we have focused on development and staging experience, user authentication, cloud-native CI pipelines, applications telemetry and service mesh. We also share our experience with Kubernetes security hardening, autoscaling and tell you about a new service creation within our infrastructure.

## Useful links from the talk

[aws-iam-authenticator](https://docs.aws.amazon.com/eks/latest/userguide/install-aws-iam-authenticator.html) - Installing aws-iam-authenticator

[Hashicorp Vault](https://www.vaultproject.io/) - Secrets Manager

[Daytona project](https://github.com/cruise-automation/daytona) – a vault client, but for servers and containers.

[SOPS: Secrets OPerationS](https://github.com/mozilla/sops) – Simple and flexible tool for managing secrets

[Telepresence](https://www.telepresence.io/) – fast, local development for kubernetes and openshift microservices

[Falco](https://falco.org/) – Container Native Runtime Security

[Clair](https://coreos.com/clair/docs/latest/) – static analysis of vulnerabilities in appc and docker containers

[Istio](https://istio.io/) - Kubernetes Service Mesh