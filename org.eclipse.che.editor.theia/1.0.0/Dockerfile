FROM eclipse/che-theia:0.3.19-nightly
RUN wget https://storage.googleapis.com/kubernetes-release/release/v1.13.3/bin/linux/amd64/kubectl && chmod +x ./kubectl
USER root
RUN mv ./kubectl /usr/local/bin/kubectl
