---
layout: page
permalink: /resume/
title: resume
nav: true
nav_order: 4
description: Current resume
---

<!-- PDF Embed using Object tag (more reliable than iframe) -->
<div class="pdf-container" style="width: 100%; height: 800px; border: 1px solid #ccc; margin: 20px 0;">
  <object data="/assets/pdf/Resume_JasonZhou.pdf" 
          type="application/pdf" 
          width="100%" 
          height="100%">
    <!-- Fallback iframe if object doesn't work -->
    <iframe src="/assets/pdf/Resume_JasonZhou.pdf" 
            width="100%" 
            height="100%" 
            style="border: none;">
      <!-- Final fallback if neither works -->
      <p>Your browser does not support PDFs. 
         <a href="/assets/pdf/Resume_JasonZhou.pdf" target="_blank">Download the PDF</a> to view it.
      </p>
    </iframe>
  </object>
</div>

<!-- Alternative: Google Drive PDF Viewer (uncomment if above doesn't work) -->
<!-- 
<div class="pdf-container" style="width: 100%; height: 800px; border: 1px solid #ccc; margin: 20px 0;">
  <iframe src="https://docs.google.com/viewer?url=https://jskzhou.github.io/assets/pdf/Resume_JasonZhou.pdf&embedded=true" 
          width="100%" 
          height="100%" 
          style="border: none;">
  </iframe>
</div>
-->

<!-- Download button -->
<div class="pdf-download" style="text-align: center; margin: 20px 0;">
  <a href="/assets/pdf/Resume_JasonZhou.pdf" 
     class="btn btn-primary" 
     target="_blank" 
     download="Jason_Zhou_Resume.pdf">
    📄 Download Resume (PDF)
  </a>
</div>

<!-- Debug: Direct link to test PDF accessibility -->
<div style="text-align: center; margin: 10px 0; font-size: 0.9em; color: #666;">
  <a href="/assets/pdf/Resume_JasonZhou.pdf" target="_blank">Direct PDF Link (for testing)</a>
</div>
