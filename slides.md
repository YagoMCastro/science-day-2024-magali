<!--
-------------------------------------------------------------------------------
This file defines the contents of each slide.
The reveal.js configuration can be found in index.html
-------------------------------------------------------------------------------
-->


<!-- .slide: class="slide-title" data-background-opacity="0.3" data-background-image="assets/magali-logo.svg" data-background-color="#000000" data-background-size="contain" -->

<!-- Place the content at the bottom of the slide -->
<div class="r-stretch">
</div>

<h1 id="talk-title">
  
  Magali: Modeling and inversion of magnetic microscopy data 🧲🔬

</h1>
<p id="talk-authors">
  <a id="talk-speaker">Yago M Castro</a>
</p>

<!-- Place location and date side-by-side with affiliation logos -->
<div class="row talk-info">
<div class="col-large">

<i class="fa fa-calendar-alt" style="margin: 0 10px 0 0"></i>
12 September 2024
<span style="margin: 0 20px"></span>
Science Day 2024 | IAG

<!-- Permission to reuse and CC-BY license logo -->
<i class="fa fa-camera" style="margin: 0 10px 0 0"></i>
Feel free to screenshot/share/reuse this presentation
<span style="margin: 0 20px"></span>
<a href="https://creativecommons.org/licenses/by/4.0/"><i class="fab fa-creative-commons"></i><i class="fab fa-creative-commons-by" style="margin: 0 10px 0 2px"></i>CC-BY 4.0 License</a>

</div>
<div class="col-medium">

<!-- Add logos here. Need these wrappers to align them to the bottom right -->
<div class="talk-logos-container">
<div class="talk-logos">
  <a href="https://www.compgeolab.org"><img src="assets/compgeolab-banner-light.svg" alt="Computer-Oriented Geoscience Lab"></a>
  <!-- <a href="https://www.iag.usp.br/"><img src="assets/iag.png" alt="Instituto de Astronomia, Geofísica e Ciências Atmosféricas"></a>
  <a href="https://www.usp.br/"><img src="assets/usp.png" alt="Universidade de São Paulo"></a> -->
</div>
</div>

</div>
</div>

===============================================================================

# Paleomagnetism


===============================================================================

<div class="r-stretch">

  <img src="assets/geomag.svg" height=100%>

</div>



===============================================================================

<div class="r-stretch">

  <img src="assets/sample.svg" height=100%>

</div>

===============================================================================

<div class="r-stretch">

  <img src="assets/microscope-sample.svg" height=100%>

</div>

<div class="footnote-center">

Souza-Junior (2024)

</div>

===============================================================================
<div class="r-stretch">

  <img src="assets/microscope.svg" height=100%>

</div>
<div class="footnote-center">

[Glenn et a. (2017)](https://doi.org/10.1002/2017gc006946)

</div>

===============================================================================


<!-- .slide: class="slide-title" data-background-opacity="1" data-background-image="assets/microscope-data.svg"  data-background-size="contain" -->

<div class="r-stretch">
</div>
<div class="footnote-left">

[Araujo et al. (2019)](https://doi.org/10.3390/s19071636)


</div>

===============================================================================

# Problems
<div class="fragment">

- No open software for forward **modeling** and **inversion** techniques specific to magnetic microscopy 

</div>

<div class="fragment text-left">

- Lack of **data conventions**  

</div>
<div class="fragment">

- No algorithms for **automatic** detection of magnetic **grains** and its **magnetic moment** determination

</div>



===============================================================================

<!-- .slide: data-background-opacity="1" data-background-image="assets/readme-banner.svg"  data-background-size="contain" data-background-color="#262626" -->

===============================================================================

<!-- .slide: data-background-opacity="0.2" data-background-image="assets/magali-logo.png"  data-background-size="contain" data-background-color="#262626" -->


<div class="huge">

Python library <i class="fab fa-python"></i>

</div>

===============================================================================
<!-- .slide: data-background-opacity="0.2" data-background-image="assets/magali-logo.png"  data-background-size="contain" data-background-color="#262626" -->


<div class="huge">

Modeling and processing magnetic microscopy data 
<br>
<i class="fas fa-magnet"></i> <i class="fas fa-microscope"></i>

</div>

===============================================================================
<!-- .slide: data-background-opacity="0.2" data-background-image="assets/magali-logo.png"  data-background-size="contain" data-background-color="#262626" -->


<div class="huge">

Free and open source 
<br>
<i class="fab fa-github"></i> <i class="fas fa-lock-open"></i>  <i class="fab fa-osi"></i>

</div>

===============================================================================


<!-- .slide: data-background-opacity="0.2" data-background-image="assets/magali-logo.png"  data-background-size="contain" data-background-color="#262626" -->

# Why do we want to make it?

<div class="fragment text-left">

- **Foundation** for new methods to conduct magnetic microscopy studies 

</div>
<div class="fragment text-left">

- **User friendly** code

</div>

<div class="fragment text-left">

- **Spatially** determine position of **several grains**

</div>
<div class="fragment text-left">

- Allow easy creation of **synthetic data**

</div>
<div class="fragment text-left">

- Propose **standard format** for data

</div>
<div class="fragment text-left">

- Leverage the potential of emerging **magnetic microscopy** studies

</div>

===============================================================================


<!-- .slide: data-background-opacity="0.2" data-background-image="assets/magali-logo.png"  data-background-size="contain" data-background-color="#262626" -->

<div class="r-stretch centered">
<div>

<i class="fas fa-comments"></i>
<br>
Contact:
<a>yagomcastro@gmail.com</a>

<i class="fab fa-github"></i>
<br>
Source code for this presentation:
<br>
[github.com/leouieda/talk-template](https://github.com/leouieda/talk-template)

<i class="fab fa-creative-commons"></i><i class="fab fa-creative-commons-by"></i>
<br>
Unless otherwise noted,
the contents of this presentation are
licensed under the
<br>
[Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).

</div>
</div>