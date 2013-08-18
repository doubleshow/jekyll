---
layout: page
title: Download
permalink: /download/
---

## Latest - 1.4.0

<table>
  <thead>
    <tr>
      <th>Name</th>
      <th>Usage</th>
      <th>Download</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><p>Sikuli Executable Jar</p></td>
	  <td><p>
		Run Sikuli Slides as a command-line program
		</p>
	   </td>
	      <td>
	<a href="/sikuli-slides-1.4.0.jar" class="download"
		onClick="_gaq.push(['_trackEvent', 'Downloads', 'Download', 'sikuli-slides-1.4.0.jar'])">
		sikuli-slides-1.4.0.jar
	</a>
		  </td>	
    </tr>
    <tr>
      <td><p>Sikuli Slides API</p></td>
	  <td><p>
		Use Sikuli Slides' functionalities in your own Java projects</p>
	   </td>
	      <td>
			<a href="/sikuli-slides-api-1.4.0.jar" class="download"
			onClick="_gaq.push(['_trackEvent', 'Downloads', 'Download', 'sikuli-slides-api-1.4.0.jar'])">
			sikuli-slides-api-1.4.0.jar
			</a>

		  </td>	
    </tr>
  </tbody>
</table>

### Requirements
* **Windows and Mac OS X**: Java Runtime Environment (JRE) version 1.6 or newer.
* **Linux**: Oracle Java Runtime Environment (JRE) version 1.7.

### Release Notes
* Sikuli Slides Java API
* Recorder.
* Code Generator.
* Control tags: `Skip`, `Optional`, `Bookmark`, and `Tag`.

---

## Older Versions

### 1.3.0

<a href="/downloads/sikuli-slides-1.3.0.jar" class="btn btn-large btn-primary"
onClick="_gaq.push(['_trackEvent', 'Downloads', 'Download', 'sikuli-slides-1.3.0.jar'])">
Download sikuli-slides-1.3.0.jar
</a>

Release Notes:
* New GUI.
* Three running modes: automation, help, and tutorial mode.
* Execute remote presentation slides. This includes the ability to execute Google Presentation stored in your Google Drive (formerly known as Google Docs), and .pptx files in DropBox.
* Added multiple monitors support.
* New delay action. The wait time unit can be in microseconds, milliseconds, seconds, minutes, hours, or even days. This can be used to make delay interval between two slides.
* Store user settings persistently in user preferences.
* Play .wav audio files.
* Display Caption/Label on the screen using any shape in a yellow background.
* Added Linux 32 and 64 bit support.
* Many bug fixes.

### 1.2.0

<a href="/downloads/sikuli-slides-1.2.0.jar" class="btn btn-large btn-primary"
onClick="_gaq.push(['_trackEvent', 'Downloads', 'Download', 'sikuli-slides-1.2.0.jar'])">
Download sikuli-slides-1.2.0.jar
</a>

Release Notes:
 * New syntax: Use any shape as a target image and text box as an input action. You can specify the user input action in a separate text box and the target images using any shape, so there is no need to memorize the meaning of each shape. This makes sikuli-slides more easy and customizable so users can customize the meaning of each shape.
 * Add multiple targets per slide support but with one input action per slide. For example, you can perform left click action on multiple targets in one slide.
 * Set the order of performing input actions. If you have multiple targets on the screen, you can specify the order in which the action is executed by inserting the numeric order into the shape.
 * Sound support: Play sound while running your visual automation. This allows you to add more informative and interactive experience for your automation as well as to test voice recognition applications.
 * Text annotation: Display an overlay text on the screen. This can be an effective way to display informative text on the screen.
 * Add new visual testing operations that can be used to know whether something is visible on the screen or not.
 * Exist: check whether the target image is visible on the screen.
 * Not Exist: check whether the target image is invisible on the screen.

### 1.1.0
<a href="/downloads/sikuli-slides-1.1.0.jar" class="btn btn-large btn-primary"
onClick="_gaq.push(['_trackEvent', 'Downloads', 'Download', 'sikuli-slides-1.1.0.jar'])">
Download sikuli-slides-1.1.0.jar
</a>

Release Notes:
 * Detect identical targets on the screen: added new algorithm that uniquely identifies a target among identical targets on the screen such as checkboxes, radio buttons, etc.
 * Added double click action using frame shape.
 * Bug fixes.