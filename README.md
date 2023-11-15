# OpenStack K8S Operators Topologies

This repo stores OpenStack K8S Operators topologies, represented as CRs for the various operators.

All [validated architectures (VA)](https://github.com/openstack-k8s-operators/architecture)
are [deployment topologies (DT)](https://github.com/openstack-k8s-operators/topologies),
but not all DTs are VAs.

DTs represent CI optimizations. We design them to test lots of things together so we can have as few of them as possible. Before proposing a new DT to test something (by PR'ing a new subdirectory), consider if an update to an existing DT will achieve the same result.
