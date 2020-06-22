# Machine-Learning-Model-Deployment-By-Web-Flask-API





![](https://lh3.googleusercontent.com/-GKP4RON282Y/XvBY8nNVFnI/AAAAAAAAoss/BPEOQL4XagsCInXSZtBdXfkvb9U5Wh0mgCK8BGAsYHg/s0/2020-06-22.png)

### How tocd to the directory where requirements.txt is located.
1. activate your virtualenv.
2. Open Cmd/Shell/Terminal.
3. Go your downloaded File Directory where `requirements.txt` is located.
4. Type this Command **pip install -r requirements.txt** in your shell/CMD/Terminal. Run the model







# Data Sources:
### The Street View House Numbers (SVHN) Dataset

SVHN is a real-world image dataset for developing machine learning and object recognition algorithms with minimal requirement on data preprocessing and formatting. It can be seen as similar in flavor to MNIST (e.g., the images are of small cropped digits), but incorporates an order of magnitude more labeled data (over 600,000 digit images) and comes from a significantly harder, unsolved, real world problem (recognizing digits and numbers in natural scene images). SVHN is obtained from house numbers in Google Street View images.

### Overview

* 10 classes, 1 for each digit. Digit '1' has label 1, '9' has label 9 and '0' has label 10.
* 73257 digits for training, 26032 digits for testing, and 531131 additional, somewhat less difficult samples, to use as extra training data
* Comes in two formats:
    1. Original images with character level bounding boxes.
    2. MNIST-like 32-by-32 images centered around a single character (many of the images do contain some distractors at the sides).
###  Download This Data From
![](http://ufldl.stanford.edu/housenumbers/examples_new.png)
<li><b>Format 1:</b> Full Numbers:  <a href="train.tar.gz">train.tar.gz</a>,  <a href="test.tar.gz">test.tar.gz</a> ,  <a href="extra.tar.gz">extra.tar.gz</a>  <b>(Note: for non-commercial use only)</b> </li>

![](http://ufldl.stanford.edu/housenumbers/32x32eg.png)
<li><b>Format 2:</b> Cropped Digits:  <a href="train_32x32.mat">train_32x32.mat</a>,  <a href="test_32x32.mat">test_32x32.mat</a> ,  <a href="extra_32x32.mat">extra_32x32.mat</a>  <b>(Note: for non-commercial use only)</b> </li>

### Reference

1. [The Street View House Numbers (SVHN) Dataset](http://ufldl.stanford.edu/housenumbers/)
2. [Data](http://ufldl.stanford.edu/housenumbers/extra_32x32.mat)
