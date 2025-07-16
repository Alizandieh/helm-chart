# generic-chart

![Version: 3.3.7](https://img.shields.io/badge/Version-3.3.7-informational?style=flat-square) ![AppVersion: 1.0](https://img.shields.io/badge/AppVersion-1.0-informational?style=flat-square)

A Helm chart for Kubernetes

## Values

| Key | Type | Default | Description |
|-----|------|---------|-------------|
| affinity | object | `{}` |  |
| autoscaling.enabled | bool | `false` |  |
| autoscaling.maxReplicas | int | `8` |  |
| autoscaling.minReplicas | int | `1` |  |
| autoscaling.targetCPUUtilizationPercentage | int | `80` |  |
| containerPorts.http | int | `80` |  |
| containerPorts.https | int | `443` |  |
| fullnameOverride | string | `""` |  |
| image.pullPolicy | string | `"Always"` |  |
| ingress.enabled | bool | `false` |  |
| migrations.command[0] | string | `"sh"` |  |
| migrations.command[1] | string | `"-c"` |  |
| migrations.command[2] | string | `"echo Running migrations..."` |  |
| migrations.enabled | bool | `false` |  |
| migrations.resources | object | `{}` |  |
| nameOverride | string | `""` |  |
| nodeSelector | object | `{}` |  |
| podDisruptionBudget.enabled | bool | `false` |  |
| resources | object | `{}` |  |
| restartPolicy | string | `"Always"` |  |
| service.ports[0].name | string | `"http"` |  |
| service.ports[0].port | int | `80` |  |
| service.ports[0].protocol | string | `"TCP"` |  |
| service.ports[0].targetPort | string | `"http"` |  |
| service.type | string | `"ClusterIP"` |  |
| serviceAccount.create | bool | `false` |  |
| serviceMonitor.enabled | bool | `false` |  |
| tolerations | list | `[]` |  |
| vpa.enabled | bool | `false` |  |

