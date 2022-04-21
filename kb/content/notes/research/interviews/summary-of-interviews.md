# Interviews
We conducted five interviews with faculty of the University of Zurich. We tried to get an insight into their specific grading process and their views on the possible use of software. This document provides an overview of their answers. Due to the small number of conducted interviews the answers cannot be considered representative.

**How do the participants grade their exams?**

All participants stated that they work in teams to share the workload of the grading, at least in large exams. While only three out of five people stated that they split up the grading exercise by exercise, also the remaining two stated that they think grading exercise per exercise is superior to grading student per student. The reason the other two participants usually conduct the grading student per student is efficiency (not having to switch between the different exams) and they would change their approach if this problem was mitigated. Three participants stated that they predefine and write down clear criteria for which they award points (these criteria may be extended) and two participants stated they do not use predefine criteria.

**What biases are the participants aware of?**

[Contrast Effects](research/challenges/biases/contrast-effects.md) were mentioned by two participants. Another bias that was once mentioned was the problem that the grader may know the people, resulting in a [Halo](research/challenges/biases/halo.md). Other mentions were: [[Halo]] if you grade student per student, bad handwriting (see [Presentation of Answer](research/challenges/biases/presentation-of-answer.md)) which has a negative impact on the points a student is awarded, and good (bad) mood which affects the grading (see [Mental Depletion](research/challenges/biases/mental-depletion.md)).

The participants mentioned the following measures to adress these biases: grading exercise per exericse (see [Grading Workflow](research/features/definitions/grading-workflow.md)), [Shuffling](research/features/definitions/shuffling.md), and prevention of bad handwriting by explicitly stating that this may have an impact on the points awarded.

**What do the participants look for when grading exercises?**

A text exercise (see [Exercise 1](research/interviews/resources/sample-exam.pdf)) was shown to three participants. Two of them stated that they explicitly look for keywords when grading such an exercise. One stated that he "knows the solution is correct when he sees it". 

All five participants were shown a quantitative exercise (see [Exercise 2](research/interviews/resources/sample-exam.pdf)). Three stated that they first look whether the result is correct. Two of them stated that when the result is correct they merely check whether there is some form of derivation and one stated that she looks at the derivation in more detail. The two other participants stated that they look at the exercise from top to the bottom (i.e. derivation first). 

**What do the participants think of [Assisted Grading](research/concepts/assisted-grading.md) Tools?**

Four out of five people stated that they would definitely use such a tool. The remaining particpant stated that he would be willing to use it, but only for large exams, the break-even was estimated to be around 200 students. The workload related to the [Digitization](research/features/definitions/Digitization.md) of the exams is perceived as a problem and the participants would view it as a substantial mitigation if this part of the work could be outsourced to e.g. student assistants.

**What do the participants think of automated features (see [Feature Categories](research/features/feature-categories.md))?**

[[Sorting]] was perceived to be, at least somehow, useful for quantitative exercises (see [Exercise 2](research/interviews/resources/sample-exam.pdf)).  While all participants stated that they would potentially use such a feature for quantitative exercises, two explicitly stated that the benefit was limited if they still had to look at each exercise and they would prefer the possibility to give points to the correct answers automatically. [Sorting](research/features/definitions/sorting.md) based on keywords for text exercises (see [Exercise 1](research/interviews/resources/sample-exam.pdf) ) was perceived to be less useful.

While all participants but one thought that [Automated Grouping](research/features/definitions/automated-grouping.md) would be useful for the presented examples (see [Exercises 4 and 5](research/interviews/resources/sample-exam.pdf)), no one stated that exercises with such a low level of complexity occur in their exams.

Four participants stated that they would be willing to apply certain structure restrictions to their exams in order to reduce the workload of the grading.

**Would the participants have concerns using automated features?**

One person stated that it is important that the result is still properly checked even if the software suggests that it is correct (false). No one uttered explicit concerns regarding the automation (in case it works properly). If you can still intervene as a human, the skepticism against automated solutions seems to be limited.

**What wishes do participants have regarding the outcome?**

We hereby list ideas for features of the participants:
- Adaptive Learning (The software learns from your grading and makes recommendation)
- Providing access to student grades (incorporated into knowledge base under [Access to Student Grades](research/features/definitions/access-to-student-grades.md))
- [Text Recognition](research/features/definitions/text-recognition.md) 
- Visual feedback during grading (how many still have to be graded, "live-time" point distribution)
- [Statistics](research/features/definitions/statistics.md)
- [Keyword Extraction](research/features/definitions/keyword-extraction.md) based features
- Automatically compare plots (see [Image Similarity Analysis](research/concepts/image-similarity-analysis.md))

