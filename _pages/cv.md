---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

You can download my CV [here](https://davidwjang.github.io/files/David_Jang_CV.pdf){:target="_blank" rel="noopener"}.

<style>
/* Only resize the element if PDF is embedded */
.pdfobject-container {
   width: 450px;
   height: 400px;
}
</style>

<div id="my-pdf"></div>

<script src="{{ base_path }}/assets/js/pdfobject.js"></script>

<script>
  var options = {
     width: "40rem",
     height: "35rem",
     fallbackLink: false
  };
  PDFObject.embed("https://davidwjang.github.io/files/David_Jang_CV.pdf", "#my-pdf", options);
</script>



<!---
<embed src="{{ site.baseurl }}/files/David_Jang_CV.pdf" width="450" height="700" type='application/pdf'>
--->
