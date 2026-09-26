# mybinder.org: start from the prebuilt tutorial image instead of rebuilding
# the toolchain (see ../Dockerfile). The image already contains the repository
# in $HOME, Jupyter, and runs as UID 1000.
#
# Update the digest after every push:
#   docker inspect --format='{{index .RepoDigests 0}}' <image>:esweek
FROM ghcr.io/joaopaulocl/cinnamon-tutorial@sha256:b1b25aaaa7e48ac3689e891d21c4f09ebf21a14a6935f3b3357faa527a14ff32
