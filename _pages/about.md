---
permalink: /
title: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I am a final year PhD Student in the [system research group](https://www.cl.cam.ac.uk/research/srg/) at the Department of Computer Science and Technology, University of Cambridge. My research focuses on RL-driven performance optimization, and recently works on LLM systems for efficient training and inference.

I have worked at **Cohere**, **Bytedance Seed** and **Shanghai AI Lab** for efficient LLM training and serving systems.

I have also contributed to open-source projects such as [Pytorch](https://github.com/pytorch/pytorch) and [Triton](https://github.com/triton-lang/triton). For more information, see my Project page.

<br>

# Latest publications
(*  denotes equal contributions)

### LLM Systems, Training and Serving

<!--
- **Efficient Pre-Training of LLMs via Topology-Aware Communication Alignment on More Than 9600 GPUs**

Guoliang He\*, **Youhe Jiang**\*, Wencong Xiao, Jiang Kaihua, Shuguang Wang, Jun Wang, Du Zixian, Zhuo Jiang, Xinlei Zhang, Binhang Yuan, Eiko Yoneki

*Arxiv*

| [paper](https://arxiv.org/abs/paper-id) | [code](https://github.com/code-link) |
-->

- **Efficient Pre-Training of LLMs via Topology-Aware Communication Alignment on More Than 9600 GPUs**<br>
    <span style="color:green">NeurIPS 2025
    **G. He**\*, Y. Jiang\*, W. Xiao, K. Jiang, S. Wang, J. Wang, Z. Du, Z. Jiang, X. Zhang, B. Yuan, E. Yoneki

- **Demystifying Cost-Efficiency in LLM Serving over Heterogeneous GPUs**<br>
    <span style="color:green">ICML 2025</span><br>
    Y. Jiang\*, F. Fu\*, X. Yao\*, **G. He**\*, X. Miao, A. Klimovic, B. Cui, B. Yuan, E. Yoneki

- **vPALs: Towards Verified Performance-aware Learning System For Resource Management**<br>
    <span style="color:green">AAAI 2024, deployable AI workshop</span><br>
    **G. He**, G. Yeung, S. Ceesay, and A. Barker

<br>


### RL-Driven Performance Optimization

- **CuAsmRL: Optimizing GPU SASS Schedules via Deep Reinforcement Learning**<br>
    <span style="color:green">CGO 2025</span><br>
    **G. He**, E. Yoneki

- **SIP: Autotuning GPU Native Schedules via Stochastic Instruction Perturbation**<br>
    <span style="color:green">EuroSys 2024, EuroMLSys workshop</span><br>
    **G. He**, E. Yoneki

- **Optimizing Tensor Computation Graphs with Equality Saturation and Monte Carlo Tree Search**<br>
    <span style="color:green">PACT 2024</span><br>
    J. Hartmann, **G. He** and E. Yoneki

- **X-RLflow: Graph Reinforcement Learning for Neural Network Subgraph Transformation**<br>
    <span style="color:green">MLSys 2023</span><br>
    **G. He**, S. Parker, and E. Yoneki

- **MCTS-GEB: Monte Carlo Tree Search is a Good E-graph Builder**<br>
    <span style="color:green">EuroSys 2023, EuroMLSys workshop</span><br>
    **G. He**, Z. Singh, and E. Yoneki


<br>

# Biography

- 2021 - 2025 : Studied PhD degree at the University of Cambridge.

- 2020 - 2021 : Worked as a software engineer in cloud infrastructure.

- 2019 - 2020 : Receive my M.Sc. degree in Machine Learning from University College London.

- 2015 - 2019 : Receive my B.Eng. degree from University of Edinburgh and South China University of Technology.






<!--
Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this template](https://github.com/academicpages/academicpages.github.io) by clicking the "Use this template" button in the top right.
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.
1. Check status by going to the repository settings, in the "GitHub pages" section

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header.

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

The repository includes [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons.

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
-->
