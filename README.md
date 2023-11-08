#### Info

Project website : https://openthaigpt.aieat.or.th/

#### Deploy 

```
docker run -it --gpus=all -v $(pwd)/OpenThaiGPT/:/app -w /app nvcr.io/nvidia/pytorch:22.07-py3 /bin/bash
pip install -r requirements-dev.txt
python main.py
```

