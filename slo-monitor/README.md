## [DEPRECATED] Since v1.26 the main metric `pod_start_sli_duration_seconds` has been added to Kubernetes core (kubelet [PR#111930](https://github.com/kubernetes/kubernetes/pull/111930))

# Kubernetes Performance SLO monitor

This tool monitors Performance SLOs that are unavailable from the API server and exposes Prometheus metrics for them.

It can be run anywhere and only requirement is that it needs to be able to talk to the API server.

# Usage

SLO monitor is a simple pod that needs to be able to read Pods and Events. On top of that it should work as long as it can communicate with the API server.