# Setup for Exercise Session

This is a quick guide/checklist that summarizes the tools and libraries that will be used in the course for the exercises and the assignments. 


### Clone repo & environment setup

To clone this repo run the following:

```
clone https://github.com/epfl-nlp/cs-552-modern-nlp.git
cd cs-552-modern-nlp
```

If you are not familiar with python environments and the CONDA toolbox, and you have not installed conda before, we recommend you to [install miniconda](https://docs.conda.io/en/latest/miniconda.html) instead of the complete anaconda, and follow [these installation steps](https://conda.io/projects/conda/en/stable/user-guide/install/index.html) for the specific OS you have. Miniconda will download less packages automatically and will space on your machine. If you would like to get started with conda environments after installation, please follow this [CONDA cheatsheet](https://docs.conda.io/projects/conda/en/4.6.0/_downloads/52a95608c49671267e40c689e0bc00ca/conda-cheatsheet.pdf) on how to run and use Conda environment manager. Depending on the exercise session you may need to create environments with different python versions. For now we recommend you to use python=3.8


### Python libraries

You can check the main python libraries that we will use for the exercise sessions in the `requirements.txt` file which is located [here](). Note that this file will probably be updated in the future as the semester progresses. You can install and use any other library you want unless specified otherwise by the Exercise, Assignement or Project description.


### PyTorch tutorial

For this course, we will also be using [PyTorch](https://pytorch.org/) and [Transformers](https://huggingface.co/docs/transformers) (by Hugging Face) libraries to build, train and test models. 

🔥 PyTorch is a free and open-source machine learning framework for building deep learning models. Written in Python, it’s relatively easy for most machine learning developers to learn and use. PyTorch is distinctive for its support for GPUs and its use of reverse-mode auto-differentiation, which enables computation graphs to be modified on the fly. This makes it a popular choice for fast experimentation and prototyping.

> - [Official API](https://pytorch.org/docs/stable/index.html)
> - Code tutorials: [PyTorchZeroToAll](https://github.com/hunkim/PyTorchZeroToAll)
> - Video tutorial: [PyTorchZeroToAll (in English)](https://www.youtube.com/playlist?list=PLlMkM4tgfjnJ3I-dbhO9JTw7gNty6o_2m)

🤗 Hugging Face's platform is developed to allow users to build, train, and deploy machine learning (ML) and artificial intelligence models. It is most notable for its Transformers library built for natural language processing applications and its platform that allows users to share machine learning models and datasets.

> - [Official API](https://huggingface.co/docs/transformers/index)
> - Code tutorials: [huggingface/transformers](https://github.com/huggingface/transformers/tree/main/examples/pytorch)
> - Video tutorials: [Hugging Face in 15 Minutes](https://www.youtube.com/watch?v=QEaBAZQCtwE&ab_channel=AssemblyAI)


### Colab tutorial

Colaboratory ("Colab" for short)  is a data analysis and machine learning tool that allows you to combine executable Python code and rich text along with charts, images, HTML, LaTeX and more into a single document stored in Google Drive. It connects to powerful Google Cloud Platform runtimes and enables you to easily share your work and collaborate with others.

You can familiarize yourself with the platform by checking this [Google Colab Guide](https://hackmd.io/@BrownDeepLearningS23/BkIT3sW6s).





