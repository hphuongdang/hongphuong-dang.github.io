---
layout: page
title: Project 1
description: IBP-DL
img: /assets/img/12.jpg
---
<strong>Non-parametric Bayesian approaches and dictionary learning for inverse problems in image processing</strong>

<div class="Toolbox">
    <h4 id="version-publique-">Toolbox:</h4>
    <p>
    Toolbox IBP-DL in Matlab is available 
    <a href="{{ site.baseurl }}/assets/code/IBP-DL-Matlab.zip">here</a>.
    </p>
    <p>
    Toolbox IBP-DL in C is available 
    <a href="{{ site.baseurl }}/assets/code/IBP-DL-CodeC.zip">here</a>.
    </p>
</div>

Dictionary learning for sparse representation has been widely advocated for solving inverse problems. Optimization methods and parametric approaches towards dictionary learning have been particularly explored. These methods meet some limitations, particularly related to the choice of parameters. In general, the dictionary size is fixed in advance, and sparsity or noise level may also be needed.

By defining prior distributions on functional spaces, nonparametrics models avoid the often painful selection of model complexity. In a parametric model, we have a finite number of parameters, and in nonparametric models, the number of parameters is (potentially) infinite. This indicates that the dimension of the unknown parameters is also a random variable. Nonparametric does not mean that they have no parameters.

Nonparametric models exhibit good adaptivity properties which make possible to overcome a model selection step. Thus, the complexity of the model increases dynamically with the richness of the data. By using nonparametric Bayesian approaches in dictionary learning, we can consider that the size of the dictionary is potentially infinite but a prior is introduced to favor the sparsity of the representation. The dictionary and coefficients are then leanrned jointly.



<div id="exemple">

                <video width="320" height="320" id="ve1">
                    <source src="{{ site.baseurl }}/assets/video/mandrillDico80.mp4">
                </video>

                <video width="320" id="ve2">

                    Image reconstruite
                    <source src="{{ site.baseurl }}/assets/video/mandrillOut80.mp4">

                    Image reconstruite
                </video>

                <br>
                <button onclick="document.getElementById('ve1').play();document.getElementById('ve2').play();">
                Play</button>

                <button onclick="document.getElementById('ve1').pause();document.getElementById('ve2').pause();">
                Pause</button>

                <br>
                <video width="320" height="320" id="ve3">
                    <source src="{{ site.baseurl }}/assets/video/fgDico50.mp4">

                    Dictionnaire
                </video>

                <video width="320" id="ve4">
                    <source src="{{ site.baseurl }}/assets/video/fgOut50.mp4">

                    Image reconstruite
                </video>

                <br>
                <button onclick="document.getElementById('ve3').play();document.getElementById('ve4').play();">
                Play</button>

                <button onclick="document.getElementById('ve3').pause();document.getElementById('ve4').pause();">
                Pause</button>

                <br>
                <video width="320" height="320" id="ve5">
                    <source src="{{ site.baseurl }}/assets/video/manDico20.mp4">

                    Dictionnaire
                </video>

                <video width="320" id="ve6">
                    <source src="{{ site.baseurl }}/assets/video/manOut20.mp4">

                    Image reconstruite
                </video>

                <br>
                <button onclick="document.getElementById('ve5').play();document.getElementById('ve6').play();">
                Play</button>

                <button onclick="document.getElementById('ve5').pause();document.getElementById('ve6').pause();">
                Pause</button>

            </div>




