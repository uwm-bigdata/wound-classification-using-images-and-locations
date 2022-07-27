# Multi-modal-wound-classification-using-images-and-locations

**Info:** AZH dataset is collected over a two-year clinical period at the AZH Wound and Vascular Center in Milwaukee, Wisconsin. The dataset includes 730 wound images in .jpg format. The images are of various sizes, where the width ranging from 320 to 700 pixels and the height ranging from 240 to 525 pixels. These images contain four different wound types: venous, diabetic, pressure, and surgical. iPad Pro (software version 13.4.1) and a Canon SX 620 HS digital camera are used to capture the images, and labeling is done by a wound specialist from the AZH Wound and Vascular Center. For most images in our dataset, each image is taken from a separate patient. But there are a few cases where multiple photos were taken from the same patient at different body sites or various healing stages. For the latter case, the wound shapes are different, so they are considered separate images.

**Processing:**
 1. The wound ROIs are cropped using our developed localizer (https://ieeexplore.ieee.org/abstract/document/9785640).
 2. The corresponding locations are annotated using our developed body map by wound professionals.

_More details can be found in the pre-print version shared here._


# Publication
Anisuzzaman, D. M., Yash Patel, Behrouz Rostami, Jeffrey Niezgoda, Sandeep Gopalakrishnan, and Zeyun Yu. "Multi-modal Wound Classification using Wound Image and Location by Deep Neural Network." arXiv preprint arXiv:2109.06969 (2021).
