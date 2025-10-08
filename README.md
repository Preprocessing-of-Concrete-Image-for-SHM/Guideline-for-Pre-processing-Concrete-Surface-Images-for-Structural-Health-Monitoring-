# Guideline-for-Pre-processing-Concrete-Surface-Images-for-Structural-Health-Monitoring-
(Code Repository, Dataset, and Theoretical Overview) 
Mahdi Asgarinejad , Milad Farmahini Farahani, Maryam Bitaraf, Amirmohammad Ramezanianpour

School of Civil Engineering, College of Engineering, University of Tehran, Tehran, Iran 
1. Project Overview 

Structural Health Monitoring (SHM) of concrete structures has become an essential area of research in recent years. Automated image-based damage detection—particularly using computer vision and deep learning—offers significant potential for early and reliable identification of cracks, bug-holes, and other surface defects. A crucial stage in such computer vision pipelines is image pre-processing, which directly affects the accuracy, generalization, and efficiency of subsequent detection models. This repository provides a comprehensive framework for image pre-processing of concrete surface images, including a curated dataset, detailed codes, and illustrative sample results. For theoretical details of the employed methods and algorithms, please refer to the accompanying document “Theoretical Overview”. 

This repository consists of three main components: 
• Dataset (raw references, labeled JSON, optimized samples) 
• Codes (Google Colab notebook + modular Python functions) 
• Image Sample Results (Some outputs of preprocessing techniques)
2. Dataset 
The dataset has been structured to facilitate supervised machine learning (ML) and deep learning (DL) tasks in SHM. It 
supports flexible labeling formats, enabling users to select between: 
1. Cracks only 
2. Bug-holes only 
3. Combined cracks and bug-holes 
The dataset includes the following parts: 
(a) Referenced datasets: Four publicly available concrete surface datasets, sizes ranging from 227×227 to 4032×3024 
pixels, comprising more than 50,000 images. 
(b) Optimized image samples: 1,599 images (256×256) processed with Color Multi-Level Thresholding. 
(c) Annotation file: A JSON file in LabelMe format containing polygons, labels, and references for the 1,599 images.
