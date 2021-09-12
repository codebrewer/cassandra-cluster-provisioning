# Cassandra Cluster Provisioning

Tinkering with [Apache Cassandra](https://cassandra.apache.org/_/index.html) by provisioning different cluster scenarios
using [Vagrant](https://www.vagrantup.com), [Parallels Desktop](https://www.parallels.com/products/desktop/) VMs (via
the [Vagrant Parallels Provider](https://github.com/Parallels/vagrant-parallels)) and [Docker](https://www.docker.com)
containers (using the [Docker Cassandra Official Image](https://hub.docker.com/_/cassandra)).

## Scenarios

* [Scenario 1.1](1_single-datacentre/1_one-node-per-vm/README.md) - a single-datacentre cluster of 4 Cassandra nodes, each node running in a Docker container hosted on its own VM.
