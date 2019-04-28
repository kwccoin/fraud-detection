# fraud-detection

A credit card fraud detection project built with the Cortex library.

## Usage

You need to put the dataset into a new directory resources at the root of the defproject

(To download the dataset you need to find under Kaggle fraud detection, the last time retrived in 2019 April 28 is in https://www.kaggle.com/mlg-ulb/creditcardfraud and you can push the "Download" Button (66MB zip) then unzip it (about 160 MB unzipped) )

To run:

1. install java and leiningen,
2. clone the project,
3. Download the dataset above
4. run `lein repl` at the root of the project, and then
5. run `(train)` in the REPL once it loads.
