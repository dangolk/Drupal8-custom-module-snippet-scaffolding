# Clear Routing Cache using Drush:
vendor/drush/drush/drush ev '\Drupal::service("router.builder")->rebuild();