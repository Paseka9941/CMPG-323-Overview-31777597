# CMPG-323-Overview-31777597

## Repositories That will be created
Project 1- Repository about Agile and Scrum
Project 2- Repository about API development
Project 3-Repository about Standards and patterns
Project 4-Repository about Testing and RPA
Project 5- Repository about Reporting and monitoring


### Diagram
![ActivityOnArrow (1)](https://user-images.githubusercontent.com/110164074/184349799-bf56a171-856d-4620-867e-306086e753c8.png)

#### Branching Strategy
The branching strategy that i will use is GitFlow whereby   i will interact with a version control system for writing and managing code.

##### Use of .Giltmore
When making commits to each repository, i will choose the files i  want to stage and then i will commit them.
But i might not want to commit every single one of my files—there are files that never need to get committed. This is where the .gitignore file is useful: it tells Git exactly which files to ignore and never track.

###### Storage of credentials and sensetive information
By default, the git credentials in the “store” mode will be stored in the
“.git-credentials” file in the user’s home directory (~/.git-credentials)

In Windows the path is C:\Users\<username>\.git-credentials
In Mac and Linux the path is /Users/<username>/.git-credentials




# CMPG-323-Project-2--31777597
In this project we are going to show why APIs are useful for more than accessing information for data-driven decision-making we have three tables which are categories, 
devices, and zones. In our project we have built APIs where we can build programs that run GET, POST, and DELETE on the data the server is hosting and transform that 
information into a different, usable format. 
APIs are meant to improve information security and the ease with which you can access the data you need to make well-informed business decisions. Since an API is a 
communication tool in our project, we have a user which is the person that makes requests, the computer that sends the requests to the server and the server responds to 
the request. In our project the user firstly must register, after registering by entering their credentials including an email after doing so the user needs to login 
using those credentials after that the user will receive a token and can use that token to execute specific actions. The user can access the data of devices by using GET 
which will retrieve device from the database based on the ID parsed through, can access the data of zones by using get which will retrieve one zone from the database 
based on the information parsed and can access categories data by using GET which will retrieve all categories. The user can POST to create new category, device, or zone 
entry. And the user can use delete to delete existing category, device, or zone. The user can use another GET which retrieve all devices within a specific category. And
the user can use GET return the number of zones that are associated to a specific category. 

End Points

![323](https://user-images.githubusercontent.com/110164074/189750399-264fd053-6f8c-4287-993b-55b1db7b27c3.PNG)


![323(1)](https://user-images.githubusercontent.com/110164074/189750949-c9b02839-98c6-440c-a737-b433795a1b63.PNG)

  
  
  # CMPG-323-Project-3--31777597

The purpose of the Device management project is to manage the clients devices
![prj1](https://user-images.githubusercontent.com/110164074/193038030-0eddaef4-59ae-4ef4-9d96-72c37d330d67.PNG)
Ubove is the  home page of device management

![prj2](https://user-images.githubusercontent.com/110164074/193038750-4d71ea33-255d-4f31-b6c5-a29fdcfafda2.PNG)
Above shows that the user can register by using their email and credentials

![prj3](https://user-images.githubusercontent.com/110164074/193038994-284f1cd5-1df5-4ddc-8df7-7208728c5334.PNG)
Above shows that the user registered successfully and can log in 
![prj4](https://user-images.githubusercontent.com/110164074/193039296-26d6e3c6-b9f5-4374-b65e-5e8a1cd3b0e7.PNG)
The user has logged in

![prj9](https://user-images.githubusercontent.com/110164074/193039571-0d19056a-5d0c-481e-b52d-2cb3fdfeb5bf.PNG)
The user creates a category

![prj10](https://user-images.githubusercontent.com/110164074/193039743-0a150da4-ca2d-4fc5-91fe-6251b8ce8b23.PNG)
The user has created a category

![prj11](https://user-images.githubusercontent.com/110164074/193039901-5dc241a8-089f-4f36-ac8f-d169fd60de04.PNG)
The user can view category details

![1](https://user-images.githubusercontent.com/110164074/193040102-99a5d74d-a2d9-4d3c-94ad-5acc884043e1.PNG)
The user can edit a category

![2](https://user-images.githubusercontent.com/110164074/193040229-28119001-f9f0-4bf8-90c2-cdca96339ecb.PNG)
Category has been edited

![3](https://user-images.githubusercontent.com/110164074/193041291-39a7f6fc-4135-4610-9f95-962fa4adecb7.PNG)
Testing if the client can delete category

![4](https://user-images.githubusercontent.com/110164074/193041490-cd48885c-78cf-42d0-ba8d-3a6b851bb0fa.PNG)
Confirming the deletion of category

![5](https://user-images.githubusercontent.com/110164074/193041620-b2d825a3-d8fd-4ac8-b3a0-d488db5e8350.PNG)
Category has been deleted

![prj12](https://user-images.githubusercontent.com/110164074/193041867-e05ad181-255a-4d54-ba5d-70b4741648a0.PNG)
Creating a zone

![prj13](https://user-images.githubusercontent.com/110164074/193042024-dc76f8b0-4920-4064-aad0-0e550f975833.PNG)
Zone has been created

![prj14](https://user-images.githubusercontent.com/110164074/193042271-3579942b-a4c3-42cb-8a4b-3db7cb509c49.PNG)
Editing a zone

![prj15](https://user-images.githubusercontent.com/110164074/193042464-f6faf9f7-6702-4eab-806b-f1391f6287c2.PNG)
Zone has been edited

![prj16](https://user-images.githubusercontent.com/110164074/193042758-fcc93345-0395-4b84-81ee-4da610f0d178.PNG)
Confirming a zone delete

![prj17](https://user-images.githubusercontent.com/110164074/193042989-b6f274b0-2f03-492b-8614-f24010ebf362.PNG)
zone has been deleted

![6](https://user-images.githubusercontent.com/110164074/193043642-3faaabdd-868b-4084-bc3c-bb0162953cb0.PNG)
Creating a device

![7](https://user-images.githubusercontent.com/110164074/193043846-a5bf69ed-5e02-4836-97b6-f53f6f4fad17.PNG)
device has been created

![prj19](https://user-images.githubusercontent.com/110164074/193044056-5bfe19f5-62a1-4bec-aea5-e1d1f9907461.PNG)
Edit a device

![prj20](https://user-images.githubusercontent.com/110164074/193044230-c85d9e3d-c23b-4038-bff6-e9eeb5f19ce4.PNG)
Device has been edited

![prj21](https://user-images.githubusercontent.com/110164074/193044369-e31aa3af-48be-45d7-8e09-efb38c090d30.PNG)
View Device details

![prj22](https://user-images.githubusercontent.com/110164074/193044522-93e85398-ffcd-4ec9-a834-7a55469d7982.PNG)
Deleting a device

![prj23](https://user-images.githubusercontent.com/110164074/193044709-004a2c89-005e-4803-aadd-344b10c97ee1.PNG)
Devive has been deleted
  
  
  # -CMPG-323-Project-4--31777597

We where given a Connedcted Office Management Site and we have to create an automation tool that will help the user in various ways.

The first thing the automation will do will forcefully open a specific browser.
The next thing that will take place is that the tool will automaticallly login using the user's credentials given that the credentials exists in the system.
The tool will then click the zone button through which the tool will tap the "+" sign where the tool will then type into the Zone Name and Zone Description  after doing so the tool will click the create button which will create Zone Name and Zone Description , the tool will then click the back to list where it will show created data.
The tool will then click the categories button and the tool will create category data same as it created the zone data. The tool will then click the Device button where through which it willl click the "+" sign also after that it will type into device name and it will select Category ID aswell as Zone ID , then it will indicate the status depending on wether the checkbox was checked or not then it will click the go back to list. Then the tool will will edit the data it entered by clicking the pencil icon. After that the tool will show the details Zones, Categories and Devices by reading them individually This takes place when the eye icon is clicked by the tool.The tool will then delete all the data entered individually so till everything is empty. If Configured properly the tool will save the time of the user or that of the company maximising the performance. For each of the above functions  There are test results which chnage the COnjnected Tested Data from FALSE to TRUE 
  
  # CMPG-323-Project-5---31777597

![high metrics](https://user-images.githubusercontent.com/110164074/200365991-5c6031f4-5f77-43ef-b837-750e3f10e9ce.PNG)

High-Level Metrics is a  summary view that shows business stakeholders a high-level view of the ‘important’ data such as number of devices, number of zones , number statuses, number of categories and so on as it shows in the image above.

![device regist](https://user-images.githubusercontent.com/110164074/200366326-125dfadb-4bcd-47b4-a65c-c8865200dc88.PNG)

Device registering the above image shows important details regarding device registration

![device monitoring](https://user-images.githubusercontent.com/110164074/200366677-89dfaa20-181e-40ee-b704-8c6a8f16ec91.PNG)

Device monitoring the above image shows how stakeholders can monitor the devices  

  
  
  
