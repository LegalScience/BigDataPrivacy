

<p>
<hr>

# Big Data Privacy Workgroup
2014-02-12

# ActionItem: Refine Scenario Template By Wed Feb 19th.  
**Work with Simon (BT) and cc David W.**  
**Input by me, Karen S and Cam K.** 
* Add "Interactions" (eg HR?  Sale of Goods?  Access netflix?
* Add "Systems" (eg ACH? a specific enterprise system?  a business or legal system? etc
* ALSO: Look at "how the system addresses the context" (as per Cam)
* ALSO: Consider how the context looks from the "system" vantage and from the "participant" vantage. (DW)

# Draft Scenarios:


MIT CSAIL Big Data Privacy WG
Scenarios Document
This document outlines a list of representative scenarios to be used to help the Working Group
explore the technical chal enges of big data privacy use cases. These scenarios are distil ed
from the original contributions of the WG members.
Beginning with the first meeting of the Big Data Privacy WG, we wil  go through the fol owing
process are part of our over goal of understanding big data privacy chal enges and assessing
utility of various technical approaches to meeting those chal enges. 

Our methodology:


1. complete scenario description and motivation (assigning teams for each)
2. develop Privacy Impact Assessment for each scenario
3. assess application of various technology approaches to supporting privacy requirements
Elements of Privacy Impact Assessment:


● Actors: who is data owner? who is using the data? who are the data subjects?
● Goals and incentives what is the benefit? who benefits? what are financial incentives?
● What are the risks? To whom? If the risk is an externality, how might it be mitigated?
● Personal data types
● Data lifecycle (retention, liability for breach, and accuracy)
● Relevant laws and regulations
● Existing or related best practices


In its first meeting the working group wil  review these scenarios to determine which are useful
for our study. During our discussion of each issue we wil  assess the group’s level of interest in
the topic assessed by whether we get folks to volunteer to shepherd the topic along to the next
level.


## Topic #1: Privacy in Online Learning Environments (Massive Open
Online Courses and Other Platforms)
Inspired by: S2, S14, edx, Coursera
Team: Una­May (MIT), David Dietrich (EMC)
Guide: Danny
Massive Open Online Courses (MOOCs) col ect large volumes of sensitive and granular
information about student’s educational practices. Many MOOCs col ect data that documents
individual student’s fine­grained study habits. This data may also be linkable to demographic
information ­­ such as age, sex, and socioeconomic status. Such data may be useful for
research assessing the effectiveness of various educational techniques. Analysis of student
behavior may also have commercial value to employers and others who seek to predict future
performance of students based on their behavior in online educational environments.


## Topic #2: Research Infrastructure for Social Media
Inspired by: S3
Team: Maritza Johnson (Facebook), tbd (MIT)
Guide: Mona
Social media represents a rich grounds for researchers to obtain valuable ethnographic,
epidemiological, and sociological data
1
 in order to study a wide variety of social phenomena.
However, it is obvious that use of such data can infringe on user privacy, and must therefore be
conducted with care. Aside from the initial use of the data, there are also questions about
expectations for the life cycle and retention of the data.


## Topic #3: Privacy in Aggregated Diverse Data Sets
Inspired by: S5
Team: Evelyne Viegas (Microsoft) and tbd (MIT)
Guide: Elizabeth
Microsoft is working with the research community on developing an open source platform for
hosting data sets and code for the machine learning research community.  CodaLab is a
Machine Learning Service which al ows researchers to share and browse code, data, and create
experiments.  CodaLab helps nurture an environment of scientific rigor, and open up new
avenues for col aboration between researchers.   How do we ensure that anyone posting data
does not inadvertently post data that contains PII (is there a way to do this automatical y)?  How
can the community keep a healthy tension between sharing real data and making sure that in the
long­run there is no privacy violation based on researchers using data sets from CodaLab in
unanticipated ways?  Privacy preservation between multiple data sets may leak more sensitive
personal information than previously expected, and the owners of those datasets may wish to
predict and prevent such data aggregation from occurring. Automatic understanding of the
privacy properties of the interaction of multiple datasets, as wel  as reasoning of differing privacy
policies attached to those datasets, may help al eviate some of these issues.
1
 
See: 
http://www.pnas.org/content/110/15/5802
 for an interesting example of this used for
predicting user attributes via facebook “likes”. These attributes are actual y quite invasive, and do
highlight the need for this section.
Topic #4: Preserve Privacy in MIT Living Lab
Inspired by: S4, S8, S12
Team:  Elizabeth Bruce and Sandy Pentland and (Hal Abelson?)
Guide: Elizabeth
The MIT Living Lab project is building a testbed at MIT that demonstrates a unified interface to
data for the MIT community and enables the community to demonstrate the value of big data
across a variety of applications on campus. The Living Lab Project aims to bring together many
kinds of data  including:  1) MIT data: data generated and col ected by MIT e.g.  campus maps;
card swipes; building maps; wifi access points and video/cctv data etc.  2) Personal Data: data
col ected and stored by individual members of MIT community that they control and choose to
share with certain groups for certain purposes  e.g. location (GPS) and "quantified self" metrics
for activity monitoring (i.e. # of steps taken) and behavior tracking; and 3) External Public Data:
data from public sources  e.g. social media data, weather data, events data, local city data etc.
The fact that the study is done by MIT on MIT’s campus, for the purposes of MIT research,
serves as an interesting case; the rules and norms that apply for col ection in this circumstance
may differ from col ection by, say, an independent corporation or other third party.  One of the
goals of the MIT Living Lab project is to demonstrate best practices for how organizations col ect
and manage personal information, including informed consent, auditable permissions and
provenance.



## Topic #4.5 - public good/ policy research using sensor data
(mobile devices, social networks, etc).
Inspired by: Gates Foundation, Health? Energy? (home data)!, Harvard six cities study
Team: [Jake Kendal /Gates Foundation?]
Guide:  Mike
Leverage mobile operator data from developing countries to track mobility, social network
information, and other indicators that would power applications to further development or social
good goals.
Utilizing data from massive networks of devices wil  inevitably lead to privacy questions forcing
the need to balance privacy and personal control over data against the goal of using the data for
the widest variety of development use cases..
Electric companies and the US government want to monitor electric usage on homes utilizing
“smart­grid” technologies,
2
 “Internet of things” devices may provide health information, and
2
 http://www.smartgrid.gov/the_smart_grid
modern cel phone technologies (such as Google Now) and personal health/activity trackers can
predict our every step. There are good uses for these technologies as wel , as increased
information and control provides better convenience, safety, and may also result in better
epidemiological data that can save lives.
3


## Topic #5: Understanding and Tracking User Consent and
Management
Inspired by: S17, S3
Team: Simon Thompson (BT), Karen Sol ins (MIT)
Guide: Elizabeth
Understanding the requirements and constraints imposed by user consent and legislation,
especial y for systems in which users may not truly understand or be legitimately informed of
what is at risk, is a difficult subject. How does an organization instruct & support a user,
manager or data owner on the their obligations and the implications of their actions in the face of
conflicting requirements. What is the best way to explain where and how data is shared, who
that data is shared with, what should be done with the data, and what information that
data could provide?


## Topic #6: Dynamic Pricing and Advertising
Inspired by: S1
Team: tbd
Guide: Elizabeth
Big data analytics can enhance site personalization and targeted product offerings.
4
 As anyone
who has used Amazon knows, such technology offers a better user interface, but can also
col ect and enable unanticipated use of personal information. What are users reasonable
expectation of privacy is for such interactions and how should service providers adjust their
practices to remain faithful with user expectations?
Topic #7: Health/Genomic Data
Team:  James Wil iams (Google) and tbd
Guide: Elizabeth
3
 An interesting case study of this kind of study is the Harvard Six CIties study, here is a good overview of
the event:
http://scienceblogs.com/thepumphandle/2012/11/02/public­health­classics­assessing­air­pol ution­and­healt
h­in­six­u­s­cities­researchers­findings­changed­the­air­we­breathe/
4
 See http://www.niemanlab.org/2012/07/are­we­stuck­in­filter­bubbles­here­are­five­potential­paths­out/
There is a growing consensus that the analysis of large repositories of genetic information has
the potential to yield major advances in the biological sciences. Due to the plummeting costs of
gene sequencing, the creation of such databases is now feasible. Unfortunately, many
institutions are restricted to data in their own custody and control, creating silos of information.
Finding secure, trusted and privacy­sensitive means for sharing genetic information wil  create
network effects that wil  accelerate scientific research. To do this, we must understand the
privacy risks associated with genetic information, and the controls available to minimize or
mitigate these risks.


## Topic #7: Big Data and Privacy in Intelligence and National
Security
Inspired by: Recent events
Team: John Delong
Guide: Danny
Recents events have made it clear that there is a need for better public understanding of privacy
guarantees in intel igence gathering. What technologies exist to prove that SIGINT data, once
col ected, wil  only be used in ways that are compliant with federal laws and policy?


## Topic #8: Financial Industry / Consumer Finance Data
Inspired by: Financial Industry
Team:
Guide: Mona
Big data offers the opportunity to develop and leverage better economic indicators. An example
of this trend is seen in the bil ion dol ar price (
http://bpp.mit.edu/
) In action:
http://www.pricestats.com/approach/overview
Are there better economic indicators that can be extracted from consumer traces on the web
such as better consumer indices?  Who can the privacy of consumer be preserved while
starting to define a more granular understanding of the economy.  Another example of granular
economic view 
http://www.spatialinformationdesignlab.org/projects.php?id=16
 that il ustrate the
level of care required to protect the privacy of consumer.


# Next steps 

* 2 weeks from now we meet again
* One month from now we present scenarios


* March 3rd, WH panel. Seeking speaker Re big data applications in health transportation and education. 