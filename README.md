Content-based Image Retrieval Considering Colour Difference Histogram of Image Texture and Edge Orientation

This repository contains the MATLAB and C# code developed as part of my research in the Data Mining and Image Processing Laboratory at Shahrood University of Technology. This work was carried out as an extension of my master’s thesis and has also contributed to related research projects at my private company and through my role as a research scientist at the laboratory. I have also advised a thesis in this field at Shahrood Non-Profit University.

The code is associated with our research published in the International Journal of Engineering in 2020. This paper is an extended version of our award-winning conference paper presented at ICSPIS 2019.

Project Overview
Content-based image retrieval (CBIR) is a significant topic in image processing and computer vision, where the goal is to retrieve images from a database that are similar in content to a query image. This project implements a CBIR system that leverages features extracted based on the human visual system, specifically considering texture and edge orientation, which are critical for human image perception.

Key Features of the System
Feature Extraction:

MATLAB scripts are used to extract image features, including the color difference histogram and texture and edge orientation features.
Feature extraction is designed to mimic the human visual system's processing of images.
Feature Selection and Optimization:

Using C# and Visual Studio, the extracted features are refined and optimized.
The Shannon entropy criterion is applied to select the most relevant features and assign appropriate weights to them for enhanced retrieval performance.
User-Friendly Interface:

The image retrieval system is implemented with a highly user-friendly interface, making it easy for users to perform image searches and view results visually.
How to Run the Code
Download and Unzip: First, download the repository as a zip file and unzip it.
Run MATLAB Scripts:
Use the provided MATLAB scripts to extract features from your image dataset.
Run C# Code:
Open the project folder in Visual Studio and run the C# code. The interface will guide you through the process of feature optimization and image retrieval.
View Results: Once the features are processed, you can explore the image retrieval outcomes through the interactive interface.
Abstract of the Paper
Content-based image retrieval is one of the interesting subjects in image processing and machine vision. In the image retrieval systems, the query image is compared with images in the database to retrieve images with similar contents. Image comparison is performed using features extracted from the query and database images. In this paper, the features are extracted based on the human visual system. Since the human visual system considers the texture and edge orientation in images for comparison, the color difference histogram associated with texture and edge orientation in images is extracted as features. The features are selected using the Shannon entropy criterion. The proposed method is tested using the Corel-5K and Corel-10K databases. The precision and recall criteria were used to evaluate the proposed system. The experimental results demonstrate the effectiveness of the proposed system in achieving more accurate image retrieval compared to recent CBIR systems.

Citation
If you use this code for your research, please consider citing our paper:

[AlyanNezhadi, M. M., Qazanfari, H., Ajam, A., & Amiri, Z. (2020). Content-based image retrieval considering color difference histogram of image texture and edge orientation. International Journal of Engineering, 33(5), 949-958.]

Acknowledgments
This work was supported and developed during my time at Shahrood University of Technology and with valuable input from the Image Processing and Data Mining Laboratory.

Contact
For any questions or further collaboration opportunities, feel free to reach out through [hamedmit.gh@gmail.com].
