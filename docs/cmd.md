---
layout: docs
title: Command Line
prev_section: recorder
next_section: gui
permalink: /docs/cmd/
---

To execute slides (e.g., [helloworld.pptx](/pptx/helloworld.pptx)), type the following in the command line:

{% highlight bash %}
$ {{site.executable}} execute helloworld.pptx 
{% endhighlight %}

There are several command line options that can be set to control the execution behavior of Sikuli Slides.


<table>
  <thead>
    <tr>
      <th>Option</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><p><code>-minscore minscore_value</code></p></td>
      <td><p>The minimum similarity score for a target to be considered as a match. 
	It's a 10-point scale where 1 is the least precise search and 10 is the most precise search (default is 7).</p></td>
    </tr>
    <tr>
      <td><p><code>-screen screen_id</code></p></td>
      <td><p>The id of the connected screen/monitor (default is 0).</p></td>
    </tr>
    <tr>
      <td><p><code>-wait max_wait_time_ms</code></p></td>
      <td><p>The maximum time to wait in milliseconds to find a target on the screen ( 
                              default is 15000).</p></td>
    </tr>
  </tbody>
</table>