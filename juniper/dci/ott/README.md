This lab deploys an over the top (OTT) DCI design using Juniper vJunos-switch nodes as leafs and spines of a 3-stage Clos fabric, with a core connecting the two DCs. You can deploy the fabric using `containerlab deploy -t dci-ott.clab.yaml`.

> [!IMPORTANT]
> Minimum Containerlab version for the deployment of this lab is v0.62. A bare metal server is needed for vJunos-switch nodes. Running Containerlab in a VM will not work.

The topology is shown below. The username/password for vJunos-switch nodes is `admin/admin@123` and the username/password for the servers is `user/multit00l`.

![dci-ott-topology](/static/images/dci-ott.png)

IP addressing for the servers is as follows:

s1 - 172.16.10.1/24  
s2 - 172.16.10.2/24  
s3 - 172.16.20.3/24  
s4 - 172.16.20.4/24  
s5 - 172.16.10.5/24  
s6 - 172.16.30.6/24  
