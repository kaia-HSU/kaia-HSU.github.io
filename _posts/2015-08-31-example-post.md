---
layout: blog
title: 'Sample post to check the functionality'
date: 2017-01-24 12:11:34
categories: blog
tags: code
image: '/images/default.jpg'
lead_text: 'Lorem ipsum dolor sit amet, consectetur adipisicing elit. Expedita maiores quisquam id sunt, a architecto molestias velit, distinctio quidem non, nostrum provident quibusdam enim. Neque ipsam temporibus commodi facere minima.'
---

Lorem ipsum dolor sit amet, consectetur adipisicing elit. Expedita maiores quisquam id sunt, a architecto molestias velit, distinctio quidem non, nostrum provident quibusdam enim. Neque ipsam temporibus commodi facere minima.

Lorem ipsum dolor sit amet, consectetur adipisicing elit. Expedita maiores quisquam id sunt, a architecto molestias velit, distinctio quidem non, nostrum provident quibusdam enim. Neque ipsam temporibus commodi facere minima.

Lorem ipsum dolor sit amet, consectetur adipisicing elit. Expedita maiores quisquam id sunt, a architecto molestias velit, distinctio quidem non, nostrum provident quibusdam enim. Neque ipsam temporibus commodi facere minima.

Lorem ipsum dolor sit amet, consectetur adipisicing elit. Expedita maiores quisquam id sunt, a architecto molestias velit, distinctio quidem non, nostrum provident quibusdam enim. Neque ipsam temporibus commodi facere minima.

Lorem ipsum dolor sit amet, consectetur adipisicing elit. Expedita maiores quisquam id sunt, a architecto molestias velit, distinctio quidem non, nostrum provident quibusdam enim. Neque ipsam temporibus commodi facere minima.

Lorem ipsum dolor sit amet, consectetur adipisicing elit. Expedita maiores quisquam id sunt, a architecto molestias velit, distinctio quidem non, nostrum provident quibusdam enim. Neque ipsam temporibus commodi facere minima.


<!-- 顯示留言區 -->
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
    s.src = 'https://kaia-hsu.disqus.com/embed.js';
    s.setAttribute('data-timestamp', +new Date());
    (d.head || d.body).appendChild(s);
    })();
</script>
<noscript>Please enable JavaScript to view the <a href="https://disqus.com/?ref_noscript">comments powered by Disqus.</a></noscript>


{% endif %}