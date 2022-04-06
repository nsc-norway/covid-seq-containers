# Containers for use with covid-seq pipeline

The pipeline is at: https://github.com/nsc-norway/covid-seq/

This repo contains the custom containers used with the pipeline, and commands to make singularity
images.

1. To build them locally, and to make Singularity images, see the commands in README_script_covid

2. The images are available at:

https://github.com/nsc-norway/covid-seq-containers/packages

Packages are tagged with the pipeline release versions. There are no docker images for the current
development version of this repo.


## Important:

Pangolin is updated more frequently than the pipeline releases, and the current
versions of pangolin may not be reflected here. If you use the pipeline, you should
check for new pangolin releases and update them. They can be built using the
dockerfiles in Docker/, see README_script_docker.

https://github.com/cov-lineages/pangolin/releases
https://github.com/cov-lineages/pangolin-data/releases

Nextclade versions are no longer maintained in this pipeline. Because the alignment
output of nextflow changed, we have to stick with version 1 to maintain consistency
with old data.
