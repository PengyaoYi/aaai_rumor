Official code for our AAAI 2023 paper - Zero-Shot Rumor Detection with Propagation Structure via Prompt Learning.

## Requirements
```
python==3.8.10
pandas==1.1.5
numpy==1.23.5
protobuf==3.19.4
torch==1.8.0
transformers==3.4.0
sentence-transformers==0.4.0
```

## Get Started
- data: download the processed data from: https://drive.google.com/file/d/1BZ-6a8chFCVATEyXH1vMO_CPAMOL0z-p/view
or run the pre-process code comment.py in data dir, you need to run the code for different type of data separately
- pretrain-model: xlm-roberta , the top 6 layers inited in our model twice: https://drive.google.com/file/d/1kF8rG1RZ1G3CFsuiIJMYgQHuaAKCFsE4/view?usp=drive_link
- Run script
```
$ sh train.sh
```

## Acknowledgement

If you find this resource useful, please let us know and cite our paper:
```
@misc{https://doi.org/10.48550/arxiv.2212.01117,
  doi = {10.48550/ARXIV.2212.01117},
  
  url = {https://arxiv.org/abs/2212.01117},
  
  author = {Lin, Hongzhan and Yi, Pengyao and Ma, Jing and Jiang, Haiyun and Luo, Ziyang and Shi, Shuming and Liu, Ruifang},
  
  keywords = {Computation and Language (cs.CL), FOS: Computer and information sciences, FOS: Computer and information sciences},
  
  title = {Zero-Shot Rumor Detection with Propagation Structure via Prompt Learning},
  
  publisher = {arXiv},
  
  year = {2022},
  
  copyright = {arXiv.org perpetual, non-exclusive license}
}

```
