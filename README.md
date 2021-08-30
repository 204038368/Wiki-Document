# Wiki-Document
## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Final Checks](#final-checks)
* [Setup](#setup)
* [Images](#images)
* [Analyse](#analyse)
 
## General info
This project is designed to run a Stroop Task and analyse response times. The Stroop task will be run through the Psychopy interface, while scripts will have been produced in Thonny/Python. This task is designed to show experimenters a delay in reaction times between our automatic and controlled information processing. This task requires a higher cognitive demand and therefore is important to run and collect data to understand automatic brain processing. This experiment will consist of (4 x 15) congruent) and (4 x 5) incongruent trials of other word colour combinations, totalling 120 trials.
 
  
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
File > Open > Pin_Assessment2 > section_A.py.
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
Once the experiment has run, the data files should be saved under 'stroop_data'. Double check these files have saved in the correct folders and are easily accessible for future data analysis. The 'stroop_data' will contain files that show the following:
trialnum  (1 up to 120), colourtext (the word shown in the trial), colourname (colour of the text shown in the trial), condition (congruent or incongruent), response (colour name of the response the participant made), rt (reaction time formatted appropriately as a floating point number in seconds), and finally correct (true or false). 

 


 ## Images 
<img width="1435" alt="Screenshot 2021-07-10 at 00 04 56" src="https://user-images.githubusercontent.com/87214421/125154791-cba42700-e153-11eb-8668-f14e82cde6e2.png">
<img width="670" alt="Screenshot 2021-07-10 at 00 06 10" src="https://user-images.githubusercontent.com/87214421/125154796-d068db00-e153-11eb-9a23-59104caebc25.png">
<img width="819" alt="Screenshot 2021-07-10 at 00 06 37" src="https://user-images.githubusercontent.com/87214421/125154806-d8287f80-e153-11eb-861f-efec1cce034b.png">
<img width="358" alt="Screenshot 2021-07-10 at 00 07 00" src="https://user-images.githubusercontent.com/87214421/125154815-deb6f700-e153-11eb-91fc-c2e15fe0374c.png">
<img width="828" alt="Screenshot 2021-07-10 at 00 08 06" src="https://user-images.githubusercontent.com/87214421/125154822-e4144180-e153-11eb-98d5-504d489e5505.png">
<img width="213" alt="Screenshot 2021-07-10 at 01 58 05" src="https://user-images.githubusercontent.com/87214421/125154829-ee364000-e153-11eb-8348-0a0c8b4597d5.png">
<img width="277" alt="Screenshot 2021-07-10 at 05 56 33" src="https://user-images.githubusercontent.com/87214421/125154832-f42c2100-e153-11eb-88fd-0001a1213071.png">
<img width="976" alt="Screenshot 2021-07-10 at 06 05 12" src="https://user-images.githubusercontent.com/87214421/125154833-faba9880-e153-11eb-8c75-e57d31e26f84.png">

## Analyse
 
Once the experiment has ended and it is time to run the code for analysing the graphical data, ensure that you can easily navigate to the correct files.
To analyse this data:
Again, we must ensure Psychopy is downloaded for the user.
To open the experiment code, open Psychopy v3.0 (click the icon). Click 'open' and navigate to:
File > Open > Pin_Assessment2 > section_B.py
Once loaded, click the green 'RUN' arrow at the top of the screen when you are ready to analyse the results of the data in a graph using matplotlib.pyplot.
The script itself, is importing the csv files created from the experiment and plotting it on a graph. This script is usuable with section_a.py as the stimulus presentation and analysis code will be working together. 

From here, the code will plot the distribution means for the congruent and incongruent conditions, utilising the most appropriate form of plot for the data. This graph will illustrate a neatly formatted table and contain the following columns: Participant, Congruent and Incongruent mean response times. Once run, a graph/plot will appear with the relevant data. The plot will show an appropriate title matching the experiment and the x (participant) and y (mean response times) axis will be easily readable for analysing the data. From here, the script will have saved that image file named 'group.png.' When writing up a report, this data will show the mean reaction times put the participant in a bin or bar of the graph in association with the congruent or incongruent word presentations.
