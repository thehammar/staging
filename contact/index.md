---
title: "News &#038; Events"
subtitle: "Contact me today!"
robots: none
---
## Reach out. I am here for you.  

page.title: {{ page.title }}
page.title.slugified: {{ page.title | slugify }}

page.url:  {{ page.url }}  
page.path:  {{ page.path }}  
page.id:  {{ page.id }}  
page.handle: {{ page.handle }}  
page.content  {{ page.content }}

site.pages {{ site.pages }}  
site.posts {{ site.posts }}
site.static_files:  {{ site.static_files }}  
site.html_pages:  {{ site.html_pages }}  

If you have general questions, please submit the form below. I will respond quickly with an answer.  

{% include {{ page.d.inc }}/contact-form.html %}

All questions, comment or requests submitted on this page go directly to my iPhone!
Of course, if you need me right away give me a call!  

{% include {{ page.d.inc }}/contact-info.md %}
