---
permalink: /
author_profile: true
title: "About me"
excerpt: "About me"
redirect_from: 
  - /about/
  - /about.html
---
<hr>
I am a 2nd year master student in Cognitive Science Program at [Seoul National University][1], advised by [Prof. Byoung-Tak Zhang][2]. My research interests mainly span in computer vision and natural lanauage processing, and machine learning. I'm particularly interested in machine learning and its application in building agents that can see everyday scenes and fluently communicate with people. <br>
Prior to joining graduate school, I received my Bachelor's degree in software and computer science from [Ajou University][3]. 
<br>

## Recent News
<div class="update content-container">
  {% for news in site.data.news %}
  <p class="content-item news news-{{ forloop.index0 }}">
    <span style="color:#ff7272"><b>NEW!</b></span>
    <span id="date">{{ news.date }}</span>
    {{ news.content }}
  </p>
  {% endfor %}
  <p class="content-item showMore">
    <span id="more" onclick="showMore()">More</span>
<span id="noMoreContext" style="display:none;color: #cccccc;"><br>No more news available.</span>
  </p>
</div>

## Publications
<table align="center" style="border-collapse: collapse; border: none;" >
    <!-- Dual Attention Networks -->
    <tr style="border: none;">
        <td align="center" style="border: none;"><img src="https://github.com/gicheonkang/gicheonkang.github.io/blob/master/images/DAN-19.png?raw=true" alt="Photo" width="300" height="150" /></td>
        <td style="border: none;"></td>
        <td align="left" style="border: none;"><b><span style="font-size: 17px;">Dual Attention Networks for Visual Reference Resolution in Visual Dialog</span></b><br>
          <span style="font-size:15px;"><u>Gi-Cheon Kang</u>, Jaeseo Lim, and Byoung-Tak Zhang</span><br>
          <span style="font-size:15px;"><i>EMNLP 2019 (long) </i></span><br>
          <span style="font-size:15px;"><a class="btn btn--info" href="https://arxiv.org/abs/1902.09368"> Paper </a></span></td>
    </tr>
    <!-- CBAN -->
    <tr style="border: none;">
        <td style="border: none;" colspan="3"><hr style="border: dashed 1px #8c8b8b;"></td>
    </tr>
    <!-- Contextualized Bilinear Attention Networks -->
    <tr style="border: none;">
        <td align="center" style="border: none;"><img src="https://github.com/gicheonkang/gicheonkang.github.io/blob/master/images/CBAN-18.png?raw=true" alt="Photo" width="300" height="150" /></td>
        <td style="border: none;"></td>
        <td align="left" style="border: none;"><b><span style="font-size: 17px;">Contextualized Bilinear Attention Networks</span></b><br>
          <span style="font-size:15px;"><u>Gi-Cheon Kang</u>, Seonil Son, and Byoung-Tak Zhang </span><br>
          <span style="font-size:15px;"><i>ECCV Workshop on VizWiz Challenge</i>, 2018</span><br>
          <span style="font-size:15px;"><a class="btn btn--info" href="https://bi.snu.ac.kr/Publications/Conferences/International/ECCV2018_Workshop_VizWiz_GCKang.pdf"> Paper </a></span>
          <!--<font size="3"><a class="btn" href="https://github.com/gicheonkang/gicheonkang.github.io/blob/master/files/ECCV2018-poster-gckang.pdf"> Poster </a> </font>--></td> 
    </tr>
</table>

<style>
  @media screen and (max-width: 750px) {
  table thead {
    border: none;
    clip: rect(0 0 0 0);
    height: 1px;
    margin: -1px;
    overflow: hidden;
    padding: 0;
    position: absolute;
    width: 1px;
  }
  
  table tr {
    border-bottom: 3px solid #ddd;
    display: block;
  }
  
  table td {
    border-bottom: 1px solid #ddd;
    display: block;
    text-align: left;
  }
  
  table td::before {
    content: attr(data-label);
    float: left;
  }
}
</style>

---
[1]: http://en.snu.ac.kr
[2]: https://bi.snu.ac.kr/~btzhang/
[3]: http://www.ajou.ac.kr/en/
[4]: http://vizwiz.org/workshop/
[5]: https://visualqa.org/workshop.html
[6]: https://visualdialog.org/challenge/2019
[7]: https://arxiv.org/abs/1902.09368
[8]: https://www.emnlp-ijcnlp2019.org/



