# KSL

### Create environment
conda env create -n environment.yml
### Activate environment
conda activate nia_ksl
conda activate environment.yml
### Train
python NIA_CSLR/main.py --config-file NIA_CSLR/configs/config.yaml
### Test
python NIA_CSLR/main.py --config-file NIA_CSLR/configs/exp_test.yaml --eval-only
