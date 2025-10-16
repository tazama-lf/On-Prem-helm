<!-- SPDX-License-Identifier: Apache-2.0 -->
# Helm Commands Shortcuts

This guide provides a comprehensive walkthrough for deploying Tazama on an on-premises Kubernetes cluster. It includes provisioning the infrastructure, as well as provide options to install the rest of the tazama stack using jenkins.

## Full Command

``helm install tazama . -f values.yaml -f values-grafana.yaml -f values-jenkins.yaml -f values-nats.yaml -f values-pgadmin.yaml -f values-prometheus.yaml -f values-kibana.yaml -f values-grafana.yaml -f values-elastic.yaml -f values-apm.yaml -f values-postgres.yaml -f values-pgadmin.yaml``

