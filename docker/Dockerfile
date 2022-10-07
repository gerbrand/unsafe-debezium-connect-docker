ARG BASE_TAG=2.0.0.Beta1

FROM debezium/connect:2.0.0.Beta1

USER root
# From https://groups.google.com/g/debezium/c/YkyXZxJGTKk?pli=1
RUN update-crypto-policies --set LEGACY
USER kafka
