# NLP: Transformer Seq2Seq Machine Translation

In this tutorial, you will learn the following:
- The process of training a translation model from the ground up using the Transformer architecture.
- Utilizing the torchtext library to acquire the [Multi30k](http://www.statmt.org/wmt16/multimodal-task.html#task1) dataset for training a model that translates from German to English.

## Recommended Preparation

Before starting this tutorial it is recommended that you have installed [PyTorch](https://pytorch.org/) or use [Google Colab](https://colab.research.google.com/?utm_source=scs-index), and have a basic understanding of [Python programming language](https://www.python.org/doc/) and [Tensors](https://pytorch.org/tutorials/beginner/basics/tensorqs_tutorial.html):

### Google Colab

For tips on running tutorial notebooks in Google Colab, see [Colab Pytorch Tutorial](https://pytorch.org/tutorials/beginner/colab)

### Conda Environment Setup

Use the first command to create new independent environment for the project. Or use the other two commands to remove or update the Conda environment.

```shell
# To create a conda environment.
conda env create -f environment.yml

# To remove a conda environment.
conda remove --name nlp --all

# To update a conda environment when some new libraries are added.
conda env update -f environment.yml --prune
```
Then, install [PyTorch](https://pytorch.org/).

And the following:
```python
pip install -U portalocker
pip install -U torchtext
pip install -U spacy
python -m spacy download en_core_web_sm
python -m spacy download de_core_news_sm
```

## References

It would also be useful to know about Sequence to Sequence networks and
how they work:

1. [Attention is all you need paper.](https://papers.nips.cc/paper/2017/file/3f5ee243547dee91fbd053c1c4a845aa-Paper.pdf)

2. [The annotated transformer.](https://nlp.seas.harvard.edu/2018/04/03/attention.html#positional-encoding)

### Citation

```bibtex

```
