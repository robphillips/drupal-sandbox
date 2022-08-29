# Cloned Drupal Code Projects

Having issues switching between composer and a cloned project? Run this command to force rediscovery:

```shell
fin drush eval "\Drupal::state()->delete('system.module.files');"
```
