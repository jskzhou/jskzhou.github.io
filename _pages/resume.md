---
layout: resumé
permalink: /resumé/
title: resumé
nav: true
nav_order: 5
description: Current resumé
---

<style>
  .pdf-wrap { height: 85vh; border: 1px solid var(--global-border-color, #e5e7eb); }
  .pdf-fallback { padding: 0.75rem 0; }
</style>

<div class="pdf-wrap">
  <object
    data="{{ '/assets/files/Resume_Fall_2025.pdf#view=FitH' | relative_url }}"
    type="application/pdf"
    width="100%" height="100%">
    <iframe
      src="{{ '/assets/files/Resume_Fall_2025.pdf#view=FitH' | relative_url }}"
      width="100%" height="100%">
    </iframe>
  </object>
</div>

<p class="pdf-fallback">
  Can’t see the PDF? <a href="{{ '/assets/files/Resume_Fall_2025.pdf' | relative_url }}" download>Download the resumé</a>.
</p>