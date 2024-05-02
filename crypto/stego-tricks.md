# Stego Tricks

#### **Steghide for Data Concealment** <a href="#steghide-for-data-concealment" id="steghide-for-data-concealment"></a>

Steghide facilitates hiding data within `JPEG, BMP, WAV, and AU` files, capable of embedding and extracting encrypted data. Installation is straightforward using `apt`, and its [source code is available on GitHub](https://github.com/StefanoDeVuono/steghide).

**Commands:**

* `steghide info file` reveals if a file contains hidden data.
* `steghide extract -sf file [--passphrase password]` extracts the hidden data, password optional.

For web-based extraction, visit [this website](https://futureboy.us/stegano/decinput.html).
