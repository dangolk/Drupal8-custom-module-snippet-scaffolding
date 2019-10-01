# Clear Routing Cache using Drush:
vendor/drush/drush/drush ev '\Drupal::service("router.builder")->rebuild();

# Clear Cache (Rebuild Cache) using Drush Console:
drupal cache:rebuild
(from project root folder)

# List all registered routes:
drupal router:debug