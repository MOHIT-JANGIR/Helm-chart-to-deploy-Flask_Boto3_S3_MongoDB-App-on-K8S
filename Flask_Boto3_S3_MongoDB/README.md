# ๐ฅ ๐๐ง๐ญ๐๐ ๐ซ๐๐ญ๐ข๐จ๐ง ๐จ๐ "๐๐ฅ๐๐ฌ๐ค+๐๐จ๐ญ๐จ๐+๐๐๐ ๐๐+๐๐จ๐ง๐ ๐จ๐๐+๐๐ข๐ง๐ฎ๐ฑ+๐๐ฒ๐ญ๐ก๐จ๐ง๐+๐๐๐๐+๐๐ฐ๐ง ๐๐ฎ๐ฌ๐ญ๐จ๐ฆ ๐๐ฒ๐ญ๐ก๐จ๐ง ๐๐จ๐๐ฎ๐ฅ๐๐ฌ"...๐ฅ

๐ข I, [MOHIT JANGIR](https://www.linkedin.com/in/mohit-jangir-86b290174/) , have successfully Created a Flask WebApp i.e. Actually like a online portal for Job-Applicants, Where they can upload their Name, Email, Resume etc , Utilising the Power of AWS S3(For Storing Big-Data Files) & MongoDB(To Store Static Data With Reference Of S3) in the BackEnd ...๐ข


# Flask

[Flask](https://flask-doc.readthedocs.io/en/latest/) is a web framework, itโs a Python module that lets you develop web applications easily. Itโs has a small and easy-to-extend core: itโs a microframework that doesnโt include an ORM (Object Relational Manager) or such features.

It does have many cool features like url routing, template engine. It is a WSGI web app framework.

This chart installs a Flask_Boto3_S3_MongoDB WebApp Over K8S which spawns agents on [Kubernetes](http://kubernetes.io) utilizing the [Jenkins Kubernetes plugin](https://plugins.jenkins.io/kubernetes/).

Created by the awesome work of [MOHIT JANGIR](https://github.com/MOHIT-JANGIR).

## Get Repo Info

```console
helm repo add jenkins https://mohit-jangir.github.io/Helm-chart-to-deploy-Flask_Boto3_S3_MongoDB-App-on-K8S/charts
helm repo update
```

_See [helm repo](https://helm.sh/docs/helm/helm_repo/) for command documentation._

## Install Chart

```console
# Helm 3
$ helm install [RELEASE_NAME] Flask_Boto3_S3_MongoDB/Flask_Boto3_S3_MongoDB [flags]
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
$ helm upgrade [RELEASE_NAME] Flask_Boto3_S3_MongoDB/Flask_Boto3_S3_MongoDB [flags]
```

_See [helm upgrade](https://helm.sh/docs/helm/helm_upgrade/) for command documentation._



## Configuration

See [Customizing the Chart Before Installing](https://helm.sh/docs/intro/using_helm/#customizing-the-chart-before-installing).
To see all configurable options with detailed comments, visit the chart's [values.yaml](https://github.com/MOHIT-JANGIR/K8S_HELM_CHART/blob/main/jenkins/values.yaml), or run these configuration commands:

```console
# Helm 3
$ helm show values Flask_Boto3_S3_MongoDB/Flask_Boto3_S3_MongoDB
```
