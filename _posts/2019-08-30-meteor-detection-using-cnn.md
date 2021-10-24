---
layout: single
title:  "Meteor Detection Using Deep Convolutional Neural Networks"
# date:   2021-08-23 20:33:00 -0300
# categories: jekyll update

header:
  image: /assets/images/nasa5.jpg
#   og_image: /assets/images/page-header-og-image.png
  caption: "Photo credit: [**NASA**](https://nasa.com)"
#   actions:
#     - label: "Learn More"
#       url: "https://unsplash.com"

excerpt: This paper describes a construction of a deep convolutional neural network applied to a classification problem of detection meteors in a dark night sky.

author_profile: true
share: true
related: true

tags: paper
---
[Paper](https://proceedings.science/sbai-2019/papers/meteor-detection-using-deep-convolutional-neural-networks){: .btn .btn--success}

_Authors: Thiago César Marsola and Ana Carolina Lorena_

<!-- {% raw %}![alt]({{ site.url }}{{ site.baseurl }}/assets/images/nasa2.jpg){% endraw %} -->
This paper describes an application of a pre-trained Deep Convolutional Neural
Network to detect meteors from night sky images. The dataset is relatively small, composed
of labeled images of meteors and non-meteors from the night sky. Techniques like data
augmentation were used to create data artificially, and a dropout layer was introduced to prevent
overfitting at the training augmented dataset. The performance obtained by the methods using
traditional five-fold cross-validation along with changing of the images for black and white,
compared with the ones obtained using only the training and validation partitions and RGB
colors, achieved a higher mean accuracy of 84.35%.

<!-- <figure>
	<a href="/assets/images/crtbp.png"><img src="/assets/images/crtbp.png"></a>
	<figcaption><a href="" title="The Circular Restricted Three-Body Problem">The Circular Restricted Three-Body Problem</a>.</figcaption>
</figure> -->
<!-- {% include figure image_path="/assets/images/crtbp.png" alt="this is a placeholder image" caption="The Circular Restricted Three-Body Problem." %} -->
![image-center](/assets/images/meteor.png){: .align-center}
Example of a meteor image.
{: .text-center}