# WillFit mobile preview

Public compiled website preview. This repository contains only built web assets,
not the private application source repository or its Git history.

Open https://gauss1992.github.io/willfit-preview/ in Safari or Chrome.
Camera access requires explicit permission and a secure connection. Pose inference
runs locally; its runtime and model are downloaded from external CDNs on first use.
Training records remain in the current browser's local storage; devices do not sync.

This static preview does not include Node server media-proxy APIs. Bundled exercise
media attribution is preserved in exercise-dataset-media/NOTICE.md.

Do not commit credentials, source maps, recordings, or exported personal records here.
