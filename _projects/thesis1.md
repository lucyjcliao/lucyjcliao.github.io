---
layout: page
title: Performance Analysis of GLRT-Based OFDM Demodulation System Over Fixed Block Dispersive Channel
description: Master Thesis (1)
img: 
importance: 1
---

:point_right: [Full Slides!](/assets/pdf/thesis_slides.pdf)

In this project, pilot-aided OFDM is integrated with SIMO antennas to enable reliable symbol decision based on the principle of generalized likelihood ratio test (GLRT) [[1]](#references) and the resultant system, which is dubbed GLRT-based SIMO-OFDM herein, is intended to provide prevailing error performance characteristics over **fixed block dispersive channels**, without the a priori knowledge of channel statistic.

#### Conditional BEP Upper Bound

<div class="w-75 p-3" style="background-color: #FFF;">{% responsive_image path: assets/img/project_thesis1/BEPP.png title: "Conditional BEP upper bound" class: "img-fluid"%}</div>

#### Fixed Block Dispersive Channel
When the communication time is very short in a stationary environment, the block dispersive channel is plausibly fixed only over a few blocks. A typical example is the short-packet uplink communication in the internet- of-things application [[2]](#references), where the few OFDM blocks contained in a packet experience fixed channel dispersion and require pilot-aided channel estimation to assist nearly coherent data decision within the same block.

Here, the fixed block dispersive channel is modeled as the exponential delay spread (EDS) [[3]](#references) channel.


#### Performance Results

<div class="container">
  <div class="row">
    <div class="col">
      {% responsive_image path: assets/img/project_thesis1/fig1.png title: "EDS channel" class: "img-fluid"%}
    </div>
    <div class="col">
      {% responsive_image path: assets/img/project_thesis1/fig2.png title: "BEP fig1" class: "img-fluid"%}
    </div>
    <div class="col">
      {% responsive_image path: assets/img/project_thesis1/fig3.png title: "BEP fig2" class: "img-fluid"%}
    </div>
  </div>
</div>
<div class="caption">
    (1)Fourier power spectrums of fixed block dispersive channel channels
    (2)BEP characteristic with QPSK
    (3)BEP characteristic with 16-ary QAM
</div>

---
##### References
[1] [H. L. Van Trees, Detection, Estimation, and Modulation Theory. John Wiley & Sons, 1968.](https://www.wiley.com/en-us/Detection+Estimation+and+Modulation+Theory%2C+Part+I%3A+Detection%2C+Estimation%2C+and+Filtering+Theory%2C+2nd+Edition-p-9780470542965)

[2] [H. Wang, Q. Yang, Z. Ding and H. V. Poor, “Secure short-packet communications for mission-critical IoT applications,” IEEE Trans. Wireless Commun., vol. 18, no. 5, pp. 2565–2578, Mar. 2019.](https://ieeexplore.ieee.org/document/8672179)

[3] [H. Arslan and T. Yucek, “Delay spread estimation for wireless communication systems,” in Proc. IEEE 8th Int. Symp. Comput. and Commun., pp. 282-287, Kemer-Antalya, Turkey, Jul. 2003.](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.1071.8614&rep=rep1&type=pdf)