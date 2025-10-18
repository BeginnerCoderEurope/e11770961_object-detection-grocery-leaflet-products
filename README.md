e11770961_object-detection-of-products-in-grocery-leaflets

# Project description

Grocery leaflets contain a diverse mix of visual and textual elements, which are often connected in a semi-structured way. This can be observed in the different placements of product prices and their corresponding descriptions.

For the Applied Deep Learning project I intend to retrieve matching product informations from each product per grocery leaflet page by using an object-detection model. The model should create a bounding box around the related product prices and names. For this I will <strong>bring my own data</strong> and fine-tuning an existing object-detection model. 

# Dataset description 

The dataset will use at least 10 austrian grocery leaflets collected from Hofer, Billa, Penny and Spar. An annotation guideline will be created for consistency purposes. This will take into account the creation of bounding boxes (inclusions and/or exclusions of items) and image formats for the specific object-detection model that will used.  


# Work Breakdown Structure
| Task ID | Task Description                | Estimated Time |
| ------- | ------------------------------- | -------------- |
| 1       | Dataset Collection              | 20h            |
| 2       | Designing and Building Network  | 15h            |
| 3       | Training and Finetuning Network | 10h            |
| 4       | Building an Application         | 6h             |
| 5       | Writing Final Report            | 3h             |
| 6       | Preparing Presentation          | 3h             |
| 7       | Total Estimated Time            | ~57h           |


# Relevant papers 
[YOLOV11: AN OVERVIEW OF THE KEY ARCHITECTURAL
ENHANCEMENTS](papers/2410.17725v1.pdf)

[FINE-TUNING WITHOUT FORGETTING: ADAPTATION OF
YOLOV8 PRESERVES COCO PERFORMANCE](papers/2505.01016v1.pdf)

[Metrics reloaded: recommendations for 
image analysis validation](papers/s41592-023-02151-z.pdf)

[Deep Learning based Visually Rich Document Content Understanding: A Survey](papers/2408.01287v1.pdf)