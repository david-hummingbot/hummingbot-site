## Requirements

For experienced and technical users, we recommend setting up a cloud instance and installing the Docker version or from source. This enables Hummingbot to run 24/7.

Hummingot Docker instances takes up around 500 MB of storage space and 4 GB for Hummingbot Docker image. We have ested to install and run Hummingbot on the following machine types:

| Provider              | Instance Type   | Instance Details      |
| --------------------- | --------------- | --------------------- |
| Google Cloud Platform | g1-small        | 2 vCPU, 4 GB memory |
| Amazon Web Services   | t2.small        | 2 vCPU, 4 GB memory   |
| Microsoft Azure       | Standard_D2s_v3 | 2 vCPU, 8 GB memory   |

These instances are pre-loaded with system files that takes up around 1.2 GB so we recommend having at least **8 GB of storage space** in your cloud server.

## 📺 Videos and Guides

:fontawesome-brands-youtube: [AWS Deployment for Hummingbot](https://www.youtube.com/watch?v=ppTxEngRDmU&list=PLDwlNkL_4MMc1GxjWShinaX4FQCxgOkyO&index=9)

- [Hummingbot on different cloud providers](https://blog.hummingbot.org/2019-06-cloud-providers/)
- [AWS - Connect to Your Amazon EC2 Instance](https://aws.amazon.com/ec2/?nc2=h_ql_prod_fs_ec2&ec2-whats-new.sort-by=item.additionalFields.postDateTime&ec2-whats-new.sort-order=desc)
- [AWS - Connecting to your Linux instance from Windows using PuTTY](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/putty.html)
- [Azure - Connect to a Linux-based VM](https://docs.microsoft.com/en-us/azure/marketplace/partner-center-portal/create-azure-vm-technical-asset#connect-to-a-linux-based-vm)
