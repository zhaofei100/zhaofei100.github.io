---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Education
======
Ph.D. in Preventive Veterinary Science                  09/02/2013‒07/05/2016
The Graduate School of Chinese Academy of Agricultural Sciences, Beijing, China 
Supervisor: Dr. Changming Liu, Ph.D.

Master in Preventive Veterinary Medicine                    09/01/2010‒07/04/2013
The Graduate School of Chinese Academy of Agricultural Sciences, Beijing, China 
Supervisor: Dr. Changming Liu, Ph.D.

Bachelor in Veterinary Medicine                           09/01/2006‒06/25/2010 
College of Veterinary Medicine, Sichuan Agricultural University, Yaan, China
Supervisor: Dr. Xiaobo Huang, Ph.D.

Research experience
======
Assistant Scientist  09/08/2021‒26/08/2022
=
Laboratory of Dr. Scott Tibbetts, Ph.D. Department of Molecular Genetics & Microbiology, College of Medicine, University of Florida, Gainesville, Florida, USA
•	Defining the in vivo function of EWSR1 during gammaherpesvirus-driven and antigen-mediated germinal center B cell responses.
•	Determining the in vivo function of EBV EBER2 polymorphisms differentially associated with B cell lymphoma during chronic infection.

Postdoctoral Associate  06/01/2017‒09/07/2021 
=
Laboratory of Dr. Scott Tibbetts, Ph.D. Department of Molecular Genetics & Microbiology, College of Medicine, University of Florida, Gainesville, Florida, USA
•	Defining the in vivo function of murine gammaherpesvirus 68 (MHV68) miRNAs and their targets during latency and pathogenesis
•	Determining the conserved in vivo function of Epstein-Barr virus (EBV) encoded RNA 2 (EBER2) during latency and pathogenesis
•	Identifying the function of MHV68-encoded circular RNA circM11_ORF69 during virus infection

Postdoctoral Fellow  09/01/2016‒05/31/2017
=
Laboratory of Dr. Ravit Arav-Boger, M.D. Department of Pediatrics, School of Medicine, Johns Hopkins University, Baltimore, Maryland, USA
•	Screening and functionally validating antiviral compounds against human and mouse cytomegaloviruses (HCMV and MCMV)
•	Investigating the interaction between HCMV IE1/2 and herpesvirus-associated ubiquitin-specific protease (HAUSP/USP7)

Ph.D. Graduate Research  09/02/2013‒07/05/2016                                     
=
Laboratory of Dr. Changming Liu, Ph.D. Division of Swine Infection Diseases, State Key Laboratory of Veterinary Biotechnology, Harbin Veterinary Research Institute, Chinese Academy of Agricultural Sciences, Harbin, China
•	Identifying the pathways by which the pseudorabies virus (PRV) DNA polymerase holoenzyme is transported into the nucleus 
•	Determining the oligomerization status of the PRV DNA polymerase processivity factor UL42
•	Investigating targeting the PRV UL42 or disrupting the PRV UL42/UL30 interaction as a potential antiviral strategy against PRV

M.S. Graduate Research  09/01/2010‒07/04/2013
=
Laboratory of Dr. Changming Liu, Ph.D. Division of Swine Infection Diseases, State Key Laboratory of Veterinary Biotechnology, Harbin Veterinary Research Institute, Chinese Academy of Agricultural Sciences, Harbin, China
•	Determining the immunoenhancement effect of porcine cytokines (IFN-γ, IL-2, and GM-CSF) on porcine circovirus 2 capsid protein-based subunit vaccine

Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this repository](https://github.com/academicpages/academicpages.github.io) by clicking the "fork" button in the top right. 
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
