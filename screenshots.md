1. Create appropriate Azure resources to utilize Application Insights and Azure Log Analytics. As evidence, provide a screenshot of the resource group containing your running resources. 

![image-20210507223736933](screenshots/resource-group.png)



## **VMMS screenshots:**

1. Enable **Application Insights** for a **VM Scale Set**. As evidence, provide a screenshot of the metrics from the VM Scale Set instance. This should show the following information:

   ​	• CPU %

   ​	• Available Memory %

   ​	• Information about the Disk

   ​	• Information about the bytes sent and received

![](screenshots/insights-cpu-utilization.png)

![image-20210507200318739](screenshots/available-memory-and-byte-sent.png)

![image-20210507200432312](screenshots/byte-received-and-logical-disk-space-used.png)



![image-20210509035155690](screenshots/instance-insights-1.png)

![image-20210509035251740](screenshots/instance-insights-2.png)

![image-20210509035337389](screenshots/instance-insights-3.png)

2. Import and reference the correct libraries to enable the collection of Application Insights telemetry data.
   * Application Insight Events that show the results of clicking vote for each Dogs & Cats

![15](screenshots/app-insights-events.png)

![image-20210507203557346](screenshots/transaction-search.png)



![image-20210507204517849](screenshots/traces.png)

![image-20210507204845823](screenshots/traces-charts.png)

![image-20210507204557857](screenshots/vmss-app.png)

3.  Create an auto scaling rule for a VM Scale Set.

![image-20210507210829821](screenshots/auto-scale-rule.png)

• The Activity log of the VM scale set that shows it scaled up, including a timestamp.

• The new instances being created.

• The metrics showing the load increasing, then decreasing once scaled up, including a timestamp.

chart-cpu-utilization-1

![image-20210507211357970](screenshots/chart-cpu-utilization-1.png)

![image-20210507211459085](screenshots/chart-cpu-utilization-2.png)

![image-20210507211606130](screenshots/chart-cpu-utilization-3.png)

![image-20210507214118679](screenshots/instances-scaling.png)

![image-20210507223308099](screenshots/scale-email.png)

![Rounded Rectangle](screenshots/vmss-activity-log.png)

## Kubernetes cluster:

![image-20210507231123925](screenshots/kubernetes-cluster.png)

![image-20210507232007121](screenshots/kubernetes-nodes.png)

![image-20210507232058214](screenshots/kubernetes-containers.png)

![image-20210508002112007](screenshots/kubernetes-alert.png)

![](screenshots/pod-count-alert.png)

![image-20210509041056440](screenshots/kubectl-replicas.png)

![image-20210509041152421](screenshots/kubectl-replicas-2.png)

## Runbooks:

![image-20210508004639729](screenshots/runbook.png)

![image-20210508010016322](screenshots/runbook-alert.png)

![image-20210508015406445](screenshots/runbook-triggered.png)

![image-20210508022022436](screenshots/runbooks-jobs.png)

![runbook-resource-group](screenshots/runbook-resource-group.png)

![image-20210508231209347](screenshots/run-book-email-alert.png)

