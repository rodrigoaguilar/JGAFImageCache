JGAFImageCache (v1.0.2 Beta)
==============

A fast reliable image cache for iOS built with AFNetworking.

1. Asynchronously loads from the fastest available source: NSCache, disk, or internet
1. Creates SHA1 hash of the url to use as the key
1. Always calls completion blocks on the main queue
1. Automatically removes old images in the background
1. Stays out of your way

You must include <a href=https://github.com/AFNetworking/AFNetworking>AFNetworking</a> in your project.

`$ git submodule add https://github.com/AFNetworking/AFNetworking.git`

Version Info:
v1.0.2
 - Add serial queue for save to disk operations.
 - Check for available free disk space before saving to disk.

v1.0.1
  - Add retry logic.
