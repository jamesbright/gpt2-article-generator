# GPT2 Article Generator

An application to allow for generating news articles using [OpenAI](https://openai.com)'s [GPT-2 text generator](https://openai.com/blog/better-language-models/).

## Setup

The model this program uses is hosted on Google Drive and can be downloaded from [here](https://drive.google.com/open?id=1Lmh7JBRkbC0jEvGtoZwVL30PT8PIt9qm). The `checkpoint` folder inside this archive should be extracted to the `gpt2-article-generator` folder.

The repository can be cloned as normal:
```shell
git clone https://github.com/DanTm99/gpt2-article-generator.git
```

Navigate into the folder:
```shell
cd gpt2-bot
```

Install the required packages:
```shell
pip3 install -r requirements.txt
```

To use this without GPU support use the following command instead:
```shell
pip3 install -r requirements-no-gpu.txt
```

## Usage

To use this with your GPU you must have and NVIDIA GPU with a CUDA Compute Capability 3.5 or higher.

If you have the required hardware you must install the required software on your system as shown [here](https://www.tensorflow.org/install/gpu#software_requirements).

To open the GUI use the following command:
```shell
python3 ArticleGenerator.py
```

This application can also be used via the command line. For detailed help use the following command:
```shell
python3 ArticleGenerator.py -h
```
