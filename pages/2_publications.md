---
layout: page
title: Publications
comments: true
permalink: /publications/

---

* content
{:toc}




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

* **Wen-Jie Zheng**, Xi-Le Zhao, Yu-Bang Zheng, Zhi-Feng Pang, \"Nonlocal Patch-Based Fully-Connected Tensor Network Decomposition for Multispectral Image Inpainting\", _IEEE Geoscience and Remote Sensing Letters_, **accepted**, doi: 10.1109/LGRS.2021.3124804, 2021. <a href="javascript:toggleBibtex('GRSL2021_NLFCTN')" class="textlink">[BibTeX]</a> [[PDF]](https://yubangzheng.github.io/papers/NL-FCTN-wjz.pdf)

<div id="bib_GRSL2021_NLFCTN" class="BibTeX noshow">
<pre>
@article{GRSL2021_NLFCTN,
  title = {Nonlocal Patch-Based Fully-Connected Tensor Network Decomposition for Multispectral Image Inpainting},
  journal = {IEEE Geoscience and Remote Sensing Letters},
  volume = { },
  pages = { },
  year = {2021},
  author = {Wen-Jie Zheng and Xi-Le Zhao and Yu-Bang Zheng and Zhi-Feng Pang},
  note = {doi: 10.1109/LGRS.2021.3124804},
  month={},
}
</pre>
</div>

<div id="bib_zhengFCTN2021" class="BibTeX noshow">
<pre>
@inproceedings{zhengFCTN2021,
  title={Fully-Connected Tensor Network Decomposition and Its Application to Higher-Order Tensor Completion}, 
  author={Zheng, Yu-Bang and Huang, Ting-Zhu and Zhao, Xi-Le and Zhao, Qibin and Jiang, Tai-Xiang}, 
  booktitle={Proceedings of the AAAI Conference on Artificial Intelligence},
  volume={35},
  number={12},
  pages={11071-11078},
  year={2021},  
}
</pre>
</div>



