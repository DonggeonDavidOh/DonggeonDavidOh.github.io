<!-- ---
layout: cv
permalink: /cv/
title: cv
nav: true
nav_order: 2
cv_pdf: CV_Donggeon_Oh_251022.pdf # you can also use external links here
description: Please click the PDF icon to open or download my most up-to-date CV.
toc:
  sidebar: left
--- -->
---
layout: page
permalink: /cv/
title: CV
nav: true
nav_order: 2
description: Curriculum Vitae
---

<!-- Top buttons -->
<p>
  <a class="btn btn-sm z-depth-0" href="{{ '/CV_Donggeon_Oh_251022.pdf' | relative_url }}" target="_blank" rel="noopener">Open in new tab</a>
  <a class="btn btn-sm z-depth-0" href="{{ '/CV_Donggeon_Oh_251022.pdf' | relative_url }}" download>Download PDF</a>
</p>

<!-- Inline PDF preview (no SCSS; styled inline) -->
<div style="position:relative;width:100%;height:100vh;border:1px solid #e5e5e5;border-radius:12px;overflow:hidden;">
  <object
    data="{{ '/assets/pdf/CV_Donggeon_Oh_251022.pdf#view=FitH' | relative_url }}"
    type="application/pdf"
    width="100%"
    height="100%">
    <!-- Fallback for browsers that don't render <object> -->
    <iframe
      src="{{ '/assets/pdf/CV_Donggeon_Oh_251022.pdf#view=FitH' | relative_url }}"
      width="100%"
      height="100%"
      style="border:0;">
    </iframe>
  </object>
</div>
