## Aim of the Workshop

To reach top-tier performance, deep learning architectures usually rely on a large number of parameters and operations, and thus require to be processed using considerable power and memory. Numerous works have proposed to tackle this problem using quantization of parameters, pruning, clustering of parameters, decompositions of convolutions or using distillation. However, most of these works aim at accelerating **only** the inference process and disregard the training phase. In practice, however, it is the learning phase that is by far the most complex. There has been recent efforts in introducing some compression on training process, however it remains challenging.

**In this workshop, we propose to focus on reducing the complexity of the training process. Our aim is to gather researchers interested in reducing energy, time, or memory usage for faster/cheaper/greener prototyping or deployment of deep learning models.** Due to the dependence of deep learning on large computational capacities, the outcomes of the workshop could benefit all who deploy these solutions, including those who are not hardware specialists. Moreover, it would contribute to making deep learning more accessible to small businesses and small laboratories.

Indeed, training complexity is of interest to many distinct communities. A first example is training on edge devices, where training can be used to specialize to data obtained online when the data cannot be transmitted back to the cloud because of constraints on privacy or communication bandwidth. Another example is accelerating training on dedicated hardware such as GPUs or TPUs.

The workshop welcomes contributions that seek to reduce the cost of the training process by taking into account the details of the computing hardware (CPU, GPU, IPU, NPU, or any other custom accelerator implemented as an ASIC or on FPGA) including (but not limited to):

- compression methods to reduce memory usage and/or complexity of deep learning during training,
- hardware architectures and implementations for deep learning training,
- energy reduction techniques for deep learning training,
- open-source designs, implementations and code related to efficient deep-learning implementations,
- energy models or energy-efficiency benchmarks for deep learning training implementations,
- applications of low-energy deep learning training,
- equilibrium-propagation-based techniques and/or their hardware implementations,
- few-shot/few-labels and semi-supervised learning methods for training on chip. 


Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/eghouti/Hardware-Aware-Efficient-Training/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
