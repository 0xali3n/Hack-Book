# File/Data Carving & Recovery Tools

#### Autopsy <a href="#autopsy" id="autopsy"></a>

The most common tool used in forensics to extract files from images is [**Autopsy**](https://www.autopsy.com/download/). Download it, install it and make it ingest the file to find "hidden" files. Note that Autopsy is built to support disk images and other kinds of images, but not simple files.

#### Binwalk <a href="#binwalk" id="binwalk"></a>

**Binwalk** is a tool for analyzing binary files to find embedded content. It's installable via `apt` and its source is on [GitHub](https://github.com/ReFirmLabs/binwalk).

**Useful commands**:

Copy

<pre class="language-bash"><code class="lang-bash">sudo apt install binwalk #Insllation
binwalk file #Displays the embedded data in the given file
<strong>binwalk --run-as=root -e file #Displays and extracts some files from the given file
</strong>binwalk --dd ".*" file #Displays and extracts all files from the given file
</code></pre>

