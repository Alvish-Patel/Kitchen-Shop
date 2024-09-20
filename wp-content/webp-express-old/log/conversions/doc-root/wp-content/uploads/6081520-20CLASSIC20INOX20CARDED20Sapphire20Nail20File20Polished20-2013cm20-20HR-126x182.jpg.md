WebP Express 0.19.0. Conversion triggered using bulk conversion, 2021-04-13 07:12:01

*WebP Convert 2.3.2*  ignited.
- PHP version: 7.3.27
- Server software: Apache

Stack converter ignited

Options:
------------
The following options have been set explicitly. Note: it is the resulting options after merging down the "jpeg" and "png" options and any converter-prefixed options.
- source: [doc-root]/wp-content/uploads/6081520-20CLASSIC20INOX20CARDED20Sapphire20Nail20File20Polished20-2013cm20-20HR-126x182.jpg
- destination: [doc-root]/wp-content/webp-express/webp-images/uploads/6081520-20CLASSIC20INOX20CARDED20Sapphire20Nail20File20Polished20-2013cm20-20HR-126x182.jpg.webp
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
- source: [doc-root]/wp-content/uploads/6081520-20CLASSIC20INOX20CARDED20Sapphire20Nail20File20Polished20-2013cm20-20HR-126x182.jpg
- destination: [doc-root]/wp-content/webp-express/webp-images/uploads/6081520-20CLASSIC20INOX20CARDED20Sapphire20Nail20File20Polished20-2013cm20-20HR-126x182.jpg.webp
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
nice cwebp -metadata none -q 80 -alpha_q '85' -m 6 -low_memory '[doc-root]/wp-content/uploads/6081520-20CLASSIC20INOX20CARDED20Sapphire20Nail20File20Polished20-2013cm20-20HR-126x182.jpg' -o '[doc-root]/wp-content/webp-express/webp-images/uploads/6081520-20CLASSIC20INOX20CARDED20Sapphire20Nail20File20Polished20-2013cm20-20HR-126x182.jpg.webp.lossy.webp' 2>&1 2>&1

*Output:* 
Saving file '[doc-root]/wp-content/webp-express/webp-images/uploads/6081520-20CLASSIC20INOX20CARDED20Sapphire20Nail20File20Polished20-2013cm20-20HR-126x182.jpg.webp.lossy.webp'
File:      [doc-root]/wp-content/uploads/6081520-20CLASSIC20INOX20CARDED20Sapphire20Nail20File20Polished20-2013cm20-20HR-126x182.jpg
Dimension: 126 x 182
Output:    992 bytes Y-U-V-All-PSNR 42.42 99.00 99.00   44.18 dB
           (0.35 bpp)
block count:  intra4:         39  (40.62%)
              intra16:        57  (59.38%)
              skipped:        62  (64.58%)
bytes used:  header:             52  (5.2%)
             mode-partition:    156  (15.7%)
 Residuals bytes  |segment 1|segment 2|segment 3|segment 4|  total
  intra4-coeffs:  |     740 |       0 |       0 |       0 |     740  (74.6%)
 intra16-coeffs:  |       5 |       0 |       0 |       7 |      12  (1.2%)
  chroma coeffs:  |       1 |       0 |       0 |       1 |       2  (0.2%)
    macroblocks:  |      44%|       0%|       4%|      52%|      96
      quantizer:  |      27 |      22 |      16 |      12 |
   filter level:  |       8 |       5 |       3 |       2 |
------------------+---------+---------+---------+---------+-----------------
 segments total:  |     746 |       0 |       0 |       8 |     754  (76.0%)

Success
Reduction: 62% (went from 2642 bytes to 992 bytes)

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
nice cwebp -metadata none -q 80 -alpha_q '85' -near_lossless 60 -m 6 -low_memory '[doc-root]/wp-content/uploads/6081520-20CLASSIC20INOX20CARDED20Sapphire20Nail20File20Polished20-2013cm20-20HR-126x182.jpg' -o '[doc-root]/wp-content/webp-express/webp-images/uploads/6081520-20CLASSIC20INOX20CARDED20Sapphire20Nail20File20Polished20-2013cm20-20HR-126x182.jpg.webp.lossless.webp' 2>&1 2>&1

*Output:* 
Saving file '[doc-root]/wp-content/webp-express/webp-images/uploads/6081520-20CLASSIC20INOX20CARDED20Sapphire20Nail20File20Polished20-2013cm20-20HR-126x182.jpg.webp.lossless.webp'
File:      [doc-root]/wp-content/uploads/6081520-20CLASSIC20INOX20CARDED20Sapphire20Nail20File20Polished20-2013cm20-20HR-126x182.jpg
Dimension: 126 x 182
Output:    2878 bytes (1.00 bpp)
Lossless-ARGB compressed size: 2878 bytes
  * Header size: 156 bytes, image data size: 2696
  * Lossless features used: PREDICTION SUBTRACT-GREEN
  * Precision Bits: histogram=3 transform=3 cache=0
  * Palette size:   240

Success
Reduction: -9% (went from 2642 bytes to 2878 bytes)

Picking lossy
cwebp succeeded :)

Converted image in 171 ms, reducing file size with 62% (went from 2642 bytes to 992 bytes)
