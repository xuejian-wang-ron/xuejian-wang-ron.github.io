---
layout: cv
permalink: /cv/
title: cv
nav: true
nav_order: 5
cv_pdf: cv_july_29.pdf # you can also use external links here
description: This is a description of the page. You can modify it in '_pages/cv.md'. You can also change or remove the top pdf download button.
toc:
  sidebar: left
---

<!-- PDF嵌入显示 -->
<div class="pdf-container mt-4">
  <iframe 
    src="{{ page.cv_pdf | prepend: 'cv/' | relative_url }}#toolbar=1&navpanes=1&scrollbar=1" 
    width="100%" 
    height="800px" 
    style="border: 1px solid #ddd; border-radius: 8px;"
    title="CV PDF Viewer">
    <p>您的浏览器不支持PDF查看。请 <a href="{{ page.cv_pdf | prepend: 'cv/' | relative_url }}" target="_blank">点击这里下载PDF</a>。</p>
  </iframe>
</div>
