# Organization and Project Background:
We are TurnerMart, we serve around 500-700 customers a day. We serve groceries, home items, medication and beauty products.  
We serve food to our customers who are usually around the local area of Morden.  
We will usually have a max of 250 users on our network at a singular time.  
The new wireless network is needed because our company has recently expanded from 100 customers at one time to 200. Our wireless network is not prepared for the expansion of our building and the increase in customers.  
Our current problem is at peak hours the network is very slow and some devices cannot connect to the network at all. In the new expansion area of our building the wifi frequently cuts in and out.  

## Project Objectives:

Reliable wireless coverage has to be better than it is now. In a lot of spots in our store we do not have network coverages or the wifi signal is very week due to the expansion of the store.  
We need better performance out of our network and in the expansion part of our building we need better coverage in that portion of our store. We will also need to update the current wifi coverage in the exsisting store because in some spots the wifi   cuts out.  
We also need better security in our network. Our main network that the employees use and the wireless network is not the same subnet. We would like to segement our network into multiple subnets and VLANS to protect our internal network that   employees use. We would also like to integrate some ACL rules so that our customers cannot access inappropriete websites and reduce bandwidth so customers can't download or upload anything so, they have less power.  
If our network bandwidth slows down or if any network components slows down or overheats we would like to implement a network and server monitoring to know what is going on with our equipment.  
Our network should be designed in a way that furture network growth is in mind.

## Scope of Work:
We have lost the documents to our original wireless site survey. The store will have to be re surveyed for the wireless network coverage. We know some spots do not have signal coverage.  
The access point placement will be on the bottom side of the roof so that it is visiable in the store. We will be using the the 2.4 GHz because we need the signal to penetrate the shelves of food. We would like the access points to be 10 to 15   meters away, in particular we would like about 10-20% overlap so there is not random cracks in between the access points without internet access.  
Before installation we would like the access points to be fully updated and documented. When installing the access point first clean the roof where the access point will be. When installing the access point lie it flat against the roof and string   the cat 6 ethernet cables into the roof to connect to the main network closet.  
After stringing the ethernet cable to the roof it should travel to the network closet where we have our network equipment. Once it gets to the right area on the roof attic you can string it down to a switch.  
Our security configuration will be wpa-3 personal, we do not have a radius server to authenticate users at this current moment so we are forced to go with the personal.  
To validate or test the network we will give you access to the network so ping or traceroute commands can be performed.  
On our central server we have made a file server and IT-help will have access to the shared file on either their devices or we can give them laptops to access the file server.  
We would be interested for ongoing support after IT-help is done with configuring the wireless network for basic maintenance and support for out wireless network.  

## Technical Requirements:
Our current environment is using wi-fi 5. We would like to increase our router to the newer model being wi-fi 6. Wi-fi 6e is to expensive for what the benefits is for us so, we will skip it for now.  
The authentication protocol we would like to upgrade to will be wpa3- personal. Currently we are running wpa-2 personal which in this current environment is outdated and needing an upgrade.  
We want to isolate the the guest network from the main employee network. For the guest network we would like to use a /23 network. This allows 510 IP addresses which more than enough.  
We would like to implement VLANS on our guest network. We would like a guest, management, data and voice VLAN.  
Priviously We were going to create a monitoring systems. We would also like to implement a reporting system based on the monitoring system as well.  
We would like the network to be scalable. In the future we might upsize again if we continue to grow so, we requrire the network to be scalable.  
We expected around 250 users/device as a max during peak hours typically around 200-215 as a baseline average.  

## Deliverables:
Site survey report:  
Pick a spot to put the access points based on a heat map range  
run wires through the attic towards the switch in the network closet  
confirm the access points turns on and gives out the wifi signal  
Configure the SSID and password to match main router  
Create subnets to seperate guests and employee network access  
Create VLANS on the guest network to segment the individual proccess on the network  
check the heat map to confirm that all places in store has connection to access points  
confirm the access points work and pinging the internet is possible  

## Wireless network design:
Our wireless network will be connected by the users via the access points being set up. The user will be put into their own VLAN so they do not have connection to any other important process on the employee network.  
Installed and configured access points
We want a total of nine access points installed on the inside roof of the store. We would like it to be set up in a way where each part of the store has access to the network and have a strong connection.  
Network diagram
Our network diagram will consist of the access points and the location of each access point. The diagram will show the exact route the cables go to the main networking closet. It will include a logical, physical and ip route/table .  
## Test results:
Connecting to each access point will give the user internet securely  
##Administrator guide 
First document the Mac address and IP address for each access point.  
Update each access point so the firmware is in the correct version  
Complete the configuration so the access point can work as intended  
string all of the wires the access points needes to work ex: power and ethernet cable  
Install the access point onto the inside of the roof of the building  
plug the access point to the previously configured wire  
test on confirm that the access point installed fully works and gives the right signal and users can access the network and internet.  
## Support plan  
We have a support plan for the network administrators, we have air conditioning in the building, there is washrooms that they can use and there is a water perifier so they can get water. We also have a breakroom with a fridge and microwave so the administrators can refridgerate food and heat it up while sitting down.  
Timeline and Pricing:
The network administrators will have three days to complete the project and test to see if the access points function as intended. THe pricing will be $1000 a day to complete it.  
Proposal deadline: 7/31/2026  
Vendor selection date: 8/1/2026  
Project start date: 8/20/2026  
Installation and testing period: 8/20/2026 and 8/23/2026  
Project completion date: 8/26/2026  
Initial and ongoing costs: Initail: $5000 Ongoing: $300  

Evaluation Criteria:
Category: 	Weight
Technical solution: 40%
Security: 25%
Implementation plan: 10%
Vendor experience: 10%
Price: 15%
Total 	100%

Submission and Terms:
We expect submissions to be in by 7/31/2026 and we would like a breakdown of the person or team who is doing the installation what their credentials are and why they were chosen for this particular job.   
Submission format  
The submission format will be in portable document format.  
Contact information  
If you have any furthur inquires about the network or about the proccess contact 111-111-1111 for support or help.  
Late-submission policy  
If any documents are late or not on time the contract will be terminated and we will not go through with creating the infraustructure with your team/company.  
Confidentiality  
We expect that the network information and confidential information about our processes to be respected and not shared or distributed to any company, agency or persons.  
Support expectations  
We expect that basic IT support will be offered if the network goes or if an IT related problem occurs before the 8/31/2026 date.  
Change-control process  
We expect at 8/31/2026 the change-control process will occur giving us full access to the network and issue regarding the network will be delt by our company.  
Contract duration  
The contract will be from 8/1/2026 to 8/31/2026.  
