# Outlier-Detection-and-Removal-from-Multimedia
Detection and removal of specific types of outliers present in different data formats, including contextual outliers from textual data using LOF, outliers from tabular numeric data using LOF, Gaussian noise from image data using NLM, and Gaussian noisy image frames from video data using autoencoder. 

## Procedure
### Textual Data
Synthetic textual data is generated based on a prompt and contaminated with 40% outliers (non-contextual data). LOF is used to detect and remove outlier sentences in the anomalous synthetic data.
- [Contextual_Textual_Outlier_Detection.ipynb](Contextual_Textual_Outlier_Detection.ipynb)
![WhatsApp Image 2024-08-10 at 8 35 01 AM](https://github.com/user-attachments/assets/cd1ef5db-9cde-45ea-98ac-56082189b133)
  

### Numeric Tabular Data
Synthetic data is generated - scaled and unscaled, scored in the data frame and contaminated with 40% outliers. LOF is used to detect and remove outlier sentences in the anomalous synthetic data.
- [Outliers_in_Numeric_Tabular_Data.ipynb](Outliers_in_Numeric_Tabular_Data.ipynb)
![WhatsApp Image 2024-08-10 at 8 35 01 AM (1)](https://github.com/user-attachments/assets/04bd6465-fb5d-4a24-b8a4-bd79212bef62)
