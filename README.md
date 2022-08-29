# Drupal Sandbox

Provides a bare bones Drupal sandbox with Acquia BLT+PHPCS and additional code tools installed.

## Getting Started

```shell
git clone git@github.com:robphillips/drupal-sandbox.git 9.x
```

## Drupal Code Repository

Need to work on an issue or new feature for a Drupal Code hosted project? Use this shortcut to clone the repository
into the `web/modules/drupalcode` directory.

```shell
fin clone [project] [git-url]
```

## Code Validation

All projects in the `web/modules/drupalcode` directory are subject to code validation. Use this command to quickly
run the currently available linters and see potential issues.

```shell
fin validate
```
