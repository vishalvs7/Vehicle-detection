# Vehicle-detection project using python



### Overview :To detect and localize vehicles in images or videos is the goal of this project.


### 📁 Dataset Used :  https://public.roboflow.ai/object-detection/undefined
**The dataset consists of 5 classes:**
- Bus
- Truck
- Car
- Traffic signal
- Truck
  # Workflow:
  ## Data Preparation:
  * Create a bounding boxes with the help of label-img And makesense.ai website according to YoloV5.
  * Prepare folder structure that can be accept by YoloV5.

## Steps to use Yolov5:
* Cloning the YoloV5 file from official repository.
* Changing the directory of yolov5
* Installing the dependencies
* Download all versions pre-trained weights.

 ## Steps Before Training Custom Dataset:
* Go to yolov5/data/.
* Open data.yaml
* Edit the following inside it:

 1. Training and Validation file path
 2. Number of classes and Class names.

  ## Training YOLOV5 Model
* Set images size 640 with batch of 8.
* Total 633 images for training and 165 images for validation present in 5 classes.
* Train model around 600 epochs .Stopping training early as no improvement observed in last 100 epochs. Best results observed at epoch 201, best model saved as best.pt.
* Visualise the training metrics with the help of tensorboard.









