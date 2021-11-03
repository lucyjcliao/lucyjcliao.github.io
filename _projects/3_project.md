---
layout: page
title: Viterbi Decoder for Convolutional Code
description: ECC Final Assigment
img: 
importance: 3
---
In this project, we consider a $(2,1,4)$ convolutional code with generator sequences $(2,3)_8$ and $(3,5)_8$ in octal form respectively. Use the Viterbi algorithm to obtain its BER performance over the AWGN.

#### Average BEP Upper Bound

<div class="w-75 p-3" style="background-color: #FFF;">{% responsive_image path: assets/img/project_thesis2/BEPP.png title: "Average BEP upper bound" class: "img-fluid"%}</div>

#### Performance Results

<div class="container">
  <div class="row">
    <div class="col">
      {% responsive_image path: assets/img/project_thesis2/fig7.png title: "Rician channel" class: "img-fluid"%}
    </div>
    <div class="col">
      {% responsive_image path: assets/img/project_thesis2/fig8.png title: "BEP fig3" class: "img-fluid"%}
    </div>
    <div class="col">
      {% responsive_image path: assets/img/project_thesis2/fig9.png title: "BEP fig4" class: "img-fluid"%}
    </div>
  </div>
</div>
<div class="caption">
    (1)Fourier power spectrums of random block dispersive channel channels
    (2)BEP characteristic with QPSK
    (3)BEP characteristic with 16-ary QAM
</div>