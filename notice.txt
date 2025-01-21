
## 2.4 数据预处理

*** 预处理 ***
```
python resample.py --skip_loudnorm
python preprocess_flist_config.py --speech_encoder vec768l12 --vol_aug
python preprocess_hubert_f0.py --f0_predictor rmvpe --use_diff
```
