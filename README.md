# Drupal Sandbox

Provides a bare-bones Drupal sandbox with Acquia BLT+PHPCS and additional code tools.

## Getting Started

```shell
git clone git@github.com:robphillips/drupal-sandbox.git
```
```shell
fin drush site:install --db-url=mysql://user:user@db:3306/default --no-interaction
```

## Drupal Code Repository

```shell
fin run-clone [project] [git-url|optional]
```
```shell
fin run-reset [project]
```

## Code Validation & Builds

```shell
fin yarn startup
```
```shell
fin blt validate:phpcs
```
```shell
fin run-lint [project]
```
```shell
fin run-build [project]
```
