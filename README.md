# ShopeeCodeLeague_Product_Detection
https://www.kaggle.com/competitions/shopee-product-detection-open

Background
At Shopee, we always strive to ensure the correct listing and categorization of products. For example due to the recent pandemic situation, face masks become extremely popular for both buyers and sellers, everyday we need to categorize and update a huge number of masks items. A robust product detection system will significantly improve the listing and categorization efficiency. But in the industrial field the data is always much more complicated and there exists mis-labelled images, complex background images and low resolution images, etc. The noisy and imbalanced data and multiple categories make this problem still challenging in the modern computer vision field.

Note: This page is for participants from open group!

# Evaluation
https://www.kaggle.com/competitions/shopee-product-detection-open/overview/evaluation

# Code Structure

1. Import base library
2. Check and using TPU v3.8 from Kaggle Kernel
3. Data access and configuration
4. Read train and test csv data
5. Show train img function
6. Show test img function
7. Pick random train 
8. List category (from 00 to 41)
9. Add train 
10. Add label
11. Convert array train path
12. Split data to train and test
13. Add test path
14. Decode image function 256x256
15. Augment data
16. Processing train dataset and valid and 
17. Import other library https://github.com/qubvel/efficientnet
18. Processing 
19. Train data with model
20. Visualize loss and val loss data
21. Procssing predict result
22. Add label for test data