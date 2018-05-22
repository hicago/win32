---
title: Creating Groups
description: Creating a group involves adding and configuring the individual resources in the group and adjusting the group's properties so that the group is ready to be brought online.
audience: developer
author: REDMOND\\markl
manager: REDMOND\\markl
ms.assetid: 'c6309c0e-fe81-4946-a333-efc5d2a7cb48'
ms.prod: 'windows-server-dev'
ms.technology: 'failover-clustering'
ms.tgt_platform: multiple
keywords: ["groups Failover Cluster ,creating"]
---

# Creating Groups

Creating a [group](groups.md) involves adding and configuring the individual resources in the group and adjusting the group's properties so that the group is ready to be brought online.

Administrators can create groups manually through [cluster management applications](cluster-management-applications.md) such as [Cluster Administrator](cluster-administrator.md), but [*cluster-aware applications*](c-gly.md#-wolf-cluster-aware-application-gly) can ease the burden on administrators by automating group creation as much as possible.

The following sections describe the tasks associated with creating groups.

**To create a group**

1.  Obtain a cluster handle. (See [Using Object Handles](using-object-handles.md).)
2.  Obtain a unique group name. To list the names of groups currently defined in the cluster, see [Enumerating Objects](enumerating-objects.md).
3.  Create the group by calling [**CreateClusterGroup**](createclustergroup.md).
4.  Add resources to the group. To move existing resources into the group, call [**ChangeClusterResourceGroup**](changeclusterresourcegroup.md). To create new resources in the group, see [Creating Resources](creating-resources.md).
5.  Set properties, checkpoints, possible owners, and dependencies for the resources. (See [Configuring Resources](configuring-resources.md).)
6.  Adjust the group's failover policies. (For the properties that affect failover, see [Failover](failover.md) and [Failback](failback.md). For information on changing properties, see [Setting Properties](setting-properties.md).)
7.  If necessary, modify the group's preferred owner nodes list by calling [**SetClusterGroupNodeList**](setclustergroupnodelist.md).

## Example Code

See [Creating Failover Cluster Instances](creating-virtual-servers.md).

 

 



