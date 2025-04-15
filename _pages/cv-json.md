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
<div class="resume-section" style="max-width: 700px; margin: 4rem auto; text-align: center;">
  <h2 style="font-size: 2.2rem; font-weight: bold; margin-bottom: 1rem;">📄 Resume</h2>
  <p style="font-size: 1.1rem; color: #555;">You can view or download my CV using the buttons below:</p>

  <div style="margin-top: 2rem; display: flex; justify-content: center; gap: 1rem;">
    <a href="/files/cv.pdf" class="btn btn--primary" style="padding: 0.8rem 1.5rem; font-size: 1rem;">⬇️ Download PDF</a>
    <a href="/cv/" class="btn btn--outline" style="padding: 0.8rem 1.5rem; font-size: 1rem;">🧾 View Online Version</a>
  </div>
</div>

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
