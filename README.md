## webcam-segmentation-using-maskrcnn
Segmenting using MaskRCNN by matterport on the live webcam feed.

**INSTRUCTIONS**

*INSTALLING CHOCOLATEY **(FOR WINDOWS ONLY)***

Run the following command in powershell as administrator: `Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))`.
Then run `choco install make`

*Library versions:*
On parent directory run the following: 
`pip install keras==2.1.3 &&
pip install tensorflow==1.15.0 &&
pip install tensorflow-gpu==1.15.0 &&
pip install scipy==1.2.2 &&
pip install Cython &&
pip install -U setuptools &&
pip install -U wheel &&
make install -C coco/PythonAPI`


**TO RUN THE APP**
1. cd into the Mask_RCNN folder
2. run `python -W ignore init.py`
