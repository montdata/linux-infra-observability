# LINUX O11Y



## Getting started

# montd-agent
Montdata Prometheus Node Exporter

# Installation
/bin/sh -c " $(curl -fsSL  https://raw.githubusercontent.com/montdata/montd-node-exporter/master/install_montd_agent.sh) " 1

# RUN with Docker
docker run -d -p 9100:9100 montdata/montd-observability-agent:0.1.0
