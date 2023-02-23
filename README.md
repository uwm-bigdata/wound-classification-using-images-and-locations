# Multi-modal-wound-classification-using-images-and-locations

**Info:** AZH dataset is collected over a two-year clinical period at the AZH Wound and Vascular Center in Milwaukee, Wisconsin. The dataset includes 730 wound images in .jpg format. The images are of various sizes, where the width ranging from 320 to 700 pixels and the height ranging from 240 to 525 pixels. These images contain four different wound types: venous, diabetic, pressure, and surgical. iPad Pro (software version 13.4.1) and a Canon SX 620 HS digital camera are used to capture the images, and labeling is done by a wound specialist from the AZH Wound and Vascular Center. For most images in our dataset, each image is taken from a separate patient. But there are a few cases where multiple photos were taken from the same patient at different body sites or various healing stages. For the latter case, the wound shapes are different, so they are considered separate images.

**Processing:**
 1. The wound ROIs are cropped using our developed localizer (https://ieeexplore.ieee.org/abstract/document/9785640).
 2. The corresponding locations are annotated using our developed body map by wound professionals.

_More details can be found in the pre-print version shared here._


# Publication
D.M. Anisuzzaman, Y. Patel, B. Rostami, J. Niezgoda, S. Gopalakrishnan & Z. Yu. Multi-modal wound classification using wound image and location by deep neural network. Sci Rep 12, 20057 (2022). https://doi.org/10.1038/s41598-022-21813-0
