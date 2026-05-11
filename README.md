# DevOps Project

Version control is a tool used to track modifications that have occurred in the program. It lets you save various versions of a project, and roll back to previous versions if something went wrong. I used a text editor to create a README.md file and Git and GitHub to establish a repository and push my project online on this assignment. In this paper, I am going to discuss what I learned about version control, DevOps, and how they can work together.
The one big thing I read through for Week 1 was about how DevOps and version control goes together. Essentially, DevOps emerged from the problem of contradictory goals between development and ops teams, as they were often working in isolation, leading to slow releases and numerous issues that arose as a result, Kim, Humble, Debois, and Willis (2021) said. If software development teams share tools such as version control, they will produce software faster with a smoother process. Version control isn’t just about saving code, it's about making teams more effective and communicating more easily.
I used the version control system 'git' for this. Loeliger and McCullough (2022) describe Git as a distributed system, meaning that all of the developers will have the entire project history stored on their local computer. It's useful since you can develop on your own branch, experiment, and only merge your branch into the main project when you're ready. Also, when one person makes a wrong move, it will not immediately be replicated for the others.
The site I used to upload my project was GitHub. According to Chacon and Straub (2014), GitHub is a site that is built upon Git and provides additional functionality, such as pull requests, issue tracking, and code reviews. The advantages of these features is that it helps the team members to see the work of the other team members easier and helps organization in the project. In this assignment I have made a public repository on github, to access and review the project easily.
Teams that adopt DevOps practices, such as version control, are significantly better than those that don't, as reported by Forsgren, Humble and Kim (2018). They found that these teams have more rapid deployment and fewer failures in their deployments. That made me realize that knowledge of Git and GitHub is crucial as part of this class and as a software worker.
Setup Process
Screenshot 1: To check version of GIT and GitHub CLI and log in to GitHub interactively.
To view version of both GIT and GitHub-cli and log in account to GitHub on terminal interactively. First I ran git --version and gh --version in the terminal, making sure that Git and the GitHub CLI are installed correctly. Both tools were confirmed as being ready to use. Then I typed gh auth login to log in my terminal to the GitHub account. It did open a browser window, and I was able to log in there, after which I was able to log into my terminal without a password every time after that.
Screenshot 2: Making a Public repository and cloning it locally.
Then I use gh repo create devops-project --public to create a new repository on GitHub, which is public by default. This resulted in a public repo named devops-project on Github. I then copied it onto my computer via gh repo clone and opened the folder in visual studio code. This step made my own computer linked to the online computer database, so that the files could be added.

Screenshot 3: you can see the repository in VS Code and on GitHub.
Once I had created and cloned the repository I have checked if the setup is okay or not. In my browser I looked at GitHub and saw devops-project in my list. It was also possible to access it in Visual Studio Code from the GitHub extension. Moving on was important at this point because this confirmation proved that the local and remote sides were properly connected.

Screenshot 4: The README.md file is created in Visual Studio Code as shown 
I created a README.md file in Visual Studio Code inside the folder of the project. I gave it a heading and wrote a short description of the project. A README file is a convention of software development that assists other people to understand what the software is without having to go through the code, according to Spinellis (2012). Markdown format was chosen, because it is a format that is nicely rendered as text on the page of the repository in GitHub.

Screenshot 5: Staging, committing and pushing the README.md file to GitHub.
The last step was to upload the README.md file to GitHub. I staged all the files with git add . and committed them with a short message, git commit -m "Initial commit". Lastly, I pushed all of my work to Github by typing git push -u origin main. Once the push was done, I could see the README.md file in the GitHub page so all was well.



Conclusion
This was a practical exercise as an introduction to the tools and methodology used in modern software development. It became familiar to them through hands-on practice with the mechanics of setting up Git, creating a GitHub repository, writing documentation and pushing code to a remote host. The reading reinforced these hands-on experiences by putting Git and GitHub into the context of the larger DevOps movement. Staging, committing and pushing changes are skills that will be used in further tasks to enable more complex collaboration and automation process.

