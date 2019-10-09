# MySQL_Enterprise_Edition_InnoDB_Cluster_Docker_Compose
 A MySQL InnoDB Cluster with Enterprise Security Features

This example does not show how to upgrade the base MOS (http://my.oracle.com) to 8.0.17

Installation assumes you are using from "~/Docker/"

RPM's are saved outside of this project so as not to violate Oracle MySQL Enterprise Edition distribution restrictions. 

By design the example uses a shared source for RPM's, BIN files or scripts. This is the alias "~/Docker/SharedSource/" that points to "~/DockerSharedSource/"

Usefull Things to Do -hint hint

1. Use intialize secure with Docker Secrets file
2. Add Data Masking and Firewall
3. Stub out External Autentication
4. Configure unattended installation of MySQL Enterprise Monitor (MEM) Agents
5. Configure a bridge network TUN for remote management of audit log, firewall and backup
6. Update documentation template
9. Create housekeeping scripts