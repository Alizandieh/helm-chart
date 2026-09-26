# Helm Charts

Generic Helm charts and templates to deploy different applications on K8s.

## Getting started

Before working with the repository it is **mandatory** to execute the following command:

```
pre-commit run -a
```

If you haven't installed pre-commit yet:

```
brew install pre-commit
pre-commit install
pre-commit run -a
```

## Principles

The generic-chart should cover most of the applications either bakcend or frontend. Only create a new chart if you need something special that the generic-chart can't offer.

