# Overview
- [Course Structure](#Course_Structure)
- [Labs](#Labs)
- [Schedule](#Lecture_and_Lab_Plan)

# Course Structure

# Labs

## Autograder

Autograder is a tool for students and teaching staff to manage the submition and
validating lab assignments. Autograder has been developed at the University of Stavanger.
All lab submissions from students are handled using Git, a source code
management system, and GitHub, a web-based hosting service for Git source
repositories.

Students push their updated lab submissions to GitHub. Every lab submission is
then processed by a custom continuous integration tool. This tool will run
several test cases on the submitted code. Autograder generates feedback that
let the students verify if their submission implements the required
functionality. This feedback is available through a web interface. The feedback
from the Autograder system can be used by students to improve their
submissions.

Below is a step-by-step explanation of how to register and sign up for the lab
project in Autograder.

### Registration

1. Go to [GitHub](http://github.com) and register. A GitHub account is required
   to sign in to Autograder. You can skip this step if you already have an
   account.

2. Click the "Sign in with GitHub" button in
   [Autograder](http://ag.itest.run) to register. You will then be
   taken to GitHub's website.

3. Approve that our Autograder application may have permission to access to the
   requested parts of your account. It is possible to make a separate GitHub
   account for only this course if you do not want Autograder to access your
   personal one with the requested permissions.

### Signing up for the course

1. Click the Courses menu item.

2. In the Courses menu select “Join a course”. Available courses will be listed.

3. Find the course “dat550-2021” and click Sign up.

4. Read through and accept the terms. You will then be invited to the
   organization [dat550-2021](http://www.github.com/dat550-2021) on GitHub. 
   
5. Wait for the teaching staff to verify your Autograder-registration.

6. After the teaching staff approves your account. An invitation will be sent to the email address registered with your GitHub
   account. Accept the invitation using the received emails. Note that you may receive up to 4 emails please accept invitations from all of them!

7. You will get your own repository in the organization "dat550-2021" on GitHub
   after your registration is verified. You will also have access to the
   feedback pages for this course on Autograder.

# Lecture and Lab Plan

(Lab submission deadlines are marked with **bold**.)

| W    |  Date     | Chap.     | Topic                                            | Resources | Travels / Remarks     |
|:----:|:---------:|:-----:    |--------------------------------------------------|:-------:|:------------:|
|  2   |  8/1      |   1,2     |  Introduction          |   [slides](https://stavanger.instructure.com/courses/6604/files?preview=645205)      |              |
|      |  9/1      |   2        | Data processing       |   [slides](https://stavanger.instructure.com/courses/6604/files?preview=646042)    |              |
|      |  9/1      |   Lab       | Get started with in autograder, play with jupyter notebook, numpy, pandas, sklearn       |       [hands-on-1](https://github.com/uis-dat550-spring20/course-info/tree/master/hands-on/hands-on-1) |              |
|  3   |  15/1     |   2       | Data sampling |   [slides](https://stavanger.instructure.com/courses/6604/files?preview=646042),   [Exercises](https://stavanger.instructure.com/courses/6604/files/649916?module_item_id=77824), [hands-on-2](https://github.com/uis-dat550-spring20/course-info/tree/master/hands-on/hands-on-2) |             |
|      |  16/1     |          |  Dimensionality reduction PCA, SVD   |  [slides](https://stavanger.instructure.com/courses/6604/files/650574?module_item_id=77979), [SVD video](https://www.youtube.com/watch?v=P5mlg91as1c), [Linear Algebra intro](https://www.deeplearningbook.org/slides/02_linear_algebra.pdf) [PCA explanation by Andrew Ng](https://www.youtube.com/watch?v=rng04VJxUt4)      |            |
|      |  16/1     |    Lab      |  Work on Lab assignment 1 (PCA)  |         |            |
|  4   |  22/1     |    Lab       |   Lab assignment 1 continued                     |       |              |
|      |  23/1     |    2        |  Data exploration, visualization                                  |  [Slides](https://stavanger.instructure.com/courses/6604/files/655308?module_item_id=79090)     |              |
|      |  23/1     |    3       |     Classfication (Decision Trees) |   [slides](https://stavanger.instructure.com/courses/6604/files?preview=673527)      |              |
|  5   |  29/1     |          |  **Lab assignment 1 Due** and Lab assignment 2 announced                     |       |              |
|      |  30/1     |    3       |   Decision trees regression                                  |   [slides](https://stavanger.instructure.com/courses/6604/files/664692?module_item_id=80768)    |              |
|      |  30/1     |    6       |  Ensemble methods, Random forests   |   [slides](https://stavanger.instructure.com/courses/6604/files/664693?module_item_id=80769)      |              |
|  6   |  5/2    |          |  Lab assignment 2 continued                     |       |              |
|      |  6/2      |     6       |   Rule based, Nearest Neighbors classifiers                                     |   [slides](https://stavanger.instructure.com/courses/6604/files/664694?module_item_id=80770)   [Exercise](https://github.com/uis-dat550-spring20/course-info/blob/master/exercises/Exercise-3.pdf) |              |
|      |  6/2      |         |    Bayesian classifiers  (Naive Bayes and Bayesian Networks)   |   [slides](https://stavanger.instructure.com/courses/6604/files?preview=673536)      |              |
|  7   |  12/2      |  Lab       |  Lab assignment 2 continued                     |     |              |
|      |  13/2     |  6         |   Bayesian classifiers                                    |   [hands-on-5]([hands-on-1](https://github.com/uis-dat550-spring20/course-info/tree/master/hands-on/hands-on-5))    |              |
|      |  13/2     |   6        |    Linear Regression  |  [slides](https://stavanger.instructure.com/courses/6604/files/675646?module_item_id=82491)   [hands-on-6](https://github.com/uis-dat550-spring20/course-info/tree/master/hands-on/hands-on-6)    |              |
|  8   |  19/2     |     Lab  | **Lab assignment 2 Due**  and Lab assignment 3 announced, projects announced                      |       |              |
|     |  20/2     |         |   Logistic Regression                                 | [slides](https://stavanger.instructure.com/courses/6604/files/675646?module_item_id=82491)      |              |
|      |  20/2     |  ch 3 from MMDS book         |    LSH      |   [slides](https://stavanger.instructure.com/courses/6604/files/675647?module_item_id=82492)  |              |
|  9   |  27/2     |     Lab       | Work on assignment3, **Project topic selection due**                                 |       |              |
|      |  27/2     |             |  LSH Continued       |        |              |
|      |  28/2     |      |  Support Vector Machines                         |      |              |
|  10  |  4/3      |      Lab       |   Work on assignment3                                    |       |              |
|      |  5/3      |         |   Cancelled      |        |              |
|      |  5/3      |        |   Cancelled                   |      |              |
|  11  |  11/3     |       Lab       |   **Lab assignment 3 Due**  Work on project                                       |       |              |
|      |  12/3     |           |  SVM   |  [slides](https://stavanger.instructure.com/courses/6604/files/689900?module_item_id=84246),  [hands-on-8](https://github.com/uis-dat550-spring20/course-info/tree/master/hands-on/hands-on-8)     |              |
|      |  12/3     |     |   Neural Networks, Deep feed forward networks, Backpropagation                   |  [slides](https://stavanger.instructure.com/courses/6604/files/689899?module_item_id=84247), [hands-on-8](https://github.com/uis-dat550-spring20/course-info/tree/master/hands-on/hands-on-8) |               |
|  12  |  18/3     |     Lab       |       Work on project                                        |       |              |
|      |  19/3     |           |   Convolutional Neural Networks (CNNs)     |    [slides](https://stavanger.instructure.com/courses/6604/modules/items/85004) [Lecture video](https://stavanger.instructuremedia.com/embed/6320d765-254d-4553-9d69-35005e488e64) [recap video and missing parts](https://stavanger.instructuremedia.com/embed/aa31bb77-d85d-4251-9ef9-5a6de3aa4042)  |              |
|      |  19/3     |    | CNN Applications             |    [Lecture video](https://stavanger.instructuremedia.com/embed/d2fb3d39-8892-445e-bdc6-1a240983783a)  |              |
|  13  |  25/3     |       Lab      |  Work on project                                      |       |              |
|      |  26/3     |       |    Recurrent Neural Networks       | [slides](https://stavanger.instructure.com/courses/6604/modules/items/85811) [RNNs Video](https://stavanger.instructuremedia.com/embed/ce8c2423-c09e-4c65-b4ab-620328dc8322)   |              |
|      |  26/3     |      | GRU, LSTM and Transformer models                    | [hands-on-10](https://stavanger.instructure.com/courses/6604/modules/items/85840),  [LSTM hands-on video](https://stavanger.instructuremedia.com/embed/3ca82f8c-9e4a-4435-a0ca-40252501dc28) |              |
|  14  |  1/4      |           |    Work on project                    |       |                 |
|      |  2/4      |  8.15 to 10         |   No lecture                             |       |         |
|      |  2/4      |  10.15 to 12         |   Guest lecture 2 (Time series analysis) ||     Given by  Magnus Book            |
|  15  |  8/4      |           |   Easter (No lab)                                    |       |              |
|      |  9/4     |           |    Easter (No lecture) |        |              |
|      |  9/4     |           |     Easter (No lecture)                     |     |              |
|  16  |  15/4     |           |     Work on project                               |       |              |
|      |  16/4     |           |  Deep learning on graphs (network embeddings)  |         |              |
|      |  16/4     |           |    Clustering (K-means, K-medoids, Spectral, EM)                    |       |              |
|  17  |  22/4     |      Lab        |  **Project + report due**                                         |       |              |
|      |  23/4     |         |   Project presentation + Q&A       |         |              |
|      |  23/4     |    |  Project presentation + Q&A                   |       |              |
