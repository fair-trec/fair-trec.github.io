---
title: How To TREC
---

- [Back to Fair Ranking Track Homepage](index)

This page provides an overview of the Text REtrieval Conference (TREC) and details of how to participate. 

# What’s the short version?
TREC is a community activity to produce shared tasks and data sets for information retrieval research.
Your team can register to participate, which gives you access to this year’s data and the opportunity to have your methods and results evaluated and included in the conference proceedings, and also for you to present and discuss them with other participants at the TREC conference.

There is a two-step process where training data is first made available for teams to develop their system approaches over a period of a couple of months, before the evaluation data (without relevance labels) is released close to submission time and teams submit their systems’ test data results.
The data and results are made generally available at the conclusion of each year’s TREC cycle with the publications of the Proceedings of TREC.

Read on for more details!


# What is TREC?
[TREC](https://trec.nist.gov/) is the Text REtrieval Conference, an annual conference operated by the U.S. National Institute of Standards and Technology (NIST) to support information retrieval research through cooperative creation of data sets and pre-competitive comparison of information retrieval approaches on shared tasks.

TREC is unlike other computer science conferences, though; rather than submitting papers for review, you register to participate and submit results and a description of what you did. It is in many ways more like a combination of a workshop and a challenge in other communities, such as the RecSys Challenge or KDDCup.

One key difference between TREC and challenges is that TREC is **strictly pre-competitive**: while participating groups’ submissions are ranked on their relative effectiveness, there is no such thing as “winning” TREC, and using TREC performance in advertising, recruiting, publicity, etc. is strictly prohibited. Ellen Voorhees called this model “coopetition” in her [2020 SIGIR Keynote](https://dl.acm.org/doi/10.1145/3397271.3402427), which we recommend watching if you’d like more information on the history and impact of TREC.


# What is a TREC Track?
TREC is organized into tracks, such as Fair Ranking, Precision Medicine, and Conversational Assistance. Each track provides a corpus of documents and 1-2 tasks: defined information retrieval tasks that participants build systems to address. The tasks usually provide a set of queries (called topics), and participants submit their systems’ responses to the queries. The task organizers then evaluate these responses and score each submission. Within this structure, the precise details can vary from track to track and year to year.


# What is the social benefit of TREC?
TREC has been instrumental in catalyzing information retrieval research and development. Besides the community and professional development it affords to participants, it produces durable artifacts (test collections) that enable substantial ongoing research. Each track and task typically results in a data set consisting of:
- A document corpus for retrieval.
- An evaluation protocol and metric for assessing system effectiveness.
- A collection of queries and associated document relevance judgements. Coverage and judgment scale varies from task to task, but these judgements are usually provided by expert assessors hired by NIST and have significantly higher coverage than the judgments in many other collections.
- The results (typically a ranking of documents for each query; a set of results for a task is called a run) provided by participants in the track.


These data sets are then made available to the community (subject to a lightweight data sharing agreement with NIST) as a long-term research resource, after an embargo period to allow track participants to write up and submit their work for conference publication before notebooks are made public. Many papers have been published using past TREC data sets to train new systems or re-analyzing the performance of runs submitted to past TRECs.

At the TREC conference, teams participating in each track present their work and discuss the task with others who are working on the same problem and data set. This exchange of ideas facilitates deep understanding of particular problems and data.

We are operating the Fair Ranking track to bring these benefits to fair ranking as employed in information retrieval and recommendation, building task definitions, data sets, and system results to catalyze further research in fair IR.


# Why should I participate in TREC?
There are a few reasons participating in TREC may be helpful to you:
- To contribute to the ongoing effort to build long-lasting resources for information retrieval research.
- To develop and test your skills by working on a task along with others.
- To collaboratively work to understand a problem through sustained work on a shared task and data set.


# How do I participate?
Due to its nature as a pre-competitive meeting focused on shared work, TREC participation is very different from other conferences or workshops. Specific dates vary by track, but the general process is:

1. [Register to participate in TREC](https://trec.nist.gov/pubs/call2021.html) by mid-February - this is essential, but non-binding. Your team must register as TREC participant for a particular year in order to get access to that year’s data and to attend and participate in TREC. After the conference, the proceedings are publicly available, and community members can request access to past data; registration is required to participate in the current year. Registration does not formally obligate you to participate or attend, but it is a necessary prerequisite for doing so.

2. Track organizers provide data (document corpus, training queries, and instructions) sometime in the spring. This does not include the final evaluation data (queries or annotations) that will be used for formal TREC evaluation.

3. You build your system using this data and instructions.

4. At the end of the participation window, organizers provide the final evaluation queries; you run your system on these queries and submit results in accordance with the instructions. There is typically a 2-3 week window between the release of evaluation queries and submission deadline.

5. Track organizers give you the evaluation scores for your runs.

6. Write a “notebook paper” describing your approach and results. This is due in October, and will be made available to other TREC participants.

7. Attend and possibly participate in the TREC conference itself in November. Each track has a plenary session at TREC, and track organizers typically invite some of the teams to present their approaches. This is a good opportunity to discuss the track and share ideas with organizers and other participants. TREC itself is a relatively informal, welcoming environment.

8. Revise your notebook paper for publications in the TREC Proceedings. This is typically due in January or early February, and the proceedings are published in February.


The process up until the published notebook paper is semi-open: the call for participation is open to the public, but only registered participants have access to the early versions of the notebook papers and to the material presented at TREC itself. It’s something of a trade: by participating in and contributing to TREC, you get advance access to the work and insights of your peers working on the same problems. After the participants have had a chance to write up their work and submit it to SIGIR, the final notebook papers are published to allow the broader public to see what was done at TREC.


# What are the deadlines for the Fair Ranking Track?
- Register by mid-February
- Training data available in May/June
- Final run submissions tentatively due Aug. 1 (precise deadline forthcoming)
- Notebook due in October


# Is the notebook a published paper?
No. Notebooks are published in the *TREC Proceedings*, but are not peer-reviewed and are scientifically the equivalent of unreviewed working papers.


# Where can I ask more questions?
If you have more questions about participating in the TREC Fair Ranking Track, feel free to ask a question in the [Google Group](https://groups.google.com/d/forum/fair-trec) or e-mail the organizers:
- Michael Ekstrand: <michaelekstrand@boisestate.edu>
- Graham McDonald: <graham.mcdonald@glasgow.ac.uk>
- Amifa Raj: <AmifaRaj@u.boisestate.edu>
