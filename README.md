# Containers for use with covid-seq pipeline

The pipeline is at: https://github.com/nsc-norway/covid-seq/

This repo contains the custom containers used with the pipeline, and commands to make singularity
images.

1. To build them locally, and to make Singularity images, see the commands in README_script_covid

2. The images are available at:

https://github.com/nsc-norway/covid-seq-containers/packages

Packages in `main/` are the current development version, and release numbers correspond to the
pipeline versions.


## Important:

Nextclade and Pangolin are updated more frequently than the pipeline releases, and the current
versions of nextclade/pangolin may not be reflected here. If you use the pipeline, you should
check for new pangolin and nextclade releases and update them. They can be built using the
dockerfiles in Docker/, see README_script_docker.

https://github.com/nextstrain/nextclade/releases
https://github.com/cov-lineages/pangoLEARN/releases
https://github.com/cov-lineages/pangolin/releases
