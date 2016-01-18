---
layout: post
title:  "ECC without BIOS setting"
date:   2016-01-xx 00:00:00 +0100
categories: posts 
tags: ecc memory linux
---
/etc/modprobe.d/amd64_edac_mod.conf

{% highlight %}
options amd64_edac_mod ecc_enable_override=1
{% endhighlight %}

