# **Foundations of Computing for Biologists**

- BIOL 2601 / 7800 • Louisiana State University • Fall 2026
- **Time / Location:** T/Th, 12:00 – 1:20 PM, 0124 Tureaud Hall
- **Instructor:** Brant Faircloth (<brant@lsu.edu>), Moreland Family Professor
- **Instructor office hours:** 492 OLOH Interdisciplinary Science Building, [Book a time][T1]

- **Graduate teaching assistant:** Rujuta Vaidya (<rvaidy2@lsu.edu>)
- **TA office hours:** 496 OLOH Interdisciplinary Science Building, [Book a time][T1]
- **Moodle:** [moodle.lsu.edu](https://moodle.lsu.edu)

*For any other meeting times, please email.*

[T1]: https://moodle.lsu.edu/course/section.php?id=1073529

# **Course Description**

The analysis of large data sets in biological research is becoming common, particularly as new sequencing technologies and automated data collection strategies exponentially increase the amount of data that can be collected by an individual researcher. Different types of programmatic approaches are often needed to quality control, format, and analyze these large data sets, yet few biologists (particularly at the undergraduate level) receive any sort of training in computational approaches to these tasks.

Foundations of Computing for Biologists is meant to introduce undergraduate and graduate students to various computing techniques that can be used to analyze biological data. As part of this course, we will cover several different modes of programming (command line interface/BASH, regular expression, Python) as well as a variety of related topics that deal with modern computing.

# **Fair Warning…**

This course is going to challenge and frustrate you. **I promise**. You are learning a whole slew of different approaches to working with computers – and several of those involve learning new (computing) languages. Along with the hard parts of learning several different types of languages in an abbreviated period, you will also have to learn new tools that you have not (likely) been exposed to. That’s also really hard. To top it all off, you’re also going to have to do some problem solving. But, if you think, work hard, and collaborate with me and your classmates to understand what’s going on, you will end up learning much, much more in a shorter period than you expected.

# **Teaching Philosophy / Communication**

I’m here to introduce you to a variety of languages, techniques, and approaches that are used in computational analyses of data – sometimes called “Data Science”. It’s up to you to learn how to make that work for you. My role is to provide guidance and direction, and your role is to use that guidance and direction to get where you want/need to go.

I teach this course like a graduate class – meaning that I try to minimize busy work… the assignments given to you are meant to teach you certain skills. **You will also have to do a fair amount of unsupervised work outside of class** to complete the assignments – meaning that sometimes you will be teaching yourself (and possibly your classmates) how to do various things related to an assignment for the course. If you decide that you like this sort of thing (computational analyses/data science) and want to do this as a career, you will be teaching yourself this way for the rest of your life. So, better to start learning how to do that now.

Part of the learning process in this course is figuring out how to search for and find the information you need to understand and solve a problem that you are having, and a wise person once said that “90% of programming is learning how to Google”. That idea is just as important today as it was when uttered. Learn how to answer a question for yourself, test out some new ideas if you’re close but not quite there, and you’ll be mastering the basics in no time.

**THAT SAID, A WISE PERSON ALSO SAID THAT USING THESE TYPES OF INFORMATION WITHOUT ATTRIBUTION IS PLAGIARISM.**

So, DO NOT use these sources without attribution (you can use code comments in your assignments for attribution of ideas – include the URL and author \[if known\]). **DO NOT** depend on these sources as a crutch to help you succeed in this course. I will eventually start to notice if all of your assignments are using code from elsewhere. And, you will eventually suffer as we reach the middle to the end of the course.

# **Statement on Using Artificial Intelligence for Assignments**

Artificial intelligence (AI) exists in lots of forms, and these tools (GPT, Claude, Gemini, etc.) can be extremely useful for helping you learn how to code, finding bugs in existing code, generally figuring out how stuff works, etc.

For most of the assignments in this class, you can definitely use artificial intelligence to get the answers to the various questions I’m posing – the skill level at which we are working in this course is simply not high enough to ask the types of questions that AI cannot answer well.

And, I cannot **force** you to limit your use of AI in the course. **BUT** I am going to require that when/if you use AI to provide an answer, you indicate to me that you’ve done so. Otherwise, I’ll put this in the same bucket as plagiarizing other answers that you might find on Google.

Additionally, if you use some sort of AI to complete **every** assignment, then you’re not really going to learn all that much about how the different tools we are covering REALLY work. You are also going to do poorly on the **written exams that you will be taking** where the only thing that you can use to answer the question is your brain and a pencil or a pen.

# **What You Should Be Doing Throughout the Course**

In a word: experimenting. The best way for you to learn what works is to try different things out. For example, if I tell you that you have a list containing \[1,2,3,4\] and ask you how to drop the last number, you should look up several ways that you might go about doing this **and you should try those in Python** (in a Codespace or on your own computer).

There are lots of solutions, like:

> \# create the list
>
> l = \[1,2,3,4\]
>
> \# the smart
>
> new_l = l\[:3\]
>
> \# the redundant
>
> new_l = \[item for item in l\[:3\]\]
>
> \# the snarky - this actually doesn’t count - you’re just making a new list.
>
> new_l = \[1,2,3\]
>
> \# the "I read the documentation and think this is smart"
>
> new_l = l.remove(4)

So, try them all out and see what each does. Maybe think about (or test) which one is faster/slower. ***You should be doing this for everything!!!*** **Part of learning this new language is experimenting with it – some of those experiments will go well, and some will not – but that is how you learn.**

# **Primary Languages For the Course**

- BASH
- Regular expressions (specifically Perl-compatible regular expressions)
- Python 3.10

I no longer include [R](https://www.r-project.org) as one of the languages used during the class. Python is an easier-to-learn, more generalizable language that (in my opinion) lets you learn the basics without getting in your way.  I also helps you learn general concepts that you can apply to other languages (at a later time), like [R](https://www.r-project.org)

# **Textbooks**

There are several references that will be helpful to you (in addition to the course slides/notes). The following are referenced in the schedule at the end of this syllabus.

## **Think Python: How to Think Like a Computer Scientist — Allen Downey (AKA HTLCS)**

This is a freely available textbook. We will follow parts of it for the class when we discuss Python. It is also an invaluable reference when you need to remind yourself of relatively simple Python details.

- [HTML](http://www.greenteapress.com/thinkpython2/html/index.html) \| [PDF](http://www.greenteapress.com/thinkpython2/thinkpython2.pdf)

# **Other Sources of Information**

The following sources of information are ancillary to the texts listed above. They can still be useful, and all are definitely useful after you finish this course (and move to more advanced data science courses).

## **Python Documentation**

- [docs.python.org/3.10](https://docs.python.org/3.10/)

This is the official Python language documentation. It tells you how the language works and should be one of the first places you look for answers when you are stuck (or when you know what you want to do, but don’t know how to do it). In particular, the “Library Reference” section of this document details how parts of the Python language work.

## **BioPython Documentation**

- [biopython.org/wiki/Documentation](https://biopython.org/wiki/Documentation)

BioPython is a module for Python that enables biologists to work more easily with different sequence data formats (sequences, alignments, etc.) from within Python. Very commonly used for various bioinformatic analyses.

## **Polars Documentation**

- [docs.pola.rs](https://docs.pola.rs)

Polars is a module for Python that basically introduces data frames to the Python language. In some senses, Polars R-ifies Python and lets you work with data frames much in the way you would using R.

## **Plotnine Documentation**

- [plotnine.org/reference/](https://plotnine.org/reference/)

Plotnine is a module for Python that introduces data frames to the Python language. In some senses, Polars R-ifies Python and lets you work with data frames much in the way you would using R.

# **GitHub, and GitHub Codespaces**

As we did the last time I taught this class, we’ll (mostly) be using an online development environment that is part of [GitHub](https://github.com/). GitHub provides a number of services, but what it is mostly known for is the fact that it helps you manage source code. This means that it helps you keep track of changes, revert changes, add improvements, make software releases, etc. It does **VERY** many other things. Because [GitHub](https://github.com/) is powerful, it can also be pretty confusing.

Within [GitHub](https://github.com/), there are these things called [Codespaces](https://github.com/features/codespaces). A Codespace is basically a way for you to start up a virtual computer in the cloud and interact with it. You can do this using any browser on your iPad, laptop, phone, etc.

I have chosen to teach the class using these Codespaces because it means we are all interacting with the *exact* same operating system in the cloud – and we don’t have to worry about weird implementation differences that can occur during class if some people are working on Macs, others on Windows, even others on Linux, some on iPads, etc. The operating system (OS) that each Codespace for this class runs is Linux. Specifically, the OS is [Ubuntu 22.04](https://releases.ubuntu.com/jammy/).

## **Why are we using GitHub Codespaces?**

1.  Because teaching computation and data science courses where everyone’s laptop runs a different OS is difficult and error prone.
2.  I can basically build a cloud computer for class that has all the stuff we need already installed.
3.  Codespaces work on a laptop, desktop, or tablet (for the most part, you just need a modern browser).
4.  Codespaces make it easier to grade assignments, provide you with feedback, interact with you when writing code, etc.

# **Grading**

In accordance with the LSU grading policy, grades will be assigned using an A–F scale and the +/– system. Grading is pretty simple:

| **Item** | **Points** | **\# of assignments** | **Total points** | **% of grade** |
|:---|:---|:---|:---|:---|
| Class assignments | 25 each | 10 | 250 | 45% |
| Exam 1 | 50 | - | 50 | 10% |
| Exam 2 | 75 | - | 75 | 15% |
| Exam 3 (Final) | 125 | - | 125 | 25% |
| **Total** |  |  | **500 points** | **100%** |

# **Absentee Policy**

You are expected to attend all classes. Doing so will make your life easier – I’ll explain the concepts we are trying to understand, we’ll have some demonstrations, you can ask questions, I can answer your questions by showing you how something works, etc.

That said, I understand that sometimes absences are inevitable. I will be putting the lecture notes online, but you are responsible for following up with me or a classmate if you have questions.

**You are also expected to turn in the assignments on time, although if you have a legitimate excuse for missing an assignment, I will work with you to make that up.**

# **Students with Accommodations**

If you require accommodations, please ensure that I know about this so that I can make the appropriate arrangements that will help you be successful in this course. I am more than happy to work with you to ensure you will be successful.

# **Course Design**

The course will be a mix of lecture, in-class “active” learning, and individual assignments. That keeps it fun for all of us. You will be expected to contribute to discussions in class. Also, see Commitment to Community and Academic Integrity, below, regarding my expectations with respect to being civil to your classmates and doing your own work.

# **Lecture**

Some portions of our class will be lecture-based. These lectures will, for the most part, derive from the slides that I will post for you. I, of course, will elaborate on some items and focus less on others during class – as I feel they are appropriate. There will sometimes be associated reading that goes along with a lecture/focus area and it would be wise for you to read that assigned reading prior to coming to class. You may want to read the same chapter, again, after lecture. Repetition is one key to learning a new language efficiently.

# **Class Assignments**

There are class assignments which are due every week, on Tuesday, before class. To receive credit for those assignments, you will need to turn them in on time. Late assignments will receive a score of zero.

Assignment scores will post to Moodle. The score that you receive on any given assignment will be based on whether or not you followed instructions and/or composed a program (or a script) that met the design goals. Generally, this means that your function or program produces the expected output by following a progression of steps.

For example, if I ask you to write a computer program to compute the value of the constant `e`, but you simply output the value of `math.e` (in Python) without specifically computing `e`, you will not receive credit for that portion of the assignment, because you have not correctly implemented the requested solution.

# **Exams**

You will have three exams associated with this class. These exams will be in-person, and they will be on paper - requiring you to use a pencil and paper to answer the questions.  This will ensure that if you have been using AI as a crutch rather than a tool to help you learn, you will not do well. The exams increase in their overall value during the course.  This gives you a chance to learn how to take the exam before the stakes get super-high.

Expect for **each exam** to be comprehensive.  Meaning, I can ask you about anything that we have covered during the course.

The types of questions on the exam may range from general (“Who was Ada Lovelace?”) to specific (“What is the difference between an integer and a float? Why is a tuple better to hold data?”). You will be requested to provide (in writing) either code or pseudocode explaining how you would solve the question.

# **Extra Credit**

There are no assignments for extra credit in this course. However, the first homework assignment is a total gimme, so that's giving you 25 points for free.

# **Conduct**

The use of your phone for texting, Facebooking, Instagramming, or (more generally) using the Internet for **non-class-related purposes** during the lecture may result in you being asked to leave the class.

Not only is this distracting for me, but it’s distracting for the other students in class who are there to learn something. We will sometimes use the Internet for class activities (and to break up the lecture) and using your phones/computers for this purpose is permitted.

# **Academic Integrity**

I take academic integrity seriously. You are expected to reference sources appropriately in your written work, as noted above. **You are absolutely expected to reference any third-party computer code that you include in your assignments**. You should also not copy the work of others. Simply copying someone’s work and changing variable names is still plagiarizing their work.

In previous years, I caught several students in this course for plagiarizing. All of them were found to have plagiarized, and all suffered several penalties including a note on their transcript that they violated the academic honor code. **YOU NEED TO BE VERY, VERY CAREFUL NOT TO INAPPROPRIATELY USE THE WORK OF OTHERS**. As mentioned above, this goes for the use of AI, as well.

High standards of academic integrity are crucial for the University to fulfill its educational mission. To uphold these standards, procedures have been established to address Academic Misconduct. LSU students are responsible for submitting work for evaluation that reflects their performance. If the student has a question regarding the my expectations for assignments, projects, tests, or other items submitted for a grade, it is the student’s responsibility to seek clarification from me. All students are expected to read and be familiar with the **LSU Code of Student Conduct**, found online in the [Student Code of Conduct](https://www.lsu.edu/saa/students/codeofconduct.php#collapseTen). It is your responsibility as a student at LSU to know and understand the academic standards for our community.

# **Working Together**

You may ask your classmates about general ideas related to the course, and you are free to demonstrate to one another how this or that idea works. **HOWEVER**, you are expected to complete your assignments on your own, without help from anyone else. If you use other sources, please cite them. If I determine that you are citing too many sources rather than doing your own work, your score for that assignment will indicate that you have not shown mastery of the material.

# **Academic Misconduct**

If I suspect that you have committed Academic Misconduct, I am required to give you an incomplete on the assignment and report the incident to the Student Advocacy and Accountability office. They will follow-up. Although this is a time-consuming process, I have taken this step several times before. Please do not make me do this.

Full definitions of academic misconduct are provided in the [Student Code of Conduct](https://www.lsu.edu/saa/students/codeofconduct.php#collapseTen).


# **Commitment to Community**

You should be familiar with the [LSU Commitment to Community](https://www.lsu.edu/saa/docs/code_of_student_conduct_revised_january_2023.pdf). You should also be familiar with the [LSU Code of Student Conduct](https://www.lsu.edu/saa/students/codeofconduct.php). You are expected to follow the Commitment to Community during your time in this class and when working on assignments outside of class. Students who do not respect the instructor(s) or other members of the class will be asked to leave the lecture. This includes using the telephone, texting, or using the internet for non-class-related purposes during the lecture.

# **Recommendation Letters**

I do not typically write recommendation letters for students in this class – even though this class is on the smaller side, it remains hard for me to interact with you in a way that ensures I write a meaningful letter of support. I write recommendation letters for those students who work in my laboratory because it gives me a chance to know them well and to write recommendations that have meaning. I suggest, if you think you will need a recommendation letter (e.g., for medical school), that you try and work directly with faculty members or faculty-led groups on campus so that these individuals or group supervisors can write meaningful recommendation letters for you.

# **Schedule**

\* CS = Github Codespace, HTLCS = How To Think Like A Computer Scientist

| **Lec.** | **Date** | **Topic** | **Reading** | **Assignment** |
|:---|:---|----|:---|:---|
| 00 | 25 Aug | [Intro: Operating and File Systems][00s] |  |  |
| 01 | 27 Aug | [Intro: Filesystems, Codespaces, Command Line][01s] |  | Homework 0 |
| 02 | 01 Sep | CLI: Intro to the command Line (notes in CS) |  |  |
| 03 | 03 Sep | CLI: More Command Line (notes in CS) |  | Homework 1 |
| 04 | 08 Sep | CLI: More Command Line Pt 2 (notes in CS) |  |  |
| 05 | 10 Sep | CLI: Variables, Loops, Variables In Loops (notes in CS) |  | Homework 2 |
| 06 | 15 Sep | CLI: More Loops, Conditionals (notes in CS) |  |  |
| 07 | 17 Sep | CLI: Flow, Conditional Statements (notes in CS) |  | Homework 3 |
| 08 | 22 Sep | CLI: SED, AWK, Others (notes in CS) |  |  |
| 09 | 24 Sep | Regular Expressions |  |  Homework 4 |
| 10 | 29 Sep | Section 1 – Review, Questions, Practice, etc. |  |  |
| — | 01 Oct | ***Exam 1 – In class. On paper.*** |  |  |
| — | 06 Oct | No Class – BCF at conference. |  |  |
| — | 08 Oct | No Class – Fall Break |  |  |
| 11 | 13 Oct | Python: Variables & Expressions| HTLCS [1][11r1] & [2][11r2] |  |
| 12 | 15 Oct | Python: Functions Part 1 | HTLCS [3][12r1] | Homework 5 |
| 13 | 20 Oct | Python: Conditional Statements | HTLCS [5][13r1] |  |
| 14 | 22 Oct | Python: Functions Part 2 | HTLCS [6][14r1] | Homework 6 |
| 15 | 27 Oct | Python: Iteration | HTLCS [7][15r1] |  |
| 16 | 29 Oct | Python: Strings and Lists | HTLCS [8][16r1] & [10][16r2] | Homework 7 |
| 17 | 03 Nov | Python: Dictionaries and Tuples | HTLCS [11][17r1] & [12][17r2] |  |
| 18 | 05 Nov | Section 2 – Review, Questions, Practice, etc. |  | Homework 8 |
| — | 10 Nov | ***Exam 2 – In class. On paper.*** |  |  |
| 19 | 12 Nov | Python: Getting Stuff In and Out |  | |
| 20 | 17 Nov | Python: File Operations | HTLCS [14][20r1] |  |
| 21 | 19 Nov | Python: The Kitchen Sink |  | Homework 9 |
| 22 | 24 Nov | Python: Modules, Biopython | Biopython |  |
| — | 26 Nov | No Class – Thanksgiving Holiday |  |  |
| 23 | 01 Dec | Python: Modules, Polars|  Polars |  |
| 24 | 03 Dec | Python: Modules, Plotnine |  |  |
| — | 10 Dec | ***FINAL EXAM, 10:00 AM – 12:00 PM. On paper.*** |  |  |

[00s]: https://www.dropbox.com/scl/fi/r03cnf78ksswit0auu0n4/00-intro-os-and-filesystems.pdf?rlkey=ti38hx93i2ozlgqob75z5gw9f&st=i7w5kj1k&dl=0
[01s]: https://www.dropbox.com/scl/fi/w1ew6bm4l7tl5rhvj0k0k/01-filesystems-and-commandline.pdf?rlkey=8ixc3imkre98ifpnphby4b091&st=eev4wau4&dl=0

[11r1]: https://www.greenteapress.com/thinkpython2/html/thinkpython2002.html
[11r2]: https://www.greenteapress.com/thinkpython2/html/thinkpython2003.html
[12r1]: https://www.greenteapress.com/thinkpython2/html/thinkpython2003.html
[13r1]: https://www.greenteapress.com/thinkpython2/html/thinkpython2006.html
[14r1]: https://www.greenteapress.com/thinkpython2/html/thinkpython2007.html
[15r1]: https://www.greenteapress.com/thinkpython2/html/thinkpython2008.html
[16r1]: https://www.greenteapress.com/thinkpython2/html/thinkpython2009.html
[16r2]: https://www.greenteapress.com/thinkpython2/html/thinkpython2011.html
[17r1]: https://www.greenteapress.com/thinkpython2/html/thinkpython2012.html
[17r2]: https://www.greenteapress.com/thinkpython2/html/thinkpython2013.html
[20r1]: https://www.greenteapress.com/thinkpython2/html/thinkpython2015.html

# **Software License**

Licenses for different code/software projects are important. I am releasing the contents of this course (e.g. all my notes, etc.) under an [open-source](https://en.wikipedia.org/wiki/Open_source) license ([MIT](https://en.wikipedia.org/wiki/MIT_License)).
