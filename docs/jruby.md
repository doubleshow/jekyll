---
layout: docs
title: JRuby
prev_section: api
next_section: code
permalink: /docs/jruby/
---

You can execute Sikuli Slides using JRuby. The *helloworld* program only takes two lines:

*helloworld.rb*
{% highlight ruby %}
require 'sikuli-slides'
Sikuli::Slides.execute "helloworld.pptx"
{% endhighlight %}

You must first install [JRuby](http://jruby.org/download) and [RubyGems](http://rubygems.org/) on your system. Then, you can do the following to install Sikuli Slides and run the *helloworld* program.

1. Install the Sikuli Slides Gem. It will download and install everything you need.   
    {% highlight bash %}
$ jruby -S gem install sikuli-slides
{% endhighlight %}
    
2. Tell JRuby to run in the 1.9 mode
    {% highlight bash %}
$ export JRUBY_OPTS=--1.9
{% endhighlight %}

3. Run *helloworld.rb*
	{% highlight bash %}
$ jruby helloworld.rb
{% endhighlight %}


## More Examples

hellouser.pptx

<img src="/img/hellouser.jpg" class="one-third polaroid">

{% highlight bash %}
["Adam","Ben","Cindy"].each do |name|
  Sikuli::Slides.execute "hellouser.pptx", :params => {:user => name}
end
{% endhighlight %}

