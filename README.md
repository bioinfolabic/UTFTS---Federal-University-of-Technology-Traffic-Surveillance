# UTFTS - Federal University of Technology Traffic Surveillance Dataset

## Fully-labeled image dataset to anomaly detection

This dataset was created specifically for anomaly detection in videos. We provide annotated video clips and still frames taken in a busy highway. Anomaly in this context, can be described as any of the present classes that are: **cars, trucks, buses, motorcycles, people and vans**. There are two datasets, **UTFTS1** and **UTFTS2**, with videos taken at different positions, transversally and longitudinally to the lane. Videos were collected at 25 fps (frames per second) with resolution 1920 x 1080 pixels. There are 61 video clips in total, comprising, 15664 frames.

## Specifications Table

![Specification Table](SpecificationTable.png)

## Value of the data

* There are very few video datasets especially devised for anomaly detection. These two datasets includes images taken in a highway where trucks are not allowed at certain hours of the day. Such events are considered anomalies. However, as all classes are fully-labeled, for academic purposes, any of the classes can be treated as anomaly.

* Data is provided mainly for training One-Class classifiers for anomaly detection, in video frames. But, due to the labeling this data can also be used for counting vehicles. This dataset includes videos and still images (frames) so that data can be analyzed  in different ways.

* Differently from other video/image datasets, we put available both the clips, the discretized frames, and a text file with the ground truth (indicating anomalies or normal frames)

## Data

Data were collected in a highway in a clear day, the initial objective was to detect large vehicles (trucks), since they are not allowed to run during certain hours of the day. Videos were collected with the camera in two positions, such that the highway lane was filmed transversally (UTFTS1) and longitudinally (UTFTS2). For the first case, the camera was positioned at the floor level. For the latter, the camera was positioned above the floor level in an elevated level. UTFTS2 has three different scenarios: (i) vehicles coming towards the camera, (ii) vehicles leaving away the camera with and without obstacles to the camera.

Videos were collected at 25 fps (frames per second) with resolution 1920 x 1080 pixels. All frames extracted from videos have the same resolution. The table below summarizes the videos and still frames.
