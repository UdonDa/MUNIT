Forked from [https://github.com/NVlabs/MUNIT](https://github.com/NVlabs/MUNIT)

## Usage

1. Run
```
python train.py --config configs/edges2handbags_folder.yaml
```

## Worried
It doesnt work DataPrallel!!!!!!!

## Info
#### 1. data_parallel_tutorial.py
Code of MultipleGPU running on Pythorch 0.4.0

#### 2. own.py
Code of MultipleGPU running on Pythorch 0.3.0


In reference to these two, let's move MUNIT with MultipleGPU!!!!


[![License CC BY-NC-SA 4.0](https://img.shields.io/badge/license-CC4.0-blue.svg)](https://raw.githubusercontent.com/NVIDIA/FastPhotoStyle/master/LICENSE.md)
![Python 2.7](https://img.shields.io/badge/python-2.7-green.svg)
![Python 3.6](https://img.shields.io/badge/python-3.6-green.svg)
## MUNIT: Multimodal UNsupervised Image-to-image Translation

### License

Copyright (C) 2018 NVIDIA Corporation.  All rights reserved.
Licensed under the CC BY-NC-SA 4.0 license (https://creativecommons.org/licenses/by-nc-sa/4.0/legalcode). 

### Code usage

Please check out the [user manual page](USAGE.md).

### Paper

[Xun Huang](http://www.cs.cornell.edu/~xhuang/), [Ming-Yu Liu](http://mingyuliu.net/), [Serge Belongie](https://vision.cornell.edu/se3/people/serge-belongie/), [Jan Kautz](http://jankautz.com/), "[Multimodal Unsupervised Image-to-Image Translation](https://arxiv.org/abs/1804.04732)" arXiv preprint arXiv:1804.04732

### Results Video
[![](results/video.jpg)](https://youtu.be/ab64TWzWn40)

### Edges to Shoes/handbags Translation

![](results/edges2shoes_handbags.jpg)

### Animal Image Translation

![](results/animal.jpg)

### Street Scene Translation

![](results/street.jpg)

### Yosemite Summer to Winter Translation (HD)

![](results/summer2winter_yosemite.jpg)

### Example-guided Image Translation

![](results/example_guided.jpg)

### Other Implementations

[MUNIT-Tensorflow](https://github.com/taki0112/MUNIT-Tensorflow) by [Junho Kim](https://github.com/taki0112)

[MUNIT-keras](https://github.com/shaoanlu/MUNIT-keras) by [shaoanlu](https://github.com/shaoanlu)

### Citation

If you find this code useful for your research, please cite our paper:

```
@article{huang2018munit,
  title={Multimodal Unsupervised Image-to-image Translation},
  author={Huang, Xun and Liu, Ming-Yu and Belongie, Serge and Kautz, Jan},
  journal={arXiv preprint arXiv:1804.04732},
  year={2018}
}
```


