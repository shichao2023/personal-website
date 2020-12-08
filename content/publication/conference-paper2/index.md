---
title: "Towards Class Imbalance in Federated Learning"
authors:
- Wang Lixu
- Shichao Xu
- Wang Xiao
- Qi Zhu
date: "2020-08-14T00:00:00"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-08-14T00:00:00"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In Proceedings of the AAAI Conference on Artificial Intelligence
publication_short: In AAAI

abstract: "Federated learning (FL) is a promising approach for training decentralized data located on local client devices while improving efficiency and privacy. However, the distribution and quantity of the training data on the clients' side may lead to significant challenges such as data imbalance and non-IID (non-independent and identically distributed) data, which could greatly impact the performance of the common model. While much effort has been devoted to helping FL models converge when encountering non-IID data, the imbalance issue has not been sufficiently addressed. In particular, as FL training is executed by exchanging gradients in an encrypted form, the training data is not completely observable to either clients or server, and previous methods for data imbalance do not perform well for FL. Therefore, it is crucial to design new methods for detecting data imbalance in FL and mitigating its impact. In this work, we propose a monitoring scheme that can infer the composition proportion of training data for each FL round, and design a new loss function -- Ratio Loss to mitigate the impact of the imbalance. Our experiments demonstrate the importance of detecting data imbalance and taking measures as early as possible in FL training, and the effectiveness of our method in mitigating the impact. Our method is shown to significantly outperform previous methods, while maintaining client privacy."

# Summary. An optional shortened abstract.
summary:

tags:
- Source Themes
featured: true

links:
url_pdf: '#' #https://arxiv.org/pdf/2008.06217.pdf
url_code: '#'
url_poster: '#'
url_slides: '#'
url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#  focal_point: ""
#  preview_only: false

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


{{% alert note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /alert %}}
