##################################################################################
#Decription : Project for building Filter Image App using Beanstalk              #
#Version: 1.0                                                                    #
#Date: 04/-9/2022                                                                #
#Author: Mostafa Ibrahim                                                         #
##################################################################################
/*This is an information for the content files names used during the project also*\
  the url which have been used during the Test the App functionalty.               
*/                                                                               *\

A Link for the code used for provsioning Filter Image application.

Code Repo : https://github.com/ibrmostafa/Image-Filter-App/

//***********************************************************************\\
BeanStalk Configuration LinK and port used to fuilfil the requirement.

Exract URL Image String and Added to running app over port 8082 with Path "/filteredimage?image_url=" to be filted

Beanstalk URL http://image-filter-app-dev2.us-east-1.elasticbeanstalk.com/filteredimage?image_url=<Image_URL>

(1)Example : http://image-filter-app-dev2.us-east-1.elasticbeanstalk.com/filteredimage?image_url=https://upload.wikimedia.org/wikipedia/commons/b/bd/Golden_tabby_and_white_kitten_n01.jpg

Old Sample with no handling any unsupported jimp images.

Beanstalk URL :http://image-filter-starter-code-dev222222222222222222.us-east-1.elasticbeanstalk.com/filteredimage?image_url=<Image_URL>

xample : 
(1)http://image-filter-starter-code-dev222222222222222222.us-east-1.elasticbeanstalk.com/filteredimage?image_url=https://video.udacity-data.com/topher/2022/March/6244e0da_screen-shot-2022-03-30-at-3.04.58-pm/screen-shot-2022-03-30-at-3.04.58-pm.jpeg


Local Test appplied on an EC2 below are a sample for an filtered image using ec2 instance 

EC2 Filter Image URL :
(1)http://ec2-54-210-61-108.compute-1.amazonaws.com:8082/filteredimage?image_url=https://video.udacity-data.com/topher/2022/March/6244e0da_screen-shot-2022-03-30-at-3.04.58-pm/screen-shot-2022-03-30-at-3.04.58-pm.jpeg  
(2) http://ec2-44-194-190-240.compute-1.amazonaws.com:8082/filteredimage?image_url=https://upload.wikimedia.org/wikipedia/commons/b/bd/Golden_tabby_and_white_kitten_n01.jpg