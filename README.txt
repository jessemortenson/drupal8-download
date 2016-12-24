
This module can compress any files attached to a node and provides a 
download link.

This module is sponsored by www.Linalis.com
and Drupal 8 port by www.origineight.net

Installation 
------------

1) Install PclZip library

To use this module you have to have the PclZip library
installed by Composer. You can accomplish this either by configuring
Drupal composer or using the Composer Manager extension. See information here:
https://www.drupal.org/docs/8/extending-drupal/installing-modules-composer-dependencies

2) Place the download folder in the modules directory of your site and
enable it on the `Extend` page.

3) Have at least one entity type that includes at least one file field

4) Add a new Download Link field to that entity type, and select the file fields
that should be included.