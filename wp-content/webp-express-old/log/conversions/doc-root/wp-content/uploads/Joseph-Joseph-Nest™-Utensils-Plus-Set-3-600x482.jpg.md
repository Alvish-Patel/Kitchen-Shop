WebP Express 0.19.0. Conversion triggered using bulk conversion, 2021-04-13 08:02:10

*WebP Convert 2.3.2*  ignited.
- PHP version: 7.3.27
- Server software: Apache

Stack converter ignited

Options:
------------
The following options have been set explicitly. Note: it is the resulting options after merging down the "jpeg" and "png" options and any converter-prefixed options.
- source: [doc-root]/wp-content/uploads/Joseph-Joseph-Nest™-Utensils-Plus-Set-3-600x482.jpg
- destination: [doc-root]/wp-content/webp-express/webp-images/uploads/Joseph-Joseph-Nest™-Utensils-Plus-Set-3-600x482.jpg.webp
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
- source: [doc-root]/wp-content/uploads/Joseph-Joseph-Nest™-Utensils-Plus-Set-3-600x482.jpg
- destination: [doc-root]/wp-content/webp-express/webp-images/uploads/Joseph-Joseph-Nest™-Utensils-Plus-Set-3-600x482.jpg.webp
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
Quality of source could not be established (Imagick or GraphicsMagick is required) - Using default instead (70).
The near-lossless option ignored for lossy
Trying to convert by executing the following command:
nice cwebp -metadata none -q 70 -alpha_q '85' -m 6 -low_memory '[doc-root]/wp-content/uploads/Joseph-Joseph-Nest-Utensils-Plus-Set-3-600x482.jpg' -o '[doc-root]/wp-content/webp-express/webp-images/uploads/Joseph-Joseph-Nest-Utensils-Plus-Set-3-600x482.jpg.webp.lossy.webp' 2>&1 2>&1

*Output:* 
cannot open input file '[doc-root]/wp-content/uploads/Joseph-Joseph-Nest-Utensils-Plus-Set-3-600x482.jpg'
Error! Could not process file [doc-root]/wp-content/uploads/Joseph-Joseph-Nest-Utensils-Plus-Set-3-600x482.jpg
Error! Cannot read input picture file '[doc-root]/wp-content/uploads/Joseph-Joseph-Nest-Utensils-Plus-Set-3-600x482.jpg'

Exec failed (return code: 255)
Creating command line options for version: 1.0.3
The near-lossless option ignored for lossy
Trying to convert by executing the following command:
nice /usr/bin/cwebp -metadata none -q 70 -alpha_q '85' -m 6 -low_memory '[doc-root]/wp-content/uploads/Joseph-Joseph-Nest-Utensils-Plus-Set-3-600x482.jpg' -o '[doc-root]/wp-content/webp-express/webp-images/uploads/Joseph-Joseph-Nest-Utensils-Plus-Set-3-600x482.jpg.webp.lossy.webp' 2>&1 2>&1

*Output:* 
cannot open input file '[doc-root]/wp-content/uploads/Joseph-Joseph-Nest-Utensils-Plus-Set-3-600x482.jpg'
Error! Could not process file [doc-root]/wp-content/uploads/Joseph-Joseph-Nest-Utensils-Plus-Set-3-600x482.jpg
Error! Cannot read input picture file '[doc-root]/wp-content/uploads/Joseph-Joseph-Nest-Utensils-Plus-Set-3-600x482.jpg'

Exec failed (return code: 255)
Creating command line options for version: 1.0.3
The near-lossless option ignored for lossy
Trying to convert by executing the following command:
nice /bin/cwebp -metadata none -q 70 -alpha_q '85' -m 6 -low_memory '[doc-root]/wp-content/uploads/Joseph-Joseph-Nest-Utensils-Plus-Set-3-600x482.jpg' -o '[doc-root]/wp-content/webp-express/webp-images/uploads/Joseph-Joseph-Nest-Utensils-Plus-Set-3-600x482.jpg.webp.lossy.webp' 2>&1 2>&1

*Output:* 
cannot open input file '[doc-root]/wp-content/uploads/Joseph-Joseph-Nest-Utensils-Plus-Set-3-600x482.jpg'
Error! Could not process file [doc-root]/wp-content/uploads/Joseph-Joseph-Nest-Utensils-Plus-Set-3-600x482.jpg
Error! Cannot read input picture file '[doc-root]/wp-content/uploads/Joseph-Joseph-Nest-Utensils-Plus-Set-3-600x482.jpg'

Exec failed (return code: 255)

