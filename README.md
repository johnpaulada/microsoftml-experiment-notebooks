# Microsoft ML Experiments
This repo is a collection of Microsoft ML experiment Jupyter notebooks on the Microsoft ML Server. I will continue adding to this repo whenever I create a new experiment notebook.

[![forthebadge](http://forthebadge.com/images/badges/60-percent-of-the-time-works-every-time.svg)](http://forthebadge.com)
[![forthebadge](http://forthebadge.com/images/badges/built-with-science.svg)](http://forthebadge.com)

## Prerequisites
To use this repo, you need to have Microsft Machine Learning Server installed.

If you're too lazy to install all of it, you can use this [Docker image](https://github.com/johnpaulada/microsoftmlserver-docker) to open up a Jupyter notebook instance  with `docker run -p 8888:8888 -v `pwd`:/home/app -it johnpaulada/microsoftml` after doing steps 1 and 2 below.

## Usage
1. Clone this repo by running `git clone https://github.com/johnpaulada/microsoftml-experiment-notebooks.git` on your console.
2. Go into the directory by running `cd microsoftml-experiment-notebooks` on your console.
3. Open up a Jupyter notebook.
4. Import these notebooks.
5. Run them and there you go! You can modify them and try things out! :tada:

## Experiments
1. [Comment Flagging](https://github.com/johnpaulada/microsoftml-experiment-notebooks/tree/master/experiments/comment-flagging) *(Sentiment Analysis)* - This experiment uses the [`get_sentiment`](https://docs.microsoft.com/en-us/machine-learning-server/python-reference/microsoftml/get-sentiment) Microsoft ML function to flag negative comments from a csv file.
2. [BASS Philippine Mobile Connection Recommender](https://github.com/johnpaulada/microsoftml-experiment-notebooks/tree/master/experiments/bass) *(Pandas & Numpy)* - Recommends the fastest mobile connection in the area (Smart, Globe, Sun, etc.). Uses BASS data.

## License
MIT