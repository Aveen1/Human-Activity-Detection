# Human-Activity-Detection
Activity detection of Reading and Texting messages.
Custom Activity Detection on Yolov3
The project is build on Stanford dataset for 40 activities, I've only used 2 classes Reading and Texting message out of it.
First of all download the dataset from here:
http://vision.stanford.edu/Datasets/40actions.html
For annotations you have to convert the .xml annotations to .txt format, for reference use this link:
https://github.com/Aveen1/XmlToTxt
Change the .cfg file according to number of classes and detector.c for backup, change drive link to save the weight files in your drive.
Add names to coco.names, obj.names and change paths in obj.data accordingly.
Add file darknet53.conv.74 in you SFOriginal folder
Zip the folder with data(pictures+txt files),cfg file,weights,obj.data,obj.names etc and upload to drive. Mount the drive with colab to move
the folder.
For further problems you can take reference from this link:
https://colab.research.google.com/drive/1WXpXOlUj5f7xdoPqvYy5V7pYWaJciBrY
Run 2classes.py and weights will save in drive in backup folder.
Test the weights on different test pictures and video.
We can use the same model yolov3 for custom actions or object detection.
