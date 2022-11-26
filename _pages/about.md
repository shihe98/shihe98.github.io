---
permalink: /
title: "About Me"
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


My current research interests are System Security, and AI Security and Privacy. I received my B.Eng degree from Nanjing Normal University of China (NNU) in 2016 and studied at Nanjing University of Science and Technology of China (NJUST), in 2020.

Publications
======
**[5]** **Shang Wang**, Yansong Gao, Anmin Fu, Zhi Zhang, Yuqing Zhang, Willy Susilo, Dongxi Liu. CASSOCK: Viable Backdoor Attacks against DNN in The Wall of Source-Specific Backdoor Defences. ACM ASIACCS, 2023. **CCF C**

**[4]** Zhenzhu Chen, **Shang Wang**, Anmin Fu, Yansong Gao, Shui Yu, Robert H. Deng. LinkBreaker: Breaking the Backdoor-Trigger Link in DNNs via Neurons Consistency Check. IEEE Transactions on Information Forensics and Security, 2022. DOI: 10.1109/TIFS.2022.3175616. **CCF A**

**[3]** **Shang Wang**, Xin Li, Yongli Song, Mang Su, Anmin Fu. A Trigger Sample Detection Scheme Based on Custom Backdoor Behaviors. Journal of Cyber Security, 2022. **CCF B**

**[2]** Anmin Fu, **Shang Wang**. A Plug-in Trigger Inputs Detection Method. Patent, 2022.

**[1]** Chunyi Zhou, Dawei Chen, **Shang Wang**, Anmin Fu, Yansong Gao. Research and Challenge of Distributed Deep Learning Privacy and Security Attack. Journal of Computer Research and Development, 2021. **CCF A**

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

I have also created [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the academicpages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring academicpages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
