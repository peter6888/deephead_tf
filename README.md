# deephead_tf
To train a state-of-art model use the MPII head data. So that can use for elevator as well as other security camera.

Done:
0. Clean/prepare MPII data
1. Read MPII data and show sample head (with OpenCV)
2. Feed head data to a vannila machine learning model, to get a good result
3. Generate a *.pb file for that vannila model and export to the other project

## deep head for elevator use
### Done:
1. Output head dataset to .txt file, so that can used by keras-frcnn model https://github.com/peter6888/deephead_tf/blob/master/showhead.ipynb
2. The output head dataset at https://github.com/peter6888/deephead_tf/blob/master/test.txt
3. Train with the head dataset test.txt (in keras-frcnn repository) https://github.com/peter6888/keras-frcnn/blob/master/train_mpii.sh
4. Save the *.pb and pickle.config file (with save model parameter) https://github.com/peter6888/keras-frcnn/blob/master/test.ipynb
5. Load the *.pb file and use to predict a whole *.h264 file (with save=False parameter) https://github.com/peter6888/keras-frcnn/blob/master/test.ipynb

### To do:
1. use c++ code to load *.pb
2. use c++ code to draw a sample result


