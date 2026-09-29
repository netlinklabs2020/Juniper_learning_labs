This lab deploys a Centrally Routed Bridging design (IRBs on the spines) using Juniper vJunos-switch nodes as leafs and spines of a 3-stage Clos fabric. You can deploy the fabric using `containerlab deploy -t crb.clab.yaml`.

> [!IMPORTANT]
> Minimum Containerlab version for the deployment of this lab is v0.62. A bare metal server is needed for vJunos-switch nodes. Running Containerlab in a VM will not work.

The topology is shown below. The username/password for vJunos-switch nodes is `admin/admin@123` and the username/password for the servers is `user/multit00l`. || here user name is admin for host 

![crb-topology](/static/images/juniper-crb.png)
