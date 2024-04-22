# How to do the assignment?
Download the [VM](https://drive.google.com/file/d/1H44wqBTilNhuIShEvsnqF9xdWNl4jnBH/view?usp=drive_link) I already created for you and import it into VirtualBox or VMWare Workstation.
If you don't know how to import the VM, please read about it online as there are plenty of resources online.
Once you imported the VM successfully, open terminal and look for cs790 repository and navigate to "exercises" folder for further information. 

# What's inside the VM?
Many things! It already has [mininet](https://mininet.org/) installed which allows you to create a virtual network. Also, it has [bmv2](https://github.com/p4lang/behavioral-model) installed on it which is a software-based programmable switch. In other words, we will use Mininet to create a network of devices while the switches in that network are programmable (using BMV2). 

# Your task:
You need to write a P4 code that runs on the BMV2 swithces and does the required task. have questions about P4? See the PDF I uploaded here. 

# Turning in:
You need to upload the successful ping output between two machines for basic exercise and you need to upload the packets arrived at the destination (either screenshot or .pcap file) that have ecn 0x3 on them for the ECN exercise. Of course you need to upload your p4 codes as well. Thus, you need to turn in the same folder of exercises with completed p4 codes along with the files I mentioned above. 
# Grading:
There are 3 exercies to do. Basic and ECN are mandatory and load balancing is optional. You will get extra credit if you do the optional exercise. 50 points for each of basic and ECN exercises. 


