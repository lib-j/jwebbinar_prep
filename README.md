# JWebbinar material

## Branch frozen for Webbinar 7

This Branch is a frozen version for JWebbinar  "NIRSpec MSA". If you want a version of the materials that is being maintained, see the `main` branch of this repository.

To download the material, you can clone this repository and navigate to this folder:  
`git clone https://github.com/spacetelescope/jwebbinar_prep.git ~/my_jwebbinar_prep`  
`cd ~/my_jwebbinar_prep`  
`git checkout webbinar7`  
`cd mos_session`  

Alternatively, you can manually download the individual notebooks by clicking on the mos_session folder, then click on each file, and right-click on "Raw" to select "Save link as".

To run these notebooks locally, you will need a Python environment set up that is capable of running Jupyter notebooks. If you are new to Python, you may want to look here: https://www.python.org/about/gettingstarted/ for some resources on how to install and learn the basics of Python. Depending on your preferences and system choices, you may find the install instructions there sufficient, but note that many scientists find it easier to use the Anaconda python distribution and package manager: https://www.anaconda.com/products/individual.

Once you have python installed, in most cases it will be sufficient to simply execute the following command at a terminal:  
`pip install -r requirements.txt`  
`pip install jupyter`  

Or if you are using anaconda, you first create an environment with the name of your choice (we use `jwebbinar7` for this example):  
`conda create -n jwebbinar7 python=3.8`  
`conda activate jwebbinar7`  
`pip install -r requirements.txt`  
`pip install jupyter`  

You can now run `jupyter notebook` in the folder where you have downloaded the webinar notebooks.

If you have problems or questions, feel free to reach out to the JWST Help Desk at http://jwsthelp.stsci.edu/.
