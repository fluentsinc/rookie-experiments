# **Create Commits**

## Commits are messages that you tag to your activity on your Git repository. So if your activity on your Git repository was adding a html file, you would write a commit message "added html file". 


# **Experiment**

### 1. After you've initialized the Git repository, just treat the repository folder as any other folder. Put some file you want to store into the folder. Execute this command only if you've stored something on the repository folder you've created above or it doesn't work: `git add .` Make sure you type the dot that comes after add. Also make sure there is a space between "add" and "." The workflow goes like this: 

- ### Set up everything as in `git/pilot-04`. 

- ### Do everything we do here on Visual Code, not on Windows file explorer. Create a file inside the repository folder and name it "start.js".  Write something inside "start.js" file and save it. 

- ### Open the terminal and enter the command: `git add .` 

### 2. The last step is to write a message that tags a message to your activity of putting something into the repository folder. So if you had put a javascript file into your folder, you would write a message "added javascript message" or any other message you like, it doesn't matter what you write as a message _**as long as**_ you understand the purpose of the message. By tradition, the first message for a Git repository is always "Initial Commit" or "initial commit". You can probably use any other message but as mentioned above, it's tradition to write "initial commit" as the first message. Type this command to create a Git repository with a message: `git commit -m "Initial Commit" Again, watch out for the spaces in the command. Use `git log` to see the commit log for this repository now. You should see the "initial commit" message. 


### 3. After you've created the "Initial Commit" message, you can write any message you like for your next activity. So if your activity on your repository folder was creating a folder named "ignition" and putting a text file named "start", your commit message could be "created ignition folder and start.txt". Let's try to do a commit now. Write any line inside the "start.txt" file you've just created. Now follow the commands below to write a commit message: 

- ### `git add .`
- ### `git commit -m "write any message you like"` inside this quote. So for the example above, you could write `git commit -m "created ignition folder" `

### 4. Make sure you understand the pattern of commands here. 

### To create the Git repository and create the initial commit, you need to follow these commands below: 

- ###  `git init`
- ###  `git add .`
- ###  `git commit -m "Initial Commit"`

### To create commits after the initial commit, you need to follow these commands below: 

- ### `git add .`
- ### `git commit -m "write any message you like"`
