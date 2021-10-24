---
layout: single
title:  "Dynamics Analysis and Control of the Malkus-Lorenz Waterwheel with Parametric Errors"
# date:   2021-08-23 20:33:00 -0300
# categories: jekyll update

header:
  image: /assets/images/nasa4.jpg
#   og_image: /assets/images/page-header-og-image.png
  caption: "Photo credit: [**NASA**](https://nasa.com)"
#   actions:
#     - label: "Learn More"
#       url: "https://unsplash.com"

excerpt: This paper presents a dynamical analysis of a Malkus-Lorenz taking into account your chaotic behavior, and a control strategy to taking the system into a periodic orbit, with parametric errors.

author_profile: true
share: true
related: true

tags: paper
---
[Paper](https://link.springer.com/chapter/10.1007/978-981-13-9463-8_2){: .btn .btn--success}

_Authors: Thiago César Marsola, Mateus Pereira, Mauricio Ribeirao, Wagner Lenz, Angelo Tusset, and José Manoel Balthazar_

<!-- {% raw %}![alt]({{ site.url }}{{ site.baseurl }}/assets/images/nasa2.jpg){% endraw %} -->
This work presents a dynamical analysis for the Malkus-Lorenz waterwheel, a physical system that behaves following the Lorenz equations. With this, two types of controllers were designed to control the system presenting chaotic behavior. The first controller is the time-delay feedback control (TDFC), and the second one is the State-Dependent Riccati Equation control (SDRE). The control strategy for the SDRE control involves the application of two signals: a nonlinear feedforward signal to maintain the controlled system in a periodic orbit, and a feedback signal, to take the system trajectory into the desired periodic orbit. Numerical simulations demonstrated the effectiveness of the control strategy in taking the system presenting chaotic behavior into a desired periodic orbit. In addition, the SDRE control robustness is investigated analyzing parametric errors in control loop.

<!-- <figure>
	<a href="/assets/images/crtbp.png"><img src="/assets/images/crtbp.png"></a>
	<figcaption><a href="" title="The Circular Restricted Three-Body Problem">The Circular Restricted Three-Body Problem</a>.</figcaption>
</figure> -->
<!-- {% include figure image_path="/assets/images/crtbp.png" alt="this is a placeholder image" caption="The Circular Restricted Three-Body Problem." %} -->
![image-center](/assets/images/chaos-waterwheel.png){: .align-center}
a Displacement in time  x1 . b Displacement in time   x2 . c Displacement in time   x3 . d Phase Diagram (  x1  vs.   x2  vs.   x3 ).
{: .text-center}