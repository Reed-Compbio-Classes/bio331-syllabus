---
title: Course Policies
layout: default
nav_order: 5
---

# Course Policies

There are four policies for this course: one for [attendance](#attendance-policy), one for [deadlines](#deadline-policy), one for [collaboration](#collaboration-policy) (which is encouraged for the programming assignments) and one for the use of [online resources and generative AI](#online-resources--generative-ai-policy) (which will be discussed in class).

## Attendance Policy

**Why Attend?** Attending the lectures and completing work during labs will put you in the best position to succeed in the course. Lectures will provide valuable information about the assignments, and labs will include some group work. Labs also offer time for me to provide guidance - they could be framed as small-group office hours working through problems together.  

**What's the Policy?**  Email me if you cannot attend lecture or lab. You are expected to review the missed material and meet with me if anything is unclear. 

There are three classes with activities and 14 labs where your engagement is expected. If you have spoken with me about not being able to attend, you will be able to catch up with this work asynchronously. 

You are expected to attend the presentations during Finals Week. 

There are some religious holidays and other events in the fall that might affect student attendance - please note these in your calendars and let me know if your attendance will be affected.

- September 22-24: Rosh Hashanah 
- October 1-2: Yom Kippur
- October 20: Diwali begins
- November 11: Veterans Day
- November 27: Thanksgiving Day

If you miss multiple classes, I may reach out to make sure you are OK. Communication is key. Please see "Illness and Exceptional Circumstances" on the [support page](support.md) for more information about extended absences. 

### The Main Takeaway: Attending and participating is expected and will set you up for success.

## Deadline Policy

The the programming assignments, quizzes, and the research project assignments all have deadlines. The purpose of these deadlines is for you to complete the assignments at a steady pace throughout the semester. 

**Why Submit Work on Time?** The programming assignments and take-home quizzes are designed so that you are working on them after you have learned the relevant material in lecture and lab. If you are working on older assignments when another assignment is out, you might lose ground with the current coursework. 

**What's the Policy?** You must submit whatever work you have by the deadline. Any work that is marked as "Missing" or "Partially Complete" can be resubmitted after receiving feedback from me.

- The deadline to resubmit programming assignments is Mon 11/10 (3 weeks after the last programming assignment is due)
- The deadline to resubmit short quizzes is Wed 12/10 (2 weeks after the last quiz is due)
- The deadline to resubmit the long quiz is during Finals Week (exact date TBD).

These details will be provided on every assignment.

### The Main Takeaway: Assignment deadlines are intentional, and you should submit your work by the deadline. You will be able to resubmit work that is marked "Missing" or "Partially Complete" after receiving feedback from me.

## Collaboration Policy

**Why Collaborate?** Collaboration on all assignments and activities (except for the quizzes) is highly encouraged. It is often easier to work through problems with a thought partner, working with someone else brings a different perspective to the challenges, you might help each other out in complementary ways, and working together can be fun! 

**What's the Policy?** When you collaborate, properly cite it in your work (see below). **You must write all of your own code for the programming assignments**, even if that means sitting next to a collaborator and typing the same thing. You have a lot of flexibility in naming variables, including print statements and comments in your code.

Code plagiarism is a real thing. Identical code is just as bad as copying and pasting entire paragraphs of an essay from another source. Just like when writing papers, there is a way to cite others' work in programs.  If you collaborate with other students in the class or sought help from a tutor, add their names as comments, e.g., 

```
# This function was written with Jane and Rob for Lab 5
# I talked about the structure of this code with Marco
# Julie and I worked on the function post_network() together.
# I modified the convert() function from Lab 3
```

Remember, this type of collaboration is expected and encouraged! People who worked together should list each other as collaborators, since this will help us determine why some code might look similar.

**Citing Previous Code from Class.** If you copy your own code from previous assignments or labs, cite in the comments where you copied the code from (e.g., `# read_graph() function from Lab1.`). Anna will post solutions to the labs on Fridays; you are free to copy pieces of these solutions for future assignments, clearly state that it is from a posted solution (e.g., `# read_graph() function from posted Lab1 solution.`). 

### The Main Takeaway: Collaboration in class and on programming assignments is expected and encouraged! You should "cite" anyone you worked with on the programming assignments and any code you copied from a previous lab or assignment. 

## Online Resources & Generative AI Policy

There are many online resources for python, including python modules that have pre-packaged functions, the [python standard library reference](https://docs.python.org/3.13/library/index.html), and user help threads like StackOverflow. Generative AI is technology that is trained to generate text, images, or code from natural language prompts.  Two examples of generative AI that you might have seen before are ChatGPT (which returns text based on prompts) and GitHub Copilot (which returns code based on prompts).

You may always use the resources linked from Moodle. This policy lays out the scope of what is allowed beyond the Moodle resources.

### Programming Assignments

The fact is, online resources and generative AI might do a good job with some of the programming assignments. But the assignments are designed for _you_ to learn about graph algorithms, which can only happen if _you_ write the code. The [course goals](goals.md) of this class include implementing graph algorithms and applying them to biological networks - if you use online resources or generative AI, you are not demonstrating what you have learned.

1. Do not use python packages that provide code for working with graphs (e.g., `networkx` or `igraph`) or other math/stats packages (e.g., `scipy` or `numpy`) unless otherwise directed. You _may_ use `pandas` to manage datasets, but check with Anna before using any of the built-in functions.

2. You may look up basic Python syntax online (using either a search engine or, **new this year,** using generative AI). Some examples of basic syntax are "how do I structure a double FOR loop?" "How do I sort a list?" "How do I initialize a dictionary"?. 

3. **New this year,** you may use generative AI to help debug your code. If you do, you must add a comment with the ChatGPT prompt you provided. 

4. You may not look up the code for entire functions that are part of an assignment or lab (e.g., calculating the degree distribution of a graph or the shortest paths algorithm). While it may take some time for you to write these functions yourself, they are important for the learning goals in the class. 

When in doubt, "cite" your online resources in the comments of your code.

### Quizzes

The quizzes are intended to be done on your own with your notes and the resources available on Moodle. They are an assessment of your understanding of biological networks and graph algorithms, so online resources (beyond the ones linked from Moodle) and generative AI are not allowed for quizzes.

### Research Project 

The research project, on the other hand, might have opportunities for using new packages and getting help with generative AI. We will have a class discussion about how to use generative AI in your research project to set the class policy then.

### The Main Takeaway: Online Resources and Generative AI should not be used for generating entire functions, but they may be used to help understand basic python syntax and debug issues (with proper citation). Online resources should not be used for quizzes (beyond what Moodle provides), and we will discuss the role of online resources for the research project as a class.
