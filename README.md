# opso-agile-al

Based on https://github.com/climatechange-ai-tutorials/bioacoustic-monitoring?tab=readme-ov-file


# Tensorflow environment

```

conda create -n agile-al python==3.10
conda activate agile-al
pip install tensorflow==2.15.0
pip install jupyterlab
pip install git+https://github.com/google-research/perch.git@e27e95344c84601759d4d881289a1c2b53697fa6

```

# Create symbolic link to data



# Running on Snowy

```
jupyter-lab --no-browser --port=8080
```


```
ssh -L 8080:localhost:8080 let110@10.220.222.226

```