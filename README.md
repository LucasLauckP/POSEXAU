# POSEXAU

POSEXAU is a Tool to Auxiliate Exercises Execution Pose did to my Final Paper.
That was done in an Anaconda enviroment with python 3.7.11 using Jupyter Notebook IDE.

The first function of posexau is to inspection of shoulders exercise Lateral Raise, you can put a video in de input and verify if you are doing correct. 

The principal function is:

posexau.inspec_lateral_raise(confs,prob_min_lateral_raise,frame, points, angle_max_arms, True)

That recive with parameters:

"confs" =  vetor with confiabilities.

"prob_min_lateral_raise" = minimal confiability choose for the user.

"frame" = frame for the video.

"poitns" = points of body positions in the frame.

"angle_max_arms" = minimal angle accept for the tool choose for the user to the arms in the exercise.

Flag to choose if the Tool draw the angles about the arms and chest in the frame.

1.
Tutorial to create the enviroment necessary to use that Tool.

conda create --name POSEXAU python=3.7.11

2.
Activate the enviroment:

conda activate POSEXAU

3.
Install packages dependencies: 

conda install -c anaconda jupyter

conda install -c conda-forge opencv=4.5.3

conda install -c anaconda numpy=1.21.2

conda install -c jmcmurray os=0.1.4

pip install import-ipynb=0.1.3


Obs:
The Caffe Model weights used can be dowloaded at
http://posefs1.perception.cs.cmu.edu/Users/tsimon/Projects/coco/data/models/mpi/pose_iter_160000.caffemodel
