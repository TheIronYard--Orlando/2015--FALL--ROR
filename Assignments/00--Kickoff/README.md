# 00 -- Kickoff

## Overview 

There are several components to this assignment: 

* setting up a GitHub account
  * setting up a progress monitor with your new GitHub account
* learning about git and GitHub
* learning your way around the command line
* installing some software
* reading about Ruby
* reading about learning in general
* think and write about this assignment and your expectations of the course

## Set Up

You will use two web applications, GitHub and Slack, every day in this course and in your career (until something 
better comes along to replace them, of course). Because Slack is intuitive (because its purpose is familiar: it's a 
communications tool), we'll wait to sign up for it until class starts. GitHub is harder to understand because it's used for
a less familiar purpose: version control. Since version control is probably as unfamiliar to you as it is essential
for this course and your career, I want you to register for a GitHub account and spend some time learning your way 
around the site before you get here. 

If you haven't already, [create a GitHub account](http://github.com/signup) (or use your existing one) and [edit your 
GitHub profile](https://github.com/settings/profile). Add a _recent, clear picture_ so we can recognize your face, 
_your full name_ so we can recognize your name, and _a valid public email address_ so we can contact you. _Star the 
class repo_, if you haven't already, and read through [the wiki](../wiki) and the various README files in the repo.

### You've Got Issues

One of the uses of GitHub is to track progress on working through issues, like fixing bugs or adding features to code.
To help you get accustomed to that aspect of the site, and to keep me appraised of your progress, you're going to use 
the issue mechanism to track progress on your assignments - starting with this one. 

[Create an Issue in the class repo (this one)](https://github.com/TheIronYard--Orlando/2015--FALL--ROR/issues/new) and 
name it `00 -- YOUR NAME`, where `YOUR NAME` is, well... your name. Your real, full name. Copy and paste the 
checklist from the **Tasks** sections below into the **Description** of your issue _as is_. You should end up with a 
bunch of checkboxes thanks to [the way that GitHub interprets 
text](https://guides.github.com/features/mastering-markdown/). As you complete parts of the assignment, check off the 
corresponding checkboxes and watch your progress bar fill! Read [Mastering 
Issues](https://guides.github.com/features/issues/) for more information on creating issues in GitHub.

_This task list should be complete by the first day of class!_

## Git'er Done

Because version control is probably unfamiliar to you, part of the second component of this assignment is to go 
through several short online tutorials that introduce what version control is and how git and GitHub are used. Version
control is a subject that is unfamiliar to most non-developers yet essential to most developers. 

There is a very good introduction to what version control is and why it's important in [the first section of the Git 
Basics course at Treehouse](http://teamtreehouse.com/library/git-basics). [Note that Treehouse charges after a 14 day 
free trial.] The rest of the Git Basics course is good as well.

You can get more practice on the basic git commands with the (free) interactive tutorial from our friends at 
CodeSchool, [Try Git](http://try.github.com). CodeSchool also has [a `git` path](https://www.codeschool.com/paths/git).

There are [helpful Guides on GitHub](http://guides.github.com) to introduce you to several aspects of the site, 
and an [extensive help section](https://help.github.com/). Start with 
[Hello World](https://guides.github.com/activities/hello-world/).

## Whoa...I Know Command Line Fu

Like version control, the command line is unfamiliar to non-developers and essential to developers. It's also the
best way to make it clear to anybody looking at your screen that you're a hacker, second only to firing up 
http://hackertyper.net/ in your browser and typing like the wind.

In this class, we're going to use the Command Line Interface (CLI) _a lot_. There's a nice overview of most of the
basic commands you'll use on the command line in [_An Intro to the OS X 
Command Line_](http://eddywashere.com/blog/an-intro-to-the-os-x-command-line/), and you can reinforce that quick read
with some practice at [_Learn the Command Line_ on 
CodeCademy](https://www.codecademy.com/courses/learn-the-command-line/). 

If you're looking for more of a challenge, you can try the [_CLI Crash Course_ by Zed Shaw](http://cli.learncodethehardway.org/book/).

### Downloading...

Most of the individual tasks in this assignment involve getting your laptop ready for Day 1 by installing a few key 
pieces of software. _Please have these installed on your Mac before the start of class!_ If you have trouble, 
please put a comment on your WIP Issue so I can see it. 

Now to the installations. Start with [Homebrew](http://brew.sh), a package manager (software that helps install other
software). Use the `brew` command to install several more packages:

* `zsh` - an improved command shell (which is the program that does the work on the command line)
* `git` - which you have met already
* `hub` - a tool which eases the use of `git` with GitHub
* `chruby` - a Ruby version manager (which lets you have more than one version of Ruby installed at a time)
* `ruby-install` - which lets you...oh, I bet you can guess

Homebrew was originally made for those kinds of command line tools, but it's so convenient to have a package manager,
a package called [Caskroom was written to manage application installation too](http://caskroom.io/). 

Use Caskroom to install the following applications:

* [Google Chrome](http://google.com/chrome) - unless you have it already
* [Sublime Text](http://sublimetext.com) - a text editor and your new home
* [Slack](http://www.slack.com) - remember when I mentioned Slack? Good times.
* [Flux](http://www.justgetflux.com) - your eyes will thank you

There are several things we're going to do to improve the command line experience, most of which involve a project
called Prezto, which lives on GitHub. You're going to fork and then clone that project. You probably don't know
what forking means, so read about it [in the "Forking Projects" Github 
guide](https://guides.github.com/activities/forking/). Then use the `hub` command to clone the forked project to
your Mac, and install Prezto. The install instructions are a little tricky, so pay careful attention. 
If you get stuck, please leave a comment on your issue and move on.

### Reading About Learning

Just by this point in the prework assignment, you are probably getting the idea that you will have a lot to learn 
during this course. I used to think that how much and how fast I could learn was mostly an accident of genetics which 
I could never change, but I've changed my mind based on some research I've read about, applied in my own life, and 
asked my students to apply. You will read about that in an introduction to mindsets. 

### Reading About Ruby

Last but not least, you will read over one of the best (and free!) introductory books on the Ruby language.
[Learn to Program](https://pine.fm/LearnToProgram/) is a terrific tutorial if you've never written any code before, 
or if you've never worked with Ruby before. You can read the original version on the author's website for free, or 
follow the link he gives to purchase the latest version. For this assignment, the exercises in the book are optional.

### Pause and Reflect

Please answer the following questions in short essay form. Try to keep each answer between 200-500 words (3-5 paragraphs). Don't worry about grammar or spelling -- use this time to reflect on yourself and your upcoming adventure!  Please submit your answers as a comment on your WIP Issue. 

1. What difficulties do you predict that you will encounter during our course? How have you reacted to similar situations in the past? How do you plan on reacting to these situations during the class?
1. Which part of the prework did you like the MOST? Which part of the prework did you like the LEAST? If you found any of the prework confusing, please explain.


## Tasks

```markdown
* [X] [Create a Github account](https://github.com/signup)
* [ ] *5 min* [Edit your Github profile](https://github.com/settings/profile) to provide:
    * [ ] A picture, so I can recognize your face.
    * [ ] Your full name, so I can recognize your name.
    * [ ] A valid public email address, so I can contact you if I need to.
* [ ] [Star the class repo](https://github.com/TheIronYard--Orlando/2015--FALL--ROR)
* [ ] *10 min* Read over [the class wiki](https://github.com/TheIronYard--Orlando/2015--FALL--ROR/wiki)
* [ ] *10 min* Read the `README.md` files in:
    * [ ] [Assignments](https://github.com/TheIronYard--Orlando/2015--FALL--ROR/tree/master/Assignments)
    * [ ] [Notes](https://github.com/TheIronYard--Orlando/2015--FALL--ROR/tree/master/Notes)
* [ ] *5 min* [Create a new *WIP Issue*](https://github.com/TheIronYard--Orlando/2015--FALL--ROR/issues/new)
  * [ ] Named `00 -- YOUR NAME` (where `YOUR NAME` is _your_ name)
  * [ ] With this checklist as the description
* GIT 'ER DONE
  * [Git Basics course at Treehouse](http://teamtreehouse.com/library/git-basics) (optional)
  * [`git` path at CodeSchool](https://www.codeschool.com/paths/git) (optional)
  * [ ] *20 min* Complete the CodeSchool short course, [Try Git](https://www.codeschool.com/courses/try-git)
  * [ ] *10 min* [Complete the "Hello World" Github guide](https://guides.github.com/activities/hello-world/)
    * [ ] Add a link to your new Github repo as a comment in your WIP Issue.
* COMMAND LINE FU
  * [ ] *5 min* Read http://eddywashere.com/blog/an-intro-to-the-os-x-command-line/
  * [ ] *30 min* Complete https://www.codecademy.com/courses/learn-the-command-line/
  * [Do It The Hard Way](http://cli.learncodethehardway.org/book/) (optional)
* [ ] *15 min* [Install Homebrew](http://brew.sh) on your Mac
    * [ ] Open `Terminal.app`
    * [ ] [Install Homebrew and the `brew` command](http://brew.sh/#install)
    * [ ] Read [the Homebrew Wiki](https://github.com/Homebrew/homebrew/tree/master/share/doc/homebrew#readme) to learn more about Homebrew
* [ ] *10 min* Using the `brew` command, install the following packages:
    * [ ] `zsh`
    * [ ] `git`
    * [ ] `hub`
    * [ ] `chruby`
    * [ ] `ruby-install`
* [ ] *10 min* Using the `ruby-install` command, install Ruby 2.2.3.
* [ ] *5 min* Set the default version of Ruby to 2.2.3.
* [ ] *10 min* Add the output of the following commands as comments on your *WIP Issue*:
  * [ ] `which zsh && zsh --version`
  * [ ] `which git && git --version`
  * [ ] `which hub && hub --version`
  * [ ] `which ruby && ruby -v`
* [ ] *10 min* [Install Caskroom](http://caskroom.io)
* [ ] *5 min* Using `brew cask`, install the following applications:
    * [ ] [Google Chrome](http://google.com/chrome)
    * [ ] [Sublime Text](http://sublimetext.com)
    * [ ] [Slack](http://www.slack.com)
    * [ ] [Flux](http://www.justgetflux.com)
* NOTE: The above looks like a lot, but those tasks go quickly. The following items require, and deserve, more time. Don't put them off!    
* [ ] *5 min* [Complete the "Forking Projects" Github guide](https://guides.github.com/activities/forking/)
    * [ ] Add a link to your `Fork-and-Spoon` repo as a comment on your *WIP Issue*
* [ ] *20 min* Install Prezto
  * [ ] Find _and fork_ the Prezto project on Github; add a link as a comment on your *WIP Issue*
  * [ ] Use the `hub` command to clone your fork into your home directory as `.zprezto`: 
  `hub clone prezto ~/.zprezto`
  * [ ] Follow the installation instructions in the `README.md` file
* [ ] *20 min* Read the first four pages about growth vs fixed mindsets at http://mindsetonline.com/whatisit/about/index.html. I'll be honest, this sounded hokey to me when I first read it, but watching how people with the two mindsets performed in previous cohorts, I'm sold on the idea. You have much more control over how much you can learn than you might think.
* [ ] *5 hr* Read the book [Learn to Program](https://pine.fm/LearnToProgram/). 
  * [ ] 0. Getting Started
  * [ ] 1. Numbers
  * [ ] 2. Letters
  * [ ] 3. Variables and Assignment
  * [ ] 4. Mixing It Up
  * [ ] 5. More About Methods
  * [ ] 6. Flow Control
  * [ ] 7. Arrays and Iterators
  * [ ] 8. Writing Your Own Methods
  * [ ] 9. Classes
  * [ ] 10. Blocks and Procs
  * [ ] 11. Beyond This Tutorial
* [ ] **Pause and Reflect**
 * [ ] Answer question 1 in a comment on your WIP Issue.
 * [ ] Answer question 2 in a comment on your WIP Issue.
```

## Extracurricular Activities

### If You're Experiencing Windows Withdrawal

The Mac interface is great once you're used to it. For those who aren't, Apple has [a great support article on 
Apple.com called _Mac Basics_](https://www.apple.com/support/macbasics/) to get you started. 

### Keyboard is Key

Regardless of how good you think you are at typing, a lot of the mistakes you make at first will be simple typographic errors. 
If you _don't_ know how to touch type (i.e. without looking at the keyboard), start practicing _now_ with 
http://www.keybr.com/. Typing code is different from typing other documents; more characters are used, and certain 
letter combinations come up more frequently. If you're fairly confident in your typing ability, try working through 
the Ruby on Rails lessons on http://typing.io.

### On Your Markdown

You might notice by now that GitHub does something funny with the text that you write. It's using a simple formatting
system called [Markdown](http://daringfireball.net/projects/markdown/), and it adds a little of its own flavor. 
To learn more about Markdown and how GitHub uses it, check out 
[_Explaining Markdown_ on Team Treehouse](http://blog.teamtreehouse.com/explaining-markdown) and 
[_Mastering Markdown_ in the GitHub Guides](https://guides.github.com/features/mastering-markdown/).

### Recommended Reading

There are several books that I suggest you start reading. They're all available in digital format on various devices, 
and they're all relatively easy reads:

* [_Getting Things Done_ by David Allen](http://j.mp/134jABk)
* [_Pragmatic Thinking and Learning_ by Andy Hunt](http://j.mp/1D5nmu8)
* [_Make It Stick_ by Peter C. Brown, Henry L. Roediger, and Mark A. McDaniel](http://makeitstick.net/)
* [_A Mind for Numbers_ by Barbara Oakley](http://www.amazon.com/Mind-For-Numbers-Science-Flunked-ebook/dp/B00G3L19ZU)
