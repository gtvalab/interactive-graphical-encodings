
# Evaluating Interactive Graphical Encodings for Data Visualization
This paper contians materials of an experiment that is conducted to study the effectiveness of graphical encodings when serving as the method for interaction.


# Repository's Map
There are two main folders in this repository: Experimental Software and Supplementary Materials

** ***Experiment Software:*** 
This folder contains the code (JS, CSS, HTML) for our experiment. After downloading/cloning the repository, navigate to the code folder. Open the trialQuestions.html file in a browser to go through the trial questions participants were given. On completeing the 12 trial questions, you will be navigated to actualquestionsset.html automatically. This file has the code used to generate randomly ordered sets of 84 questions for each session. The responses to these questions were used for our analysis.


** ***Supplementary Materials:*** 
Under the supplementary_materials folder, you can find five folders.

* **SPSS Files:** This folder contains the results of our data analysis using in both SPV and pdf formats.
* **ScreenShots for all the encodings:** This folder contains the screen shots of all 84 encodings (12 encodings * 7 target values. To see all 84 encodings, you can open the "experiment_summary.html" in the folder using any browser.)
* **Raw Data:** This contains the raw data collected from the experiment. 
* **Interaction Logs for all the encodings:** This folder the interaction logs for all 84 encodings. To see interaction logs for all 84 encodings, you can open the "InteractionAnalysis.html" file using any browser.
* **Figures:** This contains all the figures used in the paper.


## Graphical Encodings Evaluated
We studied the effectiveness of 12 versions of interactive graphical encodings (vertical length, horizontal length, horizontal distance, vertical distance, angle, circle size, square size, shading, horizontal slider, vertical slider, horizontal curve, vertical curve) for seven different target value (25%, 50%, 75%, 125%, 150%, 175%, and 200%). Each participant performed 84 tasks (12 interactive graphical encodings x 7 trials) with randomized task order. Current value (starting point) of all interactive graphical encodings was 100%. See Figure below for more details.

![header](https://cloud.githubusercontent.com/assets/4343770/23340330/6a614b16-fc02-11e6-8464-915796e3acdb.png)
![full-1](https://cloud.githubusercontent.com/assets/4343770/23340342/8a6683a4-fc02-11e6-95d0-76683354f42b.png)
![full-2](https://cloud.githubusercontent.com/assets/4343770/23340349/99e4b724-fc02-11e6-95cd-c048b0dd1794.png)

## Task
Each interactive graphical encoding was accompanied by instructions that required the participant to adjust the interactive graphical encoding to a target value. A target value is a certain percentage that we asked each participant to adjust the interactive encoding to. For example, for the length encoding, we asked participants to adjust the length to 150\% of its current value. Participants could adjust the graphical encodings' values by directly manipulating them, as described previously.

Participants in the pilot study stated that they sometimes lost track of the starting value for the question while performing a task. To address this feedback, we persisted the initial value as a reference point while users interacted with encodings. Since the order of encodings and target values was randomized, this reference point helped users to keep track of the initial position for the given encoding. The initial value was shown as a semi-transparent reference point for all the graphical encodings except shading. For shading, we used two shadings side by side. The shading on the right-side always showed the initial value. The shading on the left-sides was the one that the participants could interact with. 





