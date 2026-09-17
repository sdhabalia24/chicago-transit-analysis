# cs301final
Saahil Dhabalia,
Emilie Inzinna-Enriquez,
Ruben Carmona

This repository was apart of our Intro to Data Science (CS 301) Final Project. We were tasked with finding a real world urban problem and aggregating data sets to conduct a full data science pipeline. Our full step-by-step and results are in the Google Colab file.

Original datasets were taken from https://data.cityofchicago.org/
Datasets were then modified to work well in the colab environment due to size constraints.
All datasets used in the colab are uploaded to this repository, so you can simply click Run all and everything will work.

### For docker container:
1. Clone repo and enter the docker subdirectory
2. Run ```docker build -t test .```
3. Run ```docker run -it --rm test```
4. Inside docker container, run ```python3 cs301_milestone.py```
5. Output images are in ```./output```

