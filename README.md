# Wound classification using images and locations

**Dataset information:** AZH dataset is collected over a two-year clinical period at the AZH Wound and Vascular Center in Milwaukee, Wisconsin. The dataset includes 730 wound images in .jpg format. The images are of various sizes, where the width ranging from 320 to 700 pixels and the height ranging from 240 to 525 pixels. These images contain four different wound types: venous, diabetic, pressure, and surgical. iPad Pro (software version 13.4.1) and a Canon SX 620 HS digital camera are used to capture the images, and labeling is done by a wound specialist from the AZH Wound and Vascular Center. For most images in our dataset, each image is taken from a separate patient. But there are a few cases where multiple photos were taken from the same patient at different body sites or various healing stages. For the latter case, the wound shapes are different, so they are considered separate images.

**Pre-Processing:**
 1. The wound ROIs are cropped using our developed localizer (https://ieeexplore.ieee.org/abstract/document/9785640).
 2. Wound professionals annotate the corresponding ROI locations with detailed location information using our custom body map.

_Please read the following articles for more details._

# Publication
1. Patel, Y., Shah, T., Mrinal Kanti Dhar, Zhang, T., Niezgoda, J., Gopalakrishnan, S., & Yu, Z. (2024). Integrated image and location analysis for wound classification: a deep learning approach. Scientific Reports, 14(1). https://doi.org/10.1038/s41598-024-56626-w
2. Anisuzzaman, D. M., Patel, Y., Rostami, B., Niezgoda, J., Gopalakrishnan, S., & Yu, Z. (2022). Multi-modal wound classification using wound image and location by deep neural network. Scientific Reports, 12(1). https://doi.org/10.1038/s41598-022-21813-0
