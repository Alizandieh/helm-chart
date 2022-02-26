# Generic App Chart

Note: to use this with Helm2, use the 1.X versions.


# Changelog

#### 3.3.7

- Feature: Add ingressClassName to ingress. so that it could work with new version of k8s (1.19 and above) and nginx ingress controller

#### 3.3.6

- Feature: Add envFrom.configMaps list support.

#### 3.3.5

- Feature: Add deploymentAnnotations support.

#### 3.3.4

- Fix: Use new format for Ingress

#### 3.2.3

- Feature: Add envFrom.secretRef support.

#### 3.2.3

- Feature: Add support for restartPolicy.

#### 3.2.2

- Feature: Add support for metricsPort.

#### 3.2.1

- Feature: Add support for serviceMonitor.

### 3.2.0

- Fix: Use newer `networking.k8s.io/v1beta1` API for Ingresses.

#### 3.1.3
 
 - Feature: Add support for securityContext, podSecurityContext.
 - Feature: Add support for podDisruptionBudget.
 - Feature: Add support for HPA.
 - Feature: Add icon.

#### 3.1.2
 
 - Feature: Add support for serviceLabels.

#### 3.1.1
 
 - Fix: VPA is now disabled by default.
 - Fix: Helm 3.3.0 compat (fix warning about configMaps name).

### 3.1.0
 
 - PL-114 Add support to DB migrations

## 3.0.0

- BREAKING: `probes` don't have an `enabled` field anymore.

### 2.0.2

- Feature: Add support for `image.name`.

### 2.0.1

- Fix: Fix volumes/volumesMounts.

## 2.0.0

- BREAKING: `apiVersion` is now `v2`, so the 2.X versions are only compatible with Helm3.

## 1.0.3 and Before

Original version.
