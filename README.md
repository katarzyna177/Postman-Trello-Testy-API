# Postman-Trello-Testy-API

Project name: Cherry-IT: COLT 1/2023
led by Anna Czyrko (https://www.linkedin.com/in/ania-czyrko-05933aa1/)

##Trello REST API testing with Postman

💁 About project
COLT is a 4-week test project organized by Cherry IT. During the project, I gained knowledge about the REST API and got to know the Postman tool. I created my own collections based on Trello technical documentation. I practiced GIT and Github.

☑️ getting to know the basic knowledge of REST API 
☑️ getting to know the Postman tool 
☑️ creating my own collections based on Trello documentation
☑️ learning to report bugs
☑️ learning to create test cases
☑️ learning GIT and getting to know GitHub


Trello API documentation

Trello REST API tests done in Postman during the project:

🔎 Test scope based on Trello API documentation
Board
Create a Board
Get a Board
Update a Board
List
Create a List on a Board
Get Lists on Board
Update a List
Archieve all Cards in List
Card
Create a new Card
Get a Card on a Board
Update a Card
Checklist
Create Checklist on a Board
Get Checklists on a Board
Create Checkitem on Checklist
Delete
Delete a Checklist on a Card
Delete a Card
Delete a Board
🚀 Getting started
📌 List of steps needed to run collection and tests
1️⃣ Postman installation

2️⃣ Creating a Trello account

3️⃣ Trello authentication

4️⃣ Importing a file into Postman

5️⃣ Creating environment variables in Postman

6️⃣ Run collection and testing

💻 Postman installation
Go to the Postman website and click the orange button with name of your operating system.
Download the installation file, then run the installer and follow the instructions that appear.
Postman is ready to use.
📅 Creating a Trello account
Go to the Trello website and click the blue button with text "Get Trello for free".
Create a Trello account by following the instructions that appear.
Your Trello account is ready to use.
🔑 Trello authentication
Log in to your Trello account.
Go to the Trello developer API key generation page.
Click on the "Go to the Power-Up Admin Portal", then click "Create New Key" button and enter the required details.
Your API key will be displayed on the page. Copy and save it for later use in Postman.
Next, click on the Token link that appears under the key you just generated.
Allow application to access your Trello account.
Your token will be displayed on the page. Copy and save it for later use in Postman.
📂 Importing a file into Postman
Go to my Postman collection file.
Click on the three dots icon in the top right corner and click "Download".
Run Postman and click on "Import" button in the top left corner.
Drag and drop the downloaded file from the Download folder into the "Import" window.
The collection will appear in Postman, ready for use.
🌍 Creating environment variables in Postman
Click on the "Environment" dropdown in the top left corner in Postman.
Click on the "New" button to create a new environment and choose "Environment" icon.
Give your environment a name.
Create a "key", "token" and "baseURL" variable. You should enter the value "https://api.trello.com/1/" into the "baseURL" variable and the value of your key and token in the "key" and "token" variable. For collections from this repository, the API key variable is named {{key}}, the token variable is named {{token}} and the URL variable is named {{baseURL}}.
Click "Save" button to save the environment.
Click on the "Environment" dropdown in the top left corner and select the environment you just created.
🏃 Run collection and testing
Click on the "Collections" icon in Postman.
From the list of collections, select the one named "Trello - REST API" and click on the icon with three dots that appears when you hover over the collection name.
Select "Run collection" from the list.
Click one the orange button "Run Trello - REST API".
👇 If the view in your Postman looks like the one on the screenshot below, then you have successfully completed all the steps and run my collection. CONGRATULATIONS! 👏
2023-05-21_17h00_40
