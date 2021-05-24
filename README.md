# Face-Mask-Detection
This project was done using MATLAB to detect if face masks are present - worn properly. Two different models are included here - one using Training of Deep Learning Model and the other implemented using Viola Jones Algorithm. 

Model 1: Deep Learning with CNN

I have designed a classification based neural network comprising of 15 layers and trained it with 2767 images. Due to absence of GPU, I have designed a simple network which attained a validation accuracy of 94.5%
The trained network is uploaded along with the code files.

Execution:

            run the training.m file on the command window if you want to train the network first.
            
            else , use the trained network - gen_net, by just running facedetecttest.m file directly.
            
          
Model 2: Viola Jones Algorithm based

I have designed a simple model which detects presence of mask by using Viola Jones algo to detect presence/absence of certain facial features and tested on the same dataset. 

Execution:

            run the facedettest.m file on the command window directly.
          
Technical Details of Project mentioned in the Report.
