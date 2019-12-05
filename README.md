# Quick-Draw-Subset

A subset of the famous Google "Quick Draw" dataset ( https://github.com/googlecreativelab/quickdraw-dataset )

The original dataset is very noisy and big, this dataset was created for images similarity algorithms or for evaluation of these.

## The dataset
* classes num: 182
* images num: 18.200 (100 images per class)
* images: 128x128 / RGB

## A non noisy dataset
* the data was downloaded and sorted by similarity with the "Shape Context" algorithm, and then checked manually (yes... manually :sweat:)
* too similar and too noisy classes are filtered and deleted (this is the reason why it contains only 182 classes, and not 345)

## Can a Backpack looks like a dog?
![alt text](https://raw.githubusercontent.com/emizzz/Quick-Draw-Subset/master/readme_images/backpack.png)
![alt text](https://raw.githubusercontent.com/emizzz/Quick-Draw-Subset/master/readme_images/dog.png)

The answer is yes.

This is only one example of noise removed in this subset.

## Download
https://www.kaggle.com/emiliuz/quick-draw-subset
