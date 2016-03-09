# Create a Virtual Machine from a Windows Image with 4 Empty Data Disks

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fgithub.com%2Fjimyjohny%2Fazure-quickstart-templates%2Fsoftnas-cloud%2Fazuredeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>
<a href="http://armviz.io/#/?load=https%3A%2F%2Fgithub.com%2Fjimyjohny%2Fazure-quickstart-templates%2Fsoftnas-cloud%2Fazuredeploy.json" target="_blank">
    <img src="http://armviz.io/visualizebutton.png"/>
</a>

This template allows you to create a Windows Virtual Machine from a specified image during the template deployment and install the VM Diagnostics Extension. It also attaches 4 empty data disks. Note that you can specify the size of each of the empty data disks. This template also deploys a Storage Account, Virtual Network, Public IP addresses and a Network Interface.

NOTE: The configuration of the VM diagnostics extension relies on a Base64 encoded string for the xmlConfig. This configures a basic set of counters, including CPU and Memory. 

