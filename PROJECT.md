
### 1. install

```
conda create -n vlm python==3.10
conda activate vlm
pip3 install torch torchvision
pip3 install flash-attn --no-build-isolation

git clone git@github.com:chunhuizhang/verl_vlm.git
cd verl_vlm
pip3 install -e .[vllm]

pip3 install vllm==0.8.3

# qwen/vlm related
pip3 install qwen_vl_utils, mathruler

# misc
pip3 install ipython
```


### 2. geo3k

```
python ./examples/data_preprocess/geo3k.py
```

### 3. training

```

```