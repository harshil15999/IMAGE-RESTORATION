# IMAGE-RESTORATION
In this project we have used a Gan to increase the resolution of the images.I have learnt about this from the Fast AI course V3 PART 1(VIDEO 7)
https://course.fast.ai/videos/?lesson=7

## APPROACH USED
1.Firstly to create the dataset we have used images of faces and made a function which decreases the picture quality of the images.I have tried making it in such a way that for each picture  quality is differently decreased .
2.I trained the classifier on the high quality faces data
3.Then I trianed the generator and we ping ponged the training from training the classifier and the generator

### Future Work Extension
1.Provided any low quality and high quality images we can use it to enhance other images in the same way.This can be possibly used for medical images where it is not feasible to have expensive hardware but we require high quality images
2.It can also be added as a software component to mobile phone cameras
