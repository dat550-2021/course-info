# Course info page of DAT550 (Data Mining and Deep Learning, Spring 2021)
# Overview
- [Course Structure](#Structure)
- [Labs](#Labs)
- [Schedule](#Schedule) 
- [Updates](#Updates)

# Updates

# Structure
- Lectures:
   - The lectures are currently fully online until further notice
   - Video lectures will be published on canvas with a link in [Schedule](#Schedule) at least 1 week before the discussion
   - Video discussions will happen twice a week from 12.15 to 14.00 on Mondays and Wednesdays
   - You must watch the video lectures and come to the live zoom call discussions (zoom link will be shared in canvas)
   - First dicussion will happen live on 4th Januaray 2021 12-2 pm (video lectures are already published)
- Labs:
   - The labs are online in week 1 and 2 and the rest will be hybrid (you can show up physically with a prior appointment with the TAs)
   - Make an appointment with the student assistants for the help with lab
   - 3 ungraded (pass/fail) mandatory assignments for qualification to final exam
- Project:
   - 40% of the final grade is assigned to the group project (working code + written report + presentation)
   - 60% of the final grade is based on a written home exam

# Labs

## Autograder

This course uses Autograder, a tool developed at the University of Stavanger
for students and teaching staff to manage the submission and validation of
lab assignments. All lab submissions from students are handled using Git,
a source code management system, and GitHub, a web-based hosting service for
Git source repositories. Thus, basic knowledge of these tools are necessary.
The procedure used to submit your lab assignments is explained in the [lab submission process](lab-submission.md).

Students push their updated lab submissions to GitHub. Every lab submission is
then processed by a custom continuous integration tool. This tool will run
several test cases on the submitted code. Autograder generates feedback that
let the students verify if their submission implements the required functionality.
This feedback is available through a web interface. The feedback from the
Autograder system can be used by students to improve their submissions.

## Git and GitHub

Git is a distributed revision control and source code management system.
Basic knowledge of Git is required for handing in the lab assignments.
There are many great resources available online for learning Git.
A good book is Pro Git, which is available for free [here](https://git-scm.com/book).
Chapter 2.1 and 2.2 should contain the necessary information for delivering the lab assignments.

GitHub is a web-based hosting service for software development projects that use the Git revision control system.
An introduction to Git and GitHub is available in [this video](http://youtu.be/U8GBXvdmHT4).

You need to sign up for a GitHub account to get access to the needed course material.

## Autograder Registration

Follow the steps below to register and sign up for the course on Autograder.
Here are two short videos recorded by Prof. Hein Meling (inventor of Autograder) describing these steps in the context of a different course DAT320 (same steps should work with DAT550): [Part 1](https://youtu.be/3KJm4ABvTAo) and [Part 2](https://youtu.be/kMyH_-8xMGc).

1. Go to [GitHub](http://github.com) and register.
   A GitHub account is required to sign in to Autograder.
   You can skip this step if you already have an account.

2. Click the "Sign in with GitHub" button in [Autograder](http://uis.itest.run) to register.
   You will then be taken to GitHub's website.

3. Approve that our Autograder application may have permission to access to the requested parts of your account.
   It is possible to make a separate GitHub account for only this (and other) courses if you do not want Autograder to access your personal one with the requested permissions.

## Signing up for the Course on Autograder

1. Click the Plus (+) menu and select “Join course”. Available courses will be listed.

2. Find the course and click Enroll.

3. Wait for the teaching staff to confirm your Autograder registration.

4. You will then be invited to the course organization on GitHub and two separate repositories.
   You will need to navigate to each of these links and accept these invitations:

   - Navigate to the course organization [dat550-2021](https://github.com/dat550-2021) accept the invitation.
   - Navigate to the [assignments](https://github.com/dat550-2021/assignments) repository and accept the invitation.
   - Navigate to your private <https://github.com/dat550-2021/username-labs> repository and accept the invitation. Remember to replace `username` in this link with your own GitHub `username`.

   Several invitation emails will also be sent to the email address associated with your GitHub account.
   However, emails from GitHub can sometimes take a while to arrive.

5. Once you have accepted the invitations, you will get your own repository under `dat550-2021`, which is the course's organization on GitHub.

## Group Signup on Autograder

1. Read the [policy about group assignments](policy.md#group-assignments).
   Find and agree with another student to form a group.
   We prefer groups of two, but will allow groups of three.
   It is important that all group members agree to contribute equally to the group assignments.

   If you prefer to work alone, you must still create a group.

2. Agree on a name for the group.
   The name will be used as the group's GitHub repository.
   We prefer group names that identifies the persons in the group.
   **The group name cannot be changed later.**

3. Navigate to the course's left menu bar and select “New Group”.

4. Enter the name of the group in the textbox above the list of students.

5. In the dialog, find your own name via the “Search for students” text box.
   Click the Plus (+) symbol to add yourself to the group.

6. Repeat the above step for the other group members.

7. Click the “Create” button.

## Discord DAT550 Server Registration

1. Go to [Discord](https://discord.com/register) and register.
   A Discord account is required to sign in to communicate with the teaching staff during lab hours.
   You can skip this step if you already have an account.

2. To join our UiS DAT550 Discord server, navigate [here](https://discord.gg/XbZhc9eQhx).

3. Once connected to the server, please register with our bot, `@dat550_helperbot`, by sending it a direct message:

   ```text
   !register username
   ```

   where `username` is your GitHub username.

   Note that to register with the bot, you must previously have registered with Autograder.
   Hence, please make sure that you have joined the [`dat550-2021`](https://github.com/dat550-2021) GitHub organization and registered with Autograder first.

   If you need help with registering on the server, send a message in `#new-users`.
 
# Schedule

(Lab submission deadlines are marked with **bold**.)

| W    |  Date     | Chap.     | Topic                                            | Resources | Travels / Remarks     |
|:----:|:---------:|:-----:    |--------------------------------------------------|:-------:|:------------:|
|  1   |  4/1      |   1,2     |  Introduction          |   [slides]() [video]()      |              |
|      |  6/1      |   2        | Data processing       |   [slides]() [video]()   |              |
|      |  8/1      |   Lab       | Get started with in autograder, play with jupyter notebook, numpy, pandas, sklearn       |       [hands-on-1](https://github.com/dat550-2021/course-info/tree/master/hands-on/hands-on-1) |              |
|  2   |  11/1     |   2       | Data sampling, exploration, visualization  |   [slides]() [video](), [hands-on-2](https://github.com/dat550-2021/course-info/tree/master/hands-on/hands-on-2) |             |
|      |  13/1     |    3       |     Classfication (Decision Trees) |   [slides](https://stavanger.instructure.com/courses/6604/files?preview=673527)      |              |
|     |  15/1     |    Lab       |   Work on lab assignment 1                      |       |              |
|   3   |  18/1     |    3       |   Decision trees regression                                  |   [slides]() [video]()     |              |
|      |  20/1     |    6       |  Ensemble methods, Random forests   |   [slides]() [video]()       |              |
|      |  22/1    |          |  Lab assignment 1 continued                     |       |              |
|   4   |  25/1     |  ch 3 from MMDS book         |    Locality Sensitive Hashing (LSH)      |   [slides]() [video]()   |              |
|      |  27/1     |             |  LSH Continued       |        |              |
|      |  29/1     |          |  **Lab assignment 1 Due** and Lab assignment 2 announced                     |       |              |
|   5   |  1/2     |          |  Dimensionality reduction SVD, PCA   |  [slides]() [video]()      |            |
|       |  3/2     |          | Recommender Systems (Collaborative Filtering)   |  [slides]() [video]()      |            |
|      |  5/2     |    Lab      |  Work on Lab assignment 2 (LSH)  |         |            |
|   6   |  8/2      |     6       |   Rule based, Nearest Neighbors classifiers                                     |   [slides]() [video]()   [Exercise](https://github.com/dat550-2021/course-info/blob/master/exercises/Exercise-3.pdf) |              |
|      |  10/2      |         |    Bayesian classifiers  (Naive Bayes and Bayesian Networks)   |   [slides]() [video]()       |              |
|      |  12/2     |    Lab      |  Work on Lab assignment 2 (LSH)       |         |            |
|  7    |  15/2     |  6         |   Bayesian classifiers                                    |   [hands-on-5](https://github.com/dat550-2021/course-info/tree/master/hands-on/hands-on-5)    |              |
|      |  17/2     |   6        |    Linear Regression  |  [slides]() [video]()     |              |
|      |   19/2     |     Lab  | **Lab assignment 2 Due**  and Lab assignment 3 announced, projects announced     |       |         
|  8   |  22/2     |         |   Logistic Regression                                 | [slides]() [video]()       |              |
|      |  24/2     |      |  Support Vector Machines (SVM)                        |      |              |
|      |  26/2     |    Lab      |  Work on Lab assignment 3 (SVD/Recommendation Systems)  **Project selection due**     |         |            |
|   9   |  1/3     |           |  SVM (continued)   |  [slides]() [video]()      |              |
|      |  3/3     |     |   Neural Networks, Deep feed forward networks, Backpropagation                   |  [slides]() [video]() |               |
|    |  5/3     |     Lab       |       Work on Lab assignment 3 (SVD/Recommendation Systems) / Work on project                                   |       |              |
|   10   |  8/3     |           |   Convolutional Neural Networks (CNNs)     |    [slides]() [video]()  |              |
|      |  10/3     |    | CNN Applications             |    [slides]() [video]()   |              |
|     |  12/3     |       Lab       |   **Lab assignment 3 Due**  Work on project                                       |       |              |
|   11   |  15/3     |       |    Recurrent Neural Networks       | [slides]() [video]()   |              |
|      |  17/3     |      | GRU, LSTM and Transformer models                    |  |              |
|   |  19/3      |     Lab      |    Work on project                    |       |                 |
|  12    |  22/3      |         |  Guest lecture 1 (Deep Reinforcement Learning) |  [slides]() [video]() |     Given by  Diana Spencer                             |       |         |
|      |  24/3      |         |    Guest lecture 2 (Deep Reinforcement Learning) |   [slides]() [video]() |     Given by  Diana Spencer           |
|      |  26/3      |   Lab    |  Work on project ||               |
|  13  |  29/3      |           |   Easter (No lecture)                                    |       |              |
|      |  1/4     |           |    Easter (No lecture) |        |              |
|      |  3/4     |           |     Easter (No lab)                     |     |              |
|  14  |  5/4     |           |     Easter (No lecture)                            |       |              |
|      |  7/4     |           |  Deep learning on graphs (network embeddings)  |    [slides]() [video]()      |              |
|      |  9/4      |       |  Work on project ||               |
|   15   |  12/4     |           |    Clustering (K-means, K-medoids, Spectral, EM)                    |   [slides]() [video]()     |              |
|      |  14/4      |         |   Guest lecture 3 (Time series analysis) |   [slides]() [video]() |     Given by  Magnus Book            |
|    |  16/4     |      Lab        |  **Project + report due**                                         |       |              |
|   16   |  19/4     |         |   Project presentation + Q&A       |         |              |
|      |  21/4     |    |  Project presentation + Q&A                   |       |              |
