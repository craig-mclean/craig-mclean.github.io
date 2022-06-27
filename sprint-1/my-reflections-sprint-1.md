# My Reflections - Sprint One 

In addition to the challenge specific reflections, answer the following questions:

# Command Line Primer 

<!-- Copy the answers you wrote in your temporary file earlier, under the sections below -->

### In a couple of sentences, how would you describe the command line in plain English? Can you think of an analogy for it?

This morning I learnt about the “Command Line”
I have seen the command line before (usually when an IT guy has been trying to fix things on my computer), so I had a basic idea of what it is – e.g. you can do things like creating directories, renaming files, navigating, etc, etc, by typing commands, rather than through the GUI.
I’m not yet 100% sure why it is better to use this that the GUI, but I guess that will become clearer in time!
My analogy would be that it is like playing an pold fashioned, text-based adventure game (e.g Zork), where you type the commands and interpret the response.  Versus playing a game that has graphics.


### Did you stick to the timebox guidelines? If not, what change would you make next time?
I didn't start using the timer right away, so I'm not sure - but I suspect I might have taken longer. I went off on some tangents, to figure some things out - such as trying to find out what the Windows equivalent of 'open' is (I found that it was 'code', but then eventually found that that was mentioned further down in our course notes). So I guess I've learned to 1) use the timer and 2) read ahead a little to see if something you are unsure of is mentioned later on. If it's not, then google away and find the answer.


### Name 5 commands you used, and what they do.

1. pwd - print working directory (tells you where you are currently)
2. cd - change directory
3. mkdir - create a new directory
4. rm <file> - remove a file
5. touch <file> - create a new file


### Did you learn anything unexpected?

I watched the start of the "50 most popular linux & terminal commands" and learned that most operating systems (other than windows) can trace their origins way back to the 1960s and Unix!


# Version Control with Git 

<!-- Copy your reflection answers into this file -->

### What's the difference between git and GitHub?

Both provide source code management and make it easier to merge and share code.
Git is installed locally on a developer's machine and you intereact with it via command line. It is focused on versaion control and code sharing
GitHub is a cloud-based hosting service for Git repositories. It has a GUI and allows you to manage multiple versions of source code edits that are then transferred to files in a Git repository.
Git is maintained by Linux.  GitHub is maintained by Microsoft. 

### Can you think of an analogy to describe them?

Git is a bit like “Track Changes” in Word – showing who has changed what in a document.
Github is like DropBox, in that your files are on your computer, but they also live in the cloud. If you change your local copy, GitHub manages the process of putting those changes into the cloud.


### Do you think you would still remember the difference a week from now if you didn't revisit the material?

Yes, I think so.

### Did you stick to the timebox suggestions? If not, why not?

Same answer as above (re: Command Line)

# Install and Explore Git

<!-- Copy your reflection answers into this file -->

### What is a Git workflow?

Per Atlassian, a git workflow is a recipe or recommendation for how to use Git to accomplish work in a consistent and productive manner. 

Because git is flexible, there is no standardised process, so you need to work as a team to agree on how the flow of changes will be applied. Consider:
-	Does the workflow scale with team size?
-	Is it easy to undo mistakes and errors?
-	Does it make things unnecessarily hard for the team?

### What did you notice about your own learning? What did you do when you were confused or blocked?

It is definitely helpful to be doing the example exercises as we go.

There were some things that were frustrating – e.g. how to search through a git log to find a specific SHA.  I knew there must have been a faster way than just scrolling through, but **ctrl+f** didn’t work, so I googled how to do a search. Found out that within WSF it is **ctrl+shift+f**.  
Later in the lesson they introduced us to **git log show**, which made it heaps easier too!
I also found that writing notes/reflections helped consolidate some of the knowledge for me and I found myself referring back to my notes regularly for guidance,
I’ve probably been writing too much (will be interesting to look back on it in a few weeks!) but it’s working for now!


### Is there anything you'd do differently if you were to repeat the learning exploration again?

Not so far – though I’m hoping to speed up soon. Seems like pretty slow progress so far – but then it’s only been a couple of days so far and I’ve already learnt so much!
I hadn’t been using Toggle, but I started using it part way through the day, to try and get a better handle on how long things are taking.


# Track and Commit

<!-- Copy your reflection answers into this file -->

### How would you describe stage and commit to your non-tech-savvy friend?

