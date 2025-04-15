---
layout: archive
title: "CV (JSON Version)"
permalink: /cv-json/
author_profile: false
redirect_from:
  - /resume-json
---

{% include base_path %}

<!-- 样式文件导入 -->
<link rel="stylesheet" href="{{ base_path }}/assets/css/cv-style.css">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">

<!-- 响应式样式 -->
<style>
  .archive {
    width: 80%;
    margin: 0 auto;
    float: none;
    padding-right: 0;
  }

  @media (min-width: 80em) {
    .archive {
      width: 70%;
    }
  }
</style>

<!-- 插入 CV 模板 -->
{% include cv-template.html %}

<!-- 下载按钮区域 -->
<div class="cv-download-links" style="margin-top: 2em;">
  <a href="{{ base_path }}/files/cv.pdf" class="btn btn--primary">
    <i class="fas fa-file-pdf"></i> Download CV as PDF
  </a>
  <a href="{{ base_path }}/cv/" class="btn btn--inverse">
    <i class="fas fa-file-alt"></i> View Markdown CV
  </a>
</div>
