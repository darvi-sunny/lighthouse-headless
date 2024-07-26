# escape=`

ARG PARENT_IMAGE
ARG SXA_IMAGE

FROM ${SXA_IMAGE} AS sxa
FROM ${PARENT_IMAGE}


# Copy and init the SXA Module
COPY --from=sxa C:\module\solr\cores-sxa.json C:\data\cores-sxa.json