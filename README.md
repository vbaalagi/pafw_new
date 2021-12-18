####### Basic Idea ##############
THIS IS PALO ALTO FIREWALL DEPLOYMENT JASON FILE SCRIPT IaC 
ORIGINAL INTENTIONAL TO CREATE FILE PALO ALTO FIREWALL DEPLOYEMENT TO CREATE A JASON SCRIPT TO DEPLOY PALO ALTO FIREWALL WIHT 2 VMS FOR ACTIVE/ACTIVE OR ACTIVE/PASSIVE SCENARIO DEPLOYENT
BUT DUE TO SOME LIMITATION IN AZURE/PALO ALTO WE CAN NOT CREATE IT.
#
####### Azure / Palo Alto limitation ###########
#
#For an HA configuration, both HA peers must belong to the same Azure Resource Group. 
If you deploy the first instance of the firewall from the Azure Marketplace, and must use your custom ARM template or 
the Palo Alto Networks sample GitHub template for deploying the second instance of the firewall into the existing Resource Group. 
The reason you need a custom template or the Palo Alto Networks sample template is 
because Azure does not support the ability to deploy the firewall in to an Resource Group that is not empty.
please refere this link for more#
https://docs.paloaltonetworks.com/vm-series/9-0/vm-series-deployment/set-up-the-vm-series-firewall-on-azure/configure-activepassive-ha-for-vm-series-firewall-on-azure.html

##################################################
