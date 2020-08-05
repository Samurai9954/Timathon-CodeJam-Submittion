# Timathon Submittion (Koro Sensei and I'm Batman)
This is the GitHub repository for Timathon Competition by "Koro Sensei" and "I'm Batman"
       
          
Following the Theme of the competition "Generate", This program generates Image Captions with the help of a user-friendly Flask GUI.
              
              
You can easily just drag and drop your file and The Artificial Intelligent Model will give you 2 Captions it predicts related to the Picture that you gave with ease.        
      
      
It uses 2 Neural Networks based on the Microsoft Common Objects in Context (MSCOCO) Which has a large dataset of over 125,000 Pictures!
         
         
The models have been trained on High-Quality Specifications including a Threadripper, 128GB RAM, And Trained on a 3 Titan RTX Graphics Cards Running in SLI (Yes, We have those) for enhancing these images up to 30K Resolution. 
               
# But, How to use it for me?
#### Requirements :-
##### 1) Ubuntu or Windows 10 (64bit Only)
##### 2) Python 3.6, git,  Installed and in the Enviorment Paths
##### 3) Run the command "pip install -r requirements.txt" **(BEFORE RUNNNING THE FILES)**
##### 4) You don't need beastly specs to run this cause the models have been Pre-Trained 😁               
             
             
After you match your PC with the requirements you can just use this tool with a single click. You can find the respective folders according to your Operating System named "Ubuntu" and "Windows 10". Run "run.sh" for Ubuntu and "run.bat" if you are on Windows 10.        
                        
That's It!! The program will automatically open a Web GUI in your chosen Web browser. For Eg. Google Chrome or Microsoft Edge          

### But Why Am I Getting Two Predictions?
This is to present security that you get the best and accurate results. There are 2 Neural Networks in this process. A CNN (Convolutional Neural Network) and an RNN-LSTM (Long Short Term Memory Neural Network). As sometimes one of the Neural Networks fails to give optimal results (Which is unlikely to happen but 2 is always better than 1!) The other Neural Network gives the accurate result! The CNN is best at giving accurate results but will not give much extra detail, The LSTM Will sometimes be Wrong (20% Failure Rate) but will give extra detail about the Photo's Caption.
            
            
### How does this AI Give Such Human-Like Grammer?
There is a vocabulary file attached to the Pre-Trained Models. The Vocabulary file is based on the "Oxford English Directory". Just to be safe (As Mistakes Happen) The Captions also go through the "Grammarly API for Grammer Correction".
               
### But I don't understand English / Not good at it. What should I do?
We got you! The Flask GUI has a dropdown containing languages you want the website in. Just click and select your native language. This is possible due to the "Google Translate API". This is amazing if you don't want to waste time opening a Dictionary or Copy and Pasting each sentence again and again into Google Translate.
          
### This seems all nice and all, But what if I don't get the results I expected?
If you don't get the experience you expected, You can join our Discord Server @ linkBLABLA
You can give suggestions or if you are a Developer (Oh, Nice you too?) Then you can also help our Devs improve the performance of this tool.

**NOTE: THIS PROGRAM WILL NOT RUN ON WSl (WINDOWS SUBSYSTEM FOR LINUX).**
If facing any issues you can contact us on our Discord - https://www.discord.com/THISISOURHELPSERVERBLABLABLA
