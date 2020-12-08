---
title: "Opportunistic Intermittent Control with Safety Guarantees for Autonomous Systems"
authors:
- Wang Lixu
- Shichao Xu
- Wang Xiao
- Qi Zhu
date: "2020-11-01T00:00:00"
doi: "10.1145/3408308.3427617"

# Schedule page publish date (NOT publication's date).
publishDate: "2020-11-01T00:00:00"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In Proceedings of the 7th ACM International Conference on Systems for Energy-Efficient Buildings, Cities, and Transportation
publication_short: In BuildSys

abstract: "The design of building heating, ventilation, and air conditioning (HVAC) system is critically important, as it accounts for around half of building energy consumption and directly affects occupant comfort, productivity, and health. Traditional HVAC control methods are typically based on creating explicit physical models for building thermal dynamics, which often require significant effort to develop and are difficult to achieve sufficient accuracy and efficiency for runtime building control and scalability for field implementations. Recently, deep reinforcement learning (DRL) has emerged as a promising data-driven method that provides good control performance without analyzing physical models at runtime. However, a major challenge to DRL (and many other data-driven learning methods) is the long training time it takes to reach the desired performance. In this work, we present a novel transfer learning based approach to overcome this challenge. Our approach can effectively transfer a DRL-based HVAC controller trained for the source building to a controller for the target building with minimal effort and improved performance, by decomposing the design of neural network controller into a transferable front-end network that captures building-agnostic behavior and a back-end network that can be efficiently trained for each specific building. We conducted experiments on a variety of transfer scenarios between buildings with different sizes, numbers of thermal zones, materials and layouts, air conditioner types, and ambient weather conditions. The experimental results demonstrated the effectiveness of our approach in significantly reducing the training time, energy cost, and temperature violations."

# Summary. An optional shortened abstract.
summary:

tags:
- Source Themes
featured: true

links:
url_pdf: '#' #https://arxiv.org/pdf/2008.03625.pdf
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
