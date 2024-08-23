# Lab 4 - Test the Policy  

## Lab Overview
Lab time:  30 minutes  

In preparing for this lab, a pair of distributed virtual switches have been created. One connects to the **Leaf1A-10K** and the other connects to **Leaf1B-10K**. Proper connections have been made in advance. WL01 and WL02 are in vlan 10 port group, and WL03 is in vlan 20 port group.
At this point of the lab. All traffic between the endpoint groups should be blocked except ssh from **workload01** & **workload02** to **workload03**. Open up a SSH session on all of the workloads.

## Lab 4.1 - Configure the Overlay  

1. On the desktop, in the windows search bar (bottom left of screen) enter CMD to open a command window. Use SSH to connect to **all** the workloads out-of-band-management interface. 

|||||
|---|---|---|---|
| WL-Name | User Name | Password | Address
| Workload01 | arubatm | admin | 10.250.2<span style="color:orange">**[LG]**</span>.201 | 
| Workload01 | arubatm | admin | 10.250.2<span style="color:orange">**[LG]**</span>.201 | 
| Workload01 | arubatm | admin | 10.250.2<span style="color:orange">**[LG]**</span>.201 | 

<hr>
<br>

Enter these commands on the jumphost.
<br>

``C:\Users\Admin> ssh arubatm@10.250.2LG.201 ``
``C:\Users\Admin> ssh arubatm@10.250.2LG.202 ``
``C:\Users\Admin> ssh arubatm@10.250.2LG.203 ``


### Description  


### Validate   

### Expected Results  
