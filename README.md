# Project-1: Spam Detector for YouTube Comments #

UCS757 - Building Innovative Systems <br>

## Overview: ##
The purpose of this project is to detect tampering of PAN card using computer vision. This project will help different organization in detecting whether the Id i.e. the PAN card provided to them by thier employees or customers or anyone is original or not.

### Live Link: https://sdyc.herokuapp.com/ ###
(Sample Data already enclosed in this github-repo)

### I/O Screenshot :<br/> ###
#### Input-1 (Not Spam) ####
![1](https://user-images.githubusercontent.com/43958244/133942116-a751a3eb-869d-4e38-a367-7c26983d9e62.png)
<br>
<br>
Output-1
![1-output](https://user-images.githubusercontent.com/43958244/133942176-935f3854-391c-42cd-b1ef-c03eae874d0a.png)
</br>
#### Input-2(Spam) ####
![2](https://user-images.githubusercontent.com/43958244/133942222-0b4276a8-515d-4b84-9df4-fa89ff9b690e.png)
<br>
<br>
Output-2
![2-output](https://user-images.githubusercontent.com/43958244/133942243-c4774aaa-71c4-4fbc-ae73-03c5dfbbf48f.png)
</br>
### Summary :<br/> ###

-Finding out structural similarity of the images helped us in finding the difference or similarity in the shape of the images. Similarly, finding out the threshold and contours based on those threshold for the images converted into grayscale binary also helped us in shape analysis and recognition.<br>

-As, our SSIM is ~28.5% we can say that the image user provided is fake or tampered.<br>

-Finally we visualized the differences and similarities between the images using by displaying the images with contours, difference and threshold.<br>

### Novelty :<br/> ###
●	This project can be used in different organizations where customers or users need to provide any kind of id in order to get themselves verified.<br>

● The organization can use this project to find out whether the ID is original or fake. Similarly this can be used for any type of ID like adhar, voter id, etc.<br>


