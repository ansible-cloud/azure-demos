# Create a "Workflow Template"

Use the numbered Job Templates to create a Workflow Template using the Workflow Visualizer.


The following are the extra vars for the Workflow template.

```yaml
---
resource_group_name: "ansible_test"
region: "eastus"
vnet_cidr: "10.0.0.0/16"
subnet_cidr: "10.0.1.0/24"
vnet_name: "demo_vnet"
subnet_name: "demo_subnet"
network_sec_group_name: "demo_sec_group"
win_vm_name: "WIN-ansible"
win_vm_size: "Standard_DS1_v2"
win_vm_sku: "2022-Datacenter"
win_public_ip_name: "win_demo_ip"
win_nic_name: "win_demo_nic"
win_admin_user: "azureuser"
win_admin_password: "AnsibleTest@123"
```
