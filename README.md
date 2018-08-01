# labelImg


When trainning a CNN, labeling images is a tiring work. 
So why not use a CNN to finish the most of work for you and you just need to check the result and correct it if the labeling result is wrong. 
And this project just do things like this.  
The project is used to labeling the color of traffic lights.
The project is modified based on the `labelImg <https://github.com/tzutalin/labelImg>` and 
the excellent work if identify traffic light color which is done by `Francisco Gorina <https://github.com/fgorina>` as well as all other group members of Udacity CarND Term3.

To make program work:
1. you need install all packages as original `labelImg <https://github.com/tzutalin/labelImg>` required. 
2. Besides tensor_flow also is required as well as other package required by 'label_files.py'

To check the label result:
1. first make sure the CSV file name is 'images_label.csv' and put it in the same dirctory with all images. 
2. Then select the images location by 'Open Dir' button on the left tool bar. 
3. Next select file saving location by 'Change Save Dir' button on the left tool bar, 
and this will specify the location to store VOC file which is generated when checking the CSV file.
4. Remember to check 'Auto Saving' under 'View' menu, 
5. then click 'Check Label' under 'AutoLabel' menu to start checking labels. 
6. After that continue click 'Next Image' button on the left tool bar to check all the images.

To covert the VOC file to CSV file:
1. select the images dir by 'Open Dir' button on the left tool bar which contain all images, 
2. select file saving dir by 'Change Save Dir' button on the left tool bar which contain all VOC files, 
3. then click 'Convert Label' under 'AutoLabel' menu to start convert labels. 
4. After that continue clicking 'Next Image' button on the left tool bar to convert all the images.

To auto label the images:
1. select the images dir by 'Open Dir' button on the left tool bar, 
2. select file saving dir by 'Change Save Dir' button on the left tool bar, 
3. check 'Auto Saving' under 'View' menu, 
4. then click 'Auto Label' under 'AutoLabel' menu to start auto labeling, 
selecting network dir 'faster_rcnn_inception_resnet_v2_atrous_coco_2018_01_28' where you put your CNN net. 
5. After that click 'Next Image' button on the left tool bar to label all the images.

note:
1. when you check CSV file and find a wrong label, you can modify it, 
when you move to next image, you modification will save automatically, 
but in VOC format, so, if your need CSV format, you need to covert the VOC file to CSV file. 

