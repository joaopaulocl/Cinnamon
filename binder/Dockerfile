# mybinder.org: start from the prebuilt tutorial image instead of rebuilding
# the toolchain (see ../Dockerfile). The image already contains the repository
# in $HOME, Jupyter, and runs as UID 1000.
#
# Update the digest after every push:
#   docker inspect --format='{{index .RepoDigests 0}}' <image>:esweek
FROM ghcr.io/joaopaulocl/cinnamon-tutorial@sha256:0a2337e76ff8fd72884b2f81cc2ad95a2a73d4a2b1c3cca055f910a711665bfd
