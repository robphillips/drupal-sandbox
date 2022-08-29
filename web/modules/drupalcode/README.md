# Drupal Code

Clone the [Drupal Code](https://git.drupalcode.org/) projects into this directory.

To switch a project between composer and cloned run the following command to force extension rediscovery:

```shell
fin drush eval "\Drupal::state()->delete('system.module.files');"
```
