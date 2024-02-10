# Pattern Recognition and Machine Learning
Image Recognition includes 3 phases; feature extraction, data exploration and model selection, and performance estimation.

- Rice is a popular ingredient all around the world. It's nutritious and it can be harvested in many places. To have high-quality rice on the table, it needs to go through some phases. Some unwanted things should be removed from it. So, we need classification for these phases. In this task, we are trying to come up with the best model and hyperparameters for classification.
  
- Based on the article[1], the data was gathered by taking pictures of different species of rice in a laboratory. The camera had the power of 2.2 megapixels and 2048 × 1088 resolution. However, the pictures are not directly used. Using some image processing techniques, the contour of each rice and the geometric features of the kinds of rice are extracted and saved in a chart for any analytic use.

- For the image processing phase, the contours of the pictures were extracted by OpeCV. After that, some features like roundness and skew were calculated using the RGB numbers of the pixels inside the contour.

- For classification, KNN, Random Forest, and MLP models were trained and tested. To evaluate these methods facing unseen data, the cross-validation method was used.

All models were evaluated and after getting the best hyperparameters were tested again. The results are: KNN: 98% accuracy, Random forest: 96% accuracy, MLP: 91% accuracy.

[1]: Cinar, Ilkay, and Murat Koklu. "Identification of rice varieties using machine learning algorithms." Journal of Agricultural Sciences (2022): 9-9.
