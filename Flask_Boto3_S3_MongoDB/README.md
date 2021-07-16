# 🔥 𝐈𝐧𝐭𝐞𝐠𝐫𝐚𝐭𝐢𝐨𝐧 𝐨𝐟 "𝐅𝐥𝐚𝐬𝐤+𝐁𝐨𝐭𝐨𝟑+𝐀𝐖𝐒 𝐒𝟑+𝐌𝐨𝐧𝐠𝐨𝐃𝐁+𝐋𝐢𝐧𝐮𝐱+𝐏𝐲𝐭𝐡𝐨𝐧𝟑+𝐇𝐓𝐌𝐋+𝐎𝐰𝐧 𝐂𝐮𝐬𝐭𝐨𝐦 𝐏𝐲𝐭𝐡𝐨𝐧 𝐌𝐨𝐝𝐮𝐥𝐞𝐬"...🔥

📢 I, [MOHIT JANGIR](https://www.linkedin.com/in/mohit-jangir-86b290174/) , have successfully Created a Flask WebApp i.e. Actually like a online portal for Job-Applicants, Where they can upload their Name, Email, Resume etc , Utilising the Power of AWS S3(For Storing Big-Data Files) & MongoDB(To Store Static Data With Reference Of S3) in the BackEnd ...📢


# Flask

[Flask](https://flask-doc.readthedocs.io/en/latest/) is a web framework, it’s a Python module that lets you develop web applications easily. It’s has a small and easy-to-extend core: it’s a microframework that doesn’t include an ORM (Object Relational Manager) or such features.

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
