# Utility for stress-testing NVIDIA GPU accelerators

stripped-down mod of https://github.com/Microway/gpu-burn to burn a single GPU

```sh
gpu_burn -i 7  # burn device index 7
```

```sh
watch nvidia-smi --query-gpu=index,utilization.gpu,temperature.gpu --format=csv
```
