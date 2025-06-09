# methylation-deconvolution
## Using Methylation Atlas Deconvolution: nloyfer/meth_atlas 

### Package Plan ###

  environment location: /opt/anaconda3/envs/methatlas

  added / updated specs:
    - matplotlib
    - numpy
    - pandas=1.5.3
    - python=3.10
    - scipy

python3 deconvolve.py --atlas_path reference_samples.csv --out_dir /Meth_atlas/ --plot --residuals bulk_samples.csv 