**Error: ** **Failed converting. Check the conversion log for details.** 
Failed converting. Check the conversion log for details.
cwebp failed in 81 ms

*Trying: vips* 

**Error: ** **Required Vips extension is not available.** 
Required Vips extension is not available.
vips failed in 0 ms

*Trying: imagemagick* 

Options:
------------
The following options have been set explicitly. Note: it is the resulting options after merging down the "jpeg" and "png" options and any converter-prefixed options.
- source: [doc-root]/wp-content/uploads/Joseph-Joseph-Nest™-Utensils-Plus-Set-3-600x482.jpg
- destination: [doc-root]/wp-content/webp-express/webp-images/uploads/Joseph-Joseph-Nest™-Utensils-Plus-Set-3-600x482.jpg.webp
- default-quality: 70
- encoding: "auto"
- log-call-arguments: true
- max-quality: 80
- metadata: "none"
- quality: "auto"
- use-nice: true

The following options have not been explicitly set, so using the following defaults:
- alpha-quality: 85
- auto-filter: false
- low-memory: false
- method: 6
- skip: false

The following options were supplied but are ignored because they are not supported by this converter:
- near-lossless
------------

Encoding is set to auto - converting to both lossless and lossy and selecting the smallest file

Converting to lossy
Version: ImageMagick 6.9.11-27 Q16 x86_64 2020-08-11 https://imagemagick.org
Quality of source could not be established (Imagick or GraphicsMagick is required) - Using default instead (70).
using nice
Executing command: nice convert -strip -define webp:alpha-quality=85 -define webp:method=6 '[doc-root]/wp-content/uploads/Joseph-Joseph-Nest-Utensils-Plus-Set-3-600x482.jpg' 'webp:[doc-root]/wp-content/webp-express/webp-images/uploads/Joseph-Joseph-Nest-Utensils-Plus-Set-3-600x482.jpg.webp.lossy.webp' 2>&1

*Output:* 
wp-admin: unable to open image `[doc-root]/wp-content/uploads/Joseph-Joseph-Nest-Utensils-Plus-Set-3-600x482.jpg': No such file or directory @ error/blob.c/OpenBlob/2924.
wp-admin: no images defined `webp:[doc-root]/wp-content/webp-express/webp-images/uploads/Joseph-Joseph-Nest-Utensils-Plus-Set-3-600x482.jpg.webp.lossy.webp' @ error/convert.c/ConvertImageCommand/3226.

return code: 1

**Error: ** **The exec call failed** 
The exec call failed
imagemagick failed in 37 ms

*Trying: graphicsmagick* 

**Error: ** **gmagick is not installed** 
gmagick is not installed
graphicsmagick failed in 2 ms

*Trying: ffmpeg* 

**Error: ** **ffmpeg was compiled without libwebp** 
ffmpeg was compiled without libwebp
ffmpeg failed in 5 ms

*Trying: wpc* 

**Error: ** **Missing URL. You must install Webp Convert Cloud Service on a server, or the WebP Express plugin for Wordpress - and supply the url.** 
Missing URL. You must install Webp Convert Cloud Service on a server, or the WebP Express plugin for Wordpress - and supply the url.
wpc failed in 0 ms

*Trying: ewww* 

**Error: ** **Missing API key.** 
Missing API key.
ewww failed in 0 ms

*Trying: imagick* 

**Error: ** **Required iMagick extension is not available.** 
Required iMagick extension is not available.
imagick failed in 0 ms

*Trying: gmagick* 

**Error: ** **Required Gmagick extension is not available.** 
Required Gmagick extension is not available.
gmagick failed in 0 ms

*Trying: gd* 

Options:
------------
The following options have been set explicitly. Note: it is the resulting options after merging down the "jpeg" and "png" options and any converter-prefixed options.
- source: [doc-root]/wp-content/uploads/Joseph-Joseph-Nest™-Utensils-Plus-Set-3-600x482.jpg
- destination: [doc-root]/wp-content/webp-express/webp-images/uploads/Joseph-Joseph-Nest™-Utensils-Plus-Set-3-600x482.jpg.webp
- default-quality: 70
- log-call-arguments: true
- max-quality: 80
- quality: "auto"

The following options have not been explicitly set, so using the following defaults:
- skip: false

The following options were supplied but are ignored because they are not supported by this converter:
- encoding
- metadata
- near-lossless
- skip-pngs
------------

GD Version: 2.2.5
image is true color
Quality of source could not be established (Imagick or GraphicsMagick is required) - Using default instead (70).
gd succeeded :)

Converted image in 163 ms, reducing file size with 71% (went from 18 kb to 5 kb)
