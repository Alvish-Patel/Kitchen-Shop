WebP Express 0.19.0. Conversion triggered using bulk conversion, 2021-04-14 03:34:36

*WebP Convert 2.3.2*  ignited.
- PHP version: 7.3.27
- Server software: Apache

Stack converter ignited

Options:
------------
The following options have been set explicitly. Note: it is the resulting options after merging down the "jpeg" and "png" options and any converter-prefixed options.
- source: [doc-root]/wp-content/uploads/WHIHWD01SS_2ff29fd5-8a8d-4ce2-9efd-ebbeee72bc01_1024x1024.png
- destination: [doc-root]/wp-content/webp-express/webp-images/uploads/WHIHWD01SS_2ff29fd5-8a8d-4ce2-9efd-ebbeee72bc01_1024x1024.png.webp
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
- source: [doc-root]/wp-content/uploads/WHIHWD01SS_2ff29fd5-8a8d-4ce2-9efd-ebbeee72bc01_1024x1024.png
- destination: [doc-root]/wp-content/webp-express/webp-images/uploads/WHIHWD01SS_2ff29fd5-8a8d-4ce2-9efd-ebbeee72bc01_1024x1024.png.webp
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
nice cwebp -metadata none -q 85 -alpha_q '80' -m 6 -low_memory '[doc-root]/wp-content/uploads/WHIHWD01SS_2ff29fd5-8a8d-4ce2-9efd-ebbeee72bc01_1024x1024.png' -o '[doc-root]/wp-content/webp-express/webp-images/uploads/WHIHWD01SS_2ff29fd5-8a8d-4ce2-9efd-ebbeee72bc01_1024x1024.png.webp.lossy.webp' 2>&1 2>&1

*Output:* 
Saving file '[doc-root]/wp-content/webp-express/webp-images/uploads/WHIHWD01SS_2ff29fd5-8a8d-4ce2-9efd-ebbeee72bc01_1024x1024.png.webp.lossy.webp'
File:      [doc-root]/wp-content/uploads/WHIHWD01SS_2ff29fd5-8a8d-4ce2-9efd-ebbeee72bc01_1024x1024.png
Dimension: 880 x 1000 (with alpha)
Output:    39666 bytes Y-U-V-All-PSNR 45.69 52.54 54.86   47.11 dB
           (0.36 bpp)
block count:  intra4:       1276  (36.83%)
              intra16:      2189  (63.17%)
              skipped:      1651  (47.65%)
bytes used:  header:            311  (0.8%)
             mode-partition:   6666  (16.8%)
             transparency:     4705 (73.9 dB)
 Residuals bytes  |segment 1|segment 2|segment 3|segment 4|  total
  intra4-coeffs:  |   20107 |     641 |     430 |     913 |   22091  (55.7%)
 intra16-coeffs:  |    1804 |     323 |     651 |     626 |    3404  (8.6%)
  chroma coeffs:  |    2010 |      50 |     106 |     269 |    2435  (6.1%)
    macroblocks:  |      33%|       4%|       7%|      56%|    3465
      quantizer:  |      20 |      16 |      12 |       9 |
   filter level:  |       9 |       7 |       9 |      10 |
------------------+---------+---------+---------+---------+-----------------
 segments total:  |   23921 |    1014 |    1187 |    1808 |   27930  (70.4%)
Lossless-alpha compressed size: 4704 bytes
  * Header size: 121 bytes, image data size: 4583
  * Lossless features used: PALETTE
  * Precision Bits: histogram=5 transform=4 cache=0
  * Palette size:   96

Success
Reduction: 95% (went from 706 kb to 39 kb)

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
nice cwebp -metadata none -q 85 -alpha_q '80' -near_lossless 60 -m 6 -low_memory '[doc-root]/wp-content/uploads/WHIHWD01SS_2ff29fd5-8a8d-4ce2-9efd-ebbeee72bc01_1024x1024.png' -o '[doc-root]/wp-content/webp-express/webp-images/uploads/WHIHWD01SS_2ff29fd5-8a8d-4ce2-9efd-ebbeee72bc01_1024x1024.png.webp.lossless.webp' 2>&1 2>&1

*Output:* 
Saving file '[doc-root]/wp-content/webp-express/webp-images/uploads/WHIHWD01SS_2ff29fd5-8a8d-4ce2-9efd-ebbeee72bc01_1024x1024.png.webp.lossless.webp'
File:      [doc-root]/wp-content/uploads/WHIHWD01SS_2ff29fd5-8a8d-4ce2-9efd-ebbeee72bc01_1024x1024.png
Dimension: 880 x 1000
Output:    264942 bytes (2.41 bpp)
Lossless-ARGB compressed size: 264942 bytes
  * Header size: 5131 bytes, image data size: 259785
  * Lossless features used: PREDICTION CROSS-COLOR-TRANSFORM SUBTRACT-GREEN
  * Precision Bits: histogram=5 transform=4 cache=10

Success
Reduction: 63% (went from 706 kb to 259 kb)

Picking lossy
cwebp succeeded :)

Converted image in 1430 ms, reducing file size with 95% (went from 706 kb to 39 kb)
