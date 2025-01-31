# KSL

### Create environment
conda env create -n environment.yml
### Activate environment
conda activate nia_ksl
conda activate environment.yml
### Train
python main.py --config-file configs/config.yaml
### Test
python main.py --config-file configs/exp_test.yaml --eval-only
