WebP Express 0.19.0. Conversion triggered using bulk conversion, 2021-04-13 11:59:06

*WebP Convert 2.3.2*  ignited.
- PHP version: 7.3.27
- Server software: Apache

Stack converter ignited

Options:
------------
The following options have been set explicitly. Note: it is the resulting options after merging down the "jpeg" and "png" options and any converter-prefixed options.
- source: [doc-root]/wp-content/uploads/JJ-Bathroom-Split-Bin-70514-IU1-scaled-1-768x926.jpg
- destination: [doc-root]/wp-content/webp-express/webp-images/uploads/JJ-Bathroom-Split-Bin-70514-IU1-scaled-1-768x926.jpg.webp
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
- source: [doc-root]/wp-content/uploads/JJ-Bathroom-Split-Bin-70514-IU1-scaled-1-768x926.jpg
- destination: [doc-root]/wp-content/webp-express/webp-images/uploads/JJ-Bathroom-Split-Bin-70514-IU1-scaled-1-768x926.jpg.webp
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
nice cwebp -metadata none -q 80 -alpha_q '85' -m 6 -low_memory '[doc-root]/wp-content/uploads/JJ-Bathroom-Split-Bin-70514-IU1-scaled-1-768x926.jpg' -o '[doc-root]/wp-content/webp-express/webp-images/uploads/JJ-Bathroom-Split-Bin-70514-IU1-scaled-1-768x926.jpg.webp.lossy.webp' 2>&1 2>&1

*Output:* 
Saving file '[doc-root]/wp-content/webp-express/webp-images/uploads/JJ-Bathroom-Split-Bin-70514-IU1-scaled-1-768x926.jpg.webp.lossy.webp'
File:      [doc-root]/wp-content/uploads/JJ-Bathroom-Split-Bin-70514-IU1-scaled-1-768x926.jpg
Dimension: 768 x 926
Output:    15250 bytes Y-U-V-All-PSNR 46.38 53.12 52.62   47.68 dB
           (0.17 bpp)
block count:  intra4:       1359  (48.81%)
              intra16:      1425  (51.19%)
              skipped:       311  (11.17%)
bytes used:  header:             94  (0.6%)
             mode-partition:   4645  (30.5%)
 Residuals bytes  |segment 1|segment 2|segment 3|segment 4|  total
  intra4-coeffs:  |    3163 |     680 |    1397 |     878 |    6118  (40.1%)
 intra16-coeffs:  |     250 |     208 |     742 |    1465 |    2665  (17.5%)
  chroma coeffs:  |     744 |     123 |     285 |     547 |    1699  (11.1%)
    macroblocks:  |      16%|       7%|      21%|      55%|    2784
      quantizer:  |      27 |      25 |      19 |      15 |
   filter level:  |      18 |      16 |      17 |      10 |
------------------+---------+---------+---------+---------+-----------------
 segments total:  |    4157 |    1011 |    2424 |    2890 |   10482  (68.7%)

Success
Reduction: 64% (went from 41 kb to 15 kb)

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
nice cwebp -metadata none -q 80 -alpha_q '85' -near_lossless 60 -m 6 -low_memory '[doc-root]/wp-content/uploads/JJ-Bathroom-Split-Bin-70514-IU1-scaled-1-768x926.jpg' -o '[doc-root]/wp-content/webp-express/webp-images/uploads/JJ-Bathroom-Split-Bin-70514-IU1-scaled-1-768x926.jpg.webp.lossless.webp' 2>&1 2>&1

*Output:* 
Saving file '[doc-root]/wp-content/webp-express/webp-images/uploads/JJ-Bathroom-Split-Bin-70514-IU1-scaled-1-768x926.jpg.webp.lossless.webp'
File:      [doc-root]/wp-content/uploads/JJ-Bathroom-Split-Bin-70514-IU1-scaled-1-768x926.jpg
Dimension: 768 x 926
Output:    164052 bytes (1.85 bpp)
Lossless-ARGB compressed size: 164052 bytes
  * Header size: 2860 bytes, image data size: 161167
  * Lossless features used: PREDICTION CROSS-COLOR-TRANSFORM SUBTRACT-GREEN
  * Precision Bits: histogram=5 transform=4 cache=10

Success
Reduction: -290% (went from 41 kb to 160 kb)

Picking lossy
cwebp succeeded :)

Converted image in 1026 ms, reducing file size with 64% (went from 41 kb to 15 kb)
