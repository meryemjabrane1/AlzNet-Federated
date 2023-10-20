# Alzheimer's Disease Detection Using CNNs and Federated Learning
(Python, Pytorch, NUmpy, Flower FL )

Alzheimer's disease is a devastating condition with a significant impact on individuals, families, and society as a whole. In the United States alone, the projected cost of Alzheimer's and other dementias is expected to reach a staggering $1.1 trillion by 2050. Unfortunately, underdiagnosis is a critical issue, especially in regions like Morocco, where there is a shortage of healthcare professionals trained in dementia care and limited access to healthcare services.

In light of these challenges, early detection of Alzheimer's disease is crucial for improving treatment outcomes, enabling better planning and management, enhancing the quality of life for affected individuals, and providing increased opportunities for participation in clinical trials.

This project started as my bachelor's capstone but carries on as personal research. 

# Project Overview:

Our project aims to address the issue of underdiagnosis and improve the early detection of Alzheimer's disease. To achieve this, we have developed an automated classification system utilizing advanced technology. We have implemented a Convolutional Neural Network (CNN) with a specific focus on the DenseNet121 architecture.

The system takes Magnetic Resonance Imaging (MRI) images as input and classifies them into one of four classes:

Non-Demented
Moderate Demented
Mild Demented
Very Mild Demented


# Federated Learning:

Handling sensitive medical data is a paramount concern in our project. Ensuring the privacy and security of patient information is of utmost importance. To address this, we have incorporated Federated Learning into our system.

Federated Learning allows us to train an accurate classification model without compromising patient data. Our approach involves a cross-silo model where three hospitals simulate communication with a central server. This enables the model to be trained on their respective data without the need to send or share sensitive information, thus preserving patient privacy.

By combining advanced machine learning techniques and a privacy-centric approach, our project seeks to make a substantial impact on Alzheimer's disease diagnosis and patient care. We are dedicated to the mission of improving the lives of individuals affected by this devastating disease and contributing to the advancement of medical science.


