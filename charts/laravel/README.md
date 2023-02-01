# Laravel Helm chart

Helm chart for Laravel applications

## Installation

To add the `laravel` helm repo, run:

```sh
helm repo add laravel https://sre-charts.github.io/laravel-helm-chart
```

To install a release named `laravel`, run:

```sh
helm install laravel laravel/laravel
```

## Chart values

```sh
helm show values laravel/laravel
```

