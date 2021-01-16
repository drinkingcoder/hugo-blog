---
title: "Prior Guided Dropout for Robust Visual Localization in Dynamic Environments"
authors:
- Zhaoyang Huang
- Yan Xu
- Jianping Shi
- Xiaowei Zhou
- Hujun Bao
- Guofeng Zhang
date: "2019-11-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2019-11-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *ICCV2019*
publication_short: ICCV2019

# abstract: Camera localization from monocular images has been a long-standing problem, but its robustness in dynamic environments is still not adequately addressed. Compared with classic geometric approaches, modern CNN-based methods (e.g. PoseNet) have manifested the reliability against illumination or viewpoint variations, but they still have the following limitations. First, foreground moving objects are not explicitly handled, which results in poor performance and instability in dynamic environments. Second, the output for each image is a point estimate without uncertainty quantification. In this paper, we propose a framework which can be generally applied to existing CNN-based pose regressors to improve their robustness in dynamic environments. The key idea is a prior guided dropout module coupled with a self-attention module which can guide CNNs to ignore foreground objects during both training and inference. Additionally, the dropout module enables the pose regressor to output multiple hypotheses from which the uncertainty of pose estimates can be quantified and leveraged in the following uncertainty-aware pose graph optimization to improve the robustness further. We achieve an average accuracy of 9.98m/3.63◦ on RobotCar dataset, which outperforms the state-of-the-art method by 62.97%/47.08%. The source code of our implementation is available at https://github.com/zju3dv/RVL-Dynamic.
# Summary. An optional shortened abstract.
summary: ---

tags:
- Visual Localization
- PoseNet
featured: true

links:
#- name: Custom Link
#  url: http://example.org
url_pdf: http://openaccess.thecvf.com/content_ICCV_2019/html/Huang_Prior_Guided_Dropout_for_Robust_Visual_Localization_in_Dynamic_Environments_ICCV_2019_paper.html
url_code: 'https://github.com/zju3dv/RVL-Dynamic'
#url_dataset: '#'
url_poster: 'poster/ICCV2019-Poster.pdf'
#url_project: ''
#url_slides: ''
#url_source: '#'
#url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: Smart
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects:
#- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---

<!--{{% alert note %}}-->
<!--Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.-->
<!--{{% /alert %}}-->

<!--{{% alert note %}}-->
<!--Click the *Slides* button above to demo Academic's Markdown slides feature.-->
<!--{{% /alert %}}-->

<!--Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/).-->

