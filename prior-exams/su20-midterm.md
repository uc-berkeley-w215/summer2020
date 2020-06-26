# MICS W215 Midterm Exam (SU'20)

## Rules

You may ask the course staff questions privately during the exam, but otherwise may not use any human assistance. You may use your book and readings as a reference, as well as static web-based materials (e.g., Wikipedia, Berkeley Library resources) during this exam. However, if you do, please cite the materials you used (e.g. Textbook sections 8.6.7 & 5.3.0.9, or the URL of a web-based resource) in your answer.

You must submit your exam by the end of class via the learning management system.

If you take this exam by copying the Google Doc, you may *optionally* share your work in progress with the instructors (imposter@berkeley.edu and cbravolillo@berkeley.edu).  If you do, we will watch to see if there are any common points of confusion that may warrant clarification to the class.

--------------

# Section 1: Concepts *(6 questions, 40 points)*

--------------

**1.1** *(4 points)*

Ecological validity is often used to justify the use of deception in security studies. Why?

> Participants will behave differently when they know security is a purpose of a study or if they are otherwise primed to think about security, and so deception is often used so to ensure that participants do not believe security is their primary task.

**1.2** *(4 points)*

How might a budgetary constraint impact the choice between a between-subjects experiment and a within-subjects experiment?

> Running a within-subjects experiment allows a researcher to collect data on multiple conditions from a single participant.  Differences in the population can be observed to be statistically significant using a smaller budget when the number of observations is greater.  In other words, a 100-participant budget would yield 100 data points for each treatment in a within-subjects experiment, but only 50 data point per treatment if between-subjects (and two treatments).

**1.3** *(5 points)*

A morale survey of a team of penetration testers reveals that one of the parts of the job they like the least is working with the static analysis tool. The survey gives no insight into why the tool is so despised. What form of study would you use to learn how to improve the tool and why?

> Since you don't yet know what the problems might be, you need to perform a qualitative study to identify possible problems (e.g. interview or focus group). Only when you understand what needs to be measured could you design a survey/quantitative study.

**1.4** *(8 points)*

Researchers are developing security software to help victims of abusive relationships protect their data.  The researchers can start with a laboratory study or a field study, the latter of which would provide greater ecological validity.  List two reasons why researchers might still choose the laboratory study.

> A laboratory may have lower risk to participants, as participants won't be relying on unproven technology to protect themselves. *(4 points)*

> The laboratory study provides researchers the opportunity to interact with participants to learn information that can't be observed remotely. *(4 points, other valid answers may substitute for this one)*

**1.5** *(8 points)*

