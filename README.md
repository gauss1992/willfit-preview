# WillFit mobile preview

Public compiled website preview. This repository contains only built web assets,
not the private application source repository or its Git history.

Open https://gauss1992.github.io/willfit-preview/ in Safari or Chrome.
Camera access requires explicit permission and a secure connection. Pose inference
runs locally; its runtime and model are downloaded from external CDNs on first use.
Training records remain in the current browser's local storage; devices do not sync.

The motion-analysis preview includes exercise-cycle gating, adaptive smoothing,
per-repetition curves, optional distance calibration and explicit load-marker tracking.
Measurements are 2D estimates, not validated professional VBT or muscular power.
Occlusion or ambiguous movement can prevent counting. Real-device and real-exercise
accuracy validation is ongoing. No camera frames or measurement snapshots are uploaded.

This static preview does not include Node server media-proxy APIs. Bundled exercise
media attribution is preserved in exercise-dataset-media/NOTICE.md.

Do not commit credentials, source maps, recordings, or exported personal records here.
