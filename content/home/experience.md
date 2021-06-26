---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

title: Experience
subtitle:

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: Visual Document Intelligence Research Intern
    company: AI & RD Center, Microsoft
    company_url: 'https://www.microsoft.com/zh-tw/abouttaiwan/'
    company_logo: org-Microsoft
    location: Taipei, Taiwan
    date_start: '2018-10-06'
    date_end: '2021-03-31'
    description: |2-
        * Implemented a unified multi-vertical document understanding model <br /> for variaous kinds of documents' named entity recognition (NER)
        * Migrated and refactored model training to [Pytorch Lightning](https://pytorch-lightning.readthedocs.io/en/latest/) for much faster development and maintenance
        * Migrated model training to the official AzureML training pipeline
  - title: Graduate Student & Network Adminstrator
    company: Speech Processing & Machine Learning Lab, <br/>National Taiwan University (NTU)
    company_url: 'https://www.ntu.edu.tw/english/index.html'
    company_logo: org-NTU
    location: Taipei, Taiwan
    date_start: '2018-10-02'
    date_end: '2020-09-30'
    description: |2-
        As the __graduate student__

        * Graduate Researcher in Speech Processing & Machine Learning Lab, <br />
          supervised by Prof. [Hung-Yi Lee](https://speech.ee.ntu.edu.tw/~hylee/)
        * Researched on low-resource speech recognition, focusing on improving the system with gradient-based meta learning and transfer learning
        * Teaching assistant of Deep Learning for Human Language
          Processing (Spring 2020) [[CommE5054]](https://speech.ee.ntu.edu.tw/~hylee/dlhlp/2020-spring.html)
        
        <br />
        As the __network adminstrator__

        * Managed the [slurm-based](https://slurm.schedmd.com/documentation.html) computation cluster (10 nodes, over 20 GPUs)
        * Migrated [netdata](https://www.netdata.cloud/) to replace the original unstable monitor system to support real-time resource monitoring for users
        * Developed health check and notification mechanism to drain problematic nodes and notify to the public platform automatically
  - title: NLP Research Intern
    company: Apple Inc.
    company_url: 'https://www.apple.com/careers/us/machine-learning-and-ai.html'
    company_logo: org-Apple
    location: Cupertino, CA, USA
    date_start: '2018-06-26'
    date_end: '2018-09-30'
    description: |2-
      * Researched on deep generative model to develop algorithms improving keyboard experience of users
      * The research results have been published in iOS 13 (2019) and [US patent](https://patents.google.com/patent/US20200379640A1/en?oq=US20200379640A1) (2020)
  - title: Exchange Student
    company: Kungliga Tekniska högskolan (KTH)
    company_url: 'https://www.kth.se/en'
    company_logo: org-KTH
    location: Stockholm, Sweden
    date_start: '2017-08-01'
    date_end: '2018-06-02'
    description: |2-
      Exchanged to the department of Comuter Science & Communication (CSC)
      * Travelling in Europe [[link]](https://sunprinces.github.io/photography/) 
      * Life murmur [[link]](https://sunprincelife.wordpress.com/)

  - title: Speech Research Intern
    company: Delta Research Center (DRC)
    company_url: 'https://www.deltaww.com/en-US/index'
    company_logo: org-Delta
    location: Taipei, Taiwan
    date_start: '2016-07-03'
    date_end: '2016-08-30'
    description: |2-
      * Researched on end-to-end speech recognition based on CTC
      * Reduced 3% CER on the corpus held by DRC, comparable to the original system
      * Migrated acoustic modeling to Tensorflow for faster development <br /> (building the interface between Kaldi & Tensorflow)
  - title: Undergraduate Student
    company: National Taiwan University (NTU)
    company_url: 'https://www.ntu.edu.tw/english/index.html'
    company_logo: org-NTU
    location: Taipei, Taiwan
    date_start: '2013-09-13'
    date_end: '2018-06-06'
    description: |2-
      * Undergraduate Researcher in Speech Processing & Machine Learning Lab
      * Proposed the hierarchical attention-based model for the TOEFL Listening Comprehension Test by machine
      * Researched on unsupervised audio embeddings
      * Teaching assistant of Machine Learning → [EE5184 designed assignment](https://sunprinces.github.io/ML-Assignment3/)


design:
  columns: '2'
---
