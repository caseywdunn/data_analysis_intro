# Introduction to data analysis

This is a series of resources and tutorials for modern practices in data analysis. It is geared toward biologists.

If data analysis and computation is going to be a significant part of your research, I strongly suggest familiarizing yourself with the following tools and topics. The materials here are designed as an on-ramp to these topics.

- Getting around at the command line. 
- Version control with git and GitHub
- Regular expressions for text processing
- Python and/or R.
- If Python, then also:
  - Jupyter notebooks(https://jupyter.org/)
  - Pandas, numpy, and matplotlib libraries
  - Conda package manager
- If R, then also:
  - [Quarto](https://quarto.org/docs/computations/r.html) notebooks
  - Tidyverse libraries
- [Markdown](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax), a simple markup language for formatting in plain text.
- [VS Code](https://code.visualstudio.com). I strongly suggest using this as your primary code editor, regardless of whether you use Python, R, or other languages.
- Using generative AI tools like [GitHub Copilot](https://github.com/features/copilot), ChatGPT, and Google Gemini to help learn, review, and write code.

## Resources

- [Practical Computing for Biologists](https://global.oup.com/academic/product/practical-computing-for-biologists-9780878933914?cc=us&lang=en&). Topics here are covered primarilly in chapters 8-10, but other chapters are relevant too.
- [Python Data Science Handbook](https://jakevdp.github.io/). Read this book cover to cover if you use python. We will focus on the materials in chapters 2-3.
- If you use R, many of the same topics are covered in [R for Data Science](https://r4ds.had.co.nz/). Read this book cover to cover if you use R.

## Preparations ahead of first meeting

Before the first class, please do the following:

- Get a github account - https://github.com/ . Make sure your academic email is registered with the account, it can be primary or secondary.
- Activate your free academic GitHub copilot account. It may take a few days to activate, so be sure to do it well before class - https://github.blog/2022-09-08-github-copilot-now-available-for-teachers/ .
- Install VS Code - https://code.visualstudio.com .
- Install miniconda - https://docs.conda.io/projects/miniconda/en/latest/miniconda-install.html .

Optional:
- If on Windows, install Windows Subsystem for Linux (WSL) - https://docs.microsoft.com/en-us/windows/wsl/install .
- If you use R, install R https://cran.r-project.org/ 

## Topics

### Data visualization

See `visualizaiton` in this repository. 

For a broader discussion, see the class I did on [interacting with data](https://github.com/Brown-BIOL2430-S04-Fall2015/syllabus).

Resources:

Shneiderman 1996, http://www.mat.ucsb.edu/~g.legrady/academic/courses/11w259/schneiderman.pdf - "Visual Information-Seeking Mantra: overview first, zoom and filter, then details on demand."
Tufte, ER (2001). The Visual Display of Quantitative Information, 2nd edition.

### Measurement theory

Houle et al (2011) Measurement and Meaning in Biology. https://www.journals.uchicago.edu/doi/10.1086/658408

### Machine learning

This video introduces the basic concepts of neural networks - https://www.youtube.com/watch?v=aircAruvnKk

[This](https://kili-technology.com/data-labeling/machine-learning/neural-network-architecture-all-you-need-to-know-as-an-mle-2023-edition) is a good overview of network architectures.

This is the paper that introduced the Transformer and kicked off extensive progress in generative AI - https://arxiv.org/abs/1706.03762

#### Generative AI

A leaderboard of chatbots - https://huggingface.co/spaces/lmsys/chatbot-arena-leaderboard

To install and run your own chatbot locally, first install [ollama](https://ollama.com/)

For a small model that can run on most laptops, try:

    ollama run llama2

If you have 40GB of disk space to spare, at least 64GB of RAM, and a good GPU, try:

    ollama run dolphin-mixtral:latest

