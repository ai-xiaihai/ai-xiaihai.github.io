---
layout: post
title: "Multi-agent Simulation & Dynamic Ride-sharing (Summer Research 2017)"
date: 2017-07-31
excerpt: "With the mentorship of Prof. Adam Eck, I conducted to research to investigate the relationship between dynamic ride-sharing (e.g., Uber) and traffic congestion using multi-agent simulation (MATSim)."
tags: [research, oberlin]
comments: false
---

With the mentorship of <a href="http://www.cs.oberlin.edu/~aeck/">Prof. Adam Eck</a>, I conducted to research to investigate the relationship between dynamic ride-sharing (e.g., Uber) and traffic congestion using multi-agent simulation (<a href="https://matsim.org">MATSim</a>). I ran several simple simulations based on traffic and census data from Cleveland.

### Title
Impact of Real-time Ride-sharing Software on Traffic Congestion in Metropolitan Cleveland: Multi-agent Simulation Approach

### Abstract
The use of ride-sharing services for transportation have seen explosive growth in recent years due to the ease, popularity, and ubiquity of apps such as Uber and Lyft. Although the commonly held intuition is that dynamic ride-sharing alleviates traffic congestion, there are speculated reasons why ride-sharing might actually exacerbate congestion. For instance, additional travel demand (reduced public transportation usage) due to low cost and convenience of ride-sharing and increased de facto taxi supply can both lead to more traffic. We aim to investigate such theory through multi-agent simulation (MAS), where we can test different behaviors by individual drivers and passengers to better understand the impact of ride-sharing under different scenarios of human behavior. Our simulation leverages the popular multi-agent traffic simulation framework MATSim. We will include a case study of the city of Cleveland, Ohio by basing the simulation on Cleveland map, traffic, survey and census data. This study can provide a better understanding of fast-expanding dynamic ride-sharing, and potentially lead to traffic condition improvement.

### Poster
<figure>
	<a href="http://farm9.staticflickr.com/8426/7758832526_cc8f681e48_b.jpg"><img src="http://farm9.staticflickr.com/8426/7758832526_cc8f681e48_c.jpg"></a>
</figure>

### Mentor 
<a href="http://www.cs.oberlin.edu/~aeck/">Professor Adam Eck</a>

### Funding
<a href="https://www.oberlin.edu/undergraduate-research/our-fellowships/oberlin-college-research-fellowship">Oberlin College Research Fellowship</a>

### Alternative way

Another way to achieve the same result is to include `gallery` Liquid template. In this case you
don't have to write any HTML tags – just copy a small block of code, adjust the parameters (see below)
and fill the block with any number of links to images. You can mix relative and external links.

Here is the block you might want to use:

{% highlight liquid %}
{% raw %}
{% capture images %}
	http://vignette2.wikia.nocookie.net/naruto/images/9/97/Hinata.png
	http://vignette4.wikia.nocookie.net/naruto/images/7/79/Hinata_Part_II.png
	http://vignette1.wikia.nocookie.net/naruto/images/1/15/J%C5%ABho_S%C5%8Dshiken.png
{% endcapture %}
{% include gallery images=images caption="Test images" cols=3 %}
{% endraw %}
{% endhighlight %}

Parameters:

- `caption`: Sets the caption under the gallery (see `figcaption` HTML tag above);
- `cols`: Sets the number of columns of the gallery.
Available values: [1..3].

It will look something like this:

{% capture images %}
	http://vignette2.wikia.nocookie.net/naruto/images/9/97/Hinata.png
	http://vignette4.wikia.nocookie.net/naruto/images/7/79/Hinata_Part_II.png
	http://vignette1.wikia.nocookie.net/naruto/images/1/15/J%C5%ABho_S%C5%8Dshiken.png
{% endcapture %}
{% include gallery images=images caption="Test images" cols=3 %}
