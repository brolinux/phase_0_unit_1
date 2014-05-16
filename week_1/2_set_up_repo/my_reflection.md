## 2. [Open Source and Repo Setup](2_set_up_repo/readme.md) Reflection

* Explain how to create a repository on GitHub and clone the repository to your local computer to a non-technical person
* Describe what open source means
* What do you think about Open Source? Does it make you nervous or protective? Does it feel like utopia?
* Assess the importance of using licenses
* What concepts were solidified in the challenge? Did you have any "aha" moments? What did you struggle with?
* Did you find any resources on your own that helped you better understand a topic? If so, please list it.

<!-- Add your reflection here. Remove the comment markers -->

* Explain how to create a repository on GitHub and clone the repository to your local computer to a non-technical person

First thing to do after opening a free account with github, is install git on your machine by going to thsi URL: http://git-scm.com.
Once fully installed, you can locate your git folder by typing 
$ which git 
Your Unix/Linux terminal window will show where git was downloaded to, so inside terminal change directory until you're inside the git folder. 
Once inisde your git folder, type into terminal window 
$ ssh-keygen -t rsa -C "your_github_email_aaccount_address@example.com.

Now that you have generated your ssh key through git, it needs to be linked to github.
This is done by going to github.com entering your account with the email and password and going into Account Settings at the upper right corner. Under Account Settings you'll find SSH KEYS option. Click on SSH KEYS and github will ask you enter the SSH key you generated moments ago. Paste the whole string and save it iin github, and now you have linked your pc to your github account.
Go back to your pc and change into a directory you want designated as a github reposity. In terminal window enter the command:
$ git init
This now tells git to start keeping track of the changes that are created inside the chosen folder.
Now when you type into terminal:
$ git status
and then type:
$ git add
and then type:
$ git commit -m"some personal reference text"
your changes should show up inside github, thanks to the ssh key that was generated and linking your git directory to your github account.
