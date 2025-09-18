### Quick Start
Before running the script, install the following dependencies:

```shell
pip install -r requirements.txt
```

To run DvD model as shown above:

#### pretrained model download
https://drive.google.com/drive/folders/1RBt9t_5igAlN1BlQAkVLwJ_rZXITy_pN?usp=sharing


#### Inference code
```bash
python run_sampling.py \
  --train_module 'dvd' 
  --train_name 'val_TDiff' --name "0918"
```

#### Training code
```bash
mpiexec -n 1 python run_training.py \  
  --train_module 'dvd' 
  --train_name 'train_TDiff' 
```

