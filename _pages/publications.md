---
title: "Publications"
layout: gridlay
sitemap: false
permalink: /publications/
---

<style>
.jumbotron{
    padding:3%;
    padding-bottom:10px;
    padding-top:10px;
    margin-top:10px;
    margin-bottom:30px;
}
</style>

<div class="jumbotron">
### Published articles
{% bibliography --query @article %}
</div>

<div class="jumbotron">
### Preprints
{% bibliography --query @unpublished %}
</div>
