This lab deploys a Edge-Routed Bridging design with an asymmetric routing model using Juniper vJunos-switch nodes as leafs and spines of a 3-stage Clos fabric. You can deploy the fabric using `containerlab deploy -t erb-asymmetric.clab.yaml`.

> [!IMPORTANT]
> Minimum Containerlab version for the deployment of this lab is v0.62. A bare metal server is needed for vJunos-switch nodes. Running Containerlab in a VM will not work.

The topology is shown below. The username/password for vJunos-switch nodes is `admin/admin@123` and the username/password for the servers is `user/multit00l`.

![erb-topology](/static/images/juniper-erb.png)
<img width="1037" height="637" alt="Screenshot 2026-09-29 at 9 09 18 PM" src="https://github.com/user-attachments/assets/cd555dbb-3113-4028-8078-9043b2b96524" />
