# Timathon Submittion (Koro Sensei and sQuidWaRdRoXXX)
This is the GitHub repository for Timathon Competition by Koro Sensei and sQuidWaRdRoXXX
       
          
Following the Theme of the competition 'Generate', this program generates image captions with the help of a user-friendly Flask GUI.
              
             
You can easily just drag and drop your file and the artificially intelligent model will give you two predicted captions in reference to the picture picture that you gave with ease.        
      
      
It uses two neural networks based on the Microsoft Common Objects in Context (MSCOCO) which has a large dataset of over 125,000 Pictures!
         
         
The models have been trained on cutting edge specifications including an AMD Threadripper pro, 128GB RAM, and trained on a three Titan RTX graphics cards running in SLI (Yes, We have those) for enhancing these images up to 30K Resolution. 
               
# But, How to use it for me?
### Requirements :-
##### 1) Ubuntu or Windows 10 (64bit Only)
##### 2) Python 3.6, git, installed and in the Enviorment Paths
##### 3) Run the command "pip install -r requirements.txt" **(BEFORE RUNNNING THE FILES)**
##### 4) You don't need beastly specs to run this cause the models have been Pre-Trained 😁               
             
             
After you match your PC with the requirements, you can just use this tool with a single click. You can find the respective folders according to your OS named "Ubuntu" and "Windows 10". Run "run.sh" for Ubuntu or run "run.bat" if you are on Windows 10.        
                        
That's It!! The program will automatically open a Web GUI in your default web browser eg:- Google Chrome, Microsoft Edge, Opera etc. (Yes, I still use it)         

### But Why Am I Getting Two Predictions?
This is to ensure you that you WILL get the best and most accurate results. There are two neural networks in this process. A CNN (Convolutional Neural Network) and an RNN-LSTM (Long Short Term Memory Neural Network). As sometimes, one neural network may fail to give optimal results (Which is unlikely to happen but two is always better than one!), the other neural network gives the accurate result! CNN is the best at giving accurate results but will not give additional details. The LSTM on the other hand will sometimes be wrong (12% Failure Rate) but will give the details left out by CNN about the photo's caption.
            
            
### How does this AI Give Such Human-Like Grammer?
There is a vocabulary file attached to the Pre-Trained Models. The vocabulary file is based on the "Oxford English Directory" versions 2017, 2018, 2019. Just to be safe (as mistakes happen), the captions also go through the Grammarly API for Grammer Correction.
               
### But I don't understand English / Not good at it. What should I do?
We got it covered up for you! The Flask GUI has a dropdown containing languages in which the website is available. Just click and select your preffered language. This is possible due to the "Google Translate API". This is amazing if you don't want to waste time opening a Dictionary or copy-pasting each sentence into Google Translate.
          
### This seems all nice and all, But what if I don't get the results I expected?
If you don't get the experience you expected, You can join our Discord Server @linkBLABLA
Suggestions and feedbacks are always welcome. If you are a developer (Oh, you too?), then you can also help our Devs improve the performance of this tool.

**NOTE: THIS PROGRAM WILL NOT RUN ON WSl (WINDOWS SUBSYSTEM FOR LINUX).**
If facing any issues you can contact us on our Discord - https://www.discord.com/THISISOURHELPSERVERBLABLABLA
