### Steps to run the app
1. Clone the repository
2. Run **pip3 install -r requirements.txt** under the root directory of the project
2. Go inside the app directory and run **python3 main.py**
3. Console will prompt you to enter the choice of operation
4. Enter the choice of operation that you want to perform

### Config
Provide the json file name in the config.yaml file under the config folder.

### Datastore
Datastore used here is a simple json file. The file is created under the datastore directory of the project.
The same file name has to be referenced in the config.yaml file

### Operations supported:
1. Add contact
2. Search Contact by name
3. Update contact by phone number
4. Delete contact by name
5. List available contacts
6. Filter contacts by tag (Eg. Colleague, Family, Friend, etc.) 

**Note:** It is ensured that there won't be any duplicate contacts in the contact list. If there is any contact
with the same name already exists, it will prompt the user to enter a different name.

### Python version - 3.10
