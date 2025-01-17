# testkube-dashboard

![Version: 1.14.2](https://img.shields.io/badge/Version-1.14.2-informational?style=flat-square) ![Type: application](https://img.shields.io/badge/Type-application-informational?style=flat-square) ![AppVersion: 1.14.2](https://img.shields.io/badge/AppVersion-1.14.2-informational?style=flat-square)

A Helm chart for Kubernetes

## Requirements

| Repository | Name | Version |
|------------|------|---------|
| file://../global | global | 0.1.2 |

## Values

| Key | Type | Default | Description |
|-----|------|---------|-------------|
| affinity | object | `{}` |  |
| apiServerEndpoint | string | `""` |  |
| autoscaling.annotations | object | `{}` |  |
| autoscaling.enabled | bool | `false` |  |
| autoscaling.labels | object | `{}` |  |
| autoscaling.maxReplicas | int | `100` |  |
| autoscaling.minReplicas | int | `1` |  |
| autoscaling.targetCPUUtilizationPercentage | int | `80` |  |
| autoscaling.targetMemoryUtilizationPercentage | int | `80` |  |
| crdRevision | string | `"main"` |  |
| disableTelemetry | bool | `false` |  |
| extraEnvVars | list | `[]` |  |
| fullnameOverride | string | `""` |  |
| global.annotations | object | `{}` |  |
| global.imagePullSecrets | list | `[]` |  |
| global.imageRegistry | string | `""` |  |
| global.labels | object | `{}` |  |
| image.digest | string | `""` |  |
| image.pullPolicy | string | `"IfNotPresent"` |  |
| image.pullSecrets | list | `[]` |  |
| image.registry | string | `"docker.io"` |  |
| image.repository | string | `"kubeshop/testkube-dashboard"` |  |
| ingress.annotations | object | `{}` |  |
| ingress.enabled | bool | `false` |  |
| ingress.hosts | list | `[]` |  |
| ingress.ipv6enabled | bool | `false` |  |
| ingress.labels | object | `{}` |  |
| ingress.path | string | `"/"` |  |
| ingress.tls | list | `[]` |  |
| ingress.tlsenabled | bool | `false` |  |
| kubeVersion | string | `""` |  |
| nameOverride | string | `""` |  |
| nodeSelector | object | `{}` |  |
| oauth2.annotations | object | `{}` |  |
| oauth2.args | list | `[]` |  |
| oauth2.enabled | bool | `false` |  |
| oauth2.env.clientId | string | `""` |  |
| oauth2.env.clientSecret | string | `""` |  |
| oauth2.env.cookieSecret | string | `""` |  |
| oauth2.env.cookieSecure | string | `"false"` |  |
| oauth2.env.githubOrg | string | `""` |  |
| oauth2.env.redirectUrl | string | `"http://testkube.example.com/oauth2/callback"` |  |
| oauth2.env.secretClientIdKey | string | `""` |  |
| oauth2.env.secretClientIdName | string | `""` |  |
| oauth2.env.secretClientSecretKey | string | `""` |  |
| oauth2.env.secretClientSecretName | string | `""` |  |
| oauth2.env.secretCookieSecretKey | string | `""` |  |
| oauth2.env.secretCookieSecretName | string | `""` |  |
| oauth2.env.secretGithubOrgKey | string | `""` |  |
| oauth2.env.secretGithubOrgName | string | `""` |  |
| oauth2.extraEnvFrom | list | `[]` |  |
| oauth2.extraEnvVars | list | `[]` |  |
| oauth2.image.pullPolicy | string | `"Always"` |  |
| oauth2.image.pullSecrets | list | `[]` |  |
| oauth2.image.registry | string | `"quay.io"` |  |
| oauth2.image.repository | string | `"oauth2-proxy/oauth2-proxy"` |  |
| oauth2.image.tag | string | `"latest"` |  |
| oauth2.ingress.labels | object | `{}` |  |
| oauth2.labels | object | `{}` |  |
| oauth2.name | string | `"oauth2-proxy"` |  |
| oauth2.path | string | `"/oauth2"` |  |
| oauth2.podAnnotations | object | `{}` |  |
| oauth2.podLabels | object | `{}` |  |
| oauth2.port | int | `4180` |  |
| oauth2.priorityClassName | string | `""` |  |
| oauth2.serviceAnnotations | object | `{}` |  |
| oauth2.serviceLabels | object | `{}` |  |
| oauth2.serviceType | string | `"ClusterIP"` |  |
| oauth2.volumeMounts | list | `[]` |  |
| oauth2.volumes | list | `[]` |  |
| podAnnotations | object | `{}` |  |
| podLabels | object | `{}` |  |
| podSecurityContext | object | `{}` |  |
| priorityClassName | string | `""` |  |
| proxyPrefix | string | `""` |  |
| replicaCount | int | `1` |  |
| resources | object | `{}` |  |
| securityContext | object | `{}` |  |
| service.annotations | object | `{}` |  |
| service.port | int | `8080` |  |
| service.type | string | `"ClusterIP"` |  |
| serviceAccount.annotations | object | `{}` |  |
| serviceAccount.create | bool | `true` |  |
| serviceAccount.name | string | `""` |  |
| testConnection.enabled | bool | `false` |  |
| tolerations | list | `[]` |  |

----------------------------------------------
Autogenerated from chart metadata using [helm-docs v1.11.2](https://github.com/norwoodj/helm-docs/releases/v1.11.2)
