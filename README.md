# YOLO

YOLO — You Only Look Once, is a state-of-the-art, real-time object detection system. 

YOLO can do object detection + object classification + multiple object detection all at the same time. Assuming each information in our ID card is an object, we used YOLO to identify the bounding boxes for this information.

We use Yolo v3 in this project.

## LabelImg

Download and Install LabelImg which uses for annotation cards.
I put a demo dataset of images and annotation in the project.
```bash
mydata/images
```

*Pay attention I covered the name because of privacy*

*Please download ever files which have ?.download at the end and replace with that file*

I create classes.txt for the following:

```bash
card_name
card_nic
card_vin
card_number
```


*this project run on Ubuntu 20*
