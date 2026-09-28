# Culling Engine — releases

Public update manifest for Culling Engine (the app's source is private).

Installed copies poll [`latest.json`](latest.json) and show an "update available" banner
when its `version` is newer than theirs. Installers themselves are distributed through a
shared Dropbox folder, which `downloadUrl` points to.

Update `latest.json` only **after** the new installers are in that folder.
