---
layout: publication
title: "Building an enhanced vocabulary of the robot environment with a ceiling pointing camera"
date: 2016-04-07
publication_date: 2016-04-07
publication_media: "Sensors 2016, 16(4), 493"
publication_media_short: "Sensors"
publication_file: http://www.mdpi.com/1424-8220/16/4/493/htm
authors: "Alejandro Rituerto, Henrik Andreasson, Ana C. Murillo, Achim Lilienthal, J.J. Guerrero"
published: true
---

**Abstract:**
Mobile robots are of great help for automatic monitoring tasks in different environments. One of the first tasks that needs to be addressed when creating these kinds of robotic systems is modeling the robot environment. This work proposes a pipeline to build an enhanced visual model of a robot environment indoors. Vision based recognition approaches frequently use quantized feature spaces, commonly known as Bag of Words (BoW) or vocabulary representations. A drawback using standard BoW approaches is that semantic information is not considered as a criteria to create the visual words. To solve this challenging task this paper studies how to leverage the standard vocabulary construction process to obtain a more meaningful visual vocabulary of the robot work environment using image sequences. We take advantage of spatio-temporal constraints and prior knowledge about the position of the camera. The key contribution of our work is the definition of a new pipeline to create a model of the environment. This pipeline incorporates (1) tracking information to the process of vocabulary construction and (2) geometric cues to the appearance descriptors. Motivated by long term robotic applications, such as the aforementioned monitoring tasks, we focus on a configuration where the robot camera points to the ceiling, which captures more stable regions of the environment. The experimental validation shows how our vocabulary models the environment in more detail than standard vocabulary approaches, without loss of recognition performance. We show different robotic tasks that could benefit of the use of our visual vocabulary approach, such as place recognition or object discovery. For this validation, we use our publicly available data-set.

{% highlight bib %}
@article{rituerto2016building,
title={Building an enhanced vocabulary of the robot environment with a ceiling pointing camera},
author={Rituerto, Alejandro and Andreasson, Henrik and Murillo, Ana C and Lilienthal, Achim and Guerrero, José Jesús},
journal={Sensors},
volume={16},
number={4},
pages={493},
year={2016},
publisher={Multidisciplinary Digital Publishing Institute}
}
{% endhighlight %}
