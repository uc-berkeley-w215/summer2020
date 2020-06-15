# Usable Privacy and Security (MICS W215) Syllabus

### Sync Session Time

THURSDAYS@ 4:00pm Pacific

Office hours: Mondays @ 4:00pm Pacific

### Slack channel

### Instructors

> Cristian Bravo-Lillo cristian.bravo \<a\> gmail.com
>
> Stuart Schechter, imposter \<at\> berkeley.edu

### Course Lead

> Stuart Schechter

### Original Course Creators & Video Lecturers

> [Maritza Johnson](http://maritzajohnson.com/), UC Berkeley School of Information
>
> [Serge Egelman](https://www.guanotronic.com/~serge/), UC Berkeley and International Computer Science
> Institute

## Course Description

When computers first came into prominence, security problems were mostly
thought of as technical ones: vulnerabilities were exploited due to
technical errors—software bugs that needed to be patched. However, as is
demonstrated over and over again, the vast majority of modern software
security issues stem from human factors. For instance, most software
vulnerabilities are exploited because *humans* fail to apply patches in
a timely manner; authentication systems that are difficult to use result
in *humans* choosing weaker passwords (or bypassing security measures
altogether); *humans* are tricked into downloading malware or divulging
credentials via phishing; and Internet traffic is easily intercepted
because *humans* fail to properly use encryption technologies.

As you will learn in this course, despite the fact that many security
problems are caused by human error, in most cases, the users aren’t to
blame. Many security problems exist because software is simply
*unusable*; when software engineers fail to account for the abilities
and expectations of their users, those users will make preventable
errors. Security and privacy systems can be made more usable by
designing them with the user in mind, from the ground up. In this
course, you will learn many of the common pitfalls of designing usable
privacy and security systems, techniques for designing more usable
systems, and how to evaluate privacy and security systems for usability.
Through this course you will learn methods for designing software
systems that are more secure because they minimize the potential for
human error.

## Prerequisites

Completion of at least one of the three core courses for the MICS degree
program or permission of the instructor.

## Course Objectives

1.  > Students will learn to identify human factors issues that impact
    > the security and privacy of systems.

2.  > Students will develop skills reading research papers, evaluating
    > their findings, and identifying their limitations.

3.  > Students will learn multiple experimental approaches to evaluating
    > human factors issues in security and privacy.

4.  > Students will learn about current research findings and methods in
    > usable security and privacy.

## Course Evaluation

  - > Async responses and reflections (10%)

  - > Live session participation (20%)

      - > You will lead the discussion of 1-3 papers (depending on
        > course enrollment)

  - > Assignments (10%)

      - > Traditional homeworks

      - > Acting as reviewer or pilot participant for other teams’
        > course projects

  - > Midterm (20%)

  - > [<span class="underline">Final
    > project</span>](/project/)
    > (40%)

## Collaboration Policy

We encourage studying in groups of two to four people. This applies to
working on homework, discussing material, and studying for the exam.
However, students must always adhere to the UC Berkeley Code of Conduct
(http://sa.berkeley.edu/code-of-conduct) and the UC Berkeley Honor Code
(https://teaching.berkeley.edu/berkeley-honor-code). In particular, all
materials that are turned in for credit or evaluation must be written
solely by the submitting student or group. Similarly, you may consult
books, publications, or online resources to help you study. In the end,
you must always credit and acknowledge all consulted sources in your
submission (including other persons, books, resources, etc.).

## Assignments

When homework is assigned, it will be due two hours before the beginning
of the live session.

## Late Submission Policy

Solutions will be discussed during the live sessions of the course.
Therefore, any assignment that is submitted after the deadline will be
returned without grading and will receive a grade of zero.

## Participation

Participation and taking an active part in every aspect of the course
are key to internalizing the material of the course. Participation
includes, but is not limited to, (i) active participation in live
sessions, (ii) discussing assignments with other students, and/or (iii)
activity in the class forum (by asking questions and/or contributing to
answering other students’ questions).

The instructors will also reward participation credit for those who
choose to live tweet their experiences reading the assigned research
papers (see more in the next section). Tag the tweets with
[<span class="underline">\#uc\_berkeley\_w215</span>](https://twitter.com/search?q=%23uc_berkeley_w215).
We would also encourage you to find the authors’ twitter handles and @
them in your tweet. If you have an insight that you’d rather not be made
public, the class slack channel may be a more appropriate forum to share
those thoughts.

## Readings

Reading and understanding research papers is one of the fundamental
skills you will develop in this course. You are expected to read and be
prepared to discuss all the assigned readings. You will be asked to lead
the discussion of research papers in class.

The instructors selected the papers in the first half of the course
(through Unit 7) to provide key background in the field and inspiration
for your course projects.

In the second half of the class, the instructors will examine students’
project proposals and seek out readings that may serve as important
background for those projects. The instructors may then replace many of
the readings tentatively on the syllabus with those new selected
readings.

When it’s your turn to lead the 10-15 minute discussion of the paper,
you'll want to read the guidelines on [leading paper discussions](/leading-paper-discussions.md).

## Textbook

(Required) *Research Methods in Human-Computer Interaction* by Lazar,
Feng, and Hochheiser.



# Schedule

## Unit 1: Human–Computer Interaction – *May 7*

### Readings due

  - Lazar et al., **Skim** Chapter 1: “Introduction” (or just read the end-of-chapter summary)

  - Lazar et al., Chapter 2: “Experimental Research”

  - [<span class="underline">Password Security, A Case History</span>](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.128.1635&rep=rep1&type=pdf), by Morris and Thompson, which describes an early experiment in computer security.

  - [<span class="underline">Why Johnny Can’t Encrypt</span>](http://citeseerx.ist.psu.edu/viewdoc/summary?doi=10.1.1.40.9279), by Whitten and Tygar.

  - [<span class="underline">Simson Garfinkel’s Thesis</span>](https://simson.net/thesis/), Chapter 1.1–1.5, pp. 13–34, and Chapter 10.3 Patterns for Overall Security

### Assignments due

Submit as **assignment 1** a list of three user interfaces or user experiences *related to security or privacy* that you find most infuriating or would most want to fix. Be prepared to talk about them in class during introductions. You may include not only stuff that happened personally to you, but either to your family or friends, or even things that you observed at your work among your colleagues.

### Synchronous discussion agenda

  - Introductions and discussion of personal experiences with usable security & privacy (see assignments) \[Cristian\]

  - Course overview \[Stuart\]

      - Seminar style (explain what that means)

      - The midterm, project, and class participation dominate grading

      - Project: get started early and expect lots of bugs, even the pros require many iterations (and still mess things up in the final problem)

      - Project funding ($100/person)

  - Course participation options (\#uc\_berkeley\_w215) \[Stuart\]

  - Answer administrative questions \[Cristian\]

  - Discussion of readings:
	- \[Cristian: Simson Garfinkel’s Thesis\]
	- \[Stuart:Why Johnny Can’t Encrypt, Password Security, a Case History\]


## Unit 2: Studying Decision making – *May 14*

### Readings due

  - > [<span class="underline">“The Framing of Decisions and the
    > Psychology of
    > Choice”</span>](https://www.jstor.org/stable/1685855?seq=1#page_scan_tab_contents),
    > by Tversky and Kahneman.

  - > [<span class="underline">“Judgment Under Uncertainty: Heuristics
    > and Biases”</span>](https://www.jstor.org/stable/1738360), by
    > Tversky and Kahneman.

  - > [<span class="underline">“Institutional Review Board (IRB) and
    > Ethical Issues in Clinical
    > Research”</span>](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3272525/),
    > by Kim.

### Assignments due

1.  > Complete the IRB training by following the instructions here:
    > [<span class="underline">https://cphs.berkeley.edu/training.html</span>](https://cphs.berkeley.edu/training.html).
    > Make sure that you complete the “Group 2 (soc-behav) Human
    > Subjects Curriculum.” Submit a PDF of your completion certificate
    > as proof of completion.

2.  > Pick a cognitive bias from [<span class="underline">this
    > list</span>](https://en.wikipedia.org/wiki/List_of_cognitive_biases).
    > Create a slide to present in class that explains the bias and how
    > it might impact users’ security or privacy behavior (or the study
    > of that behavior). The slide should be accessible from a URL
    > (link) that you can share via the class chat function.

3.  > Please spend a few minutes writing down your thoughts to each of
    > the questions and be prepared to share them with the class.

    1.  > What are some examples of security interfaces that you use in
        > your daily life that lead to irrational behaviors? (You may
        > start with the examples you and your classmates came up with
        > last week.)

    2.  > What specific biases might impact computer security
        > decision-making and how?

    3.  > What sort of problems are IRBs likely to prevent?

    4.  > What problems are they unlikely to prevent?

    5.  > Should private companies use IRBs for their human-subjects
        > research?

### Synchronous discussion agenda

  - > Apology \[ Stuart\]

  - > First two presentations on user biases \[Stuart\]

  - > Address those questions about ethics training that can’t wait
    > until everyone has completed it \[Stuart\]

  - > Remaining presentations on user biases \[Stuart\]

  - > DIscuss readings \[Cristian\]

  - > Discussion of questions if time available (assignment part 3)
    > \[Cristian\]



## Unit 3: Research Methods: Experimental – *May 21*

### Readings due

  - > Lazar et al., Chapter 3 Experimental Design

  - > Lazar et al., Chapter 10 Usability Testing

  - > [<span class="underline">The Emperor’s New Security Indicators: An
    > Evaluation of Website Authentication and the Effect of Role
    > Playing on Usability
    > Studies</span>](http://commerce.net/wp-content/uploads/2012/04/The%20Emperors_New_Security_Indicators.pdf),
    > by Schechter et al.

### Assignments due

  - > **Heuristic evaluation** (a method discussed in the async lecture
    > for this unit)**
    > **Perform a heuristic evaluation of a security feature in your web
    > browser or on a website. You may do this either in pairs, or
    > individually. You may find useful the classic article on
    > [<span class="underline">how to conduct an heuristic
    > evaluation</span>](https://www.nngroup.com/articles/how-to-conduct-a-heuristic-evaluation/),
    > by Jakob Nielsen.

<!-- end list -->

1.  > Choose a set of heuristics or create your own, but be sure to do
    > so **before analyzing the security feature**. Document the
    > heuristics that you plan to use, and explain why you chose them.

2.  > Apply those heuristics to a security feature in an application or
    > website, or apply security-specific heuristics to a feature that
    > impacts security even though security is not its primary function.
    > Be sure to mention who you’re designing for. If you do this
    > assignment in pairs, each evaluator should apply the heuristics
    > separately, and then merge the results.

3.  > Document your results using screenshots of the application or
    > website you are analyzing; if possible, draw over the images to
    > highlight those features that you (or any other evaluators) are
    > focusing on when conducting the evaluation.

4.  > Provide suggestions on how any potential problems could be
    > improved.
    > *Your suggestion might be a new design, change to a feature, or it
    > might be a suggestion for additional empirical research.*

### Synchronous discussion agenda

  - > Discuss answers to the assignment. (15 minutes)

  - > Discuss paper. (15 minutes) \[Cristian\] (Stuart will use this
    > time to put together breakout groups\]

  - > Split into breakout groups to discuss the following: \[Cristian\]

> *“Imagine you are the head of engineering for a software company.
> Based on reports from customers, you are aware of some usability
> issues in the latest version of your product. How would you go about
> designing a study to determine how prevalent this problem is across
> your user base?”*
>
> The class will be split into groups of 3 students, so that each group
> designs a study to examine one of the following products and
> associated usability issues:

1.  > *Phone lock screen software*: users complain about it taking too
    > much time to login.

2.  > *Photo-sharing software*: users complain upon discovering that all
    > of their photos are publicly-accessible.

3.  > *Application Programming Interface (API) for Cryptographic
    > Operations*: a measurement study shows that most applications use
    > the API incorrectly, resulting in insecure software built around
    > the API.

4.  > *Secure messaging software*: users complain about not
    > understanding how to verify that the people with whom they
    > communicate via the software are the people they believe them to
    > be. Some people have even reported cases of impersonation.

5.  > *Social media authentication*: users complain that they cannot log
    > into their accounts when they have multiple devices.

> Please be aware that descriptions above are (purposefully) incomplete;
> use the assigned sync time to attempt to define exactly what is the
> question you would like to have answered to improve your product, and
> how human subjects may help you answer that question. This discussion
> will be wrapped up during Unit 4, where you will read about research
> methods to complete your task.


## Unit 4: Research Methods: Descriptive and Relational – *May 28*

### Readings due

  - > Lazar et al., Chapter 5 Surveys

  - > Lazar et al., Chapter 8 Interviews and Focus Groups

  - > [<span class="underline">Using Fingerprint Authentication to
    > Reduce System Security: An Empirical
    > Study</span>](https://drive.google.com/file/d/1iXa3nLVlDFnsRxzT5d1d3Dpnr1mNX2i7/view?usp=sharing),
    > by Wimberly and Liebrock

  - > [<span class="underline">Operating System Framed in Case of
    > Mistaken
    > Identity</span>](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/osframed.pdf),
    > by Bravo-Lillo et al., *discussion to be lead by Ramana
    > Kapavarapu*

### Assignments due

  - Complete breakout group mini-project proposal from Unit 3

### Synchronous discussion agenda

1.  > Stuart leads discussion of Wimberly and Liebrock (15 min)

> *Beginning of student-led discussions of assigned papers. You may
> volunteer to briefly discuss a paper (no more than 10 minutes); please
> read the instructions in the “Readings” section at the beginning of
> this document.*

2.  Ramana leads discussion of Bravo-Lillo et al. (15 min)

3.  Cristian discusses answers to async content (hard stop at 50 minutes
    after)

    1.  > The purpose of a survey and each question are not always
        > apparent to participants.

    2.  > Sometimes “distractor” questions exist to hide the purpose of
        > another question, or of an entire survey.

    3.  > Providing the wording of questions, but not the answer
        > options, interferes with reviewers’ understanding of how
        > participants answered the survey.

4.  Breakout-group teams from previous class present \[4 groups x 5
    minutes/group\]

5.  Stuart introduces
    [<span class="underline">projects</span>](/project/)


## Unit 5: Statistics – *June 4*

### Readings due

  - > Lazar et al., Chapter 4 Statistical Analysis

  - W215 [<span class="underline">Project
    Guidelines</span>](/project/)
    (guidelines for *your* course project)

  - [<span class="underline">When Security Gets in the
    Way</span>](https://jnd.org/when_security_gets_in_the_way/), by Don
    Norman
    *Discussion lead: Kai Tang*

[<span class="underline">A Large-Scale Study of Web Password Habits, by
Florencio & Herley</span>](https://cormac.herley.org/docs/www2007.pdf)
(2007)

*Discussion lead: \<submit a pull request to replace this with your
name\>*

  - > [<span class="underline">Experimenting at Scale With Google
    > Chrome’s SSL
    > Warning</span>](https://static.googleusercontent.com/media/research.google.com/en//pubs/archive/41927.pdf),
    > by Felt et al. (2014)
    > Discussion lead: Neeraj Singh

### Assignments due

  - [Perform a sample-size determination](/assignments/sample.size.md)

### Synchronous discussion agenda

  - Discuss sample size assignment and its implications for projects (15
    minutes, Stuart leads) \[Encourage suggestions for improvements in
    assignment text?\]

  - Readings (\~45 minutes, 15-minutes each), note problem/hypothesis
    statements (Cristian)

  - Introduction to course project (remaining time)


## Unit 6: Usable Security – *June 11*

### Readings due

  - > Lazar et al., Chapter 11 Analyzing Qualitative Data

  - > [<span class="underline">No One Can Hack My
    > Mind</span>](https://www.usenix.org/system/files/conference/soups2015/soups15-paper-ion.pdf),
    > by Ion, Reeder, and Consolvo
    > *Discussion lead: Neeraj Singh (back for more\!)*

  - > [<span class="underline">The Quest to Replace Passwords: A
    > Framework for Comparative Evaluation of Web Authentication
    > Schemes</span>](https://www.cl.cam.ac.uk/~fms27/papers/2012-BonneauHerOorSta-password--oakland.pdf),
    > by Bonneau et al.
    > *Discussion lead: Christian Hercules*

### A brief note about framing a research problem

In the breakout group projects that we started during class 4 and
presented in class 5, we hope you all learned that:

1.  > Understanding the specifics of a problem is an essential first
    > step and worth your time.

2.  > Different assumptions of costs and benefits can lead to very
    > different research designs.

Therefore, when you are pitching projects ideas, put 80% of your effort
into writing a crisp and clear definition of the problem you want to
investigate or hypothesis you wish to test, and then 20% of effort into
saying which research method (survey, lab study, field study, etc.)
would best apply to the problem.

### Assignments due

  - Submit a proposed course project idea

Share the idea as a Google doc with at least two paragraphs, share a link to it to the course slack channel at least an hour before the sync session, and be prepared to answer questions about what you wrote during the session.

### Synchronous discussion agenda

  - Readings (30 minutes)

  - Individuals to present project ideas.

  - Students to split off into groups to discuss proposed ideas in
    depth.



## Unit 7: Privacy – *June 18*

### Readings due

  - > [<span class="underline">A Taxonomy of Privacy</span>](https://www.law.upenn.edu/journals/lawreview/articles/volume154/issue3/Solove154U.Pa.L.Rev.477\(2006\).pdf), by Solove. (Please read up to page 491; that is, right before the section “Information collection”).
    > *Discussion lead: Bryan Everly*

  - > [<span class="underline">Privacy Attitudes and Privacy Behavior: Losses, Gains, and Hyperbolic Discounting</span>](http://www.heinz.cmu.edu/~acquisti/papers/acquisti_grossklags_eis_refs.pdf), by Acquisti and Grossklags.
    > *Discussion lead: Josh Arteaga*

  - > [<span class="underline">The Effect of Online Privacy Information on Purchasing Behavior: An Experimental Study</span>](http://www.guanotronic.com/~serge/papers/isr10.pdf) by Tsai, Egelman, Cranor, and Acquisti.
    > *Discussion lead: David Ng*

### Assignments due

  - [<span class="underline">Identify flaws in a study design</span>](/assignments/study-design-flaws.md)

  - Prepare to discuss your progress on your project proposal so you can get more feedback before it’s due at Unit 8.

### About the midterm

It will be open book; topics to include (but not limited to):

  - Readings

  - Types of experiments (Survey, Interview, Lab, Field, Focus group, etc.)

  - Sources of bias, alternative hypotheses, and other methodological limitations

  - Statistical tests

  - Ethics

### Synchronous discussion agenda

  - Project updates (45 minutes)

  - Paper discussion (45 minutes)



## Unit 8: Midterm – *June 25*

### Readings due

  - > Lazar et al., Chapter 9 Ethnography

### Assignments due

  - > **Project proposals due 48 hours before class (June 22)**
    > *During those 48 hours you can focus on the midterm, and your
    > instructors will do their best to ensure there’s valuable feedback
    > waiting for you when the midterm is over or shortly thereafter.*

### Synchronous agenda

> **Midterm**



## Unit 9: Authentication & Trusted Path – *July 2*

### Readings

  - [<span class="underline">Of Passwords and People: Measuring the
    Effect of Password-Composition
    Policies</span>](https://users.ece.cmu.edu/~mmazurek/papers/chi2011_passwords_people.pdf)
    *Discussion lead: Ramadhan Putra*

  - [<span class="underline">It’s Not What You Know, but Who You Know: A
    Social Approach to Last-Resort
    Authentication</span>](http://robreeder.com/pubs/whoYouKnow_CHI09.pdf)
    *Discussion lead: Chukwunenye Nnebe*

**or\*** (\* please DM the instructors before class to let them know
which you chose)

  - > [<span class="underline">It’s No Secret: Measuring the Security
    > and Reliability of Authentication via “Secret”
    > Questions</span>](http://www.guanotronic.com/~serge/papers/oakland09.pdf)
    > *Discussion lead: Jacky Ho*

### Assignments due

  - > Make progress on your course project

### Synchronous discussion agenda

  - > Post-midterm sync (15 minutes)

  - > Discuss papers (45 minutes: 15 each)

  - > Discuss projects (remaining time)


## Unit 10: Access Control – July 9

### Possible readings (actual readings TBD \~8 days in advance)

  - > Anderson, R. (2008) *Security engineering: A guide to building
    > dependable distributed systems*. Chapter 4.
    > [<span class="underline">https://www.cl.cam.ac.uk/\~rja14/Papers/SEv2-c04.pdf</span>](https://www.cl.cam.ac.uk/~rja14/Papers/SEv2-c04.pdf)

  - > Maxion, R. A., & Reeder, R. W. (2005). Improving user-interface
    > dependability through mitigation of human error. *International
    > Journal of Human–Computer Studies, 63*(1–2), 25–50.
    > [<span class="underline">http://www.robreeder.com/pubs/salmonIJHCS2005.pdf</span>](http://www.robreeder.com/pubs/salmonIJHCS2005.pdf)

  - > Mazurek, M. L., Arsenault, J. P., Bresee, J., Gupta, N., Ion, I.,
    > Johns, C., . . . Reiter, M. K. (2010). *Access control for home
    > data sharing: Attitudes, needs and practices.* Proceedings of the
    > SIGCHI Conference on Human Factors in Computing Systems, ACM,
    > [<span class="underline">https://www.archive.ece.cmu.edu/\~lbauer/papers/2010/chi2010-home-access-control.pdf</span>](https://www.archive.ece.cmu.edu/~lbauer/papers/2010/chi2010-home-access-control.pdf)

<!-- end list -->

  - > Bauer, L., Cranor, L. F., Reeder, R. W., Reiter, M. K., & Vaniea,
    > K. (2009, April). *Real life challenges in access-control
    > management*. Proceedings of the SIGCHI Conference on Human Factors
    > in Computing Systems, CHI.
    > [<span class="underline">https://www.archive.ece.cmu.edu/\~lbauer/papers/2009/chi09-management.pdf</span>](https://www.archive.ece.cmu.edu/~lbauer/papers/2009/chi09-management.pdf)

  - > Johnson, M. L., Bellovin, S. M., Reeder, R. W., & Schechter, S. E.
    > (2009). Laissez-faire file sharing: Access control designed for
    > individuals at the endpoints. *New Security Paradigms Workshop*,
    > NSPW.
    > [<span class="underline">https://academiccommons.columbia.edu/doi/10.7916/D8D79J6W/download</span>](https://academiccommons.columbia.edu/doi/10.7916/D8D79J6W/download)

  - > He, W., Golla, M., Padhi, R., Ofek, J., Durmuth, M., Fernandes,
    > E., & Ur, B. (2018). *Rethinking access control and authentication
    > for the home internet of things (IoT*). Proceedings of the 27th
    > USENIX Security Symposium (USENIX Security 18).
    > [<span class="underline">https://www.blaseur.com/papers/usenixsec18.pdf</span>](https://www.blaseur.com/papers/usenixsec18.pdf)

  - > Jaferian, P., Rashtian, H., & Beznosov, K. (2014). *To authorize
    > or not authorize: Helping users review access policies in
    > organizations.* Proceedings of the 10th Symposium on Usable
    > Privacy and Security, SOUPS.
    > [<span class="underline">https://www.usenix.org/system/files/conference/soups2014/soups14-paper-jaferian.pdf</span>](https://www.usenix.org/system/files/conference/soups2014/soups14-paper-jaferian.pdf)

### Assignments due

  - > Second discussion-lead for those who haven’t done two already
    > (Previous term did: Assignment 8: Research paper summary)

### Synchronous discussion agenda

  - > Discuss the assigned reading (\~60 minutes)

  - > Project teams give project update (5m per group)

  - > Remainder of time for project team breakouts.



## Unit 11: Warnings – *July 16*

### Possible readings (actual readings TBD 8 days before)

  - > [<span class="underline">You’ve Been Warned: An Empirical Study of
    > the Effectiveness of Web Browser Phishing
    > Warnings</span>](http://www.guanotronic.com/~serge/papers/warned.pdf)

  - > [<span class="underline">A Week to Remember: The Impact of Browser
    > Warning Storage
    > Policies</span>](https://www.usenix.org/system/files/conference/soups2016/soups2016-paper-weinberger.pdf)*,
    > by Weinberger and Felt*

  - > [<span class="underline">Put your warning where your link is:
    > Improving and evaluating email phishing
    > warnings</span>](https://dl.acm.org/doi/pdf/10.1145/3290605.3300748)*,
    > by Petelka et al.*

### Assignment

  - > Submit updated drafts of final project plans

  - > Review or pilot study materials for another project team

### Synchronous discussion agenda

  - > Discuss assigned readings (\~45 minutes)

  - > Discuss projects progress (\~45 minutes)



## Unit 12: Mobile Permissions – *July 23*

### Readings

  - Balebako, R., Jung, J., Lu, W., Cranor, L., & Nguyen, C. (2013).
    *Little brother’s watching you: Raising awareness of data leaks on
    smartphones.* Proceedings of the 9th Symposium on Usable Privacy and
    Security, SOUPS.
    [<span class="underline">http://cups.cs.cmu.edu/soups/2013/proceedings/a12\_Balebako.pdf</span>](http://cups.cs.cmu.edu/soups/2013/proceedings/a12_Balebako.pdf)
    *Discussion lead: Abdulkadir Egal*


### Possible readings (actual readings TBD 8 days before)

  - > Felt, A. P., Ha, E., Egelman, S., Haney, A., Chin, E., & Wagner,
    > D. (2012). *Android permissions: User attention, comprehension,
    > and behavior.* Proceedings of the 8th Symposium on Usable Privacy
    > and Security. ACM.
    > [<span class="underline">http://cups.cs.cmu.edu/soups/2012/proceedings/a3\_Felt.pdf</span>](http://cups.cs.cmu.edu/soups/2012/proceedings/a3_Felt.pdf)

  - > Kelley, P. G., Cranor, L. F., & Sadeh, N. (2013). *Privacy as part
    > of the app decision*-*making process.* Proceedings of the SIGCHI
    > Conference on Human Factors in Computing Systems, CHI.

  - > Egelman, S., Felt, A. P., & Wagner, D. (2013). Choice architecture
    > and smartphone privacy: There’s a price for that. In *The
    > economics of information security and privacy.* Berlin, Germany:
    > Springer, 211–236.
    > [<span class="underline">https://www.guanotronic.com/\~serge/papers/weis12.pdf</span>](https://www.guanotronic.com/~serge/papers/weis12.pdf)

  - > Thompson, C., Johnson, M., Egelman, S., Wagner, D., & King, J.
    > (2013). *When it’s better to ask forgiveness than get permission:
    > Attribution mechanisms for smartphone resources.* Proceedings of
    > the 9th Symposium on Usable Privacy and Security, ACM.
    > [<span class="underline">https://www.guanotronic.com/\~serge/papers/soups13.pdf</span>](https://www.guanotronic.com/~serge/papers/soups13.pdf)

### Assignments due

  - > Prepare to present your project study materials

  - > Review or pilot at least two other teams’ survey instrument, study
    > design, or other materials

### Synchronous discussion agenda

  - > Discuss the assigned reading (\~15 minutes)

  - > Project teams present their current draft study design/materials
    > (e.g. survey instrument)



## Unit 13: Secure Communication – *July 30*

### Possible readings (actual readings TBD)

  - > Unger, N., Dechand, S., Bonneau, J., Fahl, S., Perl, H., Goldberg,
    > I. & Smith, M. (2015). *SoK: Secure messaging*. Proceedings of the
    > 2015 IEEE Symposium on Security and Privacy, pp. 232–249, IEEE.
    > [<span class="underline">https://oaklandsok.github.io/papers/unger2014.pdf</span>](https://oaklandsok.github.io/papers/unger2014.pdf)

<!-- end list -->

  - > Lerner, A., Zeng, E., & Roesner, F. (2017). *Confidante: Usable
    > encrypted email: A case study with lawyers and journalists*.
    > Proceedings of the 2017 IEEE European Symposium on Security and
    > Privacy (EuroS\&P), IEEE.
    > [<span class="underline">https://www.franziroesner.com/pdf/confidante-eurosp17.pdf</span>](https://www.franziroesner.com/pdf/confidante-eurosp17.pdf)

  - > Edwards, W. K., Poole, E. S., & Stoll, J. (2007). *Security
    > automation considered harmful?* Proceedings of the 2007 Workshop
    > on New Security Paradigms, ACM.
    > [<span class="underline">https://www.cs.drexel.edu/\~greenie/cs680/nspw07-security-automation.pdf</span>](https://www.cs.drexel.edu/~greenie/cs680/nspw07-security-automation.pdf)

  - > Smetters, D. K., & Grinter, R. E. (2002). *Moving from the design
    > of usable security technologies to the design of useful secure
    > applications.* Proceedings of the 2002 Workshop on New Security
    > Paradigms, ACM.
    > [<span class="underline">https://www.nspw.org/2009/proceedings/2002/nspw2002-smetters.pdf</span>](https://www.nspw.org/2009/proceedings/2002/nspw2002-smetters.pdf)

### Assignment

  - > Help a project team other than (in addition to) your own.

### Synchronous discussion agenda

  - > Discuss the assigned reading (\~45 minutes)

  - > Project teams give project update (5m per group)

  - > Remainder of time for project teams.



## Unit 14: Privacy Policies – *August 6*

### Possible readings (actual readings TBD)

  - > [<span class="underline">Necessary but Not Sufficient:
    > Standardized Mechanisms for Privacy Notice and
    > Choice</span>](http://www.jthtl.org/content/articles/V10I2/JTHTLv10i2_Cranor.PDF)

  - > [<span class="underline">User Interfaces for Privacy
    > Agents</span>](http://lorrie.cranor.org/pubs/privacy-bird-20050714.pdf)

  - > [<span class="underline">What Do Online Behavioral Advertising
    > Privacy Disclosures Communicate to
    > Users?</span>](http://www.blaseur.com/papers/wpes2012-obaicons.pdf)

  - > [<span class="underline">A Comparative Study of Online Privacy
    > Policies and
    > Formats</span>](http://lorrie.cranor.org/pubs/authors-version-PETS-formats.pdf)

### Assignment

  - > Final project due

### Synchronous discussion agenda

  - > Final project presentations (15 minutes, 5-10 for presentation)

  - > Paper discussions (45 minutes)
