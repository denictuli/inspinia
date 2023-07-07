# How to Download and Install Palo Alto Firewall VM Image on VMware ESXi
 
Palo Alto Networks is a leading provider of next-generation firewalls that protect networks from cyber threats. Palo Alto Networks offers virtualized firewalls (VM-Series) that can run on different platforms, such as VMware ESXi, AWS, Azure, KVM, Hyper-V, and NSX-T.
 
**Download File ✺ [https://t.co/jNKbb4QM6J](https://t.co/jNKbb4QM6J)**


 
In this article, we will show you how to download and install Palo Alto Firewall VM image on VMware ESXi. We will use the latest PAN-OS version 10.0 for this demonstration.
 
## Prerequisites
 
- A VMware ESXi host with enough resources to run the VM-Series firewall. The minimum requirements are 2 vCPUs, 4 GB RAM, and 40 GB disk space.
- A valid support account and license for VM-Series from Palo Alto Networks. You can obtain a trial license from [here](https://www.paloaltonetworks.com/try-now.html).
- A web browser to access the Palo Alto Networks Customer Support Portal and the VMware vSphere Client.

## Steps

1. Log in to the [Palo Alto Networks Customer Support Portal](https://support.paloaltonetworks.com/) with your credentials.
2. Go to Updates > Software Updates and select PAN-OS for VM-Series from the dropdown menu.
3. Choose the PAN-OS version 10.0 and download the OVA file for VMware ESXi. The file name should be something like PA-VM-ESX-10.0.0.ova.
4. Log in to the VMware vSphere Client and select the ESXi host where you want to deploy the VM-Series firewall.
5. Right-click on the host and select Deploy OVF Template.
6. Browse to the location where you saved the OVA file and click Next.
7. Review the details of the OVF template and click Next.
8. Enter a name for the VM-Series firewall and select a folder to place it. Click Next.
9. Select a datastore to store the VM files and click Next.
10. Select a network to connect the VM interfaces and click Next.
11. Review the settings and click Finish to start the deployment.
12. Wait for the deployment to complete and power on the VM-Series firewall.
13. Open a console window to the VM-Series firewall and log in with the default credentials (admin/admin).
14. Enter configuration mode by typing configure and set a management IP address, netmask, default gateway, and DNS server for the VM-Series firewall. For example:

        set deviceconfig system ip-address 192.168.1.100 netmask 255.255.255.0 default-gateway 192.168.1.1 dns-setting servers primary 8.8.8.8
        commit

15. Exit configuration mode by typing exit and reboot the VM-Series firewall by typing request restart system.
16. After the reboot, open a web browser and access the web interface of the VM-Series firewall using https://<ip-address>. Log in with the same credentials as before (admin/admin).</ip-address>
17. Go to Device > Licenses and click Activate feature using authorization code.
18. Enter your authorization code that you received from Palo Alto Networks and click OK.
19. Select the features that you want to activate and click OK.
20. Wait for the license activation to complete and click OK.
21. Congratulations! You have successfully downloaded and installed Palo Alto Firewall VM image on VMware ESXi. You can now configure your firewall policies and rules according to your needs.

palo alto firewall vm image pavm esx 6.1 ova download,  palo alto firewall virtual machine image for esxi 6.1,  palo alto networks firewall vm image pavm esx 6.1 ova file,  how to install palo alto firewall vm image pavm esx 6.1 ova on vmware,  palo alto firewall vm image pavm esx 6.1 ova license,  palo alto firewall vm image pavm esx 6.1 ova configuration guide,  palo alto firewall vm image pavm esx 6.1 ova system requirements,  palo alto firewall vm image pavm esx 6.1 ova release notes,  palo alto firewall vm image pavm esx 6.1 ova upgrade,  palo alto firewall vm image pavm esx 6.1 ova support,  palo alto firewall vm image pavm esx 6.1 ova features,  palo alto firewall vm image pavm esx 6.1 ova pricing,  palo alto firewall vm image pavm esx 6.1 ova trial,  palo alto firewall vm image pavm esx 6.1 ova demo,  palo alto firewall vm image pavm esx 6.1 ova review,  palo alto firewall vm image pavm esx 6.1 ova comparison,  palo alto firewall vm image pavm esx 6.1 ova best practices,  palo alto firewall vm image pavm esx 6.1 ova troubleshooting,  palo alto firewall vm image pavm esx 6.1 ova backup and restore,  palo alto firewall vm image pavm esx 6.1 ova high availability,  palo alto firewall vm image pavm esx 6.1 ova performance,  palo alto firewall vm image pavm esx 6.1 ova security,  palo alto firewall vm image pavm esx 6.1 ova integration,  palo alto firewall vm image pavm esx 6.1 ova migration,  palo alto firewall vm image pavm esx 6.1 ova deployment options,  palo alto firewall vm image pavm esx 6.1 ova network topology,  palo alto firewall vm image pavm esx 6.1 ova interface configuration,  palo alto firewall vm image pavm esx 6.1 ova routing configuration,  palo alto firewall vm image pavm esx 6.1 ova policy configuration,  palo alto firewall vm image pavm esx 6.1 ova logging and reporting,  palo alto firewall vm image pavm esx 6.1 ova administration and management,  palo alto firewall vm image pavm esx 6.1 ova user identification and authentication,  palo alto firewall vm image pavm esx 6.1 ova application identification and control,  palo alto firewall vm image pavm esx 6.1 ova threat prevention and detection,  palo alto firewall vm image pavm esx 6.1 ova data filtering and protection,  palo alto firewall vm image pavm esx 6.1 ova vpn configuration and setup,  palo alto firewall vm image pavm esx 6.1 ova cloud integration and automation,  palo alto firewall vm image pavm esx 6.1 ova zero trust architecture and design,  palo alto firewall vm image pavm esx 6.1 ova scalability and elasticity,  palo alto firewall vm image pavm esx 6.1 ova disaster recovery and business continuity,  benefits of using palo alto firewall vm image pavm esx 6.1 ova ,  disadvantages of using palo alto firewall vm image pavm esx 6.1 ova ,  alternatives to using palo alto firewall vm image pavm esx 6.1 ova ,  testimonials of using palo alto firewall vm image pavm esx 6.1 ova ,  case studies of using palo alto firewall vm image pavm esx 6.1 ova ,  tutorials of using palo alto firewall vm image pavm esx 6.1 ova ,  FAQs of using palo alto firewall vm image pavm esx 6.1 ova ,  tips and tricks of using palo alto firewall vm image pavm esx 6.1 ova ,  common errors and solutions of using palo alto firewall vm image pavm esx 6.1 ova
 8cf37b1e13
 
