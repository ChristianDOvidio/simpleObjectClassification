# simpleObjectClassification
Simple object detection script using tensorflow and Inception v3/v4.
Extremely simple step by step guide to use for beginners

To Use:
1)  Make sure you have python3 installed on your linux computer:  
   $ sudo apt-get update  
   $ sudo apt-get install python3.6  
   
2) Make sure you have tensorflow installed on your linux computer within a virtual environment:  
    https://www.tensorflow.org/install/install_linux#InstallingVirtualenv  
    
3) Download this repository to computer  

4) Open a command prompt in the models/research/slim directory of the download  

5) Open your tensorflow environment:  
     $ source ~/tensorflow/bin/activate      # bash, sh, ksh, or zsh  
     $ source ~/tensorflow/bin/activate.csh  # csh or tcsh  
     
6) Open your python environment:  
     $ python  

7) Import python function:  
     $ from predict import predict  
     
8) Call function on image of your choice (two images are provided: 'image1.jpg' and 'image2.jpg', additional images should be .png or .jpg and should be placed in /models/research/slim/models/images):  
     $ predict('image1.jpg')  
