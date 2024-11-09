# 2.156 Project
2D sketch (+ text) to 3D CAD model

## Convert py2step
### Install
```
git colone https://github.com/Yuki-Kokomi/OpenECADtoSTEP.git
conda create -n 2-156 python=3.7
conda activate 2-156
cd OpenECADtoSTEP
pip install -r requirements.txt
conda install -c conda-forge pythonocc-core=7.5.1
```

### convert
```
cd OpenECADtoSTEP
python py2step.py --src <src directory> -o <output directory>
```
- example
```
python py2step.py --src examples -o output
```