# Georeference of Point Cloud from GeoLiDAR Equipment

 
**Candidate Name:** Darmawan  

## Introduction

In this repository, I present my approach to solving the georeferencing problem for point cloud data captured with GeoLiDAR equipment. The dataset originates from a location in the United States and uses a local reference system. My task involves accurately georeferencing this data into the EPSG:26985 coordinate system. The process is detailed in the following sections.

## Methodology

The georeferencing process involves several key steps, which are outlined in the flowchart below:

![Flowchart_georef](https://github.com/user-attachments/assets/b6f56db8-5a71-44b3-b3f8-1787367327f7)

### Step-by-Step Explanation

1. **Data Import, Checking and Preprocessing:** Import the point cloud data, verify data integrity, and prepare it for transformation.
2. **Transformation to EPSG:26985:** Convert the data from its original reference system to EPSG:26985, ensuring all necessary alignment checks.
3. **Verification and Quality Control:** Cross-check the georeferenced data for accuracy, confirming the transformation's success.
4. **Export of Final Dataset:** Export the georeferenced dataset for further analysis or application.

## Results

The final georeferenced point cloud can be seen in the videos below, illustrating the transformation from the local reference system to EPSG:26985:

- Visualisation with ArcGIS Pro [Video 1](https://www.youtube.com/watch?v=mTUAYxJaoQw)
- Visualisation with Cloud Compare [Video 2](https://www.youtube.com/watch?v=AfLoG1WUx2s)

(Disclaimer: I will delete the videos in 72 hours for safety and privacy reason.)
## Conclusion

Through this project, I have demonstrated the process of transforming and verifying a point cloud dataset from a local reference system to the EPSG:26985 system. This georeferencing allows for standardized integration of the data in broader spatial analyses and applications.

---

**Note:** Replace `path/to/flowchart-image.png` and `path/to/video1.mp4`, `path/to/video2.mp4` with the actual paths to your flowchart image and videos.

