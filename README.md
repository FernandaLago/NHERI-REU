# NHERI-REU

"""

This project is based on an NSF goal to use a machine learning image annotation model to recognize damage from a hurricane in a 
Twitter image. Another facet of the project is to find local journalists from a Twitter dataset. 

In the Tweet Pre-Processing script, the code is used to remove retweets, duplicate tweets, and tweets with less than two links
in their description to extract images. 

In the Extract tweet images script, the code is used to isolate Tweet IDs from tweet links and use the IDs to extract 
twitter image links. The script also saves the images in a folder and as a zip file. 

In the Google AutoML Vision Model script, the code is used to input a user's image to my pre-trained machine learning model 
on Google. The model recognizes presence of damage (damage, undamaged, none), type of damage (wind, erosion, flooding, debris),
infrastructure damaged (house, commercial building, agriculture, utilities, personal belongings, road, statue), and other labels
(rescue, animal, human). 

In the Boolean Screening for local journalist script, the code is used to screen for local journalists on Twitter
using follower count and user bios. 