Researchers in a between-subjects experiment find that 17 of 30 participants heed red warnings and 14 of 31 participants heed blue warnings.  The correct statistical test (Fisher's Exact Test, two tailed) yields a p value of 0.4462, far above the 0.05 threshold to show a significant difference.  The researchers conclude that color has no impact on warnings.  Give two reasons why they might be wrong.

>1. While the difference was not statistically significant, over 56% of participants in the red group heeded warnings and 45% heeded blue warnings: an 11% difference.  The sample size would not yield statistical test for that 11% difference, so we simply don't know if the observed difference is due to chance or because reactions to red and green warnings matter.  Even if the same fraction of participants in both groups heeded the warning, failure to disprove the null hypothesis and a random sample of the population does not prove that the null hypothesis is true. (At best, we can put statistical bounds the size of the difference.) *(4 points)*

>2. Even if we knew for certain there was no difference between red and green, we cannot conclude there is no other color that would have made a difference. (A matter of external validity.) *(4 points)*


**1.6** *(11 points)*

You design a controlled experiment to test five different potential improvements to a notification widget and determine which works best via two metrics:
  - the treatment for which the greatest fraction of participants report having seen the widget or
  - the greatest fraction who can correctly answer a comprehension question

Identify the dependent variable(s), the independent variable(s), and the number of groups in a between-subjects design.

> 2 dependent variables: the fraction reporting seeing the widget and fraction who get comprehension question right (4 points: 2 points each)

> (b) the independent variable is design used, or treatment group, (3 points)

> (c) 6 groups: 5 treatments + 1 control  (4 points for 6, 2 points if missing the control)

-----------------------------

# Section 2: Readings  *(9 questions, 52 points)*

-----------------------------

**2.1** *(5 points)*:

In which reading did the authors assert without evidence that their technological approach makes users very safe?

> Morris and Thompson stated that password rules make users "very safe indeed."

**2.2** *(5 points)*:

In which reading did the researchers conduct a field experiment using a browser toolbar?

> Florencio & Herley

**2.3** *(5 points)*:

In which reading were the traditional authentication categories of *something you have, something you know, and something you are* reintroduced as *something that you have forgotten, lost, or no longer are*?

> Garfinkel's thesis

**2.4** *(6 points)*:

In which reading did the researchers test whether participants would behave more securely if they were given instructions indicating that security was important to the study?  Did a greater fraction of participants who received that instruction behave more securely than the control?

> Schechter et al. *(3 points)*

> No. *(3 points)*

**2.5** *(5 points)*:

A friend wants to meet to ask you to invest in a company to re-invent web authentication. Which of our readings do you ask them to read first and why?

> Bonneau et al.'s quest to replace passwords.

**2.6** *(8 points)*:

NanoBank receives 2,000 free 6-month trial licenses of SomeAntic Malware Defense.  To evaluate the software, Tess Driver, NanoBank's Chief Security Officer, runs a randomized trial. She identifies the 4,000 employees believed to most benefit from the software, randomly assigns 2,000 to be required to install the software (the treatment group), leaving the other 2,000 in the control group to receive no security software.  She successfully enforces the requirement and all 2,000 members of the treatment install the software.

During the six-month trial, Dr. Driver's security team detects 23 employees in the control group to be compromised by malware, and 47 employees in the treatment group infected by malware.  Which reading explains why the treatment group performed worse than the control group?  Please explain why.

> Wimberly and Liebrock's Using Fingerprint Authentication to Reduce System Security.  Employees who believed anti-malware was protecting them may have behaved more recklessly: e.g., installing software they might have avoided if they did not have faith in the additional layer of defense protecting them. *(4 points for paper, 4 points for explanation)*

**2.7** *(6 points)*

In the paper “Operating system framed in case of mistaken identity”, by Bravo-Lillo et al., the authors studied how likely it was for users to enter their passwords in spoofed security pop-ups. A relatively large proportion of users did not enter their passwords but were nevertheless considered likely to fall for other scams similar to the one used in the paper. Explain briefly why this is so.

> Participants didn't enter the password because they didn't want to install software, not because they didn't believe the password-dialog was created by the operating system.

**2.8** *(6 points)*:

In the paper “Experimenting at scale with Google Chrome’s SSL Warnings”, by Felt et al., the authors report on a massive experiment run with real users of Chrome 29, including a bit more than 130,000 observations. Explain why they might not have chosen to study a larger sample of users even if they had the opportunity to do so at no additional cost.

> Each experimental treatment has a risk of harm. As the number of participants goes up, the marginal value of each participant to the statistical analysis decreases, whereas the aggregate risk grows linearly with the number of participants.

**2.9** *(6 points)*:

You redesign a browser security warning and run a security study similar to that of Felt et al.'s "Experimenting at Scale with Google Chrome's SSL Warning."  The fraction of participants who ignore the warning drops from 40% to 20%, but a year later the fraction returns to 37%.  You then introduce yet another new design, the rate drops back to 20%, but again it returns to 38% a year later.  There is no change to risk over time, as the number of warnings that are actually false positives and false negatives stays constant.  What explains this phenomenon?

> Novelty effect causes attention to the warning when a redesign is released and habituation causes users to ignore the design over time.