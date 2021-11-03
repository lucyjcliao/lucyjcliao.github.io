---
layout: page
title: Power Allocation of GLRT-Based OFDM Demodulation System
description: Master Thesis (3)
img: 
importance: 3
---

:point_right: [Full Slides!](/assets/pdf/thesis_slides.pdf)

The BEP characteristic of the SIMO GLRT receiver depends strongly on the power allocation to pilot symbols. When the larger pilot power is allocated, the better pilot-aided channel estimation is achieved and this entails the better BEP performance even for a fixed received bit DNR. Because the BEP performance improves with an increasing data power as well, there exists an optimum DPR $$\varphi^{(opt)}$$ when the total power allocated to the entire OFDM block is fixed.

In this project, I adopted curve fitting method [[1]](#references) to quickly obtained the optimum data-to-pilot power ratio (DPR) $$\varphi^{(opt)}$$ for both conditional BEP upper bound and average BEP upper bound.

#### Polynomial Functions

<div class="w-100 p-3" style="background-color: #fff;">
{% responsive_image path: assets/img/project_thesis3/table1.png title: "Rician channel" class: "img-fluid"%}
</div>
<div class="w-100 p-3" style="background-color: #fff;">
{% responsive_image path: assets/img/project_thesis3/table2.png title: "Rician channel" class: "img-fluid"%}
</div>
<div class="caption">
    (1) Polynomial function over fixed block dispersive channel
    (2) Polynomial function over i.n.i.d. random block dispersive channel
</div>


---
##### References
[1] [J. H. Mathews and K. K. Fink, Numerical Methods Using Matlab, 4th ed. Prentice Hall, 2004.](https://d1wqtxts1xzle7.cloudfront.net/61513423/dokumen.tips_numerical-methods-using-matlab-4ed-solution-manual20191214-91078-13xt4iv-with-cover-page-v2.pdf?Expires=1635916320&Signature=Huj5R~44NSxRGBlHNPM~sd3kpzUwRjf~UszpPgfLDarQrvCwo0JVp59xYlugSySJ0AOlyT8gOog5nvq9xMxJitkpwLdjwgkIdNPhR8xXXjkxjvFvlp4XUVAN0m2lm6og3boqrJ8EWG6NhwJdLym1hcuO1~586mrpMZqmMtbnjqeuY4KAYe96Z~Lwj7zvbTZLI9yhKqHMbOYt-kQXTzCrkK-oCv-XYZdcaVQq4EzaeYLdsvqf0fbHpG5Exs8GCjJ0pCKRDmg-VBn1UmAhgIE~JIby2djLLOHVSXnX--cLpCCr~WpAsPkARAXk3syQeCOnp5PDVThdu4ZW5JC6WgSLtA__&Key-Pair-Id=APKAJLOHF5GGSLRBV4ZA)