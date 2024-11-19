# Black-and-white-image-colourization
Credits and Reference
	1. http://richzhang.github.io/colorization/
	2. https://github.com/richzhang/colorization/

---------------------------------------------------------------------------------------------------------------------------------------------

Model files:
       Get Model files ("colorization_deploy_v2.prototxt"), ("colorization_release_v2.caffemodel"), ("pts_in_hull.npy") from below link
       https://www.dropbox.com/scl/fi/9pktz9vbwdqmbny9sdzps/Model.zip?rlkey=xoxhlhbobboxm5zaet4m7ylvk&st=yl0ce3in&dl=0


       Download the zip folder from the link and extract the folder and paste the folder in the project folder
change the above model files path in colorize.py according to your folder location in your laptop

----------------------------------------------------------------------------------------------------------------------------------------------

Suggested python version - 3.10.11

To clone this repository you can use this syntax

    git clone https://github.com/ramcharantejpuli/Colorization.git


Download/install dependencies from requirements.txt
Syntax - 


    pip install requirements.txt

Now open terminal or command prompt and change directory to the project folder by 
cd <path_directory>
now run the below command
| | | | | | | | | | | | | | | | | | | | | | | 
     
    python colorize.py -i images/path_of_image.jpg

Colorize! This script will colorize an image. The results should match the images in the imgs_out folder.
------------------------------------------------------------------------------------------------------------------------------------------------
                                            THANKYOU - PULI RAM CHARAN TEJ
