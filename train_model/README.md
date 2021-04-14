# STEPS TO TRAIN A MODEL 

1. Step-1: Pre-process data (preprocess_crystals.py)

* edit the path to energy training data in line 21 if using your own data 
* edit the path to POSCARs in line 25 if using your own crystal structures
* python preprocess_crytals.py 
* this will create a folder "tfrecords" containing following the files 
* (1) train.tfrecord.gz (2) valid.tfrecord.gz (3) test.csv.gz (4) preprocessor.json

2. Step-2: train the model (train_model.py)

* python train_model.py    
* this will create a folder "trained_model" containing the following files
* (1) log.csv (#epochs, #training loss, #validation loss) (2) best_model.hdf5 (trained weights) 

3. Step-3: test the model (run_test.py)

* edit the path to POSCARs in line 28 
* python run_test.py    
* this will use the model created in step 2 to make energy predictions on the test set from step 1
* file predicted_test.csv will be saved containing predicted energies   
