---
layout: default
title: search
date: 01/01/2014
author: marie
categories:
comments: false
---
<h2>Posts by tag</h2>

{% for atag in site.tags  %}
  <div id = "catlinks">
  <a href = "http://tmxoxo.github.io/blog/{{{atag | first}}" >{{{atag | first}}</a> <br>
  </div>
{% endfor %}


<script>
  (function() {
    var cx = '007344001035800283464:zwpj83rpmd0';
    var gcse = document.createElement('script');
    gcse.type = 'text/javascript';
    gcse.async = true;
    gcse.src = (document.location.protocol == 'https:' ? 'https:' : 'http:') +
        '//www.google.com/cse/cse.js?cx=' + cx;
    var s = document.getElementsByTagName('script')[0];
    s.parentNode.insertBefore(gcse, s);
  })();
</script>
<gcse:search></gcse:search>
