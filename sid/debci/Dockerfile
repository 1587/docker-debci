FROM debian:sid

MAINTAINER You-Sheng Yang <vicamo@gmail.com> (@vicamo)

RUN apt-get update \
	&& apt-get install -y --no-install-recommends \
		debci \
	&& apt-get clean \
	&& rm -rf /var/lib/apt/lists/*_dists_*
