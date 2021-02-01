---
layout: blog
title: '使用Github Pages架設技術網站'
date: 2021-01-26
categories: blog
tags: code
image: 'https://www.bbc.com/staticarchive/57aaecf7e633cdfe10d8f6c303f911a142f7da57.jpg'

---

Lorem ipsum dolor sit amet, consectetur adipisicing elit. Expedita maiores quisquam id sunt, a architecto molestias velit, distinctio quidem non, nostrum provident quibusdam enim. Neque ipsam temporibus commodi facere minima.

# 教學

{% if site.comments %}

<div id="disqus_thread"></div>
<script>
    /**
    *  RECOMMENDED CONFIGURATION VARIABLES: EDIT AND UNCOMMENT THE SECTION BELOW TO INSERT DYNAMIC VALUES FROM YOUR PLATFORM OR CMS.
    *  LEARN WHY DEFINING THESE VARIABLES IS IMPORTANT: https://disqus.com/admin/universalcode/#configuration-variables    */
    /*
    var disqus_config = function () {
    this.page.url = PAGE_URL;  // Replace PAGE_URL with your page's canonical URL variable
    this.page.identifier = PAGE_IDENTIFIER; // Replace PAGE_IDENTIFIER with your page's unique identifier variable
    };
    */
    (function() { // DON'T EDIT BELOW THIS LINE
    var d = document, s = d.createElement('script');
    s.src = 'https://kaiachun.disqus.com/embed.js';
    s.setAttribute('data-timestamp', +new Date());
    (d.head || d.body).appendChild(s);
    })();
</script>
<noscript>Please enable JavaScript to view the <a href="https://disqus.com/?ref_noscript">comments powered by Disqus.</a></noscript>

{% endif %}
