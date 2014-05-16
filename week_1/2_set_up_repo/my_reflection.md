## 2. [Open Source and Repo Setup](2_set_up_repo/readme.md) Reflection

* Explain how to create a repository on GitHub and clone the repository to your local computer to a non-technical person
* Describe what open source means
* What do you think about Open Source? Does it make you nervous or protective? Does it feel like utopia?
* Assess the importance of using licenses
* What concepts were solidified in the challenge? Did you have any "aha" moments? What did you struggle with?
* Did you find any resources on your own that helped you better understand a topic? If so, please list it.

<!-- Add your reflection here. Remove the comment markers -->

* Explain how to create a repository on GitHub and clone the repository to your local computer to a non-technical person

First thing to do after opening a free account with github, is install git on your machine by going to this URL: http://git-scm.com.
Once fully installed, you can locate your git folder by typing 
$ which git 
Your Unix/Linux terminal window will show where git was downloaded to, so inside terminal change directory until you're inside the git folder. 
Once inside your git folder, type into terminal window 
$ ssh-keygen -t rsa -C "your_github_email_account_address@example.com.

Now that you have generated your ssh key through git, it needs to be linked to github.
This is done by going to github.com entering your account with the email and password and going into Account Settings at the upper right corner. Under Account Settings you'll find SSH KEYS option. Click on SSH KEYS and github will ask you enter the SSH key you generated moments ago. Paste the whole string and save it in github, and now you have linked your pc to your github account.
Go back to your pc and change into a directory you want designated as a github repository. In terminal window enter the command:
$ git init
This now tells git to start keeping track of the changes that are created inside the chosen folder.
Now when you type into terminal:
$ git status
and then type:
$ git add
and then type:
$ git commit -m"some personal reference text"
your changes should show up inside github, thanks to the ssh key that was generated and linking your git directory to your github account.


* Describe what open source means

Open Source has no proprietary ownership of its code, it's usually found under some variation of an open license. It's available for all who seek it and for all who seek to improve upon it or amend it. It is the backbone of much of the developing web and allows for the free and open exchange of ideas and code. 

* What do you think about Open Source? Does it make you nervous or protective? Does it feel like utopia?

Open source is definitely utopian. Whenever I've had an idea I wanted to share it with others. The web which has recently been stripped of its neutral footing was designed to be platform of free and open exchange regardless of content or band width. My laptop runs on Ubuntu 14.04 which is open source, free and very efficient.

* Assess the importance of using licenses

The licenses are the guidelines under which the creator of the code wishes to have their code shared/used. It's important to respect the terms of these licenses. By downloading them, we are agreeing to their terms and by violating their terms we are prospering an environment of suspicion, distrust and restriction.

* What concepts were solidified in the challenge? Did you have any "aha" moments? What did you struggle with?

I've had one big "aha" moment after the next installing git and github. Prior to this challenge I believed them to be one and the same.

* Did you find any resources on your own that helped you better understand a topic? If so, please list it.

I definitely fell on youtube to explain a lot of this, I also used the github help page which was very visual and easy to follow.
Here is the most helpful Youtube link, but I watched several videos and visited several blogs in addition to this. This took some time to understand and have sink in:
Titled:How to Use Git and GitHub 1: Install Git and Basic Commands 
https://www.youtube.com/watch?v=tRTckrrCME4
