# Terraformassignment
@@ -1,4 +1,4 @@
# cloud computing assignment EC2 creation through terraform images included for reference
# cloud computing assignment EC2 creation through terraform;images included for reference
configure CLI and terraform  run the following code 
<br />
to store the terraform state in local system exclude the following code in main
@@ -21,7 +21,9 @@ run the following commands in terminal
<br />
![](images/cc1.png)
<br />
2.terraform apply -var="instance_name=name_from_cmd1" (for overriding instance name through command line)
2.terraform plan(it will determine the desired state of all the resources it declares, then compares that desired state to the real infrastructure objects being managed with the current working directory and workspace.)
<br />
3.terraform apply -var="instance_name=name_from_cmd1" (for overriding instance name through command line)
<br />
![](images/cc2.png)
<br />
@@ -62,7 +64,9 @@ run the following commands in terminal
<br />
![](images/cc6.png)
<br />
2.terraform apply -var="instance_name=name_from_cmd2" (for overriding instance name through command line)
2.terraform plan(it will determine the desired state of all the resources it declares, then compares that desired state to the real infrastructure objects being managed with the current working directory and workspace.)
<br />
3.terraform apply -var="instance_name=name_from_cmd2" (for overriding instance name through command line)
<br />
![](images/cc7.png)
ec2 instance named "name_from_cmd2" will be created and a bucket named"terrabackendassignment" will have the terraform state.
