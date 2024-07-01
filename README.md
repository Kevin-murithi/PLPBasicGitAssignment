# PLPBasicGitAssignment

Requirements
    A GitHub account
    Git installed on your local machine
    A code editor of your choice (e.g., Visual Studio Code, Sublime Text)

Steps

    Task 1: Repository Setup
        1. GitHub Repository Creation
            i) Log in to your GitHub account
            ii)Go to GitHub and log in with your credentials. If you don't have an account, create one.
            iii) Create a new repository
            iv) Click on the "New" button in the repositories section or go to Create New Repository.
            v) Repository details
            vi) Repository name: PLPBasicGitAssignment
            vii) Description (optional): A brief description of the repository.
            viii) Public/Private: Choose whether you want the repository to be public or private.
            ix) Initialize the repository with a README file: Check the box for "Add a README file".
            x) Click the "Create repository" button.
    
![alt text](<Screenshot 2024-07-01 172511.png>)   

    Task 2: Local Setup
        2. Local Folder Setup
            Create a new folder on your local machine
            Name the folder PLPBasicGitAssignment.
            
![alt text](<Screenshot 2024-07-01 172632.png>)
            
            Open a terminal or command prompt
            Navigate to the newly created folder using the cd command.

![alt text](<Screenshot 2024-07-01 173241.png>)
        
        3. Git Initialization
            Initialize a new Git repository
            git init

![alt text](<Screenshot 2024-07-01 173328.png>)

        4. Connecting to GitHub
            Link your local repository to the GitHub repository
            git remote add origin <repository-url>
            Replace <repository-url> with the actual URL of your GitHub repository, which you can find on your repository page on GitHub.

![alt text](<Screenshot 2024-07-01 173554.png>)

    Task 3: Making Changes
        5. Create a File
            Inside your local folder, create a new text file
            Name the file hello.txt.

![alt text](<Screenshot 2024-07-01 173737.png>)

            Add a simple text message
            Open the hello.txt file in your code editor.
            Add the text: Hello, Git!

![alt text](<Screenshot 2024-07-01 173803.png>)

            Save the file.
        
        6. Committing Changes
            Stage the changes
            git add hello.txt

![alt text](<Screenshot 2024-07-01 173840.png>)

            Commit the changes
            git commit -m "Add hello.txt with a greeting"

![alt text](<Screenshot 2024-07-01 173923.png>)

    Task 4: Pushing to GitHub
        7. Pushing to GitHub
            Push the committed changes to your GitHub repository
            git push -u origin main

![alt text](<Screenshot 2024-07-01 174521.png>)

    Task 5: Verification
        8. Verify on GitHub
            Visit your GitHub repository in a web browser
            Go to your repository page on GitHub.
            Confirm that the hello.txt file and commit message are visible
            You should see the hello.txt file listed, and if you click on it, you should see the text "Hello, Git!".

![alt text](<Screenshot 2024-07-01 174554.png>)