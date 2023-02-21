---
# A section created with the Portfolio widget.
# This section displays content from `content/project/`.
# See https://wowchemy.com/docs/widget/portfolio/
widget: blank
active: true
# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 85

design:
  columns: '1'
  background:
    color: 'white'
  spacing: {padding: [50px, 0, 50px, 0]}
---
<!-- Google tag (gtag.js) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-C2THYYG4QP"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-C2THYYG4QP');
</script>

<section id="section-markdown" class="home-section wg-markdown">
  <div class="home-section-bg">
  </div>
  <div class="container">
    <div class="row justify-content-center">
      <!--<div class="section-heading col-12 mb-3 text-center">
        <h1 class="mb-0">Gallery</h1>
      </div> -->
      <div class="col-12">
        <div class="gallery-grid">
        <!-- first image, full -->
          <div class="gallery-item gallery-item--smalllogo">
            <a data-fancybox="gallery-demo" href = "https://www.utoronto.ca/" target="_blank">
            <img src="media/icons/University_of_Toronto-Logo.wine_2.svg" alt="The University of Toronto">
            </a>
          </div>
        <!-- second image, square -->
          <div class="gallery-item gallery-item--smalllogo">
            <a data-fancybox="gallery-demo" href = "https://csb.utoronto.ca/" target="_blank">
            <img src="media/csb_logo.jpeg" alt="Deparment of Cell & Systems Biology @ UofT">
            </a>
          </div>
        <!-- image, square -->
          <div class="gallery-item gallery-item--smalllogo">
            <a data-fancybox="gallery-demo" href = "https://biochemistry.utoronto.ca/" target="_blank">
            <img src="media/bch_logo.jpeg" alt="Department of Biochemistry @ UofT">
            </a>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>