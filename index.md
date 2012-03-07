---
layout: page
title: Home
tagline: Drupal Training Service by Drupal forks from Vietnam
---
{% include JB/setup %}


### Announcement
<ul class="announcements">
    {% assign pages_list = site.posts %}
    {% assign group = 'Announcement' %}
    {% include JB/pages_list %}
</ul>

### Notes
<ul class="notes">
    {% assign pages_list = site.posts %}
    {% assign group = 'Notes' %}
    {% include JB/pages_list %}
</ul>


<style>
    .row .span12 {
        position: relative;
        min-height: 250px;
        background: url(/assets/themes/twitter/images/ninja.png) 100% 10px no-repeat;
    }
</style>
