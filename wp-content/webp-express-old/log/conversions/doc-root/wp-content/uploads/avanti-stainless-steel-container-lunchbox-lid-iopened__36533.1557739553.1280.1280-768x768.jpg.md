WebP Express 0.19.0. Conversion triggered using bulk conversion, 2021-04-13 09:40:59

*WebP Convert 2.3.2*  ignited.
- PHP version: 7.3.27
- Server software: Apache

Stack converter ignited

Options:
------------
The following options have been set explicitly. Note: it is the resulting options after merging down the "jpeg" and "png" options and any converter-prefixed options.
- source: [doc-root]/wp-content/uploads/avanti-stainless-steel-container-lunchbox-lid-iopened__36533.1557739553.1280.1280-768x768.jpg
- destination: [doc-root]/wp-content/webp-express/webp-images/uploads/avanti-stainless-steel-container-lunchbox-lid-iopened__36533.1557739553.1280.1280-768x768.jpg.webp
- log-call-arguments: true
- converters: (array of 10 items)

The following options have not been explicitly set, so using the following defaults:
- converter-options: (empty array)
- shuffle: false
- preferred-converters: (empty array)
- extra-converters: (empty array)

The following options were supplied and are passed on to the converters in the stack:
- default-quality: 70
- encoding: "auto"
- max-quality: 80
- metadata: "none"
- near-lossless: 60
- quality: "auto"
------------


*Trying: cwebp* 

Options:
------------
The following options have been set explicitly. Note: it is the resulting options after merging down the "jpeg" and "png" options and any converter-prefixed options.
- source: [doc-root]/wp-content/uploads/avanti-stainless-steel-container-lunchbox-lid-iopened__36533.1557739553.1280.1280-768x768.jpg
- destination: [doc-root]/wp-content/webp-express/webp-images/uploads/avanti-stainless-steel-container-lunchbox-lid-iopened__36533.1557739553.1280.1280-768x768.jpg.webp
- default-quality: 70
- encoding: "auto"
- low-memory: true
- log-call-arguments: true
- max-quality: 80
- metadata: "none"
- method: 6
- near-lossless: 60
- quality: "auto"
- use-nice: true
- command-line-options: ""
- try-common-system-paths: true
- try-supplied-binary-for-os: true

The following options have not been explicitly set, so using the following defaults:
- alpha-quality: 85
- auto-filter: false
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
Quality of source is 82. This is higher than max-quality, so using max-quality instead (80)
The near-lossless option ignored for lossy
Trying to convert by executing the following command:
nice cwebp -metadata none -q 80 -alpha_q '85' -m 6 -low_memory '[doc-root]/wp-content/uploads/avanti-stainless-steel-container-lunchbox-lid-iopened__36533.1557739553.1280.1280-768x768.jpg' -o '[doc-root]/wp-content/webp-express/webp-images/uploads/avanti-stainless-steel-container-lunchbox-lid-iopened__36533.1557739553.1280.1280-768x768.jpg.webp.lossy.webp' 2>&1 2>&1

*Output:* 
Saving file '[doc-root]/wp-content/webp-express/webp-images/uploads/avanti-stainless-steel-container-lunchbox-lid-iopened__36533.1557739553.1280.1280-768x768.jpg.webp.lossy.webp'
File:      [doc-root]/wp-content/uploads/avanti-stainless-steel-container-lunchbox-lid-iopened__36533.1557739553.1280.1280-768x768.jpg
Dimension: 768 x 768
Output:    11468 bytes Y-U-V-All-PSNR 46.07 61.61 99.00   47.80 dB
           (0.16 bpp)
block count:  intra4:        792  (34.38%)
              intra16:      1512  (65.62%)
              skipped:      1259  (54.64%)
bytes used:  header:             83  (0.7%)
             mode-partition:   3602  (31.4%)
 Residuals bytes  |segment 1|segment 2|segment 3|segment 4|  total
  intra4-coeffs:  |    6158 |     142 |     307 |     336 |    6943  (60.5%)
 intra16-coeffs:  |      56 |      30 |     174 |     460 |     720  (6.3%)
  chroma coeffs:  |      55 |       1 |       8 |      29 |      93  (0.8%)
    macroblocks:  |      25%|       3%|       6%|      67%|    2304
      quantizer:  |      27 |      25 |      19 |      15 |
   filter level:  |       8 |      11 |      21 |      10 |
------------------+---------+---------+---------+---------+-----------------
 segments total:  |    6269 |     173 |     489 |     825 |    7756  (67.6%)

Success
Reduction: 65% (went from 32 kb to 11 kb)

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
nice cwebp -metadata none -q 80 -alpha_q '85' -near_lossless 60 -m 6 -low_memory '[doc-root]/wp-content/uploads/avanti-stainless-steel-container-lunchbox-lid-iopened__36533.1557739553.1280.1280-768x768.jpg' -o '[doc-root]/wp-content/webp-express/webp-images/uploads/avanti-stainless-steel-container-lunchbox-lid-iopened__36533.1557739553.1280.1280-768x768.jpg.webp.lossless.webp' 2>&1 2>&1

*Output:* 
Saving file '[doc-root]/wp-content/webp-express/webp-images/uploads/avanti-stainless-steel-container-lunchbox-lid-iopened__36533.1557739553.1280.1280-768x768.jpg.webp.lossless.webp'
File:      [doc-root]/wp-content/uploads/avanti-stainless-steel-container-lunchbox-lid-iopened__36533.1557739553.1280.1280-768x768.jpg
Dimension: 768 x 768
Output:    73900 bytes (1.00 bpp)
Lossless-ARGB compressed size: 73900 bytes
  * Header size: 1699 bytes, image data size: 72175
  * Lossless features used: PREDICTION CROSS-COLOR-TRANSFORM SUBTRACT-GREEN
  * Precision Bits: histogram=4 transform=4 cache=10

Success
Reduction: -124% (went from 32 kb to 72 kb)

Picking lossy
cwebp succeeded :)

Converted image in 815 ms, reducing file size with 65% (went from 32 kb to 11 kb)
