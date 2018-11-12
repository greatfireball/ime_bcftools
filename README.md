# Docker image for bcftools software package
## ime_bcftools
This repository contains the Dockerfile to create a docker image for the bcftools software package.

## Usage of this docker image
Calling `bcftools` is the default entrypoint of this image. The parameter `--help` is the default command. Therefore, running the image will result in a call of `bcftools --help` within the folder `/data`.
### Data im-/export
The working directory `/data` is defined as a volume and can be used for data im- and export while using this image.

## Current version
The current version is bcftools [![](https://images.microbadger.com/badges/version/greatfireball/ime_bcftools:v1.7.svg)](https://microbadger.com/images/greatfireball/ime_bcftools:v1.7 "Get your own version badge on microbadger.com").

| Version tag/branch | Size | Commit |
|-|-|-|
| [![](https://images.microbadger.com/badges/version/greatfireball/ime_bcftools:v1.7.svg)](https://microbadger.com/images/greatfireball/ime_bcftools:v1.7 "Get your own version badge on microbadger.com") | [![](https://images.microbadger.com/badges/image/greatfireball/ime_bcftools:v1.7.svg)](https://microbadger.com/images/greatfireball/ime_bcftools:v1.7 "Get your own image badge on microbadger.com") | [![](https://images.microbadger.com/badges/commit/greatfireball/ime_bcftools:v1.7.svg)](https://microbadger.com/images/greatfireball/ime_bcftools:v1.7 "Get your own commit badge on microbadger.com") |
| [![](https://images.microbadger.com/badges/version/greatfireball/ime_bcftools:master.svg)](https://microbadger.com/images/greatfireball/ime_bcftools:master "Get your own version badge on microbadger.com") | [![](https://images.microbadger.com/badges/image/greatfireball/ime_bcftools:master.svg)](https://microbadger.com/images/greatfireball/ime_bcftools:master "Get your own image badge on microbadger.com") | [![](https://images.microbadger.com/badges/commit/greatfireball/ime_bcftools:master.svg)](https://microbadger.com/images/greatfireball/ime_bcftools:master "Get your own commit badge on microbadger.com") |
| [![](https://images.microbadger.com/badges/version/greatfireball/ime_bcftools:develop.svg)](https://microbadger.com/images/greatfireball/ime_bcftools:develop "Get your own version badge on microbadger.com") | [![](https://images.microbadger.com/badges/image/greatfireball/ime_bcftools:develop.svg)](https://microbadger.com/images/greatfireball/ime_bcftools:develop "Get your own image badge on microbadger.com") | [![](https://images.microbadger.com/badges/commit/greatfireball/ime_bcftools:develop.svg)](https://microbadger.com/images/greatfireball/ime_bcftools:develop "Get your own commit badge on microbadger.com") |

## All tags
All tags are listed on the [docker hub page](https://hub.docker.com/r/greatfireball/ime_bcftools/tags/). Versions with a tags are:
- v1.2
- v1.3
- v1.3.1
- v1.4
- v1.4.1
- v1.5
- v1.6
- v1.7

## Further information
Further documentation about bcftools can be found on the [official site](http://www.htslib.org/doc/bcftools.html)
