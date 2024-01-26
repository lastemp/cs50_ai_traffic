# cs50_ai_traffic

This is an AI program that identifies which traffic sign appears in a photograph.
It forms part of the projects for the course [CS50’s Introduction to Artificial Intelligence with Python](https://cs50.harvard.edu/ai/2024/).

The program has below listed dependencies:
- [opencv-python](https://pypi.org/project/opencv-python/) It is used for image processing.
- [Scikit-learn](https://scikit-learn.org/stable/) It is an open source machine learning library that supports supervised and unsupervised learning.
- [tensorflow](https://www.tensorflow.org/) It is an end-to-end open source platform for machine learning.

## Usage

All the following commands assume that your current working directory is _this_ directory. I.e.:

```console
$ pwd
.../cs50_ai_traffic
```

1. Install the required Python packages (opencv-python, Scikit-learn and tensorflow) for the project:

   ```sh
   pip3 install -r requirements.txt
   ```
   
1. Run the application:

   ```sh
   py traffic.py gtsrb
   ```