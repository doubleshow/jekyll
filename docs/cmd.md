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

## Executing Remote Files

If the file is hosted on a remote web server, you can execute it by supplying the URL to that remote file as an argument. Sikuli Slides will try to download the file for you and executing it. For instance, suppose helloworld.pptx is hosted at the URL  [http://silides.sikuli.org/helloworld.pptx](http://silides.sikuli.org/helloworld.pptx), you can execute this remote file as follows:

{% highlight bash %}
$ {{site.executable}} execute http://slides.sikuli.org/helloworld.pptx 
{% endhighlight %}

If the file is a Google Presentation hosted on Google Drive, you can execute it by supplying its public sharing link. Make sure you have already set the file's sharing setting as "Anyone who has the link can **view**". This enables Sikuli Slides to download the file for you.

{% highlight bash %}
$ {{site.executable}} execute https://docs.google.com/presentation/d/1w48gExh5oLIT0J8xYXR1RxpqTrZTXJC8OR4UXxShTQ8/edit?usp=sharing
{% endhighlight %}


## Options

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
      <td><p><code>-minscore score</code></p></td>
      <td><p>The minimum similarity score for a target to be considered as a match. 
	It's a 10-point scale where 1 is the least precise search and 10 is the most precise search (default is 7).</p></td>
    </tr>
    <tr>
      <td><p><code>-screen id</code></p></td>
      <td><p>The id of the connected screen/monitor (default is 0).</p></td>
    </tr>
    <tr>
      <td><p><code>-wait time</code></p></td>
      <td><p>The maximum time to wait in milliseconds to find a target on the screen ( 
                              default is 5000).</p></td>
    </tr>
  </tbody>
</table>