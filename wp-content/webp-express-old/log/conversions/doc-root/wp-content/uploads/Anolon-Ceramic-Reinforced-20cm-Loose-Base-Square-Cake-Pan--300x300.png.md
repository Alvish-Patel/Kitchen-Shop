WebP Express 0.19.0. Conversion triggered using bulk conversion, 2021-04-13 08:05:32

*WebP Convert 2.3.2*  ignited.
- PHP version: 7.3.27
- Server software: Apache

Stack converter ignited

Options:
------------
The following options have been set explicitly. Note: it is the resulting options after merging down the "jpeg" and "png" options and any converter-prefixed options.
- source: [doc-root]/wp-content/uploads/Anolon-Ceramic-Reinforced-20cm-Loose-Base-Square-Cake-Pan--300x300.png
- destination: [doc-root]/wp-content/webp-express/webp-images/uploads/Anolon-Ceramic-Reinforced-20cm-Loose-Base-Square-Cake-Pan--300x300.png.webp
- log-call-arguments: true
- converters: (array of 10 items)

The following options have not been explicitly set, so using the following defaults:
- converter-options: (empty array)
- shuffle: false
- preferred-converters: (empty array)
- extra-converters: (empty array)

The following options were supplied and are passed on to the converters in the stack:
- alpha-quality: 80
- encoding: "auto"
- metadata: "none"
- near-lossless: 60
- quality: 85
------------


*Trying: cwebp* 

Options:
------------
The following options have been set explicitly. Note: it is the resulting options after merging down the "jpeg" and "png" options and any converter-prefixed options.
- source: [doc-root]/wp-content/uploads/Anolon-Ceramic-Reinforced-20cm-Loose-Base-Square-Cake-Pan--300x300.png
- destination: [doc-root]/wp-content/webp-express/webp-images/uploads/Anolon-Ceramic-Reinforced-20cm-Loose-Base-Square-Cake-Pan--300x300.png.webp
- alpha-quality: 80
- encoding: "auto"
- low-memory: true
- log-call-arguments: true
- metadata: "none"
- method: 6
- near-lossless: 60
- quality: 85
- use-nice: true
- command-line-options: ""
- try-common-system-paths: true
- try-supplied-binary-for-os: true

The following options have not been explicitly set, so using the following defaults:
- auto-filter: false
- default-quality: 85
- max-quality: 85
- preset: "none"
- size-in-percentage: null (not set)
- skip: false
- rel-path-to-precompiled-binaries: *****
- try-cwebp: true
- try-discovering-cwebp: true
------------

Encoding is set to auto - converting to both lossless and lossy and selecting the smallest file

