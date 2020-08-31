# BigDataProject
This project is about generating the raw data and cleaning the data and finally analyzing it. Also creating ETL jobs to process the data.
https://confusedcoders.com/data-engineering/how-to-become-a-big-data-engineer


# Generating raw data by cloning the repo and finally executing the python script which generates huge data.
https://confusedcoders.com/general-programming/aws/how-to-generate-synthetic-log-data-for-data-analysis

vim ~/.bash_profile
source ~/.bash_profile
vim ~/.bashrc
source ~/.bashrc
conda create -n myenv python=2.7
source activate myenv
pip install -r requirements.txt
python apache-fake-log-gen.py -n 20 -o GZ
