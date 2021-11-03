---
layout: page
title: Performance Analysis of GLRT-Based OFDM Demodulation System Over Random Block Dispersive Channel
description: Master Thesis (2)
img: 
importance: 2
---

:point_right: [Full Slides!](/assets/pdf/thesis_slides.pdf)

In this project, pilot-aided OFDM is integrated with SIMO antennas to enable reliable symbol decision based on the principle of generalized likelihood ratio test (GLRT) [[1]](#references) and the resultant system, which is dubbed GLRT-based SIMO-OFDM herein, is intended to provide prevailing error performance characteristics over **random block dispersive channels**, without the a priori knowledge of channel statistic.

We assumed all channel path coefficients are independent but not necessarily identically distributed. In this case, the [conditional BEP upper bound](https://lucyliao1997.github.io/projects/thesis1/) is averaged over the joint density of CIRs to yield the upper bound to the average BEP.

#### Average BEP Upper Bound

<div class="w-100 p-3" style="background-color: #FFF;">{% responsive_image path: assets/img/project_thesis2/BEPP.png title: "Average BEP upper bound" class: "img-fluid"%}</div>

#### Random Block Dispersive Channel

 When the communication time is relatively long in a low-to-medium mobility environment, the block dispersive channel is virtually random in the manner that multiple channel paths are fixed within one OFDM block but they exhibit short coherence times not shorter than the block time.


Here, the random block dispersive channel is modeled as the multipath Rician fading channel similar in [2].

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
    (1) Fourier power spectrums of random block dispersive channel channels
    (2) BEP characteristic with QPSK
    (3) BEP characteristic with 16-ary QAM
</div>

---
##### References
[1] [H. L. Van Trees, Detection, Estimation, and Modulation Theory. John Wiley & Sons, 1968.](https://www.wiley.com/en-us/Detection+Estimation+and+Modulation+Theory%2C+Part+I%3A+Detection%2C+Estimation%2C+and+Filtering+Theory%2C+2nd+Edition-p-9780470542965)

[2] [R.-Y. Yen, H.Liu and W.-K.Tsai, “QAM symbol error rate in OFDM systems over frequency-selective fast Rician-fading channels,” IEEE Trans. Veh. Technol., vol. 57, no. 2, pp. 1322-1325, Mar. 2008.](https://www.researchgate.net/publication/3156754_QAM_Symbol_Error_Rate_in_OFDM_Systems_Over_Frequency-Selective_Fast_Ricean-Fading_Channels)