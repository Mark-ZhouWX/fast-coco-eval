# Introduction
A fast coco eval api that wraps facebook's coco eval api in detectron2

# Installation
```shell
pip install fast-coco-eval-python
```

# Usage
The function of fast_coco_eval is equal equivalent to original cooc_eval api in pycocotools. To implement fast_coco_eval, replace the following code
```python
from pycocotools.cocoeval import COCOeval
```
with
```python
from fast_coco_eval import COCOeval_fast as COCOeval
```

# Reference
The code file `cocoeval.cpp` in folder `cocoeval` is referenced from repository https://github.com/facebookresearch/detectron2.
The corresponding commit id is 3e71a2711bec4eaa488d29cd07f124d384d9d69e 'Apply clang-format update fixes'.

The code file `cocoeval.h` in folder 'cocoeval` is referenced from repository https://github.com/facebookresearch/detectron2.
The corresponding commit id is 60d7a1fd33cc48e58968659cd3301f3300b2786b 'update copyright header'.

The python `fast_coco_eval_api.py` is referenced from repository https://github.com/facebookresearch/detectron2.
The corresponding commit id is 28b1bd2396cb88676f0f13537e499373ad24f4f7 'better logging in COCO evaluator'.