![GeneralAssemb.ly](https://github.com/generalassembly/ga-ruby-on-rails-for-devs/raw/master/images/ga.png "GeneralAssemb.ly")

#BEWD - Working Like A Developer 

###Salman Ansari

Principal Software Engineer, Oracle


---


##Agenda

*	Intros
*	Setup
*	What is Web Development
*	Command Line
*	Git & GitHub

---

##About Me

* I'm a founding engineer of Involver (now part of Oracle)
* I'm a teacher
* I'm a DJ
* I'm a writer

---

##I'm not related to Aziz Ansari.


![NotAzizAnsari](../../assets/misc/azizansari.jpg)

### Sorry.

---

##About your TA's

1. Brooks Swinnerton
2. Brian Fountain

---

##Course Overview

At a high level, we will focus on developing expertise with the following:

* The command line (terminal)
* Git and GitHub (source control)
* Ruby (programming language)
* Rails (web application framework)
* Developer tools & resources


---

##Course Administration

*	What you will get from us:
	* 	In-class labs
	* 	Homework
	* 	Class slides (viewable in GitHub)
	* 	Instructor & TAs!

*	What you need to submit to us:	
	*	At least 80% of all assigned homework
	*	A completed final project


---

##Setup
###Getting Your Dev Environment Ready


This class is using Ruby 2.0 (p195) and Rails 4.0 (RC1). 

If you haven't done so already, please take some time now to get your machine set up. 

View the installation guide here:

-	[tinyurl.com/bewd-install](http://tinyurl.com/bewd-install)


---


##Web Development
###The Web Application Stack

![NotAzizAnsari](../../assets/misc/server-side.jpg)

---

##Web Development
###Back-end vs Front-end Development

Let's define a few terms:

* _Web Development_ -> apps built for the web
* _Front-End Development_ -> client / browser code (HTML, CSS, JS)
* _Back-End Development_ -> server-side code (Ruby, C#.NET)

---



##Work Like a Developer
###Integrate into the developer community

* Choose the right OS, editors, & tools for your projects.
* Leverage the online community's vast libraries and documentation.
* Spread the knowledge you gain, and give back to the community when you can.
* Take pride & and joy in what you work on.
* Be efficient:
	* Use the keyboard as much as possible
	* If you find yourself doing the same thing repeatedly, automate it

---

##The Command Line
###What is it?

The command line is a terminal giving you direct access to your operating system. You can enter simple commands to perform a variety of functions.

Many of the tasks we need to carry out (such as committing our code) are best performed in the command line.

---

##The Command Line
###How do I start?

For Macs:

* Open the "Terminal" app
* For a better experience, download and install "iTerm 2", which is a replacement app that is slightly better.


For Windows:

* Open the "Command Prompt" application
* For a better experience, try "Console" (http://sourceforge.net/projects/console/)

---


![GeneralAssemb.ly](../../assets/ICL_icons/Code_along_icon_md.png)
##Command Line Basics (~20 min)

1. Make a script in bash to create a directory named code. 
2. Change into this folder
3. Create a file, complete, with the contents “Completed the exercise”
4. Change to your home directory
5. Show the contents of the completed file to the terminal
6. Make it executable
7. BONUS: Modify the script in some way to accept arguments.


---


![GeneralAssemb.ly](../../assets/ICL_icons/Exercise_icon_md.png)
##Command Line Exercise (~20 min)

-	Pair program.
-	Make a script in bash to create a directory named lists. 
-	Change into this folder
-	Create a file and use the first argument passed as the name.
-	Insert the contents of the second argument into the file
-	Show the contents of the completed file to the terminal

---


##Work Like a Developer
###Integrate into the developer community

Congrats! You just took your first steps to becoming a developer. Keep it up.

* If you are still a bit lost, don't worry. 
* Practice makes perfect. 
* Take a look at the cheat sheet in the Resources slide at the end of the class for a list of common commands.

---


##Git
###What Is GIT?

* GIT is a source control management tool.
* GIT allows you to store and update your code in a structured way.
* GIT includes history of changes you make, so you can create "checkpoints" and track your work better over time.
* GIT allows multiple contributors to work on the same project, and has intelligence to resolve conflicts between changes committed by different people at different times.
* GIT is smart, but can be tricky.

---

![GeneralAssemb.ly](../../assets/ICL_icons/Code_along_icon_md.png)
##Git Basics (~30 min)

**_1. Adding git to a folder_**

-	Create a folder and change into it
-	Create 3 files config, log, runner.rb
-	Tell git to add this folder as a new repository
-	Tell git to track the 3 files in the repo

---

![GeneralAssemb.ly](../../assets/ICL_icons/Code_along_icon_md.png)
##Git Basics


**_2. Commiting_**

-	Open runner.rb in sublime text
-	Type ‘print “Commited!”’
-	Check the status of the file
-	Look at the difference in the file
-	Tell git it’s ok to commit this file
-	Commit the file
---

![GeneralAssemb.ly](../../assets/ICL_icons/Code_along_icon_md.png)
##Git Basics

**_3. Pushing Changes To GitHub_**

-	Log into Github
-	Create a new repository without a readme named first\_push
-	Go back to your folder and add the remote branch
-	PUSH your code to GitHub

---


##Git vs GitHub

*	<b>Git</b>: A tool used to manage <b>local</b> repositories
*	<b>GitHub</b>: A cloud-based platform used to manage <b>remote</b> repositories

![Using Git](../../assets/GitHub/git_general_diagram.png)

---


##GitHub Forks
###Forks Explained
![ Git In Class Diagram](../../assets/GitHub/fork_Diagram.png)

---



![GeneralAssemb.ly](../../assets/ICL_icons/Code_along_icon_md.png)
##Git In Class (~15 min)

-	Fork BEWDIful repository
-	Clone your copy of the repository
-	Set BEWDIful repository as a remote called instructor:
	-	```git remote add instructor <YOUR GIT REPO URL>```
-	Pull updates from BEWDiful instructor
	-	```git fetch instructor``` then ```git merge instructor/master```
	- 	or just ```git pull instructor master``` (auto-merges)

---


![GeneralAssemb.ly](../../assets/ICL_icons/Exercise_icon_md.png)
## Git It Together
-	Add a .txt file named blog and type your name and the URL to your blog
-	Commit your changes
-	Push them to your repository
-	Submit a pull request for your instructor to access those changes

---


## Homework

-	Create a blog to document your experience
-	Write about your first BEWD class in your blog

---

##Additional Resources: Command Line Basics & Git

##Cheat Sheet

The terminal (command prompt on Windows) is the developer way of navigating your computer. You are probably used to using the graphical interface provided (Finder on a mac and MyComputer on Windows).

Here is a quick reference for some of the most common commands you will use in this class. 
Remember when you see ```“$”``` or ```“C:\>”``` in these notes that is the prompt, don’t type it.

 		$  MAC
		C:\>  WINDOWS
		
---

####Navigation


How do I get into a folder?

  		$cd folder_name
		C:\> cd folder_name

Use quotation marks if your folder name has spaces.

How do I get to the parent folder?

		$cd ..
		C:\> cd ..

How do I see what is in the folder?

		$ls
		C:\> dir


How do I know what folder I am in?

		$pwd
		C:\> cd

How do I create a new folder?

		$mkdir folder_name
		C:\> mkdir folder_name

---

####Deleting - (Proceed With Caution)

How do I delete a folder?

		$rm -r folder_name
		c:\> rmdir folder-name

How do I delete a file?
		
		$rm -f file_name
		C:\> del file_name

How do I move a file?

		$mv file_name folder_name
		C:\> move file_name folder_name
The file is removed from the old location and moved to the new one.

You can rename a file the same way

		$mv old_name new_name
		C:\> move old_name new_names

---

##Tips, Tricks & Motivation

Here are some keyboard shortcuts in the command line to help you keep up (note: not all command line apps support these):

**Tab Completion**: Press Tab to complete folder and file names                                                       

**Control + a**: Go to the beginning of the line                                                                      

**Control + e**: Go the the end of the line                                                                      

**Option + b**: Move back one word

**Option + f**: Move forward one word

**Up/Down Arrow Keys**: Repeats previous commands                                                               

**Control + w**: Delete last word typed

**Control + u**: Delete last line typed

**Control + y**: Paste last deleted item

**Control + l**: Clear the screen        
 
---

##Git Diagrams and Pictures

Fork Button

![Fork Button](../../assets/GitHub/fork_button.png)

Pull Request Buttons

![Pull Request](../../assets/GitHub/pull_request_button.png)

---

##Still Feel Lost? 
###Catch Up With These Resources

- 	[Terminal Commands](../resources/Terminal_Commands.docx)

-	[Command Line Crash Course](http://cli.learncodethehardway.org/book/)

-	[GitHub Cheat Sheet](https://na1.salesforce.com/help/doc/en/salesforce_git_developer_cheatsheet.pdf)

-	[Intro to Git Videos](http://git-scm.com/videos)

-	[Intro to Git Tutorial](http://www.codeschool.com/courses/try-git) from Code School.
