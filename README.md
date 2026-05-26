# VAE-DDPM-Image-Generation-Comparison
# Reproducing Results

## VAE Experiments

To reproduce the VAE results, rerun the notebook after updating the model configuration with the parameters reported in `vae_report.pdf`.

Configuration files (`config.json`) can be found in the following experiment directories:

```text
exp_1
with_KL_equals_1
with_KL_equals_one_over_ten_and_30_epoch
with_KL_equals_one_over_ten_for_30_epoch_with_atten
with_KL_equals_one_over_ten_for_30_epoch_with_atten_interpolation_upsampling
```
**Note** : The last two experiment are not reported.

Each directory contains the corresponding experiment configuration and hyperparameters used during training.

## DDPM Experiments

For the DDPM experiments, running all notebook cells sequentially should reproduce the pipeline without requiring additional configuration changes.

## Notes on Reproducibility

The codebase was not fully standardized for deterministic reproducibility. However, based on multiple reruns for some experiments, the obtained results remain relatively stable and do not show significant variance.

## Additional Experiments

An additional branch named:

```text
extra_mile
```

will be added to the repository and may contain supplementary experiments, trials, or exploratory implementations.

## Support

If you encounter any issues or unclear steps while reproducing the experiments, feel free to contact me.
