# LabelImg2YOLO
Convert the voc labels generated from labelImg tool into yolo format for training


**INTRODUCTION**

The script helps in converting the voc label datat generated from the labelImg tools csv to yolo format for training it in darkent yolo

**CONFIGURATION**

The configuration files has the data required to do the convertion process

  file_name = train_labels.csv 'The name of the csv file with the voc data'		
  width = 1024|width	'The column name of the csv which holds the width data or an integer represnting the width of all images'
  height = 1024|height 'The column name of the csv which holds the height data or an integer represnting the height of all images'
  xmin = xmin	'The column name of the csv which holds the xmin data'
  ymin = ymin 'The column name of the csv which holds the ymin data
  xmax = xmax 'The column name of the csv which holds the xmax data
  ymax = ymax 'The column name of the csv which holds the ymax data'
  label = class 'The column name of the csv which holds the label data
  class_name = nine,ten,jack,queen,king,ace 'All the classes that you want to parse for the output each seperated by "," '
  output_csv_name = yolo_output_voc 'The name of the output csv file with the yolo data'
  txt_file_path = ./train/ 'The folder in which the txt files with its image name and values to be stored'
  txt_images_path = ./ 'The folder in which the output csv file to be stored'
  
**GENERATING THE LABELS**

To Generate the labels execute all blocks of the labelimg2yolo_updated.ipynb
