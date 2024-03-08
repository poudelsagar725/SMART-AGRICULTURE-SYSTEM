HOW TO RUN .

Before the following steps make sure you have git, Anaconda or miniconda installed on your system
Clone the complete project with git clone https://github.com/Gladiator07/Harvestify.git or you can just download the code and unzip it
Note: The master branch doesn't have the updated code used for deployment, to download the updated code used for deployment you can use the following command
❯ git clone -b deploy https://github.com/Gladiator07/Harvestify.git 
deploy branch has only the code required for deploying the app (rest of the code that was used for training the models, data preparation can be accessed on master branch)
It is highly recommended to clone the deploy branch for running the project locally (the further steps apply only if you have the deploy branch cloned)
Once the project is cloned, open anaconda prompt in the directory where the project was cloned and paste the following block
conda create -n harvestify python=3.6.12
conda activate harvestify
pip install -r requirements.txt
And finally run the project with
python app.py
Open the localhost url provided after running app.py and now you can use the project locally in your web browser.
