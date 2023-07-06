<div align="center">
	<img src="./assets/img/banner.jpg">
</div>



# splitMe : a simple video splitter



[![PyPI version](https://badge.fury.io/py/splitme.svg)](https://badge.fury.io/py/splitme)
[![PyPI license](https://img.shields.io/pypi/l/splitme.svg)](https://pypi.python.org/pypi/splitme/)
[![PyPI pyversions](https://img.shields.io/pypi/pyversions/splitme.svg)](https://pypi.python.org/pypi/splitme/)
[![PyPI status](https://img.shields.io/pypi/status/splitme.svg)](https://pypi.python.org/pypi/splitme/)
[![PyPI download month](https://img.shields.io/pypi/dm/splitme.svg)](https://pypi.python.org/pypi/splitme/)
[![PyPI download week](https://img.shields.io/pypi/dw/splitme.svg)](https://pypi.python.org/pypi/splitme/)
[![PyPI download day](https://img.shields.io/pypi/dd/splitme.svg)](https://pypi.python.org/pypi/splitme/)
 

## What is it

Most simple program writen in python to split a video in 2 or more parts.

## Usage 

```shell
splitme [video] 
# or
splitme -n 3 [video] # split in 3 parts
# or 
splitme -d [video] # split and delete original file

```

## Install

Install ffmpeg
```shell
sudo apt install ffmpeg
```

Install splitme
```shell
pip install splitme
```

Alias .basrhc our .zshrc :  
```shell
echo "alias splitme='python3 -m splitme'" >> ~/.bashrc # or ~/.zshrc
```

## Changelog

- No tags for now