# Flask

[Flask](https://flask-doc.readthedocs.io/en/latest/) is the leading open source automation server, Jenkins provides hundreds of plugins to support building, deploying and automating any project.

This chart installs a Flask_Boto3_S3_MongoDB WebApp Over K8S which spawns agents on [Kubernetes](http://kubernetes.io) utilizing the [Jenkins Kubernetes plugin](https://plugins.jenkins.io/kubernetes/).

Created by the awesome work of [MOHIT JANGIR](https://github.com/MOHIT-JANGIR).

## Get Repo Info

```console
helm repo add jenkins https://mohit-jangir.github.io/K8S_HELM_CHART/charts
helm repo update
```

_See [helm repo](https://helm.sh/docs/helm/helm_repo/) for command documentation._

## Install Chart

```console
# Helm 3
$ helm install [RELEASE_NAME] flask/flask [flags]
```

_See [configuration](#configuration) below._

_See [helm install](https://helm.sh/docs/helm/helm_install/) for command documentation._

## Uninstall Chart

```console
# Helm 3
$ helm uninstall [RELEASE_NAME]
```

This removes all the Kubernetes components associated with the chart and deletes the release.

_See [helm uninstall](https://helm.sh/docs/helm/helm_uninstall/) for command documentation._

## Upgrade Chart

```console
# Helm 3
$ helm upgrade [RELEASE_NAME] jenkins/jenkins [flags]
```

_See [helm upgrade](https://helm.sh/docs/helm/helm_upgrade/) for command documentation._



## Configuration

See [Customizing the Chart Before Installing](https://helm.sh/docs/intro/using_helm/#customizing-the-chart-before-installing).
To see all configurable options with detailed comments, visit the chart's [values.yaml](https://github.com/MOHIT-JANGIR/K8S_HELM_CHART/blob/main/jenkins/values.yaml), or run these configuration commands:

```console
# Helm 3
$ helm show values flask/flask
```
