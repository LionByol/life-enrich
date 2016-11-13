---
layout: page
title: NLP執行師證書課程
subtitle: NLP Practitioner Certification
keywords: NLP課程,NLP免費講座,free talk,NLP執行師,溝通技巧,身心語言程式學,人際關係,NLPU,NFNLP, ABNLP,SNLP,EQ,推銷能力,說服力,感染力,商業管理效能
description: 助你提升EQ,溝通技巧,人際關係,增加自信,說服力,感染力,商業管理效能,去除負面情緒。參加免費講座,了解更多!
navbar: NLP
comments: false
sharing: true
footer: true
lang: en
translation_id: 4d9f59d08e580006000ff7205d01f009
---

<ul class="nav nav-pills">
  <li class='active'><a data-toggle='pill' href="#intro">課程簡介</a></li>
  <li><a data-toggle='pill' href="#course-detail">課程內容</a></li>
  <li><a data-toggle='pill' href="#trainer">導師</a></li>
  <li><a data-toggle='pill' href="#certification">專業資格</a></li>
  <li><a data-toggle='pill' href="#testimonial">學員心聲</a></li>
  <li><a data-toggle='pill' href="#timetable">上課時間/學費</a></li>
  <li><a data-toggle='pill' href="#free-seminar">免費講座</a></li>
  <li><a data-toggle='pill' href="#enroll">報名</a></li>
</ul>

<div class="tab-content">
  <div id="intro" class="tab-pane fade in active">
    {% render_partial nlp/practitioner/_intro.markdown %}
  </div>
  <div id="course-detail" class="tab-pane fade">
    {% render_partial nlp/practitioner/_course_outline.markdown %}
    {% render_partial nlp/practitioner/_classroom.markdown %}
    {% render_partial nlp/practitioner/_why_choose_us.markdown %}
  </div>
  <div id="trainer" class="tab-pane fade">
    {% render_partial nlp/_trainer_bio.markdown %}
  </div>
  <div id="certification" class="tab-pane fade">
    {% render_partial nlp/practitioner/_certification.markdown %}
  </div>
  <div id="testimonial" class="tab-pane fade">
    {% render_partial nlp/practitioner/_testimonial.markdown %}
  </div>
  <div id="certification" class="tab-pane fade">
    {% render_partial nlp/practitioner/_certification.markdown %}
  </div>
  <div id="timetable" class="tab-pane fade">
    {% render_partial nlp/practitioner/_timetable.markdown %}
  </div>
  <div id="free-seminar" class="tab-pane fade">
    {% render_partial nlp/practitioner/_free_seminar.markdown %}
  </div>
  <div id="enroll" class="tab-pane fade">
    {% render_partial nlp/_payment_method.markdown %}
    {% render_partial nlp/practitioner/_download_form.markdown %}
  </div>
</div>


{% render_partial _download_form.markdown %}
