# MICS W215 Spring 2020 Midterm

---------------------------------------
### Epilog to exam
This exam was used in Spring Term of 2020.

We observed students taking the exam and found that we had underestimated the time required, so we extended the time to two hours for those who wanted it. We concluded future exams should be shorter.

We found students struggled most in Section 3, though perhaps they would have done better if there were a final and this type of question were used in a final.  For the next midterm, so we are likely to ask more concrete questions, fewer hypotheticals about fictional studies, and more concrete questions from the readings.

Ironically, as Stuart wrote about hypothetical Stanford researchers authenticating users from images of lips, actual Stanford researchers were identifying individuals from images of the opposite ends of their digestive tracts.
 as Stuart wrote Section 3, the scenario in which hypothetical Stanford researchers test technology to authenticate users from images of their lips, actual Stanford researchers were busy publishing [research testing technology to establish identity from images of the opposite ends
 of individuals' digestive tracts](https://www.nature.com/articles/s41551-020-0534-9#auth-1).

---------------------------------------

You may ask the course staff questions privately during the exam, but
otherwise may not use any human assistance. You may use your book as a
reference, as well as static web-based materials during this exam.
However, if you do, please write down the portion (e.g. 8.6.7 & 5.3.0.9)
of the book you use as part of each answer. Similarly, if you use any
web-based materials, note the URLs.

## How to take/submit this exam

Make a copy of this exam. Share it with the instructor
([<span class="underline">imposter@berkeley.edu</span>](mailto:imposter@berkeley.edu)).
Then begin to work. At the end of the exam period, save as PDF and
submit as the “Midterm” assignment.

# Section 1: Concepts

### 1.1 \[10 pts\] Why should one be skeptical of a study with low intracoder reliability (a.k.a. stability)?

> Two different researchers categorized data differently, so the rules for categorizing qualitative data did not lead to reliable categorization.

### 1.2 \[10 pts\] What are the benefits and draw-backs of conducting a field study vs. a lab study?

### 

### 1.3 \[10 pts\] What are the benefits and draw-backs of conducting a survey vs. an interview?

### 

### 1.4 \[10 pts\] What are the benefits/draw-backs of between- vs. within-subjects designs?

#   

# Section 2: Readings

### 2.1 \[8 pts\] What factors might lead the “Why Johnny Can’t Encrypt Paper” to have understated or overstated the likelihood that users actually be able to successfully accomplish the tasks measured in the paper?

>(max 8 pts, two of 3 sufficient for full credit)
>Selection bias [4 pt]
>
>Demand effects/pressure may have led to overperformance [4 pts]
>
>Role-playing scenario may have led to underperformance [4 pts]

### 2.2 \[5 pts\] Critics of “The Emperor’s New Security Indicators” suggested that having a researcher in the room might have biased participants to enter their passwords when their site-authentication image (SiteKey) was absent, even if they would not have in real life. Explain one reason why this might be a concern for this experiment. Bonus if you can identify a reason it might not have been a concern.

>Demand effects: they felt pressure to complete the task for the authority figure (researcher) [5 pts]

>Bonus [2] - many participants heeded warning despite demand effects

>Bonus [2] - the researchers were not actually in the room with the participants

### 2.3 \[5 pts\] In “The effect of online privacy information on purchasing behavior” paper, researchers were expecting to find a difference in the purchase behavior between participants who bought batteries and those who bought sex toys. Give two potential explanations for why no effects were observed and at least one change to the study that might address at least one of these explanations.

> The sample size might have been too small to detect an effect

> Participants might have figured out study was about privacy and did the private thing


> Researchers could could increase the sample size

> Researchers could add more tasks or search features to distract from purpose of the study


# Section 3: Analysis of Experiment

*This section is about the following experimental scenario.*

## Background

A research team at Stanford considers fingerprint authentication
problematic because fingerprint readers can be tricked into reading
replicas of users’ fingers and fingerprints \[1\] \[2\], and those
fingerprints are readily available to attackers because humans leave
fingerprints on many things we touch. They note that lips also leave
unique prints \[3\] but are typically harder to collect as most humans
do not place their lips on as many surfaces as their fingers.

The research team has developed a lip-based authentication prototype
built into a Voxel SmartPhone running the Cyborg operating system. To
direct users to place their lips on the glass screen directly above the
sensor, the researchers have built a user interface widget that renders
a pair of lips onto the target. Their authentication system even gives
users the option to choose an animated emoji face to be rendered around
the lips. To ensure the interface is as inclusive as possible, they
include emojis with a diverse range of races, gender expressions, and
body types.

The researchers will conduct a six-week field study using the prototype
phones. During the first two weeks, the researchers will instruct
participants to use conventional PIN-based authentication. After two
weeks, the researchers call the participants back into the lab and
instruct them to use fingerprint based authentication. After the fourth
week, the researchers will call participants back into the lab a second
time, introduce participants to the lip-print authentication feature,
and instruct them to use lip-prints for authentication during the final
two weeks of the field study.

In surveys and pilots, some participants expressed reservations about
placing their lips onto their phones, citing potential embarrassment,
social stigma, and hygiene. To ensure a representative sample of the
population is willing to participate in a study where participants will
have to trade their phone in for a prototype, and spend two weeks
authenticating with their lips, the researchers offer a generous $750
gratuity to participants who join and complete the study. They will also
provide participants with an unlimited number of antiseptic cleaning
wipes.

For fingerprint and lip-print authentication, the researchers will
instrument the devices to measure:

1.  > Authentication latency **L**, measured as the time from skin
    > contact to time of authentication decision.

2.  > Success rates **S1**, **S2**, & **S3**, measured as the fraction
    > of attempts that succeed within 1, 2, and 3 tries.

With participants consent, the researchers will also capture one
fingerprint and lip-print from each participant and then measure the
false-accept rate F0: the fraction of authentication attempts that the
algorithm would accept when given the print of someone other than the
authorized user.

To measure authentication speeds after the adjustment period needed to
learn a new authentication mechanism, the researchers discard data from
the first 10 days of each two-week (14-day) period and use statistics
from the final four days of the the fingerprint and lip-print periods.

\[1\]
[<span class="underline">https://cryptome.org/gummy.htm</span>](https://cryptome.org/gummy.htm)

\[2\]
[<span class="underline">https://hackaday.com/2019/04/08/fooling-fingerprint-scanners-with-a-resin-printer/</span>](https://hackaday.com/2019/04/08/fooling-fingerprint-scanners-with-a-resin-printer/)

\[3\]
[<span class="underline">https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5596687/</span>](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5596687/)


### 3.1 \[8 pts\] Identify any ethical concerns with this study (which would hopefully be identified during ethics (IRB) review.)  

> [4 pts]
>Disclosure: The researchers failed to disclose that participants would be required to perform an action they might find uncomfortable until four weeks into the study.

>[4 pts]
> Coercion: The gratuity is coercive, using money to get people to do something that pilot participants and survey respondents were uncomfortable doing.  Those who most need the money will feel the most pressured to do things they might not be comfortable with.

### 3.2 \[6 pts\] How might these ethical concerns be addressed?

>Tell participants all requirements ahead of time [6 pts]

> Participants must be allowed to leave the study at any time without sacrificing their gratuity. [5 pts]

> Possible Bonus: by telling participants that they will be reporting on the fraction of participants unwilling to try lip-based authentication as one of their study findings, and using the data from the first four weeks, they will be giving participants additional implicit permission to leave. (Participants will know they are still contributing data to the findings.)



The researchers performed the study with 100 participants.

At the end of the study, the researchers surveyed participants. The
researchers asked “During the study, did you prefer using lip-print
authentication or fingerprint authentication.” 75% of participants
responded that they preferred lip-prints, and a chi-square test showed
that this difference was statistically significant. They conclude that,
on average, users like lip-prints more than fingerprints.

### 3.3 \[6 pts\] Identify and explain the reasons why the researchers’ conclusions may not correctly reflect users’ true preferences.

> Maximum 6 pts, with...

>   Demand effects [4]

>   Novelty effect [4]

>   Ordering effects [4] (in both experience and wording of question)
   Self-reported preference may not be real preference [2 if no demand effect listed]


The researchers also asked participants to “please list any experiences
in which you benefited from being able to use your fingerprint instead
of a PIN.” They asked the question again with lip-prints in place of
fingerprints: “please list any experiences in which you benefited from
being able to use your lip-print instead of a PIN.”

Participants reported a median of 1.3 positive experiences for
fingerprints and 2.1 positive experiences for lip-prints. The
researchers used a Wilcoxon Signed Rank test to determine that the
difference in the number of positive experiences was statistically
significant. The researchers conclude that users have more such positive
experiences when using lip-prints than when using fingerprints.

### 3.4 \[8 pts\] Identify and explain the reasons why the researchers’ conclusions may not reflect the actual difference in the number of positive experiences between fingerprints and lip-prints.

>  [4 pts]

>   - Recency effect (much easier to draw examples from past 4 days than 2 week ago) and/or
>   - Ordering effect

> [4 pts]

>    - Demand effects and/or Novelty effect [4 pts for 1, 6 pts for both if recent]

With roughly eight authentications per user per day, the researchers
observed 3218 successful fingerprint authentication samples during the
final four days of the fingerprint period and 3311 successful lip-print
samples during the final four days of the lip-print period. The
researchers calculate the mean authentication for both, finding that the
mean authentication latency for lip-prints is 5% lower than that of
fingerprints. Using t-test, they show the difference to be statistically
significant (p=0.0130). They conclude that, on average, using lip-print
authentication is faster than fingerprints.

### 3.5 \[12pts\] Identify and explain as many reasons as possible to dispute researchers’ conclusions that authenticating with lip-prints is faster than authenticating using fingerprints.

> Failures are missing from the data [3 pts]

> Data are unlikely to fit normal distribution (times have long tails) [3 pts]

> Data are not independent (multiple values from each participant) [3 pts]

> Since users need their fingers, but not their lips, to operate the screen, the definition of latency does not reflect the time needed to move one’s lips to the screen to authenticate. [3 pts]
