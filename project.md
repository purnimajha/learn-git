
Courses
Forum (10+)
Events (7)
Sharing (10+)
 Videos (8)
Resources
Exercises
Pages
 Archives
Chat Room
My Account
My Assessments
Sign Out
 BACK TO OPEN BOOK SHELF
OPEN BOOKSHELF
COVER PAGE
PREFACE
Credits
Copyright
No Offline Access?
GETTING STARTED
Introduction
Getting Started
Who Is This Guide For?
How To Read This Guide
Source Control Management
Code repositories
What is Version Control?
What is Git?
Local vs. Remote
Free and Open Source Software
What is GitHub?
Goals
Preparations
WORKING LOCALLY
Creating Repositories
Tracking Change
Branching
Summary
REMOTE REPOSITORIES
Introduction
GitHub
Passwords
CONCLUSION
Next Steps
Cheatsheets
SHARE ON
 
Introduction
Getting Started
Programming is not just code and computers. It's about people. It is decision making, information sharing, and the tools and mental models we use to solve problems and iterate on the solutions.

Git and GitHub, the topics of this guide, speak to this other side of programming. Where writing code stops, git and GitHub.com come in to give closure to our work efforts and share it with teammates and if we want, the world.

Who Is This Guide For?
If you've never used a code version control system before, or have never used git before, this book is for you.

After working through this book, you will have a solid conceptual understanding of how to work with git locally, and will have pushed commits to your first remote repository on GitHub.

How To Read This Guide
We cannot stress enough the importance of hands on practice while we explore new material. To start building the muscle memory to work with git and GitHub, you should read this guide on or near a computer and try to follow along. We will be utilizing your computer's command line terminal and web browser to walk through the examples.

Source Control Management
Before getting into the technical details, let's take a step back and quickly talk about what code source control is. Imagine you are working on a new feature for your project. You have a part of the work completed. All of a sudden your manager comes rushing to your desk and fills you in on a super urgent request which happens to affect the same file you were editing and needs your attention now. How do we handle this request without losing the work on your feature? The answer is Source Control Management.

Source Control Management or SCM, is the process programmers and software engineering organizations follow to iterate on their projects or codebases. SCM tools include git, SVN, CVS, Team Foundation, and many others. Another term for SCM is "Version Control System".

SCM tools keep a historical record of the files in your codebase, as well as manage SCM workflows that allow large teams to work on large, complex codebases with hundreds or thousands of files. Different teams employ different workflows, which is out of scope for this book. In order to understand more complicated SCM workflows, you'll first need to understand the basics, which is what we'll cover.

Code repositories
SCM tools, like git, store your files into a repository, or just repo for short. The exact implementation of a code repository will differ based on the SCM tool, but in the case of git, it's just a directory and files. There's no running database or external systems. You don't need to worry about what a repository is -- only that it's the place where your code and version history are stored.

What is Version Control?
To get a better idea of what version control is, take a few minutes to read this short tutorial on "What is Version Control?"

What is Git?
Git is one of the most popular SCM tools. It can be used for projects large and small, and is agnostic to the types of content in the projects. In fact, we use git to manage the chapter contents of this book.

Git is different from some other SCM tools because it is distributed, meaning there is no central code repository. For this reason, git has become very popular for the development of what is known as Free and Open Source Software, or FOSS. The philosophy behind a de-centralized system is that it is resilient to a single point of failure, which helps ensure that FOSS libraries stay open and free.

This intro guide to git and GitHub will cover the basics to empower you to set up your project and take 'snapshots' of your progress.

Fun Fact: git was created by Linus Torvalds, the same software engineer who created Linux.

Local vs. Remote
Git is considered a distributed version control system, or dvcs. Non-dvcs SCM tools typically require a client/server architecture, where a centralized server hosts the main repository, and developers work with clients that commit code to the main repository. A key feature of dvcs is that there is no main central repository, and all developers on a project work with local repositories, pushing commits around directly to each other.

In practice, however, most development teams that use git will not push commits directly to each other. Instead, they rely on a central repository to act as the main repo, and that main repo is typically hosted on github.com.

Despite this faux client/server usage, git at its core is still a dvcs, so it's critical to understand the concept of working locally vs pushing or pulling commits from a remote repository, like one hosted on github.com.

A local repository will refer to a repository located on the computer you are using. A remote repository, on the other hand, refers to a repository that is located on another computer or server. Repositories created on github.com, for example, are considered remote because they are located on GitHub's servers.

In the first part of this book, we'll only be working with local repositories. In the second part of this book, we'll start to work with remote repositories, but all commands are issued from the context of your local repository. In other words, if we "push" or "pull" to/from a remote repository, that's from the perspective of your local repository.

Free and Open Source Software
Free and Open Source Software, or FOSS for short, refers to computer program code that has been released to the public for reuse under a license. Just how big is FOSS? To say huge would be an understatement. There are thousands of Open Source projects in existence, and they come in sizes big and small. You might say that the LINUX operating system is one of the biggest open source projects in existence. Other highly visible open source projects include the Apache web server, and a majority of programming languages such as Ruby, PHP and Oracle's Java programming language and environment. To repeat what we said above. Programming is about people. You guessed it; there are hundreds of thousands if not millions of programmers all around the world that work on or with Free and Open Source Software. In fact, many commercial systems are built by integrating various pieces of FOSS to achieve their goals.

It is impossible to talk about git and GitHub without understanding what FOSS is because FOSS is typically built in a distributed manner, with programmers making improvements on the software from all around the world. The git program itself is FOSS. To top it off, many FOSS projects utilize git for SCM.

What is GitHub?
GitHub.com might be the best thing that has happened to software development since the Internet. GitHub took the git program and connected the people and code over the web, creating an eco-system and user interface for software projects that we can 'touch'. To quote directly from GitHub.com

"GitHub is the best place to share code with friends, co-workers, classmates, and complete strangers. Over six million people use GitHub to build amazing things together."

There you have it. By the end of this guide, you will be empowered as part of this tribe of 6 million people, capable of building amazing things.

Goals
By the end of this guide you will know how to get started with using git locally, and have launched your first small pebble of 'code' into the GitHub ecosystem, and you will have the basic git skills to contribute to a git-based project.

If you aren't on your computer already get close and continue reading.

NEXT:  PREPARATIONS Give us your feedback