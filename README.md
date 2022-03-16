<h1># Lab2-Ansible </h1>
This repo is used to configure 2 Palo alto firewalls. Both firewalls will then connect to a core router. 
The repo will contain Ansible playbooks that will grab facts about the topology to create a audit report very quickly, this repo will also contain playbooks that are used to configure the PA firewalls. 
This repo will contain the diagram of the network, playbooks, descriptions of the playbooks and how the network is deployed. 


<h2> Network Topology </h2>

![Network-Topology](https://user-images.githubusercontent.com/52250306/158625786-12b7afa1-688a-4e7c-be94-35b28b8a7b0e.jpg)

<h2> Collection Ansible-Galaxy </h2>
This repo will use the collection Ansible-Galaxy, to configure and grab facts about the network. 

<h2> Provider Module </h2>
All Ansible network modules implement the _provider argument_ which is a collection of arguments used to define characteristics of how to connect to the networking device. This repo will pull the variables needed for the provider argument inside the host_vars folder. 

<h2> Set the hostname/dns servers/NTP servers, and Panorama primary and secondary </h2>

![image](https://user-images.githubusercontent.com/52250306/158626262-9a654572-d83b-44f2-89e8-ffeefdf60843.png)

<h2> Configure sample HTTPS firewall rule </h2> 

![image](https://user-images.githubusercontent.com/52250306/158628197-ef0c192b-e09c-4624-b5d8-16e4316e9d23.png)

<h2> Grab facts about PA firewalls </h2> 

![image](https://user-images.githubusercontent.com/52250306/158628467-c255c36c-17d6-44cb-8d61-f9a525682963.png)