**Staging** is a way of reviewing all the changes you have made to a file. You can sort through what you have done and decide what is ready and what still needs more work.
The files with changes that you are happy with can then be **committed**, or added back to the main code base.


# Branch, Pull, Merge

<!-- Copy your reflection answers into this file -->

### What is main?

**Main** is the master version – the most stable/trusted version of the code base.

### Why create a Branch?

**Branching** allows you to experiment and make/test modifications to code without impacting on the master, because a branch is a copy of master.

### Do the concepts introduced feel intuitive or difficult to understand?  

These concepts do feel intuitive to me.  I’m not quite sure about the specifics of pushing and pulling (e.g. what should you do first, push or pull?) but the basic concepts of branching, making and testing changes in the branch and then merging them back to master are concepts that I am comfortable with.
Am about to do Ko Wai Koe, so this should help cement some of the detail.


# GitHub Fork & Clone

<!-- Answer the following questions -->

### What are some examples of when you would fork?

You would **fork** if you are contributing to someone else's project (e.g. open source), where you don't have control over the code base.  
The fork is like a bridge, between the original repo and your copy, allowing you to contribute back to the original. 
You can work on a copy and then use a pull request to invite the code owner to accept your changes.  

A programmer who joins a software development team and plans to contribute back to the codebase will typically clone the target repository. When changes or updates are made, either by the developer or by other members of the team, any clone can be easily synchronized with a git push or a git pull.

A developer who wants to set up a new, separate and isolated project that is based on a publicly accessible Git repo should perform a fork.

### Did you have any moments where it all clicked? What clicked?

I found the following video was helpful in describing and demonstrating forking versus cloning: https://www.theserverside.com/answer/Git-fork-vs-clone-Whats-the-difference#:~:text=Any%20public%20Git%20repository%20can,synchronize%20with%20the%20target%20repository

# Setup Repo & Create Blog

### Reflect on this activity. When did you feel frustrated?

This activity has been fine.  No real frustrations with it.  Obviously formatting of text is different from if you are using Word, but I haven't worried about that too much. I've had a look at the markdown guide and have done some **bolding** but haven't got too carried away with it yet.

### If you didn't already know that this is the way websites are made, was it what you pictured? How does the reality of this process differ from your preconceptions?

I'd say that this is more complicated than I had imagined! There is much more structure and process around making changes and then managing how they end up back in the main code base than I would have envisaged.



# Thinking like a programmer

### Understand the meaning of 'thinking like a developer.'

It's all about problem solving and planning how you come up with the solution by breaking problems down into sub-problems, or chunks.  Then try to solve each chunk, rather than attempting to solve the whole problem in one go.

## Understand flipped learning.

"Flipped learning" is where the learner is responsible for their own learning. The teacher provides the learner with tools to think critically about how to solve problems, seeks solutions and overcome obstacles, rather than just providing the knowledge and the answers.
I think this style of learning will equip us well in the workplace, where you need to stand on your own two feet and not be spoon-fed answers.

### What is your process so far for solving problems?

So far it has been a case of re-tracing my steps to see where I have gone wrong. I have also used google quite often to try to get a better understanding of topics. Finally, when I've been completely stuck, I have posted questions on Discord.


# Introduce yourself

My name is Craig McLean and I am based in Arrowtown.

As I have got older (I’m 52), I have learnt that my values have changed over time. 
I care less about prestige, status and material things and more about being authentic, treating people with respect and doing something that you enjoy.

I have been in some high-pressure, managerial roles before, but while there were rewards, they weren’t making me happy and sometimes my values were being compromised.

I am currently a company accountant but am attending DevAcademy as I like the idea of transitioning to a new career, where I can work with others to solve problems and create things, one where I am constantly being challenged and learning new things. I’ve learnt that life is too short to keep doing the same thing if you aren’t really enjoying it.

I’m hoping that Web Development will be a career that will allow for greater flexibility, and generally fit in better with my life, rather than fitting my life in and around my work, as has been the case at times.  It would also be great if it would enable me to live in different places and/or work remotely at times. 

I’m looking forward to the challenge and to working with you all over the next few months!

### What was it like trying to summarise yourself to a group of strangers? 

It was a bit strange doing this in writing to people I have yet to meet. Hard to know how much or how little to say.

### Could you feel your ego? Were you self conscious? 

I was a little self-conscious as I am a person who doesn't like to open up too much, too soon. I generally like to suss people out more before saying too much!  
