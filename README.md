# Deekshantshearlet
Deekshantshearlet is a open source library created to help researchers across the globe who are curious about shearlet wavelet
https://pypi.org/project/Deekshantshearlet6/#history is the name of python library that can be used to calculate shearlet wavelet transform coefficients for any angle or scale

Below Example will help you understand how to use it
  !pip3 install Deekshantshearlet6==0.6
  from Deekshantshearlet import shearlet1 as p
  print (p(list_image[0:2], angles=2, scales=1)) # library is designed in a way where first variable is list of images of size (100,100,3),   #second variable is of angles and third variable is of scales
  #in above example we will see shearlet coefficients for two images for all angles and scales
  # In case of any issue please write an email to me.

