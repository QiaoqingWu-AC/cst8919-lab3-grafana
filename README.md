# cst8919-lab3-grafana
Student Name: Qiaoqing Wu (wu000302@algonquinlive.com)

## Step - 1
Create an Azure Virtual Machine with Ubuntu 22.04 server and size Standard B2s v2.
![sr-1](./screenshots/Screenshot-1.png)
## Step - 2
After installing the Grafana Server in the Azure VM, verified that the Grafana service is running.
![sr-2](./screenshots/Screenshot-2.png)
## Step - 3
Enable port 3000 in the VM's network configuration.
![sr-3](./screenshots/Screenshot-3.png)
## Step - 4
Verified that the Grafana Server is accessible.
![sr-4](./screenshots/Screenshot-4.png)
## Step - 5
Enabled Managed Identity and assigned "Monitoring Reader" and "Reader" roles to the VM.
![sr-5](./screenshots/Screenshot-5.png) 
## Step - 6
Enabled Managed Identity authentication to for data source.
![sr-6](./screenshots/Screenshot-6.png)
## Step - 7
Added the "Azure Monitor" data source using Managed Identity.
![sr-7](./screenshots/Screenshot-7.png)
## Step - 8
Created a dashboard in Grafana, virtualized relevant metrics, and customized the panels.
![sr-8](./screenshots/Screenshot-8.png)
![sr-9](./screenshots/Screenshot-9.png)
![sr-10](./screenshots/Screenshot-10.png)