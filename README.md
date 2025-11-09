# Medical-Chatbot
# GEN AI Project of medical chatbot with python language

# Clone the repository

# Step 1
#Create the conda environment (if conda not availabe so first install then execute this command, add path of minoconda and till script in system variable)
# conda create -n medibot pyhton=3.14 -y

# if go error like 
# CondaToSNonInteractiveError: Terms of Service have not been accepted for the following channels. Please accept or remove them before proceeding:
# solution: run
# conda tos accept --override-channels --channel https://repo.anaconda.com/pkgs/main
# conda tos accept --override-channels --channel https://repo.anaconda.com/pkgs/r
# conda tos accept --override-channels --channel https://repo.anaconda.com/pkgs/msys2



# Step 2
# conda activate medibot

# if error : CondaError: Run 'conda init' before 'conda activate'
# "conda init bash" and restart the bash

# Step 3
# This avoids version issues with recent AI libraries.
#python -m pip install --upgrade pip

#install the requirements
#pip install -r requirements.txt