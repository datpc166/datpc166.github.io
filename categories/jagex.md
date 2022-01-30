---
layout: page
title: Jagex
permalink: /blog/categories/jagex/
---

<h5> Other Jagex related work: </h5>

<div class="row">
	{% for post in site.categories.jagex %}
        <div class="card blog-post" style="border-radius: 50px">
            <a href="{{ post.url | prepend: site.baseurl }}" data-disqus-identifier="{{ post.url }}" style="padding: 0px">
                <img class="card-img-top" src="{{site.url}}{{site.baseurl}}{{ post.thumbnail }}" alt="{{ post.title }}" style="border-radius: 30px">
            </a>
            <div class="card-body center">
                <a href="{{ post.url | prepend: site.baseurl }}" data-disqus-identifier="{{ post.url }}" style="padding: 0px">
                    <h4 class="card-title">{{ post.title }}</h4>
                </a>
                <h6 class="card-subtitle mb-2" style="{{post.color}}; text-align: center; border-radius: 50px 0px; margin: 5px">{{ post.type }}</h6>
                <hr>
                <h6 class="card-subtitle mb-2 text-muted">{{ post.date | date: "%b %-d, %Y" }}</h6>
                <p class="card-text">{{ post.summary }} </p>
                <div class="post-categories" style="vertical-align:bottom; text-align:center">
                    {% if post %} {% assign categories = post.categories %} {% else %} {%
                    assign categories = page.categories %} {% endif %} {% for
                    category in categories %}
                    <a href="{{site.baseurl}}/blog/categories/{{category|slugize}}" class="btn btn-col" style="font-size: 13px; padding: .02rem .5rem; display:inline">{{category | capitalize}}</a>
                    {% unless forloop.last %}&nbsp;{% endunless %} {% endfor %}
                </div>
            </div>
        </div>
	{% endfor %}
</div>

