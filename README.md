# VM-created
Firstly to create a Virtual machine ,you must known about the IOT service of Terraform
To create a Virtual Machine we required this thing i.e.,
1.Configure the Azure provider
2.Creating a new resource group
3.Creating a virtual network
4.Creating a subnet
5.Creating a public IP address
6.Creating a network interface
7.Creating a ip
8.Creating a virtual machine
9.Creating a storage os disk
10.Creating a image reference
11.Creating a profile credentials
And after this we must save
while you are writing a code you must need to install the Terraform and initialize the file with the command called
#bash(1) 
  `terraform init`  -->CMD
--After excuting it will show like this--
Initializing the backend...
Initializing provider plugins...
Terraform has been successfully initialized!
You may now begin working with Terraform. Try running "terraform plan" to see  
any changes that are required for your infrastructure. All Terraform commands  
should now work.
If you ever set or change modules or backend configuration for Terraform,      
rerun this command to reinitialize your working directory. If you forget, other
commands will detect it and remind you to do so if necessary.
#bash(2)
  `terraform plan`  -->CMD
--It will ask for Azure Login Account in refering to command of `az login` and redirect to azure page in selected browser--
--Apply the the credentials to continue--
--And then write the bash2 cmd--
#bash(3)
  `terraform apply`  -->CMD
 --This cmd ask YES to verify the action to perform, simply say yes and then the VM will be created in your Azure account--
If you want to connect with your Virtual Machine download the RDP file which it recommend while starting-Connect in account,
apply the ip address in remote desktop connection, user id , password too to connect 
#bash(4)
  `terraform destroy` -->CMD
--Destroy the Virtual Machine after creating if need and above is the cmd for destroy--
------------------------------------------------------------------------------------------------------
