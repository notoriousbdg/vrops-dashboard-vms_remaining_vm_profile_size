
# VMs Remaining (VM Profile Size) Dashboard for vRealize Operations 6.7 and 7.0
---------

Use this [vRealize Operations](https://www.vmware.com/products/vrealize-operations.html) dashboard to view VMs Remaining in a cluster based on a VM Profile size specified in Super Metrics.  The VM Profile size can be adjusted by modifying the Super Metrics.

## Dashboard
![Dashboard](https://raw.githubusercontent.com/notoriousbdg/vrops-dashboard-vms_remaining_vm_profile_size/master/Dashboard.png)

## Installation
1. Import the super metric at `Administration` / `Configuration` / `Super Metrics` / `Import Super Metric`  
![Import View](https://raw.githubusercontent.com/notoriousbdg/vrops-dashboard-vms_remaining_vm_profile_size/master/Import_Super_Metric.png)
2. Click `Browse...` then select the file named [SuperMetric - VMs Remaining VM Profile.json](https://github.com/notoriousbdg/vrops-dashboard-vms_remaining_vm_profile_size/raw/master/SuperMetric%20-%20VMs%20Remaining%20VM%20Profile.json)
3. Edit the Policy at `Administration` / `Policies` / `Policy Library`.  The policy should be `vSphere Solution's Default Policy (DATE)` unless a new policy was explicitly created.  
![Policy Library](https://raw.githubusercontent.com/notoriousbdg/vrops-dashboard-vms_remaining_vm_profile_size/master/Policy_Library.png)
4. Enable Super Metrics whose name begins with `Super Metric|VMs Remaining VM Profile` on Cluster Compute Resource objects only.
![Policy Metrics](https://raw.githubusercontent.com/notoriousbdg/vrops-dashboard-vms_remaining_vm_profile_size/master/Policy_Metrics.png)
5. Import the view at `Dashboards` / `Views` / `Import...`  
![Import View](https://raw.githubusercontent.com/notoriousbdg/vrops-dashboard-vms_remaining_vm_profile_size/master/Import_View.png)
6. Click `Browse...` then select the file named [Views - VMs Remaining VM Profile Size.zip](https://github.com/notoriousbdg/vrops-dashboard-vms_remaining_vm_profile_size/raw/master/Views%20-%20VMs%20Remaining%20VM%20Profile%20Size.zip)
7. Import the dashboard at `Dashboards` / `Actions` / `Manage Dashboards` / `Import Dashboards`  
![Import Dashboard](https://raw.githubusercontent.com/notoriousbdg/vrops-dashboard-vms_remaining_vm_profile_size/master/Import_Dashboard.png)
8. Click `Browse...` then select the file named [Dashboard - VMs Remaining VM Profile Size.zip](https://github.com/notoriousbdg/vrops-dashboard-vms_remaining_vm_profile_size/raw/master/Dashboard%20-%20VMs%20Remaining%20VM%20Profile%20Size.zip)
9. The dashboard should now be available in in the dashboard list  
![Dashboard List](https://raw.githubusercontent.com/notoriousbdg/vrops-dashboard-vms_remaining_vm_profile_size/master/Dashboard_List.png)

## Support

This dashboard requires vRealize Operation 6.7 or 7.0 Advanced or Enterprise edition.

Please open an [issue](https://github.com/notoriousbdg/vrops-dashboard-vms_remaining_vm_profile_size/issues) for feedback.