Converting to lossy
Looking for cwebp binaries.
Discovering if a plain cwebp call works (to skip this step, disable the "try-cwebp" option)
- Executing: cwebp -version 2>&1. Result: version: *1.0.3*
We could get the version, so yes, a plain cwebp call works
Discovering binaries using "which -a cwebp" command. (to skip this step, disable the "try-discovering-cwebp" option)
Found 2 binaries: 
- /usr/bin/cwebp
- /bin/cwebp
Discovering binaries by peeking in common system paths (to skip this step, disable the "try-common-system-paths" option)
Found 1 binaries: 
- /usr/bin/cwebp
Discovering binaries which are distributed with the webp-convert library (to skip this step, disable the "try-supplied-binary-for-os" option)
Checking if we have a supplied precompiled binary for your OS (Linux)... We do. We in fact have 3
**Binary checksum of supplied binary is invalid! Did you transfer with FTP, but not in binary mode? File:[doc-root]/wp-content/plugins/webp-express/vendor/rosell-dk/webp-convert/src/Convert/Converters/Binaries/cwebp-110-linux-x86-64. Expected checksum: 1603b07b592876dd9fdaa62b44aead800234c9474ff26dc7dd01bc0f4785c9c6. Actual checksum:5d440b28050684e669b333a554b69f979cb2ef5db13900073ea04bf5d1f9522d.** 
**Binary checksum of supplied binary is invalid! Did you transfer with FTP, but not in binary mode? File:[doc-root]/wp-content/plugins/webp-express/vendor/rosell-dk/webp-convert/src/Convert/Converters/Binaries/cwebp-103-linux-x86-64-static. Expected checksum: ab96f01b49336da8b976c498528080ff614112d5985da69943b48e0cb1c5228a. Actual checksum:7c0f7966d70649875950a4959027183d4d74b563f87649150d198a6b45de65a9.** 
**Binary checksum of supplied binary is invalid! Did you transfer with FTP, but not in binary mode? File:[doc-root]/wp-content/plugins/webp-express/vendor/rosell-dk/webp-convert/src/Convert/Converters/Binaries/cwebp-061-linux-x86-64. Expected checksum: 916623e5e9183237c851374d969aebdb96e0edc0692ab7937b95ea67dc3b2568. Actual checksum:bb874298040d57e8906693f199ac6b698feb776caf2ec7fe273204df2884890f.** 
Found 0 binaries
Detecting versions of the cwebp binaries found
- Executing: cwebp -version 2>&1. Result: version: *1.0.3*
- Executing: /usr/bin/cwebp -version 2>&1. Result: version: *1.0.3*
- Executing: /bin/cwebp -version 2>&1. Result: version: *1.0.3*
Binaries ordered by version number.
- cwebp: (version: 1.0.3)
- /usr/bin/cwebp: (version: 1.0.3)
- /bin/cwebp: (version: 1.0.3)
Trying the first of these. If that should fail (it should not), the next will be tried and so on.
Creating command line options for version: 1.0.3
Quality: 85. 
The near-lossless option ignored for lossy
Trying to convert by executing the following command:
nice cwebp -metadata none -q 85 -alpha_q '80' -m 6 -low_memory '[doc-root]/wp-content/uploads/Anolon-Ceramic-Reinforced-20cm-Loose-Base-Square-Cake-Pan--300x300.png' -o '[doc-root]/wp-content/webp-express/webp-images/uploads/Anolon-Ceramic-Reinforced-20cm-Loose-Base-Square-Cake-Pan--300x300.png.webp.lossy.webp' 2>&1 2>&1

*Output:* 
Saving file '[doc-root]/wp-content/webp-express/webp-images/uploads/Anolon-Ceramic-Reinforced-20cm-Loose-Base-Square-Cake-Pan--300x300.png.webp.lossy.webp'
File:      [doc-root]/wp-content/uploads/Anolon-Ceramic-Reinforced-20cm-Loose-Base-Square-Cake-Pan--300x300.png
Dimension: 300 x 300 (with alpha)
Output:    6430 bytes Y-U-V-All-PSNR 45.44 49.97 50.28   46.51 dB
           (0.57 bpp)
block count:  intra4:        205  (56.79%)
              intra16:       156  (43.21%)
              skipped:        71  (19.67%)
bytes used:  header:             86  (1.3%)
             mode-partition:    903  (14.0%)
             transparency:     2001 (68.5 dB)
 Residuals bytes  |segment 1|segment 2|segment 3|segment 4|  total
  intra4-coeffs:  |    2247 |      35 |     125 |     157 |    2564  (39.9%)
 intra16-coeffs:  |     210 |      43 |      80 |     101 |     434  (6.7%)
  chroma coeffs:  |     243 |      14 |      52 |      78 |     387  (6.0%)
    macroblocks:  |      51%|       4%|      15%|      30%|     361
      quantizer:  |      19 |      13 |      10 |       8 |
   filter level:  |      13 |       6 |      10 |       4 |
------------------+---------+---------+---------+---------+-----------------
 segments total:  |    2700 |      92 |     257 |     336 |    3385  (52.6%)
Lossless-alpha compressed size: 2000 bytes
  * Header size: 97 bytes, image data size: 1903
  * Precision Bits: histogram=3 transform=3 cache=0
  * Palette size:   96

Success
Reduction: 93% (went from 87 kb to 6 kb)

