![](https://github.com/shouryadey/Gun_detection_using_tensorflow/blob/master/gundet.gif)

To run the model:

1)Clone https://github.com/tensorflow/models.git

2)Install dependencies using https://github.com/tensorflow/models/blob/master/research/object_detection/g3doc/installation.md

3)In models/research/object_detection/ 

  >i)Create a folder named output_video

  >ii)Copy and paste the test_video folder from the gun_detection_tensorflow repository

  >iii)Copy and paste the gun_detection.ipynb from the gun_detection_tensorflow repository

  >iv)copy the paste the ssd_mobilenet_v1_pets.config file from the gun_detection_tensorflow repository

  >v)copy and paste gun_graphxxxxx directories  from the gun_detection_tensorflow repository/(gun_graph17230 ,gun_graph16454etc)

4)In models/research/object_detection/training

  i)Copy and paste ssd_mobilenet_v1_pets.config file from the gun_detection_tensorflow repository

5)Running the model

   In models/research/object_detection/ run jupyter notebook in terminal

  >1) then in jupyter notebook open gun_detection.ipynb 

  >2) Run 

  >3) Press Q to exit to close the running video.
  --------------------------------------------------------------------------------------------------

** to change between models,use step 3)v and remember to change accordingly in gun_detection.ipynb file

** to change the test video copy the new video to test_video as in 3)ii and also change the video name v1.mp4 accordingly in gun_detection.ipynb   

** what one requires to run the model are config file,frozen graphs(the saved models in gun_graphxxxxx folders) and the test video. 
