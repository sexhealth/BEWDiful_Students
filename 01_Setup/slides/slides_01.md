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
* Rails (web application frameework)
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

https://github.com/sansari/BEWDiful_Students/blob/master/install_instructions.md


---


##Web Development
###What is Back-End Web Development?

To understand that, we need to understand the client server model:

![NotAzizAnsari](../../assets/misc/server-side.jpg)

Now, we can define a few terms:

* Web Development (development of apps designed for the web)
* Front-End Development (developing for the client / browser)
* Back-End Development (developing for the server)

This course will heavily focus on technologies for backend development (Ruby, Rails, MySQL) and only briefly cover technologies needed for front-end development (HTML, CSS).

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

##Jump onto the Command Line
###What is it?

The command line is a terminal giving you direct access to your operating system. You can enter simple commands to perform a variety of functions.

Many of the tasks we need to carry out (such as committing our code) are best performed in the command line.

---

##Jump onto the Command Line
###How do I start?

For Macs:

* Open the "Terminal" app
* For a better experience, download and install "iTerm 2", which is a replacement app that is slightly better.

For Windows:

* Open the "Command Prompt" application
* For a better experience, try "Console" (http://sourceforge.net/projects/console/). NOTE: I have not personally used this.

---


![GeneralAssemb.ly](../../assets/ICL_icons/Code_along_icon_md.png)
##Command Line Basics

---


![GeneralAssemb.ly](../../assets/ICL_icons/Exercise_icon_md.png)
## Command Line Basics Exercise

---


##Work Like a Developer
###Integrate into the developer community

Congrats! You're on your way to becoming a developer. Keep it up.

If you are still a bit lost, don't worry. Practice makes perfect. Take a look at the cheat sheet in the Resources slide at the end of the class for a list of common commands.

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
##Git Basics

---


##GitHub
###What is GitHub?

*	Git vs GitHub. What's the difference?
*	<b>Git</b>: A tool used to manage <b>local</b> repositories
*	<b>GitHub</b>: A cloud-based platform used to manage <b>remote</b> repositories

![Using Git](../../assets/GitHub/git_general_diagram.png)

---


##GitHub Forks
###Forks Explained
![ Git In Class Diagram](../../assets/GitHub/fork_Diagram.png)

---



![GeneralAssemb.ly](../../assets/ICL_icons/Code_along_icon_md.png)
##Git In Class

---


![GeneralAssemb.ly](../../assets/ICL_icons/Exercise_icon_md.png)
## Git It Together

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


-	[Command Line Crash Course](http://cli.learncodethehardway.org/book/)

-	[GitHub Cheat Sheet](https://na1.salesforce.com/help/doc/en/salesforce_git_developer_cheatsheet.pdf)

-	[Intro to Git Videos](http://git-scm.com/videos)

-	[Intro to Git Tutorial](http://www.codeschool.com/courses/try-git) from Code School.
