# Data-606-Capstone-Project: Malware Detection using Machine Learning

A detailed description of my project can be viewed <a href="https://sites.google.com/umbc.edu/data606/spring-21-section-2/nikhil-goparapu?authuser=0">here</a>. <br>

<h3>Brief Description:</h3>
    The Malware industry is growing very rapidly day by day. Many organizations around the world are investing heavily in technologies and methods to build a system to detect and deactivate these malware files. Engineers and anti malware communities should build more robust softwares to detect and deactivate these attacks.<br>
<br>   
The goal of this project to extract useful features from raw bytes file and asm file and build a supervised machine learning model on top of those features to classify a malware file.<br>


<h3>Dataset:</h3>
The dataset is available to download from this <a href="https://www.kaggle.com/c/malware-classification/data">link</a>. Microsoft has open-sourced the dataset as a part of a competition on Kaggle. It can be used for educational and research purposes. <br>

* The dataset consists of 10,868 bytes file in a hexadecimal representation and 10,868 asm files.<br>
* The files in the dataset represent a mix of 9 different families of malware.<br>
* A file may belong to any of the following 9 classes of malware: Ramnit, Lollipop, Kelihos_ver3, Vundo, Simda, Tracur, Kelihos_ver1, Obfuscator.ACY, Gatak.<br>

<h3>Code Files</h3>
In total there are 8 jupyter notebooks.<br>

<h4>Data Preprocessing and Exploratory Data Analysis:</h4>
* <b>Malware Detection.ipynb :</b> This notebook primarily consists of dataset preperation and Exploratory Data Analysis. I have used this notebook to combine all the intermediate datasets which are extracted during feature engineering.
