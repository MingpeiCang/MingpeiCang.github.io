---
title: ""
date: 2022-10-24
type: landing

design:
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      username: admin
      text: ""
      button:
        text: 下载简历
        url: uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: markdown
    content:
      title: '📚 我的研究'
      subtitle: ''
      text: |-
        我是香港科技大学智能制造方向博士研究生，师从崔华辰博士和 Michael Yu Wang 教授，研究高精度面投影光固化（Projection SLA）与力学超材料。

        我的研究主要关注：
        1. 通过工艺优化实现高分辨率 SLA；
        2. 开发 SLA 实时原位监测系统；
        3. 设计高性能点阵力学超材料结构。

        欢迎制造科学、机械设计、计算建模方向的研究者和工程师交流合作。
    design:
      columns: '1'
  - block: collection
    id: projects
    content:
      title: 项目
      filters:
        folders:
          - project
    design:
      view: article-grid
      columns: 3
  - block: collection
    id: talks
    content:
      title: 近期与即将进行的报告
      filters:
        folders:
          - event
    design:
      view: article-grid
      columns: 2
  - block: collection
    id: papers
    content:
      title: 近期论文
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
---
