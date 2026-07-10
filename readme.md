## Quantum-Aware Learning Adapter for Few-Shot Image Classifier

The code of "Quantum-Aware Learning Adapter for Few-Shot Image Classifier"

### Abstract

The paper is under submission
The code is coming soon

### Data

* Follow [./datasets/0_dataset.md](./datasets/0_dataset.md) to install ImageNet and other 10 datasets or [Tip-Adapter DATASET.md](https://github.com/gaopengcuhk/Tip-Adapter/blob/main/DATASET.md) and [FAR DATASET.md](https://github.com/WideStars/FAR/blob/main/doc/DATASET.md) .


### Pretraining Model

* Download Pretraining Model to `./model/clip`

```
_MODELS = {
    "RN50": "https://openaipublic.azureedge.net/clip/models/afeb0e10f9e5a86da6080e35cf09123aca3b358a0c3e3b6c78a7b63bc04b6762/RN50.pt",
    "RN101": "https://openaipublic.azureedge.net/clip/models/8fa8567bab74a42d41c5915025a8e4538c3bdbe8804a470a72f30b0d94fab599/RN101.pt",
    "RN50x4": "https://openaipublic.azureedge.net/clip/models/7e526bd135e493cef0776de27d5f42653e6b4c8bf9e0f653bb11773263205fdd/RN50x4.pt",
    "RN50x16": "https://openaipublic.azureedge.net/clip/models/52378b407f34354e150460fe41077663dd5b39c54cd0bfd2b27167a4a06ec9aa/RN50x16.pt",
    "ViT-B/32": "https://openaipublic.azureedge.net/clip/models/40d365715913c9da98579312b702a82c18be219cc2a73407c4526f58eba950af/ViT-B-32.pt",
    "ViT-B/16": "https://openaipublic.azureedge.net/clip/models/5806e77cd80f8b59890b7e101eabd078d9fb84e6937f9e85e4ecb61988df416f/ViT-B-16.pt",
}
```


## Config

* Config `DATA_ROOT` in `qala_train.py`.

* Config `MODEL_CACHE_DIR` in `qala_train.py`.

* Set `LOG_ROOT` in `qala_train.py`.


## Train & Test

```
python qala_train.py
```



## Acknowledgement

This repo benefits from [FAR](https://github.com/WideStars/FAR), [Tip](https://github.com/gaopengcuhk/Tip-Adapter), [CoOp](https://github.com/KaiyangZhou/CoOp), and [CLIP](https://github.com/openai/CLIP). Thanks for their works.


