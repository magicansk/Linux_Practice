## Configure iSCSI SAN
--- 

A SAN(storage-area-network) offers shared block devices. Another commmon solution to offer shared storage is the NAS(network-attached storage). In a NAS, file systems are shared, such as NFS(network-file-system) of Server Message Block(SMB). In general, a SAN solution is prepferred because it is faster and it offers more flexibility. The user of the SAN can decide for himself what he wants to do on the SAN because it is offering shared block devices, whereas a NAS user can just mount the shared file system. Some SAN appliances offer NAS access as well so that the storage administrator can choose which solution he wants to offer.  


iSCSI | LEARN 
--- | ---
Understanding iSCSI | 
--- | iSCSI as a SAN solution 
--- | compares to Fibre Channel SAN 
--- | software targets relate to hardware iSCSI solutions 
--- | needed to setup an iSCSI SAN
Setting up the iSCSI Target |  
Setting up the iSCSI Initiator | 
Troubleshooting iSCSI |  

### Setting up Environment 
---  
Two servers:  
One is configured as the iSCSI SAN.
One is cofigured as the node that is accessing the storage devices shared by the SAN.
 
  * iSCSI target(server 1):  Need 100MB setup an LVM volume and a file.  
  * iSCSI initiator(server 2): no specific requirements.  


###  Understanding iSCSI  
---  

#### Comparing SAN solutions

> Make sure that shared disks are made available to the servers that are connecing to the SAN.   

    * Fibre Channel - using with a hardware dedicated high speed network topology to access SAN storage.  
    * iSCSI   

#### Software versus Hardware iSCSI SAN   

For fundamental there is no difference exists in the operation of software and hardware iSCSI. The main difference is that in a hardware iSCSI SAN, the hardware is optimized to deliver the best possible performance.  

Special iSCSI optimized network cards can be used, often referred to as ***host bus adapters*** (HBAs). These often include a hardware TCP offload engine that allows the iSCSI packets to be handled on the HBA.  


To be continued .... 


 
