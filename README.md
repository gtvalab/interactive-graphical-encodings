# Evaluating Interactive Graphical Encodings for Data Visualization
User interfaces for data visualization often consist of two main components: control panels for user interaction and visual representation. A recent trend in visualization is directly embedding user interaction into the visual representations. For example, instead of using control panels to adjust visualization parameters, users can directly adjust basic graphical encodings (e.g., changing distances between points in a scatterplot) to perform similar parameterizations. However, enabling embedded interactions for data visualization requires a strong understanding of how user interactions influence the ability to accurately control and perceive graphical encodings. In this paper, we study the effectiveness of these graphical encodings when serving as the method for interaction. Our user study includes 12 interactive graphical encodings. We discuss the results in terms of task performance and interaction effectiveness metrics.

## Graphical Encodings Evaluated
We studied the effectiveness of 12 versions of interactive graphical encodings (vertical length, horizontal length, horizontal distance, vertical distance, angle, circle size, square size, shading, horizontal slider, vertical slider, horizontal curve, vertical curve) for seven different target value (25%, 50%, 75%, 125%, 150%, 175%, and 200%). Each participant performed 84 tasks (12 interactive graphical encodings x 7 trials) with randomized task order. Current value (starting point) of all interactive graphical encodings was 100%. See Figure below for more details.

![header](https://cloud.githubusercontent.com/assets/4343770/23340330/6a614b16-fc02-11e6-8464-915796e3acdb.png)
![full-1](https://cloud.githubusercontent.com/assets/4343770/23340342/8a6683a4-fc02-11e6-95d0-76683354f42b.png)
![full-2](https://cloud.githubusercontent.com/assets/4343770/23340349/99e4b724-fc02-11e6-95cd-c048b0dd1794.png)

## Task
Each interactive graphical encoding was accompanied by instructions that required the participant to adjust the interactive graphical encoding to a target value. A target value is a certain percentage that we asked each participant to adjust the interactive encoding to. For example, for the length encoding, we asked participants to adjust the length to 150\% of its current value. Participants could adjust the graphical encodings' values by directly manipulating them, as described previously.

Participants in the pilot study stated that they sometimes lost track of the starting value for the question while performing a task. To address this feedback, we persisted the initial value as a reference point while users interacted with encodings. Since the order of encodings and target values was randomized, this reference point helped users to keep track of the initial position for the given encoding. The initial value was shown as a semi-transparent reference point for all the graphical encodings except shading. For shading, we used two shadings side by side. The shading on the right-side always showed the initial value. The shading on the left-sides was the one that the participants could interact with. 


## Running the study
After downloading/cloning the repository, navigate to the code folder. Open the trialQuestions.html file in a browser to go through the trial questions participants were given. On completeing the 12 trial questions, you will be navigated to actualquestionsset.html automatically. This file has the code used to generate randomly ordered sets of 84 questions for each session. The responses to these questions were used for our analysis.

## Supplementary material
Under the supplementary_materials folder, you can find all the files used for the paper (images, tables etc.) and the analysis (interaction logs, line charts etc.)
