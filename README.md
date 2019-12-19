# Game-of-Deep-Learning

# Classifying Ships 
   
Ship or vessel detection has a wide range of applications, in the areas of maritime safety, fisheries management, marine pollution,
defence and maritime security, protection from piracy, illegal migration, etc.

Keeping this in mind, a Governmental Maritime and Coastguard Agency is planning to deploy a computer visionbased automated system to
identify ship type only from the images taken by the survey boats. You have been hired as a consultant to build an efficient model for 
this project.

There are 5 classes of ships to be detected which are as follows:
   1. Cargo
   2. Military
   3. Carrier
   4. Cruise
   5. Tanker
  
# Approach
I have used fastai cnn learner datablock api. 

different image size (299/484/599)
different pre-trained architectures (resnet101/resnet152/densenet161/densenet169)
different augmentation techniques
mixup models (see the code for details)

# Score
public LB score - 0.9596 (Rank - 94/2083)
private LB Score - 0.9596 (Rank - 94/2083)
