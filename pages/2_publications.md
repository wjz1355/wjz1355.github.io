---
layout: page
title: Publications
comments: true
permalink: /publications/

---

<style>
.biblist { }

/* The item */
.biblist li { }

/* You can define custom styles for plstyle field here. */


/*************************************
   The box that contain BibTeX code
 *************************************/
div.noshow { display: none; }
div.BibTeX {
  margin-right: 1%;
  margin-left: 3%;
  margin-top: 1.2em;
  margin-bottom: 1.3em;
  border: 1px solid silver;
  padding: 0.3em 0.5em;
  background: #eeeeee;
}
div.BibTeX pre { font-size: 85%; overflow: auto;  width: 100%; }
</style>

<script>
function toggleBibtex(articleid) {
  var bib = document.getElementById('bib_'+articleid);
  if (bib) {
    if(bib.className.indexOf('BibTeX') != -1) {
    bib.className.indexOf('noshow') == -1?bib.className = 'BibTeX noshow':bib.className = 'BibTeX';
    }
  } else {
    return;
  }
}
</script>

* **Wen-Jie Zheng**, Xi-Le Zhao*, Yu-Bang Zheng*, Zhi-Feng Pang, \"Nonlocal Patch-Based Fully-Connected Tensor Network Decomposition for Multispectral Image Inpainting\", _IEEE Geoscience and Remote Sensing Letters_, vol. 19, pp. 1-5, 2022, Art no. 8025105. <a href="javascript:toggleBibtex('GRSL2021_NLFCTN')" class="textlink">[BibTeX]</a> [[PDF]](https://wjz1355.github.io/papers/NL-FCTN-wjz.pdf) [[Code]](https://wjz1355.github.io/codes/code_NLFCTN.zip)

<div id="bib_GRSL2021_NLFCTN" class="BibTeX noshow">
<pre>
@ARTICLE{GRSL2021_NLFCTN,
  author={Zheng, Wen-Jie and Zhao, Xi-Le and Zheng, Yu-Bang and Pang, Zhi-Feng},
  journal={IEEE Geoscience and Remote Sensing Letters}, 
  title={Nonlocal Patch-Based Fully Connected Tensor Network Decomposition for Multispectral Image Inpainting}, 
  year={2022},
  volume={19},
  number={},
  pages={1-5}}
</pre>
</div>

---
