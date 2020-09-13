Follow these instructions in the bash console:

git clone https://github.com/aradaha/dsc-data-science-env-setup-v2-1-onl01-dtsc-ft-012120

cd dsc-data-science-env-setup-v2-1-onl01-dtsc-ft-012120/

conda update -n base -c defaults conda

conda env create -f windows.yml

## If there's an error, run:
## conda remove --name learn-env --all
## then edit the windows.yml and try again

touch ~/.bash_profile

echo "source activate learn-env" >> ~/.bash_profile

source ~/.bash_profile

git config user.name "aradaha"

git config --global user.email reubenhough@gmail.com