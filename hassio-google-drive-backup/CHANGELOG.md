=======
## v0.109.2 [2022-11-16]
Fixes a bug causing backups in Google Drive to be erroneously deleted when "Max Backups in Google Drive" is 0 and "Delete After Upload" is enabled.

## v0.108.4 [2022-08-22]
Fixed an error causing "Undefined" to show up for addon descriptions.
Fixed an error preventing addon thumbnails from showing up.
Fixed an error causing username/password authentication to fail.

## v0.108.3 [2022-08-16]
Fixed an error preventing stopped addons form being started if they hit errors while stopping.
Fixed many, many, many gramatical errors thanks to @markvader's #665.
Fixed a missing config option in the addon schema, maximum_upload_chunk_bytes.

## v0.108.2 [2022-06-03]
Switched to ignoring 'upgrade' backups by default for new users.
Added a warning for existing users if you're not ignoring upgrade backups.
Added a warning about google's OOB deprecation for private credential users.

## v0.108.1 [2022-06-02]
Added commenting on backups, ie you can annotate them before or after creation.
Fixed layout gaps in the backup details page

## v0.107.3 [2022-05-30]
Fixed an issue causing ignored backups to get labelled as generational backups.

## [0.106.2 2022-3-23]
### New
* Added "next_backup" to published sensors.
* Added upload chunk size config option to debug connectivity issues. 

## [0.106.1 2022-3-21]
### Fixes
* Updates the mechanism for using custom/personal Google API credentials to work with Google's newer APIs
* Fixes a problem that prevented loading backups from Google Drive -> Home Assistant through the Nabu Casa remote UI

### New
* Added the ability to delete any "ignored" snapshots after a certain age.