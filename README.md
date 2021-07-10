# Wiki-Document
## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Final Checks](#final-checks)
* [Setup](#setup)
* [Images](#images)
* [Analyse](#analyse)
 
## General info
This project is designed to run a Stroop Task and analyse response times. The Stroop task will be run through the Psychopy interface, while scripts will have been produced in Thonny/Python. This task designed to show experimenters a delay in reaction times between our automatic and controlled internal visual processing. This task requires a higher cognitive demand and therefore is important to run and collect data to understand brain automatic brain processing. This experiment will consist of (4 x 15) congruent) and (4 x 5) incongruent trials of other word colour combinations, totalling 120 trials.
 
  
## Technologies
Project is created with:
* Psychopy v3.0
* Thonny 3.3.3
* Python Software Foundation
* Matplotlib.pyplot

## Final Checks
Ensure the participant understands the task. Check that your experiment code is running properly. Give the participants an opportunity to see the stimulus prior to runninng the experiment. Ensure the participants vision is corrected for glasses/lenses (if neccessary). If these are all okay, you can setup and begin running the experiment.
  
## Setup
To run this project:
We must ensure Psychopy is downloaded for the user.
To open the experiment code, open Psychopy v3.0 (click the icon). Click 'open' and navigate to:
File > Open > Pin_Assessment2 > section_a.py.
Once loaded, click the green 'RUN' arrow at the top of the screen when you are ready to start the experiment.
Participants should be told the relevant information, via the information sheet which should have been given to them prior to beginning the experiment. Participants should be fully aware of the experiment taking place and that they understand their role in the relevant task.
Before running this experiment, participants will be required to input some information (participant ID) which should be given prior to the experiment.
Before the experiment begins, particpants should be informed on the correct keys they will be interacting with during this experiment.
The Task requires participants to view a set of words that are printed on the screen ('red', 'blue', 'green', yellow) which will be presented either incongruently: the word, irrespective its colour meaning (red:blue) or congruently, respectively printed in the same colour of the meaning of the word (red:red) etc. and respond using a pre-selected set of keys on the computer. Meaning, participants will be asked to name the colour of the word represented, and not just the colour of the actual word itself.
They keys recognised by the code will be as follows:
'red' = 'f'
'blue' = 'g'
'green' = 'h'
'yellow' = 'j'
Each word will be presented for 5 seconds and then disappear if no key is pressed. It is important for participants to select the correct key in a limited time frame to accurately analyse the results.
Once the experiment has run, the data files should be saved under 'stroop_data'. Double check these files have saved in the correct folders and are easily accesible for future data analysis. The 'stroop_data' will contain files that show the following:
trialnum  (1 up to 120), colourtext (the word shown in the trial), colourname (colour of the text shown in the trial), condition (congruent or incongruent), response (colour name of the response the participant made), rt (reaction time formatted appropriately as a floating point number in seconds), and finally correct (true or false). 

 


 ## Images 


 
## Analyse
 
Once the experiment has ended and it is time to run the code for analysing the graphical data, ensure that you can easily navigate to the correct files.
To analyse this data:
Again, we must ensure Psychopy is downloaded for the user.
To open the experiment code, open Psychopy v3.0 (click the icon). Click 'open' and navigate to:
File > Open > Pin_Assessment2 > section_b.py
Once loaded, click the green 'RUN' arrow at the top of the screen when you are ready to analyse the results of the data in a graph using matplotlib.pyplot.
The script itself, is importing the csv files created from the experiment and plotting it on a graph. This script is usuable with section_a.py as the stimulus presentation and analysis code will be working together. 

From here, the code will plot the distribution means for the congruent and incongruent conditions, utilising the most appropirate form of plot. for the data. This graph will illustrate a neatly formatted table and contain the following columns: Participant, Congruent: Mean (reaction time), Stddev (reaction time), % correct. Incongruent: Mean (reaction time), Stddev (Reaction time), % correct. Once run, a graph/plot will appear with the relevant data. The plot will show an appropriate title matching the experiment and the x and y axes will be easily readable for analysing the data. From here, the script will have saved that image file named 'group.png.' When writing up a report, this data will show the mean and standard deviation reaction times and how often the participant selected the correct key in association with the congruent or incongruent word presentations. 
