Creation of a Drupal Module to display and manage DOI metadata within a Drupal website

To test this module:

  * In your Drupal instance, go to sites/all/modules/custom
  * Download or clone this repository
  * Rename folder from drupal_DOI to doi_display
  * Enable module under Modules (may need to clear cache)
  * Add a DOI content type (see doi_display.module for field definitions)
  * Add a DOI entityreference field (field_doi_reference) to the content type you'd like to display citations on (eg. Basic Page)
  * Enable "DOI Display" block under Structure -> Blocks
  * Edit "DOI Display" block visibility criteria to match your content type
  * Add a new DOI node, setting the title to the DOI itself
  * Edit your content node to reference the new DOI
  * View your content node: the "Citation" block should appear
