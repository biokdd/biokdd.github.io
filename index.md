---
layout: default-sanscontainer
title: Discovery Informatics and Computing Laboratory
tagline:
---
{% include JB/setup %}

<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.4.0/css/font-awesome.min.css">




<div class="container-fluid">
  <div class="page-lead" style="background-image:url({{ BASE_PATH }}/assets/images/gaus.jpg)">
    <!-- Image from http://www.wallpaperup.com/9263/Abstract_blurred.html -->
    <div class="wrap page-lead-content">
      <h1><strong>Discovery Informatics and Computing Laboratory</strong></h1>
      <h3>Indiana University School of Informatics and Computing</h3><br><br><br><br><br>
  <!--     <a href="//mmistakes.github.io/skinny-bones-jekyll/getting-started/"><button class="btn btn-primary btn-lg">Start Using Skinny Bones</button></a> &nbsp; or &nbsp; <a href="https://github.com/mmistakes/skinny-bones-jekyll" class="btn-inverse"><button class="btn btn-primary btn-lg">View on GitHub</button></a> -->
    </div><!-- /.page-lead-content -->
  </div><!-- /.page-lead -->
</div> <!--/.container-fluid-->

<div class="container">

    <div class="col-md-3">
      <h3><strong>About</strong></h3>
      <p>The Discovery Informatics and Computing Laboratory conducts bioinformatics research under the direction of <a href="https://soic.iupui.edu/people/jake-chen/">Dr. Jake Chen</a> at Indiana University School of Informatics and Computing in Indianapolis.</p>
    </div><!-- /.tile -->

    <div class="col-md-3">
      <h3><strong>Meet the Team</strong></h3>
      <p>Meet the team <i class="fa fa-arrow-right"></i><a href="{{ BASE_PATH }}/members"><button type="button" class="btn btn-default"><i class="fa fa-users"></i></button></a></p>
    </div><!-- /.tile -->

    <div class="col-md-3">
      <h3><strong>Resources</strong></h3>
      <p class="post-excerpt">Tools and data services from our lab <i class="fa fa-arrow-right"></i><a href="{{ BASE_PATH }}/resources"><button type="button" class="btn btn-default"><i class="fa fa-code"></i></button></a></p>
    </div><!-- /.tile -->

    <div class="col-md-3">
      <h3><strong>Research</strong></h3>
      <p>Research, projects, collaborations, publications</p>
    </div><!-- /.tile -->

    <br><br>
    <hr>

  <div class="col-xs-12">
    <h3 align="center">Posts</h3>
  </div>

  <div class="posts list-group col-md-6 col-md-offset-3 col-xs-12">
    {% for post in site.posts %}
      <a href="{{ BASE_PATH }}{{ post.url }}" class="list-group-item"><span>{{ post.date | date_to_string }}</span> &raquo; {{ post.title }}</a>
    {% endfor %}
  </div>



</div>