---
layout: docs
title: Commands
prev_section: usage
next_section: usage
permalink: /docs/commands/
---

## Basic Mouse/Keyboard Operations

	{% assign docid = '1mWe81kAkt7kWe0tBSt_VvRUXPCtdWUFhSF_yq4jH2xE' %}
	{% assign name = 'Click' %}
	{% assign description = 'Execute a mouse left click action on the target marked by the rectangle.' %}		
	{% include actions.html %}
	
	{% assign docid = '1rCvCfqRe3ke7jv2qDkNxLS2Yi79doG1t08Pzkr1OB3k' %}
	{% assign name = 'Double Click' %}
	{% assign description = 'Execute a mouse double left click action on the target marked by the rectangle.' %}		
	{% include actions.html %}


	{% assign docid = '1WGhC9ycp4Yd61W071YJMjGOoGAq3y5ChP6xn7Z2N8E8' %}
	{% assign name = 'Right Click' %}
	{% assign description = 'Execute a mouse right click action on the target marked by the rectangle.' %}		
	{% include actions.html %}


	{% assign docid = '1OHEfMB8ehcaw4GclYyCHHufcZRV3G4Wz-6MlynkJQvI' %}
	{% assign name = 'Type' %}
	{% assign description = 'Type in the target marked by the rectangle. The content to type is inside the rectangle.' %}
	{% include actions.html %}
	
	{% assign docid = '11F7ldEw8jOUZwDPiAtYxADCHc-WUch_Z-K-iKpv2ywk' %}
	{% assign name = 'Drag and Drop' %}
	{% assign description = 'Drag the target in one rectangle to the area in another rectangle.' %}
	{% include actions.html %}		

## Other Actions

	{% assign docid = '1-3SuDlrJB86sVo0lg1QP4R53n0j1qcx-qxikBjVq-YI' %}
	{% assign name = 'Caption' %}
	{% assign description = 'Display caption text on the screen in a rectangle in yellow background.' %}
	{% include actions.html %}
	
	{% assign docid = '10Oa1jp3j8pO016V-bWz6jQ2Ppfn_DRLvx7SvNb2Rc4M' %}
	{% assign name = 'Browser' %}
	{% assign description = 'Open the default web browser and load the URL written inside the shape.' %}
	{% include actions.html %}
	
	{% assign docid = '1Bfud47ZtFQQCOEvaBNUkaXvHT4G-7V6rNvcQM2EvvwI' %}
	{% assign name = 'Delay' %}
	{% assign description = 'Delay the execution by some amount of time. In this example, the execution of slide 3 is delayed by 10 seconds. The delay time unit can be in microseconds, milliseconds, seconds, minutes, hours, or even days.' %}
	{% include actions.html %}


	{% assign docid = '18euvQySosDfnS9wO2LLmKWRf_QvvIW248cMvBi5VxaY' %}
	{% assign name = 'Exist' %}
	{% assign description = 'Check if the target marked by the rectangle exists. If not, the execution is aborted.' %}
	{% include actions.html %}
	
	{% assign docid = '1EgzhcaX4aq-Z8TCdWFbKxgePvEos0h2Lsxf7xENE7bE' %}
	{% assign name = 'Not Exist' %}
	{% assign description = 'Check if the target marked by the rectangle does not exist. If it exists, the execution is aborted.' %}
	{% include actions.html %}