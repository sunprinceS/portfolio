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
  - title: Software Engineer
    company: Google Inc.
    company_url: 'https://www.google.com/'
    company_logo: org-Google
    location: Taipei, Taiwan
    date_start: '2023-09-25'
    date_end: ''
    description: |2-
      * Building infrastructure to revolutionize software development life cycle.

      <a class="badge badge-light">System Design</a>
      <a class="badge badge-light">Clean Code</a>
      <a class="badge badge-light">ML</a>

  - title: Software Engineer
    company: Computing & Artificial Intelligence (CAI) Group, MediaTek
    company_url: 'https://www.mediatek.com/'
    company_logo: org-MediaTek
    location: Hsinchu, Taiwan
    date_start: '2022-01-03'
    date_end: '2023-08-31'
    description: |2-
      * Architect and contributor of the in-house compiler auto-optimization toolkit
      * Proposed, implemented, and maintained [Prefect-based](https://www.prefect.io/) distributed computing platform for heterogeneous devices (host, various generations of smartphone platforms)
      * Proposed algorithms for compiler auto-optimization, <br />boosted the inference speed in 20 [ETHZ AI-benchmark](https://ai-benchmark.com/) models (out of 38)
      * Inventor of 4 patents in compiler auto-optimization, efficient and scenario-aware network architecture search (NAS)
      * Improved customers AI-model efficiency on time and power via team-developed toolkit

      <a class="badge badge-light">Compiler Auto-Optimization</a>
      <a class="badge badge-light">System Design</a>
      <a class="badge badge-light">Clean Code</a>
      <a class="badge badge-light">Architecture Search</a>
      <a class="badge badge-light">Quantization-Aware</a>

  - title: Visual Document Intelligence Research Intern
    company: AI & RD Center, Microsoft
    company_url: 'https://www.microsoft.com/zh-tw/abouttaiwan/'
    company_logo: org-Microsoft
    location: Taipei, Taiwan
    date_start: '2018-10-06'
    date_end: '2021-03-31'
    description: |2-
        * Proposed and refactored model training to [Pytorch Lightning](https://lightning.ai/docs/pytorch/latest/) for faster development and easier maintenance
        * Migrated model training to the official AzureML training pipeline
        * Implemented unified multi-vertical document understanding model<br /> for variaous kinds of documents' named entity recognition (NER)

        <a class="badge badge-light">Multi-Task Learning</a>
        <a class="badge badge-light">CI/CD</a>
  - title: Graduate Student & Network Adminstrator
    company: Speech Processing & Machine Learning Lab, <br/>National Taiwan University (NTU)
    company_url: 'https://www.ntu.edu.tw/english/index.html'
    company_logo: org-NTU
    location: Taipei, Taiwan
    date_start: '2018-10-02'
    date_end: '2020-09-30'
    description: |2-
        As the **graduate student**

        * Graduate Researcher in Speech Processing & Machine Learning Lab, <br />
          supervised by Prof. [Hung-Yi Lee](https://speech.ee.ntu.edu.tw/~hylee/)
        * Researched on low-resource speech recognition and improved the system with gradient-based meta-learning and transfer learning algorithms
        * Lead TA of Deep Learning for Human Language
          Processing (Spring 2020) [[CommE5054]](https://speech.ee.ntu.edu.tw/~hylee/dlhlp/2020-spring.html)
        
        <br />

        As the **network adminstrator**

        * Managed a 10+ nodes, 20+ GPU [Slurm-based](https://slurm.schedmd.com/documentation.html) computing cluster
        * Incorporated [netdata](https://www.netdata.cloud/) to the workstation for real-time monitoring
        * Developed automatic health check to improve user/administrator experience
  - title: NLP Research Intern
    company: Apple Inc.
    company_url: 'https://www.apple.com/careers/us/machine-learning-and-ai.html'
    company_logo: org-Apple
    location: Cupertino, CA, USA
    date_start: '2018-06-26'
    date_end: '2018-09-30'
    description: |2-
      * Researched on generative modeling to develop algorithms enhancing user experience during keyboard usage
      * The research results have been incorporated in iOS 13 and published as [US patent](https://patents.google.com/patent/US20200379640A1/en?oq=US20200379640A1)

      <a class="badge badge-light">Generative Modeling</a>
      <a class="badge badge-light">Domain Adaptation</a>
      <a class="badge badge-light">Seq2Seq</a>
  - title: Exchange Student
    company: Kungliga Tekniska högskolan (KTH)
    company_url: 'https://www.kth.se/en'
    company_logo: org-KTH
    location: Stockholm, Sweden
    date_start: '2017-08-01'
    date_end: '2018-06-02'
    description: |2-
      Exchanged to the department of Comuter Science & Communication (CSC)
      * Collections of journeys in Europe [[link]](outdoor-activities/world-travelling) 
      * Life whisper [[link]](https://sunprincelife.wordpress.com/)
      * Travelling gallery [[link]](https://sunprinces.github.io/photography/)

  - title: Speech Research Intern
    company: Delta Research Center (DRC)
    company_url: 'https://www.deltaww.com/en-US/index'
    company_logo: org-Delta
    location: Taipei, Taiwan
    date_start: '2016-07-03'
    date_end: '2016-08-30'
    description: |2-
      * Proposed and built the interface between Kaldi & Tensorflow, <br />migrating acoustic modeling part to Tensorflow for faster development
      * Researched on end-to-end speech recognition based on alignment-free algorithm (CTC)
      * Reduced 3% CER on the corpus held by DRC, comparable to the original system

      <a class="badge badge-light">ASR</a>
      <a class="badge badge-light">Seq2Seq</a>
  - title: Undergraduate Student
    company: National Taiwan University (NTU)
    company_url: 'https://www.ntu.edu.tw/english/index.html'
    company_logo: org-NTU
    location: Taipei, Taiwan
    date_start: '2013-09-13'
    date_end: '2018-06-06'
    description: |2-
      * Undergraduate Researcher in Speech Processing & Machine Learning Lab
      * Proposed hierarchical attention-based model for TOEFL Listening Comprehension Test by machine
      * Researched on self-supervised audio embeddings
      * TA of Machine Learning → [EE5184 designed assignment](https://sunprinces.github.io/ML-Assignment3/)


design:
  columns: '2'
---
