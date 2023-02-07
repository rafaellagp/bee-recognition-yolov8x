# Mimic Bee recognition with yolov8x

Mimic bee detection by computer vision model

Mimic bees are a group of stingless insects that have independently evolved to mimic the appearance of bees in order to deter potential predators.

Many groups of stingless insects have independently evolved mimicry of bees to fool would-be predators. To investigate this mimicry, I trained artificial intelligence (AI) algorithms—specifically, computer vision—to classify citizen scientist images of bees, non-bee insects, and bee mimics. The models achieved high accuracy in detecting the classes and were able to learn from the images using the deep learning method of class activation.

The performance metrics of the models were evaluated on a validation dataset of 50 images with 4 classes (all (background), bee, mimicbee, and nonbee). The overall precision was 0.765, recall was 0.791, and the mean average precision (mAP50) was 0.84 with mAP50-95 being 0.605. For the bee class, the precision was 0.742, recall was 0.632, mAP50 was 0.728, and mAP50-95 was 0.448. The mimicbee class had a precision of 0.859, recall of 0.867, mAP50 of 0.904, and mAP50-95 of 0.723. The nonbee class had a precision of 0.693, recall of 0.875, mAP50 of 0.888, and mAP50-95 of 0.645.

The models were trained using Ultralytics YOLOv8, with Python 3.7.12, torch 1.11.0 and CUDA 0 on a Tesla P100-PCIE-16GB GPU. The model had a total of 268 layers and 68126457 parameters with an inference speed of 36.3ms.
