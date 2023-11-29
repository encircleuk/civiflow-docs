# 🏁 Getting Started - Installing the CiviFlow Extension

Assumes CiviCRM is running on Linux

## Requirements

* Requires CiviCRM 5.57 or later
* Requires the CiviRules extension (Bundled with CiviCRM) [\[https://civicrm.org/extensions/civirules\]](broken-reference)
* Optionally Requires the CiviRulesLog extension (Bundled with CiviCRM) [https://civicrm.org/extensions/civirules-logger](https://civicrm.org/extensions/civirules-logger) (used for CiviFlow audit trail)

## Download CiviFlow Extension

Download civi extension from here: [https://civicrm.org/extensions/civiflow](https://civicrm.org/extensions/civiflow)

e.g

```bash
cd [CIVICRM-ROOT-DIR]/extentions/
wget https://lab.civicrm.org/extensions/CiviFlow/-/archive/0.4.2/CiviFlow-0.4.2.zip
unzip CiviFlow-0.4.2.zip
mv CiviFlow-0.4.2 civiflow
rm CiviFlow-0.4.2.zip
```

where _CIVICRM-ROOT-DIR_ is

* **for Drupal 8+:** `DRUPAL-ROOT/web/sites/default/files/civicrm/`
* **for Wordpress:** `WORDPRESS-ROOT/wp-content/uploads/civicrm/`

**Important:** ensure that the extracted directory is renamed to civiflow i.e.:

```bash
mv CiviFlow-0.4.2 civiflow
```

**Note:** Don't forget to secure web server permissions of the extracted files, i.e. _www-data_ group needs read permissions on all files.

## Enable CiviExtension

* Clear the CiviCache:&#x20;
* Go to the Extensions page in CiviCRM -> Administration Menu:&#x20;
* Navigate down the page to the CiviFlow Extension and click the install button:&#x20;
* On the CiviFlow Extension page, click the install button:&#x20;
