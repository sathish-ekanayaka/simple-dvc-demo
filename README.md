conda create -n wineq python=3.9 -y

conda activate wineq

created a req.txt file
pip install -r reqirements.txt

Download the Data (wine quality dataset)

git init 

dvc init

dvc add data_given/winequality.csv -: Tracking the data

/*important git commands*/

git add . -:  What ever is present in my current woeking directory is added to the staging area of the git.

git commit -m "first commit" 

&& git add . && git commit -m  "Commiting to GitHub" -: && is used to combine commands

