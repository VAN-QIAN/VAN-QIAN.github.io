---
title: ""
summary: ""
date: 2026-06-22
type: landing

sections:
  - block: resume-biography-3
    id: about
    content:
      username: me
      text: ""
      button:
        text: Download CV
        url: uploads/MAQian_Resume.pdf
      headings:
        about: Biography
        education: Education
        interests: Interests
    design:
      background:
        gradient_mesh:
          enable: true
      name:
        size: md
      avatar:
        size: medium
        shape: circle

  - block: markdown
    id: research
    content:
      title: Research
      subtitle: ""
      text: |-
        My current research focuses on multimodal learning and reasoning, vision-language models (VLMs), multimodal RAG, knowledge-based visual question answering (KB-VQA), and reliable foundation-model evaluation.

        I am interested in how foundation models ground non-textual structure, visual entities, and external knowledge. Before moving toward multimodal RAG and KB-VQA, I worked on graph learning, graph self-supervised learning, graph foundation models, spatio-temporal forecasting, time-series modeling, and urban computing.
    design:
      columns: "1"
      spacing:
        padding: ["3rem", 0, "3rem", 0]

  - block: markdown
    id: publications
    content:
      title: Publications
      subtitle: ""
      text: |-
        1. **Qian Ma**, S M Rayeed, Charles V. Stewart, Qiong Wu, Yao Ma. *Identifying and Resolving Pitfalls of Knowledge-Based VQA Benchmarks: Auditing, Repairing, and Augmenting.* ECCV 2026, to appear.
        2. **Qian Ma**, Qiong Wu, Zhengyi Zhou, Yao Ma. *Ground Then Rank: Revisiting Knowledge-Based VQA with Training-Free Entity Identification.* ACL 2026 Findings, to appear.
        3. **Qian Ma**, Haitao Mao, Jingzhe Liu, Zhehua Zhang, Chunlin Feng, Yu Song, Yihan Shao, Yao Ma. *Do Neural Scaling Laws Exist on Graph Self-Supervised Learning?* LoG 2024.
        4. **Qian Ma**, Hongliang Chi, Hengrui Zhang, Kay Liu, Zhiwei Zhang, Lu Cheng, Suhang Wang, Philip S. Yu, Yao Ma. *Overcoming Pitfalls in Graph Contrastive Learning Evaluation: Toward Comprehensive Benchmarks.* ACM SIGKDD Explorations, 2025.
        5. **Qian Ma**, Haitao Mao, Zhehua Zhang, Qiong Wu, Zhengyi Zhou, Yao Ma. *Cross-Domain GraphWalker: Harnessing LLMs for Graph Structure Learning.* Under review.
        6. **Qian Ma**, Zijian Zhang, Xiangyu Zhao, Haoliang Li, Hongwei Zhao, Yiqi Wang, Zitao Liu, Wanyu Wang. *Rethinking Sensors Modeling: Hierarchical Information Enhanced Traffic Forecasting.* CIKM 2023.
        7. Zijian Zhang, Xiangyu Zhao, Qidong Liu, Chunxu Zhang, **Qian Ma**, et al. *PromptST: Prompt-Enhanced Spatio-Temporal Multi-Attribute Prediction.* CIKM 2023.

        See my [Google Scholar profile](https://scholar.google.com/citations?user=hBic7eMAAAAJ) for updates.
    design:
      columns: "1"
      spacing:
        padding: ["3rem", 0, "3rem", 0]

  - block: markdown
    id: misc
    content:
      title: Misc
      subtitle: ""
      text: |-
        Conference notes, travel reflections, and small research-life updates will live here.
    design:
      columns: "1"
      spacing:
        padding: ["3rem", 0, "3rem", 0]

  - block: markdown
    id: gallery
    content:
      title: Gallery
      subtitle: ""
      text: |-
        A space for conference photos, posters, and snapshots from research travel.
    design:
      columns: "1"
      spacing:
        padding: ["3rem", 0, "3rem", 0]

  - block: contact-info
    id: contact
    content:
      title: Contact
      subtitle: ""
      visit_title: Affiliation
      connect_title: Connect
      username: me
      address:
        lines:
          - Department of Computer Science
          - Rensselaer Polytechnic Institute
          - Troy, NY, United States
      email: maq5@rpi.edu
      phone: "+1 518-308-3995"
      social:
        - icon: academicons/google-scholar
          url: https://scholar.google.com/citations?user=hBic7eMAAAAJ
        - icon: brands/github
          url: https://github.com/VAN-QIAN
        - icon: brands/linkedin
          url: https://www.linkedin.com/in/qian-ma-939269274/
        - icon: hb/cv
          url: uploads/MAQian_Resume.pdf
      show_form: false
    design:
      css_class: "bg-gray-50 dark:bg-gray-900"
      spacing:
        padding: ["3rem", 0, "3rem", 0]
---
