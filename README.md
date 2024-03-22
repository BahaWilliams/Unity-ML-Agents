# Unity-ML-Agents

## Note for Cloning

If you decide to clone this repository, please note that certain files are ignored. These include:

*.svd
*.pdb
*.mdb
*.pyc
*.h
*.pb
*.onnx
*.py
*.pyd
*.cpp
*.hpp
*.lib
*.cmake
*.pyi
*.dll
*.cuh

If you clone it there are couple this you need and since mlagents it's in 2.0.1 this is the most optimal one 
- python 3.9.13
- use a command prompt and go to the clone directory 
- use python -m venv venv or if you cant use the python change to py 
- go to the venv activate by using venv/Scripts/activate
- add the mlagents file with pip install mlagents
- upgrade the the pip by using py -m pip install -upgrade pip
- install the pytorch by using pip3 install torch torchvision torchaudio
- upgrade the protobuf with pip install protobuf==3.20.3
- to check if it already install use mlagents -learn -h or --help
