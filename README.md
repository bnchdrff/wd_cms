Work Dept CMS customizations
============================

Alter Drupal to be nicer for editors

theworkdept.com rolls out a lot of drupal sites on the aegir platform. This module stores consistently needed tidbits.

What does it do?
----------------

To help ease domain name migrations, URLs for image styled-files (files prefixed with `styles/`) created by `file_create_url()` will have the `sites/domain` portion removed. Aegir hosting systems provide an nginx config to rewrite requests of this type to be prefixed with `sites/domain`, so the URL doesn't need to contain it -- this makes site migrations much easier.

Installation
------------

Currently this module doesn't use the database so just enable it.

Credits
-------

Benjamin Chodoroff

License
-------

Copyright (c) 2013 Benjamin Chodoroff. Licensed under the GNU General Public License, GPL v3.
