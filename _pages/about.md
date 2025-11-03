---
permalink: /
title: "About"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a Ph.D. candidate at the <a href="https://www.life.uestc.edu.cn/" target="_blank">School of Life Sciences and Technology</a>, <a href="https://www.uestc.edu.cn/" target="_blank">University of Electronic Science and Technology of China</a>, focusing on <b>AI in medicine</b>, <b>computational neuroscience</b>, and <b>medical image analysis</b>.


<!-- ===== Services ===== -->
Services
======
- IEEE Transactions on Neural Networks and Learning Systems (**IEEE TNNLS**), Reviewer
- IEEE Journal of Biomedical and Health Informatics (**IEEE JBHI**), Reviewer
- European Journal of Radiology (**EJR**), Reviewer
- Biomedical Signal Processing and Control (**BSPC**), Reviewer
- Physical and Engineering Sciences in Medicine (**PESM**), Reviewer
<p><sub>Last updated: 2025-06-01</sub></p>


<!-- ===== News ===== -->
Recent News
======
<ul>
  <li><b>2025.4.12:</b> Our paper "<b>Multi-phase feature-aligned fusion model for automated colorectal cancer segmentation in contrast-enhanced CT scans</b>" was accepted by <i><b>Expert Systems with Applications</b></i>.</li>
  <li><b>2025.1.12:</b> Our paper "<b>AutoLDP: An accurate and efficient artificial intelligence-based tool for automatic labeling of digital pathology</b>" was accepted by <i><b>EngMedicine</b></i>.</li>
  <li><b>2024.8.13:</b> Our paper "<b>A transformer-based deep learning model for early prediction of lymph node metastasis in locally advanced gastric cancer after neoadjuvant chemotherapy using pretreatment CT images</b>" was accepted by <i><b>eClinicalMedicine</b></i>.</li>
  <li><b>2024.5.23:</b> Our paper "<b>ALIEN: Attention-guided cross-resolution collaborative network for 3D gastric cancer segmentation in CT images</b>" was accepted by <i><b>Biomedical Signal Processing and Control</b></i>.</li>
  <li><b>2024.5.21:</b> Our paper "<b>Deep learning for colorectal cancer detection in contrast-enhanced CT without bowel preparation: a retrospective, multicentre study</b>" was accepted by <i><b>eBioMedicine</b></i>.</li>
  <li><b>2024.4.25:</b> Our paper "<b>Deep learning-aided 3D proxy-bridged region-growing framework for multi-organ segmentation</b>" was accepted by <i><b>Scientific Reports</b></i>.</li>
  <li><b>2024.3.20:</b> Our paper "<b>A colorectal coordinate-driven method for colorectum and colorectal cancer segmentation in conventional CT scans</b>" was accepted by <i><b>IEEE TNNLS</b></i>.</li>
  <li><b>2024.1.20:</b> Our paper "<b>Development of a machine learning-based radiomics signature for estimating breast cancer TME phenotypes and predicting anti-PD-1/PD-L1 immunotherapy response</b>" was accepted by <i><b>Breast Cancer Research</b></i>.</li>
  <li><b>2023.11.8:</b> Our paper "<b>Pathologic complete response prediction in breast cancer lesion segmentation and neoadjuvant therapy</b>" was accepted by <i><b>Frontiers in Medicine</b></i>.</li>
  <li><b>2022.1.21:</b> Our engineering work with <a href="https://www.wchscu.cn/public/index.html" target="_blank">West China Hospital</a>, "<b>Building Structured Patient Follow-up Records from Chinese Medical Records via Deep Learning</b>", was published in <i><b>BIC 2022</b></i>.</li>
  <li><b>2020.1.7:</b> Our paper "<b>Detecting abnormal brain regions in schizophrenia using structural MRI via machine learning</b>" was accepted by <i><b>Computational Intelligence and Neuroscience</b></i>.</li>
</ul>

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one Markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a Markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each Markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

The repository includes [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual Markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the Markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and Markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a Markdown file for a talk
![Editing a Markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
