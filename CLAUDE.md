# HubSpot CMS

- Die HubSpot CLI (`hs`) ist in der Cloud-Umgebung installiert.
- Hänge an jeden hs-Befehl `--use-env` an. Zugangsdaten kommen aus den Umgebungsvariablen.
- Gib den Wert von HUBSPOT_PERSONAL_ACCESS_KEY nie aus und schreib ihn in keine Datei.
- Themes liegen unter `themes/<name>`. Upload: `hs cms upload themes/<name> <name> --use-env`.
- Uploads in den Design Manager sind sofort live. Lade erst hoch, wenn ich Go sage.
- Kein `--clean` und kein `hs cms delete` ohne meine ausdrückliche Freigabe.
