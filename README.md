# Breast-Cancer-detection

# Overview

Breast cancer is the second leading cause of cancer-related deaths among women worldwide. Early detection significantly improves treatment outcomes and survival rates. Mammography is a vital screening tool for identifying early signs of breast cancer, such as abnormal masses or calcifications, often before symptoms appear.
Common signs of breast cancer include: Unexplained weight loss, skin changes on the breast, persistent pain, noticeable breast changes.

This project leverages deep learning techniques to detect breast cancer from mammographic images.
Mammograms are specialized X-ray images of the breast, which are widely used by physicians to detect early indicators of cancer. Regular screening can identify breast cancer up to three years before physical symptoms emerge. Additionally, mammograms provide insight into breast density, an important risk factor, as denser breast tissue is associated with a higher likelihood of developing cancer.

# Project Goal

The aim of this project is to develop and evaluate deep learning models capable of accurately analysing mammographic images for tumor malignancy and breast tissue density, aiding early diagnosis and risk assessment.
It will process the medical images and use artificial intelligence to identify potential signs of breast cancer.

# Dataset
The dataset used in this project consists of mammographic images with dimensions (224, 224, 3). Each image is labeled with two key attributes:
#### 1. Breast Density
   
Breast density indicates the amount of fibroglandular tissue in the breast. Categories include:

A: Almost entirely fatty - 10% of women have breasts are mostly fatty tissue

B: Scattered fibroglandular densities - 40% of women have some dense areas, mostly non-dense

C: Heterogeneously dense - 40% of women have mostly dense tissue with some non-dense areas

D: Extremely dense - 10% of women have nearly all breast tissue is dense


#### 2. Tumor Type

Benign - Noncancerous

Malignant – Cancerous


