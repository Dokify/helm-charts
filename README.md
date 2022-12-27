# Helm-Charts

This repository contains [Helm](https://helm.sh) charts for various projects.

- [cert-manager](https://github.com/dokify/helm-charts/tree/master/charts/cert-manager)
- [common](https://github.com/dokify/helm-charts/tree/master/charts/common)
- [elasticsearch](https://github.com/dokify/helm-charts/tree/master/charts/elasticsearch)
- [external-secrets](https://github.com/dokify/helm-charts/tree/master/charts/external-secrets)
- [jx](https://github.com/dokify/helm-charts/tree/master/charts/jx)
- [jenkins-x-platform](https://github.com/dokify/helm-charts/tree/master/charts/jenkins-x-platform)
- [lighthouse](https://github.com/dokify/helm-charts/tree/master/charts/lighthouse)
- [Osiris](https://github.com/dokify/helm-charts/tree/master/charts/osiris)
- [MysqlCluster](https://github.com/dokify/helm-charts/tree/master/charts/mysql-cluster)
- [MysqlOperator](https://github.com/dokify/helm-charts/tree/master/charts/mysql-operator)
- [MongoDB Community](https://github.com/dokify/helm-charts/tree/master/charts/mongodb)
- [Octant](https://github.com/dokify/helm-charts/tree/master/charts/octant)
- [mongo-express](https://github.com/dokify/helm-charts/tree/master/charts/mongo-express)
- [keycloak](https://github.com/dokify/helm-charts/tree/master/charts/keycloak)
- [kube-prometheus-stack](https://github.com/dokify/helm-charts/tree/master/charts/kube-prometheus-stack)
- [kuberhealthy](https://github.com/dokify/helm-charts/tree/master/charts/kuberhealthy)
- [keda-add-ons-http](https://github.com/dokify/helm-charts/tree/master/charts/keda-add-ons-http)
- [keda](https://github.com/dokify/helm-charts/tree/master/charts/keda)
- [rabbitmq-cluster-operator](https://github.com/dokify/helm-charts/tree/master/charts/rabbitmq-cluster-operator)

## Installing Charts from this Repository

Add the Repository to Helm:

```sh
helm repo add dokify-helm-charts https://dokify.github.io/helm-charts
```

Install a chart:

```sh
helm install dokify-helm-charts/[CHART_NAME]
```
