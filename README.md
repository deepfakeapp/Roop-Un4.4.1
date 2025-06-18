## DOWNLOAD 

# Roop-Un4.4.1 - This project has been discontinued

The Original Count Floyd Addition to ROOP saved for posterity

### Features

- Platform-independant Browser GUI
- Selection of multiple input/output faces in one go
- Many different swapping modes, first detected, face selections, by gender
- Batch processing of images/videos
- Masking of face occluders using text prompts or automatically
- Optional Face Upscaler/Restoration using different enhancers
- Preview swapping from different video frames
- Live Fake Cam using your webcam
- Extras Tab for cutting videos etc.
- Settings - storing configuration for next session
- Theme Support

and lots more...


## Disclaimer

This project is for technical and academic use only.
Users of this software are expected to use this software responsibly while abiding the local law. If a face of a real person is being used, users are suggested to get consent from the concerned person and clearly mention that it is a deepfake when posting content online. Developers of this software will not be responsible for actions of end-users.
**Please do not apply it to illegal and unethical scenarios.**

In the event of violation of the legal and ethical requirements of the user's country or region, this code repository is exempt from liability

### Installation
Google Colab by
1. download Roop-Un4.4.1.iypnb

Local Machine ( 50 series )
0. git clone https://github.com/ravindergandhi/Roop-Un4.4.1
1. cd Roop-Un4.4.1
2. python -m venv venv && call venv/scripts/activate

pip install uv

uv pip install torch torchvision --index-url https://download.pytorch.org/whl/cu128

uv pip install numpy

uv pip install opencv-python-headless

uv pip install onnx

uv pip install insightface

uv pip install albucore

uv pip install psutil

uv pip install onnxruntime

uv pip install onnxruntime-silicon

uv pip install onnxruntime-gpu

uv pip install tqdm

uv pip install ftfy

uv pip install regex

uv pip install pyvirtualcam

pip install --force-reinstall pydantic==2.10.6

pip install --upgrade gradio==5.13.0


Local Machine (30 / 40 Series )

0. git clone https://github.com/ravindergandhi/Roop-Un4.4.1
1. cd Roop-Un4.4.1
2. python -m venv venv && call venv/scripts/activate
3. (FOR NVIDIA) conda install -c nvidia cudatoolkit=11.8 -y
3. (FOR AMD) pip install onnxruntime-directml
4. pip install -r requirementspip install 
onnxruntime-directml.txt

5. pip install --upgrade gradio --force
6. pip install --upgrade fastapi pydantic
7. pip install "numpy<2.0" 
8. python run.py

NOTE: This installation assumes a proper installation of your system. Including python, miniconda, git, ffmpeg, VSBuildTools2019

 *A free system checker can be found here*: https://www.patreon.com/posts/automated-system-117200313

*An AI System Setup Script can be acquired here*: https://www.patreon.com/posts/117210030


### Usage

- Windows: Activate the virtual environment and run python run.py


  

