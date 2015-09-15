---
layout: page
title: Discovery Informatics and Computing Laboratory
tagline: Indiana University School of Informatics, Indianapolis
---
{% include JB/setup %}

<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.4.0/css/font-awesome.min.css">

<div class="container">

    <div>
      <p class="lead">The Discovery Informatics and Computing Laboratory is under the direction of <a href="https://soic.iupui.edu/people/jake-chen/">Dr. Jake Chen</a> at Indiana University in Indianapolis.</p>
    </div>
    <div class="col-md-4">
        Meet the team <i class="fa fa-arrow-right"></i><a href="{{ BASE_PATH }}/members"><button type="button" class="btn btn-default"><i class="fa fa-users"></i></button></a>   
    </div>
    <div class="col-md-4">
        Software and applications from our lab <i class="fa fa-arrow-right"></i><a href="{{ BASE_PATH }}/resources"><button type="button" class="btn btn-default"><i class="fa fa-code"></i></button></a>
    </div>
    <div class="col-md-4">
    </div>

    <br><br>
    <hr>

  <div class="col-md-6 col-md-offset-3 col-xs-12">
    <h3 align="center">Posts</h3>
  </div>

  <div class="posts list-group col-md-6 col-md-offset-3 col-xs-12">
    {% for post in site.posts %}
      <a href="{{ BASE_PATH }}{{ post.url }}" class="list-group-item"><span>{{ post.date | date_to_string }}</span> &raquo; {{ post.title }}</a>
    {% endfor %}
  </div>



</div>