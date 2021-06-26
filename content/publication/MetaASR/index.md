---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Meta Learning for End-to-End Low-Resource Speech Recognition"
authors:
- Jui-Yang Hsu
- Yuan-Jui Chen
- Hung-Yi Lee
date: 2020-05-04T14:01:37+08:00
doi: "10.1109/ICASSP40776.2020.9053112"

# Schedule page publish date (NOT publication's date).
publishDate: 2021-06-26T14:01:37+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "45th International Conference on Acoustics, Speech, and Signal Processing, 2020"
publication_short: "ICASSP 2020"

abstract: "In this paper, we proposed to apply meta learning approach for low-resource automatic speech recognition (ASR). We formulated ASR for different languages as different tasks, and meta-learned the initialization parameters from many pretraining languages to achieve fast adaptation on unseen target language, via recently proposed model-agnostic meta learning algorithm (MAML). We evaluated the proposed approach using six languages as pretraining tasks and four languages as target tasks. Preliminary results showed that the proposed method, MetaASR, significantly outperforms the state-of-the-art multitask pretraining approach on all target languages with different combinations of pretraining languages. In addition, since MAML's model-agnostic property, this paper also opens new research direction of applying meta learning to more speech-related applications."

# Summary. An optional shortened abstract.
summary: ""

tags: ["Meta-Learning", "ASR", "Multilingual", "Seq2Seq"]
categories: ["Speech"]
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://arxiv.org/abs/1910.12094
url_code: https://github.com/sunprinceS/MetaASR-CrossAccent
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video: https://youtu.be/goav0eXKPwg

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
