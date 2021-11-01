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

* **Yu-Bang Zheng**, Ting-Zhu Huang, Xi-Le Zhao, Qibin Zhao, Tai-Xiang Jiang, "Fully-Connected Tensor Network Decomposition and Its Application to Higher-Order Tensor Completion", in _Proceedings of the AAAI Conference on Artificial Intelligence (AAAI 2021)_, vol. 35, no. 12, pp. 11071-11078, 2021. <a href="javascript:toggleBibtex('zhengFCTN2021')" class="textlink">[BibTeX]</a> [[PDF]](https://yubangzheng.github.io/papers/AAAI2021_FCTN_Decomposition_ybz.pdf) [[Material]](https://yubangzheng.github.io/papers/Supplementary_Material_FCTN_decomposition.pdf) [[Slide]](https://yubangzheng.github.io/papers/Slide_FCTN_decomposition.pdf) [[Poster]](https://yubangzheng.github.io/papers/Poster_FCTN_decomposition.pdf) [[Code]](https://yubangzheng.github.io/codes/code_FCTN_Decomposition.zip)

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



