# Support Vector Machine and Scikit-learn 🤖 🦾

Welcome, this repository contains an introduction to SVM and its application using Scikit-learn. 

**See video [here](https://pitt.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=5f994000-d1d1-49bf-bec2-ac810157b3b6)**.  


## What do you can find in this tutorial?
- What problem does SVM methods help to solve?
- Origins
- Intuition
- Important Concepts
- What are some of the research applications in social science for SVM? 
- How do you use the tool? Scikit-Learn application, and some decision when using it
- Where can you go to learn more about the tool?

## What do you can find in the zipped file?
* Jupyter notebook with links to download the data and more information. 
* Jupyter notebook downloaded as HTML for visualization. 
* Slides used in the tutorial
* Figures incorporated in the notebook
* Empirical data used in the Scikit-learn application

## Summary of what you can find in the video and files

### What is SVM?

SVM is a type of supervised learning algorithm. Its goal is to incorporate a label or set of labels into a target; that is, we classify objects. In short, what we do with the algorithm is to learn from the data and fit a model that should perform well on new observations.

We want to build/learn a *model* that links new data into the pair features $\rightarrow$ Y (survived) $\rightarrow$ (X,y)
  + $y$ label survived/did not survive $\rightarrow y_{i} \in \{0,1\}$ this is a binary label
  + $X$ vector of features
  
Then we will:
1. **Fit** a model
2. **Predict**  $\hat{y}$
3. **Evaluate** how well $(y, \hat{y})$ works. 

See the tutorial for more detail. 

### Scikit-learn tool
Python provides us some tools to fit models using an SVM classifier. For that you need some libraries, and to follow some steps. 

In this tutorial, I am presenting two examples to see the Scikit-learn application.

Examples: 
1. Health: we want to classify cancer cells into benign or malignant types. For that, we need 2 arrays:
  - an array X of shape (n_samples, n_features) holding the training samples- _size, shape, etc_,
  - an array y of class labels (strings or integers), of shape (n_samples) _benign and malignant_
2. Sentiment Analysis using Tweet: we want to classify tweets into three types of sentiments: positive, neutral, or negative. 

After we prepare the data, define the arrays, import the libraries we **fit** the model, and then evaluate. For the evaluation, we split the sample into training and test, and we then compare the prediction with the label data. We look at the accuracy to evaluate the fitted model. 

### Where can I learn more?
If you want to learn SVM I recommend some books, GitHub links, and interactive courses. 

I hope you find this tutorial useful!

Thank you!
