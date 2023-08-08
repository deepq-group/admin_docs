# 2. Dashboard

The first thing showing up in the Deeploy backstage is the dashboard. this is where the administrator can view the list of inference resources, including GPUs & CPU.

![the dashboard shows the complete list of inference resureces and their currant status](.gitbook/assets/Deeploy-adm-2-0-1.png)

The total numbers of inference resource is the max number of deployments that can run simultaneous on the system. the number of GPUs reflect how many discrete GPU cards are installed onto the system while each system will have an additional CPU resource for deployment.

For example, a Deeploy system that has 2 GPU cards can run up to 3 deployments at the same time：GPU\*2 + CPU\*1
