************************
Libratone Zipp firmwares
************************
Initial download link extracted by MITM'ing the Libratone app network
communication.
The others have been brute-force tried.

The files are no real ``.zip`` files but some proprietary format.


Libratone Zipp v1
=================
Internally the Zipp v1 (big version) has the device type ``libratone_zipp3``.

Official firmware version list:

- english: https://support.libratone.com/hc/en-us/articles/204449421-Zipp-Zipp-Mini-Firmware-versions
- german: https://support.libratone.com/hc/de/articles/204449421-Zipp-Zipp-Mini-Firmwareversionen

Download URL of latest known firmware 879::

  http://cdn.little-bird.com.cn/download/OTA/Zipp2/Zipp_02_879_FULL_20250206.zip

This URL was obtained from the speaker's firmware-check response on
2026-10-20. The response identifies the device type as ``libratone_zipp3``
(Zipp v1), despite the ``Zipp2`` directory in the URL. It reports version
879 for the EU region, published on 2025-02-12.

Package verification:

- Size: 26,464,542 bytes
- MD5 (matches the firmware-check response): ``d7a8e9e4599f3c72dc8d385024e4356c``
- SHA-256: ``578f25d36de35404ed1a021ecd091c93e4f168daa1c84edc142abde247e7e4fe``

The package was decoded locally and all ZIP entry CRCs passed. It has not
been installed or tested on a speaker by the contributor.
