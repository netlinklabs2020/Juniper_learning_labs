This lab deploys a DCI design with Type-5 stitching (integrated interconnect) using Juniper vJunos-switch nodes as leafs and spines, vJunosEvolved nodes as border leafs of a 3-stage Clos fabric, with a core connecting the two DCs. You can deploy the fabric using `containerlab deploy -t dci-t5-stitching.clab.yaml`.

> [!IMPORTANT]
> Minimum Containerlab version for the deployment of this lab is v0.62. A bare metal server is needed for vJunos-switch nodes. Running Containerlab in a VM will not work.

The topology is shown below. The username/password for vJunos-switch nodes is `admin/admin@123` and the username/password for the servers is `user/multit00l`.

![dci-t5-stitching-topology](/static/images/dci-t5-stitching.png)

<img width="1018" height="488" alt="Screenshot 2026-09-29 at 9 13 54 PM" src="https://github.com/user-attachments/assets/ffde85f1-eefd-491b-9024-98ffb01b8ddb" />


IP addressing for the servers is as follows:

s1 - 172.16.10.1/24  
s2 - 172.16.20.2/24  
s3 - 172.16.30.3/24  
s4 - 172.16.40.4/24  
s5 - 172.16.50.5/24  
