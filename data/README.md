Various data files to be loaded (all in .npy format)

1. data1 to data10 - images containing cars and pedestrians in a random background
2. car_masks - ground truth masks for cars
3. ppl_masks - ground truth masks for people
4. labels - pixels probable to contain cars and/or people in each image (based on IoU values)
5. masks - pixels of interest in each image (based on IoU values) 
6. stars - pixel-wise bounding box coordinates/width/height for car/people in each image
7. iou_ids - pixel-wise label for car/people in each image
