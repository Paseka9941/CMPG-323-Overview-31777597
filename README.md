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



###Project 2
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

