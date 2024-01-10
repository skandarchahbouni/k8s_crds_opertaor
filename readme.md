* Kind is used for this project to create multiple local Kubernetes (k8s) clusters.

* Here, you can find some recorded video demos:

  - Demo 01: click [here]([url](https://drive.google.com/file/d/19F8dYBSmTatAKSb5v7d3yGDBiR7CXbfp/view?usp=sharing)).
  - Demo 02: click [here]([url](https://drive.google.com/file/d/1lyxMUZXkYWD_nRrkYK0hLMFnWgeG5DDr/view?usp=sharing)).
* This project is not finished yet. What needs to be done further includes:

  - Adding support for external access using Ingress.
  - Adding support for stateful applications and persistent storage.
  - Propagating statuses from the workload clusters to the management cluster.
  - Establishing links between two clusters using Liqo.
  - Utilizing real Kubernetes clusters instead of Kind. The aim is to use multiple cloud providers such as AWS, Azure, etc.
  - The provisioning of the different clusters in the infrastructure must be done using the ClusterAPI tool.
  - Adding support for K3s.
