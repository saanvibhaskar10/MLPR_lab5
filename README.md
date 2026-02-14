# MLPR_lab5
Aim: The aim of this lab is to detect faces in images using Haar Cascade classifier and apply K-Means clustering on extracted color features (Hue and Saturation) to group faces based on similarity. The model is then used to classify a template image into one of the learned clusters.

Methodology:
1️. Face Detection
- Used OpenCV Haar Cascade classifier.
- Converted images to grayscale for detection.
- Drew bounding boxes around detected faces.

2. Feature Extraction
- Converted detected face regions to HSV color space.
- Extracted mean Hue and Saturation values.
- Represented each face as a 2D feature vector (Hue, Saturation).

3. K-Means Clustering
- Applied K-Means with 2 clusters.
- Computed cluster centroids.
- Visualized clusters in Hue-Saturation space.

4. Template Image Classification
- Extracted Hue and Saturation of template image.
- Used trained K-Means model to predict its cluster.
- Plotted template point along with clusters and centroids.

Key Findings:
- Hue and Saturation are effective simple color features for grouping similar faces.
- K-Means clustering successfully separated faces into meaningful clusters.
- The template image was correctly assigned to the nearest cluster based on feature similarity.

Conclusion: This lab demonstrates how computer vision techniques and unsupervised learning can be combined for image-based clustering. By extracting color-based features and applying K-Means clustering, we were able to group similar faces and classify a new image effectively.

Outputs:
<img width="940" height="463" alt="image" src="https://github.com/user-attachments/assets/f2b904b7-549f-4709-98f0-272354f4616e" />
<img width="940" height="427" alt="image" src="https://github.com/user-attachments/assets/2160a9cb-d939-4b20-9ba2-31dc905ec0f9" />
<img width="940" height="456" alt="image" src="https://github.com/user-attachments/assets/6de9d0f2-7b31-4813-b6fc-3310e8e5b91c" />
<img width="940" height="423" alt="image" src="https://github.com/user-attachments/assets/b69ca0a2-085c-4e39-9115-53cc54e38724" />
<img width="940" height="641" alt="image" src="https://github.com/user-attachments/assets/889f7fda-4dc3-41a1-8dd1-5d80a94b6dc1" />
<img width="940" height="956" alt="image" src="https://github.com/user-attachments/assets/5861a637-64c4-4f55-ad40-6047959707d4" />







