# Environment Set-up on Windows 10
```bash
# Prepare Conda environment
conda create -n project python=3.6
pip install fbs
pip install PyQt5==5.15.1
pip install qdarkstyle
pip install numpy
pip install pillow
pip install onnxruntime
pip install image4layer
pip install torch

# Get pre-trained weights "SketchColorizationModel.onnx" from https://github.com/rapidrabbit76/SketchColorization/releases
# Save it to "app/src/main/resources/base/SketchColorizationModel.onnx
```