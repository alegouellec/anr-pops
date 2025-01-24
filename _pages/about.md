---
permalink: /
title: "Academic Pages is a ready-to-fork GitHub Pages template for academic personal websites"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

This is the front page of a website that is powered by the [Academic Pages template](https://github.com/academicpages/academicpages.github.io) and hosted on GitHub pages. [GitHub pages](https://pages.github.com) is a free service in which websites are built and hosted from code and data stored in a GitHub repository, automatically updating when a new commit is made to the repository. This template was forked from the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/) created by Michael Rose, and then extended to support the kinds of content that academics have: publications, talks, teaching, a portfolio, blog posts, and a dynamically-generated CV. You can fork [this template](https://github.com/academicpages/academicpages.github.io) right now, modify the configuration and markdown files, add your own PDFs and other content, and have your own site for free, with no ads!

Proposal’s context, positioning and objective(s)
======
a. Objectives and research hypothesis
The POPS project aims to decipher the fundamental mechanisms behind the role of polyamines in bacterial virulence, using a controlled alteration approach to the two metabolic biosynthetic pathways (classical and alternative) and the "omics" analytical approaches (i.e. transcriptomics, targeted proteomics, targeted and non-targeted metabolomics). Recent evidence showed that polyamines contribute to the virulence of pathogens [1, 2]. We demonstrated a correlation between high polyamines production, increased virulence of Pseudomonas aeruginosa (Pa) and instability of respiratory function in cystic fibrosis (CF) patients [3]. We also identified a modulation of polyamines metabolism in the presence of Staphylococcus aureus (Sa), the second major pathogen in CF patients [4, 5]. However, given that correlation does not imply causation,  our goal is to establish the molecular basis relationship between the polyamines metabolism and the virulence of clinical strains of Pa and its impact on co-infecting pathogens such as Sa.

To characterize the effect of polyamines in the virulence of Pa and their effect on the physiology of Sa accross  different biological levels (RNA, protein, and metabolites), we propose the following plan : In Work package (WP) 1, demonstrate the impact of polyamines synthesis on Pa virulence in vitro and in vivo. In WP2, measure the effect of polyamines on the interaction between Pa and Sa (by transcriptomics, targeted-proteomics and -metabolomics, and phenotypic characterization). In WP3, the deployment of advanced experimental and computational metabolomics methods to build genome-wide metabolic networks will elucidate the effect of polyamines on Sa and how they drive the interaction between the two micro-organisms. Finally, in WP4, investigate the respective evolutionary origins and distribution of the classical and alternative polyamines biosynthesis pathways across bacteria using a phylogenomic approach. 

b. Position of the project as it relates to the state of the art
Polyamines (i.e putrescine, spermidine, spermine) are poly-cationic metabolites ubiquitously present in prokaryotic and eukaryotic cells that have been described as playing an important role in cell physiology. In bacteria, the metabolism of polyamines and their potential function have mainly been studied in Escherichia coli and Thermus thermophilus. Some analysis of polyamine distribution in bacteria has been performed [6, 7]. Putrescine and spermidine are the most common polyamines in bacteria [8]. Some bacteria do not produce polyamines, and one of the earliest identified examples of polyamine auxotrophy was found in the firmicute opportunistic pathogen Sa. In Pa, spermidine stimulates cell growth and proliferation and causes cytotoxicity mediated by the Type 3 secretion system (T3SS) [9]. Spermidine is also known for its roles in modulating antibiotic resistance [10],  gene expression and translation [11], as well as inhibition of biofilm formation and escape from phagocytosis [12]. Although intracellular polyamines play an essential role in ensuring optimal growth, their accumulation can lead to inhibition of protein synthesis and reduce cell viability in stationary phase in E. coli [13, 14]. A balance between polyamines synthesis and catabolism is therefore necessary to adjust the optimal concentration of these metabolites for adaptation of bacteria's to their growth environment. Polyamines serve diverse physiological roles, with many mechanisms of action yet to be fully understood. 
P. aeruginosa is a metabolically versatile opportunistic pathogen, responsible for more than 500,000 deaths every year in the world and a major cause of chronic infections suffered by cystic fibrosis (CF) and chronic obstructive pulmonary disease (COPD) patients. The World Health Organization declared Pa a critical pathogen that poses a great threat to human health. Its presence is associated with a greater frequency of exacerbations and a progressive decline in CF patients' respiratory function [15]. The chronic nature of Pa pulmonary infection requires long-term, high-dose antimicrobial therapy, creating conditions for the emergence of resistant Pa strains. In a study by Partner 1, a cohort of 32 CF adult patients (14 Women, 18 Men) was monitored over 5 years [3]. This research revealed, through metabolomics analysis, a correlation between the abundance of polyamines produced by Pa, the increased virulence of the bacterium and the observed instability in respiratory function among the patients, as evidenced by an instability of FEV1 (forced expiratory volume in one second). Identifying how Pa modulates its polyamines production could provide crucial insight into its mechanisms of modulating its cytotoxicity during chronic infections.


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
