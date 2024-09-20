WebP Express 0.19.0. Conversion triggered using bulk conversion, 2021-04-13 08:59:57

*WebP Convert 2.3.2*  ignited.
- PHP version: 7.3.27
- Server software: Apache

Stack converter ignited

Options:
------------
The following options have been set explicitly. Note: it is the resulting options after merging down the "jpeg" and "png" options and any converter-prefixed options.
- source: [doc-root]/wp-content/uploads/13442-Avanti-Go-Cup-280ml-Bushed-Stainless-Steel__45942.1565098535.1280.1280-600x600.jpg
- destination: [doc-root]/wp-content/webp-express/webp-images/uploads/13442-Avanti-Go-Cup-280ml-Bushed-Stainless-Steel__45942.1565098535.1280.1280-600x600.jpg.webp
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
- source: [doc-root]/wp-content/uploads/13442-Avanti-Go-Cup-280ml-Bushed-Stainless-Steel__45942.1565098535.1280.1280-600x600.jpg
- destination: [doc-root]/wp-content/webp-express/webp-images/uploads/13442-Avanti-Go-Cup-280ml-Bushed-Stainless-Steel__45942.1565098535.1280.1280-600x600.jpg.webp
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
nice cwebp -metadata none -q 80 -alpha_q '85' -m 6 -low_memory '[doc-root]/wp-content/uploads/13442-Avanti-Go-Cup-280ml-Bushed-Stainless-Steel__45942.1565098535.1280.1280-600x600.jpg' -o '[doc-root]/wp-content/webp-express/webp-images/uploads/13442-Avanti-Go-Cup-280ml-Bushed-Stainless-Steel__45942.1565098535.1280.1280-600x600.jpg.webp.lossy.webp' 2>&1 2>&1

*Output:* 
Saving file '[doc-root]/wp-content/webp-express/webp-images/uploads/13442-Avanti-Go-Cup-280ml-Bushed-Stainless-Steel__45942.1565098535.1280.1280-600x600.jpg.webp.lossy.webp'
File:      [doc-root]/wp-content/uploads/13442-Avanti-Go-Cup-280ml-Bushed-Stainless-Steel__45942.1565098535.1280.1280-600x600.jpg
Dimension: 600 x 600
Output:    4222 bytes Y-U-V-All-PSNR 48.65 99.00 99.00   50.41 dB
           (0.09 bpp)
block count:  intra4:        235  (16.27%)
              intra16:      1209  (83.73%)
              skipped:      1083  (75.00%)
bytes used:  header:             47  (1.1%)
             mode-partition:   1648  (39.0%)
 Residuals bytes  |segment 1|segment 2|segment 3|segment 4|  total
  intra4-coeffs:  |    1962 |      31 |       7 |      36 |    2036  (48.2%)
 intra16-coeffs:  |     209 |      97 |      82 |      69 |     457  (10.8%)
  chroma coeffs:  |       2 |       1 |       1 |       1 |       5  (0.1%)
    macroblocks:  |      22%|       3%|       3%|      73%|    1444
      quantizer:  |      27 |      25 |      20 |      15 |
   filter level:  |      36 |      16 |       9 |       3 |
------------------+---------+---------+---------+---------+-----------------
 segments total:  |    2173 |     129 |      90 |     106 |    2498  (59.2%)

Success
Reduction: 73% (went from 16 kb to 4 kb)

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
nice cwebp -metadata none -q 80 -alpha_q '85' -near_lossless 60 -m 6 -low_memory '[doc-root]/wp-content/uploads/13442-Avanti-Go-Cup-280ml-Bushed-Stainless-Steel__45942.1565098535.1280.1280-600x600.jpg' -o '[doc-root]/wp-content/webp-express/webp-images/uploads/13442-Avanti-Go-Cup-280ml-Bushed-Stainless-Steel__45942.1565098535.1280.1280-600x600.jpg.webp.lossless.webp' 2>&1 2>&1

*Output:* 
Saving file '[doc-root]/wp-content/webp-express/webp-images/uploads/13442-Avanti-Go-Cup-280ml-Bushed-Stainless-Steel__45942.1565098535.1280.1280-600x600.jpg.webp.lossless.webp'
File:      [doc-root]/wp-content/uploads/13442-Avanti-Go-Cup-280ml-Bushed-Stainless-Steel__45942.1565098535.1280.1280-600x600.jpg
Dimension: 600 x 600
Output:    22124 bytes (0.49 bpp)
Lossless-ARGB compressed size: 22124 bytes
  * Header size: 401 bytes, image data size: 21698
  * Lossless features used: PREDICTION SUBTRACT-GREEN
  * Precision Bits: histogram=4 transform=4 cache=0
  * Palette size:   249

Success
Reduction: -39% (went from 16 kb to 22 kb)

Picking lossy
cwebp succeeded :)

Converted image in 439 ms, reducing file size with 73% (went from 16 kb to 4 kb)
