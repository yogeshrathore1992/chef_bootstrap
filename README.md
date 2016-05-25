# chef_bootstrap


# Multiple Nodes Bootstrap
Objectives


Bootstrap  multiple new node 
Use knife ssh to rerun chef client
Acceptance Criteria

ALL instances bootstrapped with knife bootstrap.
Second instance running haproxy l
Answer questions


Unless you did so in the previous exercise, download the script from here.

# Steps

1. Download the script file 

2. save the file into chef-repo directory 

3. Firstly you have to choose that all hosts have password or .pem file based Authentication you simply type pass or pem 

4.


Use knife ssh to run sudo chef-client on all nodes with the role base applied directly to the run list.

Use knife ssh to report the uptime of all nodes with the recipe webserver appearing anywhere in the run list 

# Questions



How many nodes have HTTP traffic balanced by haproxy?

What other attributes does the haproxy cookbook have?

The haproxy cookbook has a default recipe. How does it differ from the app_lb recipe?

How many nodes are running Ubuntu?

What is the run list of all the nodes? What option shows only the run list from node results?

What is the node name of systems that are webservers?

Do any roles have a recipe from the apache2 cookbook in their run list?

Do any nodes have a recipe from the apache2 cookbook?
Its a multiple node bootstrap script , you can use for bulk bootstraping 