Converting to lossless
Looking for cwebp binaries.
Discovering if a plain cwebp call works (to skip this step, disable the "try-cwebp" option)
- Executing: cwebp -version 2>&1. Result: version: *1.0.3*
We could get the version, so yes, a plain cwebp call works
Discovering binaries using "which -a cwebp" command. (to skip this step, disable the "try-discovering-cwebp" option)
Found 2 binaries: 
- /usr/bin/cwebp
- /bin/cwebp
Discovering binaries by peeking in common system paths (to skip this step, disable the "try-common-system-paths" option)
Found 1 binaries: 
- /usr/bin/cwebp
Discovering binaries which are distributed with the webp-convert library (to skip this step, disable the "try-supplied-binary-for-os" option)
Checking if we have a supplied precompiled binary for your OS (Linux)... We do. We in fact have 3
**Binary checksum of supplied binary is invalid! Did you transfer with FTP, but not in binary mode? File:[doc-root]/wp-content/plugins/webp-express/vendor/rosell-dk/webp-convert/src/Convert/Converters/Binaries/cwebp-110-linux-x86-64. Expected checksum: 1603b07b592876dd9fdaa62b44aead800234c9474ff26dc7dd01bc0f4785c9c6. Actual checksum:5d440b28050684e669b333a554b69f979cb2ef5db13900073ea04bf5d1f9522d.** 
**Binary checksum of supplied binary is invalid! Did you transfer with FTP, but not in binary mode? File:[doc-root]/wp-content/plugins/webp-express/vendor/rosell-dk/webp-convert/src/Convert/Converters/Binaries/cwebp-103-linux-x86-64-static. Expected checksum: ab96f01b49336da8b976c498528080ff614112d5985da69943b48e0cb1c5228a. Actual checksum:7c0f7966d70649875950a4959027183d4d74b563f87649150d198a6b45de65a9.** 
**Binary checksum of supplied binary is invalid! Did you transfer with FTP, but not in binary mode? File:[doc-root]/wp-content/plugins/webp-express/vendor/rosell-dk/webp-convert/src/Convert/Converters/Binaries/cwebp-061-linux-x86-64. Expected checksum: 916623e5e9183237c851374d969aebdb96e0edc0692ab7937b95ea67dc3b2568. Actual checksum:bb874298040d57e8906693f199ac6b698feb776caf2ec7fe273204df2884890f.** 
Found 0 binaries
Detecting versions of the cwebp binaries found
- Executing: cwebp -version 2>&1. Result: version: *1.0.3*
- Executing: /usr/bin/cwebp -version 2>&1. Result: version: *1.0.3*
- Executing: /bin/cwebp -version 2>&1. Result: version: *1.0.3*
Binaries ordered by version number.
- cwebp: (version: 1.0.3)
- /usr/bin/cwebp: (version: 1.0.3)
- /bin/cwebp: (version: 1.0.3)
Trying the first of these. If that should fail (it should not), the next will be tried and so on.
Creating command line options for version: 1.0.3
Trying to convert by executing the following command:
nice cwebp -metadata none -q 85 -alpha_q '80' -near_lossless 60 -m 6 -low_memory '[doc-root]/wp-content/uploads/Anolon-Ceramic-Reinforced-20cm-Loose-Base-Square-Cake-Pan--300x300.png' -o '[doc-root]/wp-content/webp-express/webp-images/uploads/Anolon-Ceramic-Reinforced-20cm-Loose-Base-Square-Cake-Pan--300x300.png.webp.lossless.webp' 2>&1 2>&1

*Output:* 
Saving file '[doc-root]/wp-content/webp-express/webp-images/uploads/Anolon-Ceramic-Reinforced-20cm-Loose-Base-Square-Cake-Pan--300x300.png.webp.lossless.webp'
File:      [doc-root]/wp-content/uploads/Anolon-Ceramic-Reinforced-20cm-Loose-Base-Square-Cake-Pan--300x300.png
Dimension: 300 x 300
Output:    43846 bytes (3.90 bpp)
Lossless-ARGB compressed size: 43846 bytes
  * Header size: 2260 bytes, image data size: 41561
  * Lossless features used: PREDICTION CROSS-COLOR-TRANSFORM SUBTRACT-GREEN
  * Precision Bits: histogram=3 transform=3 cache=10

Success
Reduction: 51% (went from 87 kb to 43 kb)

Picking lossy
cwebp succeeded :)

Converted image in 394 ms, reducing file size with 93% (went from 87 kb to 6 kb)
