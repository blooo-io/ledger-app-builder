FROM ghcr.io/blooo-io/ledger-app-builder/ledger-app-builder:master

# ARG REPOSITORY
# ARG TOKEN

# RUN /bin/bash -c 'curl -o cov-analysis-linux64.tar.gz https://scan.coverity.com/download/cxx/linux64 \
#   --form project=$REPOSITORY \
#   --form token=$TOKEN'
# Coverity Scan
ADD cov-analysis-linux64.tar.gz /opt/
ENV PATH=/opt/cov-analysis-linux64-2022.6.0/bin:$PATH
