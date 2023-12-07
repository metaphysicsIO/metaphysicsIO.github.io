# metaphysicsIO.github.io

## Code review
N/A 

## Original, Pre-enhanced Artifact

[original.zip](original.zip)

## Enhanced Artifact
[Pokemon SAV Editor](https://github.com/metaphysicsIO/Pokemon-Sav-Editor)

A command-line only Pokemon SAV editor that has multiplatform support.
Currently supports Generation 1 (Red/Blue) only, as well as ROM hacks of that
generation.



## Narrative

I have one artifact that covers the three categories. This project is
called Pokemon SAV Editor (PSE) and it’s entire function is to help promote
rapid development for competitive play. The main, and most important,
feature is that you are able to customize the player’s party and that was
the main focus point for this capstone project.

[Category #1 enhancement](https://github.com/metaphysicsIO/Pokemon-Sav-Editor/commit/85a60e088b64477fb5935a9bea738d79beeda7ea)

In the first category, “Software Design/Engineering”, PSE displays my solid
grasp of good software design and engineering. The major area here is in my
backup system that both prevents accidental data loss that is sympathetic
to the user by not cluttering up their folder. Another prominent feature is
keeping subroutines separated and well commented. The documentation can
always be better, but I think I have produced a pretty good start that
allows anyone with a basic understanding of programming to be able to read,
and comprehend, what is happening in the PSE code base. I had selected this
item because It’s important to take redundancy seriously, and by
implementing this backup system, I am creating another protective stage for
protecting the user’s file. This area displays my outcome of “building
collaborative environments that enable diverse audiences to support
organizational decision making”, “Develop a security mindset that
anticipates adversarial exploits in software architecture and designs to
expose potential vulnerabilities, mitigate design flaws, and ensure privacy
and enhanced security of data and resources”, as well as “Design, develop,
and deliver professional-quality oral, written, and visual communications
that are coherent, technically sound, and appropriately adapted to specific
audiences and contexts” due to the documentation/comments, the security
mindset of checking user input, as well as allowing the user to rollback
with the backup functionality.

On reflection of the first category, over the last several weeks I became
very comfortable with C++ again. I have not have to look up documentation
very often and I think this is a great sign for my progress. With regards
to the given feedback, I made changes with issues that were of high
priority, such as necessary comments, while left the lower priority
aesthetics alone while I completed higher priority tasks in the mean time.
This was a very useful way for me to recognize my own limitations within
the given time constraints.

[Category #2 enhancement](https://github.com/metaphysicsIO/Pokemon-Sav-Editor/commit/a1f7155a1ea42fd7afa1c1546d11a6412dbd06bd)

In the second category, “Algorithms and Data Structures”, PSE shows my
execution of this category perfectly. Not only did I I developed, designed,
and implemented the functionality of editing the party’s attributes, which
is the main purpose of the program, but I also reduced the complexity of
this by using a hash table, which had a search complexity of O(1). I had
selected this item because this functionality is the life blood of the
program’s purpose. This skill covers the Design and evaluate computing
solutions that solve a given problem using algorithmic principles and
computer science practices and standards appropriate to its solution, while
managing the trade-offs involved in design choices.

On reflection of the second category, my feedback is in my writing and,
while I don’t want to work with people who need everything spelled out to
them, I do recognize that the world is a place where most people are so
genuinely stupid and incompetent that if they were horses, we wouldn’t
bother leading them to water, we’d simply inject them with saline solutions
to keep them hydrated.

[Category #3 enhancement](https://github.com/metaphysicsIO/Pokemon-Sav-Editor/commit/211369a126af84b5771e346ca5a3811a053ed172)

In the third category, “Databases”, PSE shows my understanding of CRUD
functionality with SQL. This program was made with modularity in mind, so
this implementation allows for custom ROM hacks of Blue and Red may be used
along with this program. My usage of MySQL, Python, and force C++ to
interact with python covers the outcome of “Demonstrate an ability to use
well-founded and innovative techniques, skills, and tools in computing
practices for the purpose of implementing computer solutions that deliver
value and accomplish industry-specific goals.”

Upon reflection of the third category, the feedback I was given was fairly
positive towards my database code itself, except for documentation of the
author in the header of the program. I went through each of my files and
added what I could at the top of each file, and it is much nicer to know
the purpose of the file as well as known issues. This isn’t something I had
considered doing before, but I like it because it makes it much easier to
understand what is going on in that file.

## Professional Self-Assessment

While working through a BS in computer science, I developed a number of
skills thanks to the course work and on the side when I had free time to
self-study concepts. The classes taken were an invaluable for my foundation
in computer science, as well as computer programming. I spent a lot of time
and effort in these classes and this very clearly paid off.

In CS-320 (Software Testing, Automation, and Quality Assurance), I learned
a lot about collaborating in a team environment with git in GitLab. In
CS-250 (Software Development Lifecycle), I learned about communicating to
stakeholders in an agile setting, where we communicated user stories and
translated specialized language into layman terminology for an easy way to
bridge the gap between the various teams involved in a project. In CS-260
(Data Structures and Algorithms), I learned about both algorithms and data
structures, as per the name of the class, where I learned to traverse
various trees and hash tables, as well as the mentality to have when
attempting to solve a problem in the most efficient way possible. In my
DAD-220 (Introduction to Structural Database Environments), I learned about
databases and how to use MySQL from both the interpreter as well as from
other languages which resulted in my ability to build CRUD functionality
with ease and made me have a better understanding of how to think about
database management. In IT-312 (Software Devel w/C++), I become familiar
with software engineering (as well as C++) concepts that helped me
breakdown a program into an easier to digest code base to be easy to read
through, easy to modify, and efficiently produced. Finally, with regards to
security, I had not taken a class that assisted me with security yet.
However, my experience with the “cyberSNHUpers”, the South New Hampshire
University Cybersecurity club, has helped me gain a lot of good ways to
find exploits, and thus how to correct, problems in a given program. 

The way that my artifacts fit together with my skill growth is self-evident. My artifact showcases each of these concepts together to build a well built program that achieves exactly what it sets out to do in a very, very quick way. The Pokemon SAV Editor accesses a file, protects the user’s save file from being lost, makes the user desired edits while taking into account a malicious user by sanitizing the few strings that are taken by the user, assembles a hash check to confirm the file is acceptable, implements CRUD for a database for editing the program for use with regards to hacked version of the SAV file, and implements algorithmic solutions that could not be improved upon due to being the best complexity outcome possible.
