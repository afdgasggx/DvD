### Quick Start
Before running the script, install the following dependencies:

```shell
pip install -r requirements.txt
```

To run DvD model as shown above:

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

