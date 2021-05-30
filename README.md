# Instruction Of Running The Code

*File using:
	5329assn2.ipynb
	train.csv
	test.csv
	kaggle.json (details in STEP 2)

## STEP 1 : Mount Google Drive
* If using Colab, plese amount Google Drive in the First cell of 5329assn2.ipynb.

## STEP 2 : Load Data and CSV

* To use Colab, run the 2-nd and 3-rd cells. In the 3-rd cell, upload your Kaggle account's kaggle.json file (Kaggle's token file, obtain from Kaggle->Account->API->"Create New Token API"). And in the 4-th cell (with "Please upload fixed train.csv and test.csv"), upload the fixed 'train.csv', 'test.csv'. All this fill need be put under PATH : '/content/' (the default directory of Colab)

* To use other softwares, change the file path in **download data from kaggle server with token file** section. Change the data_root_dir to the PATH that contains dataset images. And upload fixed 'trina.csv', 'test.csv' files to the running dirctory of this Notebook. (use 'pwd' command in a new cell to check in Notebook).

## For following steps (STEP 3 to STEP 10), to be simplify: You can directly run all cells after 4-th cell, until the last cell of the 5329assn2.ipynb

## STEP 3 : Create colums for each class
* run cell in **create colums for each class**

## STEP 4 : Class distribution observation
* run cell in **Class distribution observation**

## STEP 4 : Class distribution observation
* run cell in **Class distribution observation**

## STEP 5 : ImageDataset class definition
* run cell in **ImageDataset class definition**

## STEP 6 : TestDataset class definition
* run cell in **TestDataset class definition**

## STEP 7 : Using ASL
* run cell in **Using ASL**

## STEP 8 : Define resenet_50 class
* run cell in **Define resenet_50 class**

## STEP 9 : Train model and predict test
* run cell in **Train and predict**

## STEP 10 : Save and download model
* run cell in **Save and download model**
* You can check the model's size by take a look at the output file "my_model_save1.pth"

