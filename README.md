# Advanced Object Tracking: Rock Climber Detection Using SAM2
This repository showcases my project using Facebook's Segment Anything Model 2 (SAM2) to track a rock climber in video footage. SAM2 is a cutting edge model for segmenting objects in both video and image data. In this project, I explored its capabilities by creating spatio-temporal masks, or ‘masklets,’ to highlight the climber's movements as he rappels down a crag.

## Project Overview
- **Model Used:** Facebook’s Segment Anything Model 2 (SAM2)
- **Objective:** Track the movement of a rock climber in a video using zero-shot capabilities.
- **Techniques:** Created and refined spatio-temporal masks, then propagated these masklets across video frames for effective object tracking.

## Features
- **Input Points and Bounding Boxes:** Used to initialize the spatio-temporal masks around the climber.
- **Masklet Refinement:** Fine-tuned the masklets to accurately track the climber across video frames.
- **Zero-Shot Video Tracking:** Demonstrated the model's ability to perform effective object tracking without prior training on specific video data.

## Running the code
Run this Jupyter notebook: ./code/object_tracking_rock_climber.ipynb
  
## Results
The model performed impressively, accurately tracking the climber's movements throughout the video, even in challenging scenarios such as when other climbers came into view.



https://github.com/user-attachments/assets/f43bbe92-31cd-4b63-b9d9-9a5f2bf7b21c



## Skills
Computer vision, Machine learning, Python programming, Data processing
