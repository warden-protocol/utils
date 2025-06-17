FROM amazon/aws-cli:2.18.4

RUN yum install -y tar lz4 jq && \
  curl -sLO "https://dl.k8s.io/release/$(curl -sL https://dl.k8s.io/release/stable.txt)/bin/linux/amd64/kubectl" && \
  chmod +x kubectl  && \
  mv kubectl /usr/local/bin/