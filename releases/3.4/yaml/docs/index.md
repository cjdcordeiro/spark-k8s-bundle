# Charmed Spark Documentation

Charmed Spark is a set of Canonical supported artifacts (including charms, ROCK OCI images and SNAPs) that makes operating Spark workloads on Kubernetes seamless, secure and production-ready. 

The solution helps to simplify user interaction with Spark applications and the underlying Kubernetes cluster whilst retaining the traditional semantics and command line tooling that users already know. Operators benefit from straightforward, automated deployment of Spark components (e.g. Spark History Server) to the Kubernetes cluster, using [Juju](https://juju.is/). 

Deploying Spark applications to Kubernetes has several benefits over other cluster resource managers such as Apache YARN, as it greatly simplifies deployment, operation, authentication while allowing for flexibility and scaling. However, it requires knowledge on Kubernetes, networking and coordination between the different components of the Spark ecosystem in order to provide a scalable, secure and production-ready environment. As a consequence, this can significantly increase complexity for the end user and administrators, as a number of parameters need to be configured and prerequisites must be met for the application to deploy correctly or for using the Spark CLI interface (e.g. pyspark and spark-shell). 

Charmed Spark helps to address these usability concerns and provides a consistent management interface for operations engineers and cluster administrators who need to manage enablers like Spark History Server.

## Project and community

Charmed Spark is a distribution of Apache Spark. It’s an open-source project that welcomes community contributions, suggestions, fixes and constructive feedback.
- [Read our Code of Conduct](https://ubuntu.com/community/code-of-conduct)
- [Join the Discourse forum](https://discourse.charmhub.io/tag/spark)
- [Contribute and report bugs](https://github.com/canonical/spark-client-snap)

# Contents

1. [Overview](overview.md)
1. [Tutorial](tutorial)
  1. [1. Introduction](tutorial/t-overview.md)
  1. [2. Set up the environment for the tutorial](tutorial/t-setup-environment.md)
  1. [2. Interacting with Spark using Interactive Shell](tutorial/t-spark-shell.md)
  1. [3. Submitting Jobs using Spark Submit](tutorial/t-spark-submit.md)
  1. [4. Streaming workloads with Charmed Spark](tutorial/t-spark-streaming.md)
  1. [5. Monitoring the Spark cluster](tutorial/t-spark-monitoring.md)
  1. [6. Wrapping Up](tutorial/t-wrapping-up.md)
1. [How To](how-to)
  1. [Setup Environment](how-to/h-setup-k8s.md)
  1. [Manage Service Accounts](how-to/h-manage-service-accounts.md)
  1. [Use the Spark Client Python API](how-to/h-use-spark-client-from-python.md)
  1. [Run on K8s pods](how-to/h-run-on-k8s-pod.md)
  1. [Deploy Spark History Server](how-to/h-deploy-spark-history.md)
  1. [Run Spark Streaming Jobs](how-to/h-spark-streaming.md)
  1. [Enable monitoring](how-to/h-spark-monitoring.md)
  1. [Enable authorization History Server](how-to/h-history-server-authorization.md)
1. [Reference](reference)
  1. [Requirements](reference/r-requirements.md)
1. [Explanation](explanation)
  1. [Component Overview](explanation/e-component-overview.md)
  1. [Spark Client Hierarchical Configuration](explanation/e-configuration.md)