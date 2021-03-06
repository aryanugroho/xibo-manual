<!--toc=getting_started-->
# Upgrade
The CMS can be upgraded to later versions - we recommend all users upgrade when
possible to take advantage of the latest bug fixes and features.

Upgrading happens in 2 stages:

 1. Upgrade the CMS files
 2. Upgrade the database

Upgrading the CMS files is a manual process that should be completed by your
 web server administrator. Upgrading the CMS is completed in a wizard and can be
  done by the CMS administrator.

Please check the [release notes](release_notes.html) before starting the upgrade.

## Supported upgrades
The CMS can be upgraded from 1.4 to 1.7 and from 1.7 to 1.8. Direct upgrade
 from 1.4, 1.5, 1.6 to 1.8 is not supported.

## Steps
You should always take a backup before upgrading your CMS Installation.

*   *Optionally* clone your existing [[PRODUCTNAME]] database and grant permissions (see [Clone Database](release_notes_clonedb.html "Clone Database") for details). It is possible to upgrade without cloning but much harder to roll back.
*   Backup settings.php from your installation (found in `web/settings.php`)
*   Manually take a backup of your database
*   Replace your existing installation with the new version from the tar.gz or zip file. **Do not copy over the top.**
*   Replace your backup settings.php file in your [[PRODUCTNAME]] installation directory
*   Browse to [http://your.server/path](http://your.server/path) as normal
*   Log in as an administrator.
*   The upgrade wizard will open and show the list of upgrade steps.
*   Press start to run through them.
