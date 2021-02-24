.. _plan-hypervisor-capacity:



========================
Plan hypervisor capacity
========================

As your business grows and you add to or expand your VMs, you might need
to add or upgrade your ESXi hypervisors to meet demand.

To plan for ESXi capacity, consider the following questions:

* Does the environment run well, or do you need additional
  physical resources to keep up with demand from the VMs?
* What would happen if a hypervisor goes down?
* What would happen if a hypervisor undergoes maintenance?

This section includes the following topics:

* Review hypervisor performance metrics
* View hypervisor configurations




.. _review-hypervisor-performance-metrics:


Review hypervisor performance metrics
_____________________________________


The Rackspace Technology Customer Portal provides a number of useful
vCenter metrics that help you understand how your ESXi hypervisors
are used. Available metrics include but are not limited to CPU,
network, RAM, and storage.

Complete the following steps to view metrics in the
Rackspace Technology Customer Portal:

1. Log in to the
  `Rackspace Technology Customer PortalCloud Control Panel <https://login.rackspace.com/>`_
2. In the **Products** drop-down menu, select **VMware Server Virtualization**.
3. Navigate to an ESXi hypervisor or a vSphere cluster for which you want to see the metrics.
4. Scroll to the **Performance** section. In this section, you can:
    * Select the metric you want to see.
    * Change the time range you want to see.
    * Observe the graph shown based on your selections.
5.	To export data to **.csv** format for further analysis, click the
**Export to .csv** link above the graph. You can also look at
the **Available Resources** section on the same page to see what’s available.
6.	To see utilization information for each datastore, scroll down the page
and review the contents of the **Storage** section.





.. _view-hypervisor-configurations:



View hypervisor configurations
______________________________

To determine the number of disks, resources, and storage attached to a
hypervisor, complete the following steps:

1. Log in to the
   `Rackspace Technology Customer Portal<https://login.rackspace.com/>`_.
2. In the **Products** drop-down menu, select
   **VMware Server Virtualization**.
3. Navigate to an ESXi hypervisor or a vSphere cluster for which
   you want to see the metrics.
   
You can see how the hypervisor is configured, including:

* ESXi version
* Physical location
* Processor type
* RAM quantity
* Configured networks
* Chassis model
* List of VMs
