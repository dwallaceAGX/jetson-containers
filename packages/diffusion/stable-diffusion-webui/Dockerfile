#---
# name: stable-diffusion-webui
# group: diffusion
# depends: [pytorch, torchvision, transformers, xformers, pycuda, opencv]
# requires: '>=34.1.0'
# docs: docs.md
# notes: disabled on JetPack 4
#---
ARG BASE_IMAGE
FROM ${BASE_IMAGE}
    
# set the cache dir for models
ENV DIFFUSERS_CACHE=/data/models/diffusers

# default start-up command
CMD /bin/bash

