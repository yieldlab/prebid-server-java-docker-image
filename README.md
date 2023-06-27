# Prebid Server Java Docker Image

As there is currently no official Docker image for the PBS Java version available, we have to build one on our own.

The goal of this repository is to configure a GitHub action that automatically builds a properly tagged Docker image
whenever a new version of [prebid-server-java][psj] is released on GitHub. The resulting image will be pushed to the
Github Container Registry.

[psj]: https://github.com/prebid/prebid-server-java
