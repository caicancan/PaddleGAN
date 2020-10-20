English | [简体中文](./README_cn.md)

# PaddleGAN

PaddleGAN is an development kit of Generative Adversarial Network based on PaddlePaddle.


### old video restore
![](./docs/imgs/color_sr_peking.gif)

### super resolution

![](./docs/imgs/sr_demo.png)

Features:

- Highly Flexible:

  Components are designed to be modular. Model architectures, as well as data
preprocess pipelines, can be easily customized with simple configuration
changes.

- Rich applications:

  PaddleGAN provides rich of applications, such as image generation, image restore, image colorization, video interpolate, makeup shifter.

## Install

### 1. install paddlepaddle

PaddleGAN work with:
* PaddlePaddle >= 2.0.0-rc
* Python >= 3.5+

```
pip install -U paddlepaddle-gpu
```

### 2. install ppgan

```
python -m pip install 'git+https://github.com/PaddlePaddle/PaddleGAN.git'
```

Or install it from a local clone
```
git clone https://github.com/PaddlePaddle/PaddleGAN
cd PaddleGAN

pip install -v -e .  # or "python setup.py develop"
```

## Data Prepare
Please refer to [data prepare](./docs/data_prepare.md) for dataset preparation.

## Get Start
Please refer [get stated](./docs/get_started.md) for the basic usage of PaddleGAN.

## License
PaddleGAN is released under the [Apache 2.0 license](LICENSE).

## Contributing

Contributions are highly welcomed and we would really appreciate your feedback!!

## External Projects

External gan projects in the community that base on PaddlePaddle:

+ [PaddleGAN](https://github.com/PaddlePaddle/PaddleGAN)
