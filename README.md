
 
## Inference
Download pretrained models (BP4D dataset) from the following links:

Pre-trained model [fold1](https://drive.google.com/file/d/1Wk9e78TVXMF0aQ4b4c0SovIJoJOMgHL5/view?usp=sharing)

Pre-trained model [fold2](https://drive.google.com/file/d/1-uwkTp0WS-C-yRFBrm9sPl9WROAWaGUv/view?usp=sharing)

Pre-trained model [fold3](https://drive.google.com/file/d/1p7hlZ3sxhbKoZjcACPVTeago1CESLZQ_/view?usp=sharing)

```
python inference.py
```

# Usage
 

```
git clone https://github.com/RIT/FAU_transformers.git
pip install -r requirements.txt
conda install cmake==3.9.1
pip install dlib
```

 
## Data preparation
 先自行下载bp4d数据集
 ```
python Prepare_data.py
```

## Train models
 
```
python main.py
```

