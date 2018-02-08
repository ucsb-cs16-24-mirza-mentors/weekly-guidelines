---
topic: "Creating feedback repos"
desc: "A private repo that students can read, but not edit"
---

One of the ways that mentors can give feedback (NOT GRADES) to students in CS16/24 is via the use of private feedback repos.

The private repos are read/write for course staff (organization owners, including instructors, TAs, and mentors), but read only
for the students.

Eventually, we will have an automated way to create these feedback repos, but for now it is still a manual process.  Fortunately,
as long as the mentor / mentee ratio remains fairly small (each mentor having between 3 and 10 pairs), the creation process does not
take very long.

The naming convention is as follows.  Put the <strong>githubids in alphabetical order by github id</strong>.

* FEEDBACK_githubid1_githubid2 for pairs 
* FEEDBACK_githubid for individuals

To create these repos:

* Go to the web page of the organization for the course
* For each pair,individual: create a private repo with this name.
    * Initialize it with a README.md.  
    * You don't need a .gitignore or a LICENSE file.
* After creating each repo, add each of the individuals with READ ONLY access to the repo.  You do this by adding them as collaborators.
    * On the repo page, click "Settings"
    * Menu at left, click "Collaborators and Teams"
    * You might be asked to confirm your password
    * Go to "collaborators", and add each of the students.  You'll have their githubid handy from the name of the repo.
    * IMPORTANT: Change the access level from "Write" which is the default, to "Read".

# What do you do in these repos?

In these feedback repos, you should create a file named feedback.md with
the following sections

At the top, put a top level heading with the names of the students,  the quarter, and some general reference information.
It will be very handy later to have these links at hand.

Then create separate sections for each of the labs that involves legacy code.

```
# Feedback for Selena Gomez and Justin Timberlake, CS24 W18

* Mentor: Lily Gaucho

# lab02 feedback: initial code review of repo

# lab04 feedback: 

etc...
```

You'll be given instructions as to what to fill in for those specific sections.

This page concerns only getting the feedback repos set up, so our work here is done.
