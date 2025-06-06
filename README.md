# Room Cleaning
## Final project for EECS 442: Computer Vision
A cluttered environment can contribute to feelings of stress, anxiety, and lowered mood. 
The ability to quickly visualize a messy room as clean can be helpful for motivating someone to clean it up or motivate them to clean it up. 

For real estate, it’s useful to remove unwanted items from scenes to help convince potential buyers or tenants more easily.


## Approach
1. Train an object detection model on images of messy rooms, identifying messy areas/objects.
2. Based on the parts of the room classified as clutter, create masks of the image.
3. Use inpainting to fill in the masked areas, removing all objects identified as clutter. 
