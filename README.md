# OpenShift Container Platform with VSphere Cloud Provider 

This repository contains all necessary playbooks to install VSphere as cloud provider in OpenShift Container Platform as post installation step.


1. Fill all the necessary variables with the correct value **inventory/group_vars/OSEv3/main.yaml**
    
2. Launch **vsphere-config.yaml**

    ```
        ansible-playbook playbooks/vsphere-config.yaml
    ```
    
3. Launch **cloud-provider.yaml**


    ```
        ansible-playbook playbooks/cloud-provider.yaml
    ```
    
4. Launch **storage-class.yaml**


    ```
        ansible-playbook playbooks/storage-class.yaml
    ```
