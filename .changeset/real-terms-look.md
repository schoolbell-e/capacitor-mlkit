---
'@capacitor-mlkit/barcode-scanning': major
---

Included cornerPoints without normalization upon readBarcodesFromImage and scan since developer always can and have to calculate the positions afterwards to properly draw a box(s) on webview level.
Return empty data when there is no detection on readBarcodesFromImage.
