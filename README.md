# Human-Activity-Detection
Activity detection of Reading and Texting messages.

Custom Activity Detection on Yolov3

The project is build on Stanford dataset for 40 activities, 
I've only used 2 classes Reading and Texting message out of it.

1. First of all download the dataset from here:
   http://vision.stanford.edu/Datasets/40actions.html
2. For annotations you have to convert the .xml annotations to .txt format, for reference use this link:
   https://github.com/Aveen1/XmlToTxt
3. Change the .cfg file according to number of classes and detector.c for backup, 
   change drive link to save the weight files in your drive.
4. Add names to coco.names, obj.names and change paths in obj.data accordingly.
5. Add file darknet53.conv.74 in you SFOriginal folder
6. Zip the folder with data(pictures+txt files),cfg file,weights,obj.data,obj.names etc and upload to drive. 
   Mount the drive with colab to move in zipped folder to darknet
7. Run 2classes.py and weights will save in drive in backup folder.
8. Test the weights on different test pictures and video.


For further problems you can take reference from this link:
https://colab.research.google.com/drive/1WXpXOlUj5f7xdoPqvYy5V7pYWaJciBrY

We can use the same model yolov3 for custom action detection or object detection.:woman_technologist:

![GitHub Logo](/5.png)

![GitHub Logo](/21.png)

![GitHub Logo](/12.png)
