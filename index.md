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

### Ads

- [Drupal Vietnam Group](http://groups.drupal.org/node/209718)
- [Drupal @ Linkhay](http://linkhay.com/course-xay-dung-website-bang-drupal-dau-tien-tai-viet-nam/684585)
- [Web Dev @ Linkhay](http://linkhay.com/khoa-hoc-tim-hieu-drupal-tai-sai-gon-drupal-dpvn/684584)

<style>
    .row .span12 {
        position: relative;
        min-height: 250px;
        background: url(/assets/themes/twitter/images/ninja.png) 100% 10px no-repeat;
    }
</style>
