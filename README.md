CSS Injector Import
===================

* Developed by Stillfinder - http://stillfinder.net/en
* http://stillfinder.net/en/project/css-injector-import-drupal-module-import-css-injector-rules
* https://github.com/stillfinder/css_injector_import

Drupal module for import CSS Injector rules from production to pre-production environments.

As a developer I would like to have a functionality to import CSS Injector rules from production environment to pre-production environments by 1-click-action. Right now CSS Injector rules cannot be exported/imported using "BackUp & migrate" module or DB update from production. It can be imported only using copy-paste method, which can take some time. And this module created to solve issue with manual copy-paste work.

CSS Injector import only works with 1.x. The 2.x branch moved the CSS to CTools plugins largely so they could be captured by Features.

Installation
------------
1. Download latest module code or use terminal command `git clone https://github.com/stillfinder/css_injector_import.git`
2. Enable the module.

Usage
-----
1. Goto admin/config/system/css_injector_import url.
2. Setup 'Production site URL'.
3. Push 'Update CSS Injector rules and Save configuration' button to update and save configuration or 'Save' to save without updating CSS Injector rules.
