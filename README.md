# Detecting Political Bias Using Deep Learning
Detecting Political Bias in Speeches and News Articles in the US Using Deep Learning Methods

Notes on Convote scraped dataset:
The ```test_set```, ```development_set```, and ```training_set``` were scraped from the Convote ```data_stage_three``` folder.

The data is stored in CSVs in the format ```text,party``` e.g. ```data,label```.

In the ```raw``` folder is the the raw textual data.
The raw textual data has a lot of commas, so a semicolon ```;``` is used as a delimeter between text and party.

The ```stripped``` folder has the same text stripped of commas, and a comma ```,``` delimeter is used between text and party.


Preprocessing is implemented in ```preprocess.py```. In order to run the script, you need to install the huggingface library:

```pip install transformers```

I had some install problems that were solved by installing Rust, which it should be easy to find instructions for online.
