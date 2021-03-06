## Guidelines for the project:


* Decide the topic (see [topics](mini_projects.md))
  * Specify the preferences [here](https://forms.gle/oPEK8kD5nbS5GoKY6)
* Register your team in autograder (group registration)
* Check if know the task clearly, 
  * Is it supervised? or unsupervised task?
  * Pattern detection or anomoly detection?
  * Write down the task description, input, expected output, potential challenges you expect
* if you have the appropriate data for the task
  * Look for multiple datasets preferably
  * if it is supervised task do you have labels?
  * If you want to use deep learning do you have enough data?
* Decide your roles in the project
  * Divide tasks team work is important
  * Roughly each member should contribute for 1/3rd of the load (or whatever your team size is)
* Cleanup, Explore the data
  * Remove noise if any
  * Check for outliers
  * Normalize, feature scaling, binarize see what is necessary
  * apply SVD or PCA or TSNE to visuzalize
* Decide which data mining algorithm is suitable?
  * Possibly several
  * Try a few algorithms you are free to use sklearn or whatever library you prefer
  * Possibly ensemble techniques like random forest or adaboost work better
  * Possibly a new method, or novel set of features for the same methods
* Experiments 
  * paramter tuning 
   - Learning rate, regurlarization parameter, dropout etc 
   - Depth and width of neural network
   - Model specific parameters for CNNs and RNNS or any other type of neural network you are training
   - For unsupervised techniques cluster size etc
  * compare all the approaches
  * document the limitations of all the approaches you try
  * Choose the best performing method and do more detailed analysis
  * evaluation measures
  * Precision, Recall, F1, ROC curve
  * Statistical significance test (see the examples [here](https://machinelearningmastery.com/parametric-statistical-significance-tests-in-python/))
* Report
  * At least 4 pages (max 10 pages) in 2 column ACM conference style in latex (Here is the link to the template on [overleaf](https://www.overleaf.com/latex/templates/acm-conference-proceedings-new-master-template/pnrfvrrdbfwt))
  * Writing should be high quality technical writing not copy pasting think of this as a writing practice for your thesis (Refer to this [book](https://pingpong.chalmers.se/public/pp/public_courses/course08583/published/1510227352918/resourceId/4156227/content/Zobel%20-%20Writing%20for%20computer%20science%203rd%20edition.pdf) for tips on good writing )
  * Describe the task, dataset, methods you use and discuss their limitations you saw in the experiments
  * Don't forget to include the github link to your code in the report along with a README.md in github repository which mentions how to reproduce your results in the report.
  * Very important: Document who did what and justify you did equal share of the tasks
* Presentation
  * 5-10 minutes presentation per team
  * Discuss the problem, data, interesting findings etc
  * In person project presentations are not preferred. Threfore, each team needs to send a video recording of the presentation with voice over (10 minutes max per team). I will setup a call on zoom with each team for a Q&A session after that. Exact date for the presentation will be coming soon! Or optionally you can do it in the presentation + Q&A in a zoom call jointly live.
 * Deadline
   * Deadline for project code (in github), report and presentation video is extended to 23.04.2021 (end of the day CET)
   * Live zoom presentations will happen on 26th and 28th April (12-2). Doodle poll will be sent out soon for choosing time slots. Each team gets 10 minutes for presentation + 5 minutes for Q&A
