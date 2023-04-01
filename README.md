# ACM IaC


pass bond0 config to assist installer

prereq
all control cluster
ovirt operator
localVolume operator https://docs.openshift.com/container-platform/4.11/storage/persistent_storage/persistent-storage-local.html 
NodeNetworkConfigurationPolicy to spread all nodes instead of per cluster
1 per node bridge
nad - 
    - Multus network bond1

all the clusters
nmstate operator and instance

data1 and data2 interfaces on managedcluster


TBD: Change to Dell for local volume operator
hostpathprovisioner CR
machineconfig CR
storageclass CR



How machine gets the 
Dell container storage module

Ian recommends to not touch bond0 with nmstate



UID: T13311B
Initial PW: WvbLdiW8