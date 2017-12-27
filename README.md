# gdown

[![PyPi Version](https://img.shields.io/pypi/v/gdown.svg)](https://pypi.python.org/pypi/gdown)
[![Travis Status](https://travis-ci.org/wkentaro/gdown.svg?branch=master)](https://travis-ci.org/wkentaro/gdown)

Wget for files at Google Drive.


## Installation

```bash
pip install gdown
```


## Usage

```bash
$ # gdown URL [-O FILENAME]

$ gdown https://drive.google.com/uc?id=0B9P1L--7Wd2vU3VUVlFnbTgtS2c
$ cat spam.txt
spam

$ gdown --id 0B9P1L--7Wd2vU3VUVlFnbTgtS2c
$ cat spam.txt
spam

$ gdown https://httpbin.org/ip -O ip.json
$ cat ip.json
% cat ip
{
  "origin": "126.169.213.247"
}
```
