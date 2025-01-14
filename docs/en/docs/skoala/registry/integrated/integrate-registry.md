---
hide:
  - toc
---

# Access registry

Registry supports access [Nacos Registry](../../../reference/basic-knowledge/registry.md#nacos-Registry), [ The Eureka Registry ](../../../reference/basic-knowledge/registry.md#eureka-Registry), [ Zookeeper Registration Center ](../../../reference/basic-knowledge/registry.md#zookeeper-Registry), [ Kubernetes Registry ](../../../reference/basic-knowledge/registry.md#kubernetes-Registry), [Mesh Registry](../../../reference/basic-knowledge/registry.md#service-mesh-Registry).

In contrast to managed registries, access registries support only basic operations, such as viewing basic information and monitoring information. To perform more advanced and comprehensive management operations, create [Managed Registry](../managed/registry-lcm/create-registry.md).

To access the registry, perform the following steps:

1. In the left navigation bar click `Microservice Governance` -- > `Integrate Registry`, then at the upper right corner of the page by clicking on the `Integrate Registry`.

    <!--!\[.*?\]\((?:https?:\/\/)?\S+\.(?:png|jpg|jpeg|gif|bmp)\)-->

2. Fill in the configuration information, then click `OK` at the bottom of the page.

    Different types of registries require different configurations.

    - Kubernetes/Mesh Registry: Directly select the cluster or mesh service you want to access.

        - If you cannot find the Kubernetes cluster you want to add, you can go to the container management module [Integrate Cluster](../../../kpanda/user-guide/clusters/integrate-cluster) or [Create Cluster](../../../kpanda/user-guide/clusters/create-cluster.md).

        - If you cannot find the grid service you want to add, you can go to the grid service module [Create Mesh](../../../mspider/user-guide/service-mesh/README.md).

            <!--!\[.*?\]\((?:https?:\/\/)?\S+\.(?:png|jpg|jpeg|gif|bmp)\)-->

    - Nacos/Zookeeper/Eureka Registry: Fill in the name and address of the registry and click `Test Connectivity`.

        If the address bar is gray, the access test is successful. For distributed high availability registries, you can also enter multiple addresses by clicking `+ Add`.

        <!--!\[.*?\]\((?:https?:\/\/)?\S+\.(?:png|jpg|jpeg|gif|bmp)\)-->