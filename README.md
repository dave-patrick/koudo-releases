# Koudo releases

Published Windows builds of Koudo. The app checks this repository for updates
(Settings > About > Check for updates) and installs a build only after its SHA-256
matches the `latest.json` published with it.

Each release is tagged `windows-<build ID>` (build IDs are `YYYY.DD.MM.revision`) and
carries the installer plus `latest.json`. The source lives in a private repository.
