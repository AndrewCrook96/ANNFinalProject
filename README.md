# ANNFinalProject
Final Project for Artificial Neural Networks class

The code is broken up into several Jupyter Notebook files. The Jupyter server is hosted on WSL2 in order to enable gpu acceleration. The code attempts to use a gpu if one is available. I'm not sure if it will work on a cpu. 

The code requires tensorflow version 2.17.0 and Keras version 3.4.1
it also requires boto3, logging, botocore, numpy, matplotlib, scipy, s3fs, h5py.
These can all be installed with pip if missing. 

To save data locally run the script dasEventDetectionSaveLocal. This will require at least 10 Gb of space.
To train a model, run training3 or training4. 
For inference run inference. Output graphs will be saved to a file.

The code is kind of a mess, but you should just be able to run the whole file and it should work. I didn't do a very good job of setting up the code to tweak parameters, so reach out if you need to change something and can't figure out where to do it. 
If you run into any problems running the files you can reach out with questions to andrew.crook@usu.edu


