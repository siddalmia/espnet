<!-- Generated by scripts/utils/show_enh_score.sh -->
<!-- These results are from the code before refactoring  -->
# RESULTS
## Environments
- date: `Thu Jul 30 08:30:20 CST 2020`
- python version: `3.7.3 (default, Mar 27 2019, 22:11:17)  [GCC 7.3.0]`
- espnet version: `espnet 0.7.0`
- pytorch version: `pytorch 1.5.1`
- Git hash: `2887ca2d0bdc57244b488de86adf2d55026105f0`
  - Commit date: `Fri Jul 24 04:04:52 2020 +0800`


## enh_train_enh_beamformer_no_wpe_8k_2ch_4gpu_raw

config: conf/tuning/train_enh_beamformer_no_wpe.yaml

|dataset|STOI|SAR|SDR|SIR|
|---|---|---|---|---|
|enhanced_cv_spatialized_anechoic_multich|0.965245|24.4831|20.6248|23.7421|
|enhanced_tt_spatialized_anechoic_multich|0.968908|24.3599|20.4742|23.5676|
