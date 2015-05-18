JBoss JDG_MR Demo Guide
============================================================
Demo based on JBoss DataGrid and EAP products.

Setup and Configuration
-----------------------
See docs directory for details on this project.

For those that can't wait, see README in 'installs' directory, add products, 
run 'init.sh' and follow the instructions given.

0) Download and cCopy jboss-eap-6.4.0.zip and jboss-datagrid-6.4.1-eap-modules-library.zip to the installs dir.

1) Change to the projects/CDRFileGenerator directory, and run "mvn compile exec:java -Dexec.args=n", with n being the amount of CDR records you want to generate.

2) Change back to the root dir and run "init.sh --nodeCount=n" with the amount of nodes you want to create.

3) Access the URL: http://localhost:8080/JDG_MR_WEB/ and play with the demo as instructed in the docs dir.

4) If you want to add new nodes later, you can run "addNode.sh --nodeNumber=n" where "n" is the node number.

Released versions
-----------------
See the tagged releases for the following versions of the product:

JBoss DataGrid 6.4
EAP 6.4