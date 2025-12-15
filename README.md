# Aerial-Object-Classification-Detection

## Problem Statement
This project aims to develop a deep learning-based solution that can classify aerial images into two categories — Bird or Drone — and optionally perform object detection to locate and label these objects in real-world scenes.
The solution will help in security surveillance, wildlife protection, and airspace safety, where accurate identification between drones and birds is critical. The project involves building a Custom CNN classification model, leveraging transfer learning, and optionally implementing YOLOv8 for real-time object detection.

## Real-Time Business Use Cases
1.	**Wildlife Protection** - Detect birds near wind farms or airports to prevent accidents.
2.	**Security & Defense Surveillance** - Identify drones in restricted airspace for timely alerts.
3.	**Airport Bird-Strike Prevention** - Monitor runway zones for bird activity.
4.	**Environmental Research** - Track bird populations using aerial footage without misclassification.

## Summary of the Project
- This project developed a deep learning solution to classify aerial images as either 'Bird' or 'Drone', with an optional object detection feature. This addresses critical needs in areas like security, wildlife protection, and airspace safety.

- We explored two classification models: a "**Custom CNN**" and a "**ResNet50**" transfer learning model. In this specific training run, the Custom CNN demonstrated superior performance (Best Validation Accuracy: 0.7014, Lowest Validation Loss: 0.6528) due to better generalization and less overfitting compared to ResNet50, which showed signs of significant overfitting despite its high training accuracy. Therefore, the Custom CNN is the preferred deployment model based on these results.

- For object detection, "**YOLOv8**" was integrated to locate and label objects within images accurately. Finally, Streamlit web applications were developed and publicly deployed using Pyngrok to provide interactive user interfaces for both classification and object detection.

- In essence: We've built an AI system that can effectively differentiate between birds and drones, with the Custom CNN model showing robust performance in this iteration, and YOLOv8 adding valuable object localization. Further optimization is planned to harness the potential of transfer learning with ResNet50 fully.
