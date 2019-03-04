Removing noise from a wave using ADALINE. There are two files:
1) ADALINE - Reproducing original sound: Noise was added to an audio file. The original audio was reproduced after applying an ADALINE Network to remove the noise.
2) ADALINE - Noise pass filter: Noise was added to randomly generated sine wave and then removed using ADALINE.

NOTE:

1) The code has been written in Python3 on Jupyter Notebook (ipynb files).
 
If you do not have Jupyter Notebook in your system, please install it according the instructions given at:
https://www.digitalocean.com/community/tutorials/how-to-set-up-a-jupyter-notebook-to-run-ipython-on-ubuntu-16-04

2) Check if your system has git installed using:
	git --version

If not, install using:
	sudo apt update
	sudo apt install git

3) Install the required packages using the following(depending on the version of Python installed on your system). Start Jupyter Notebook after the successful installation of packages:
	
	pip install -r requirements.txt 

			or

	pip3 install -r requirements.txt

4) The input speech file(OSR_us_000_0030_8k.wav) has been included in the folder.

