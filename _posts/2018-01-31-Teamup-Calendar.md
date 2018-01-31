---
layout:     post
title:      Using Teamup Calendar
author:     Eric Miller
tags: 		post
subtitle:  	Using the Teamup calendar, as used in QEA

project:	guides
permalink:	/guides/teamup

published: 	true
---
<!-- Start Writing Below in Markdown -->

<p><iframe src="https://teamup.com/ksibd8hjseukqomw2y?view=w&amp;showHeader=0&amp;showSidepanel=0" width="100%" height="500"></iframe></p>
<p><span style="font-size: 10pt;"><a href="https://teamup.com/ks9qxcm91eqa3668wi">[edit]</a></span></p>
<h2>Subscribing to the calendar</h2>
<p>You are not required to subscribe to the QEA calendar, but doing so allows it to appear next to your personal calendar in Outlook or Google Calendar. We hope this makes it possible to "notice" when office hours are happening without having to explicitly check. This is an experiment.</p>
<p>Follow the instructions <span style="text-decoration: underline;"><span style="color: #0000ff;"><a style="color: #0000ff; text-decoration: underline;" href="https://calendar.teamup.com/kb/subscribe-teamup-calendar-feed-from-other-calendars/">here</a></span></span> (for Google Calendar or Outlook).</p>
<p>The "feed URL" should come from the table below:</p>
<table border="1">
<tbody>
<tr>
<td>All Events</td>
<td>webcal://ics.teamup.com/feed/ks9qxcm91eqa3668wi/0.ics</td>
</tr>
<tr>
<td>All Office Hours</td>
<td>webcal://ics.teamup.com/feed/kszaak9dm7r3rdg1fn/0.ics</td>
</tr>
<tr>
<td>Class periods only</td>
<td>webcal://ics.teamup.com/feed/ks9qxcm91eqa3668wi/3735226.ics</td>
</tr>
<tr>
<td>Professor Hours Only</td>
<td>webcal://ics.teamup.com/feed/ks9qxcm91eqa3668wi/3735220.ics</td>
</tr>
<tr>
<td>NINJA Hours Only</td>
<td>webcal://ics.teamup.com/feed/ks9qxcm91eqa3668wi/3735192.ics</td>
</tr>
</tbody>
</table>
<p>&nbsp;</p>
<h2>Setting up Teamup for another organization</h2>
<p>Using Teamup calendar is an experiment, if it goes well, other organizations (classes, clubs, teams, etc.) are welcome to try as well. This page documents various tips used in setting it up for QEA that might be useful.</p>
<h3>Embedding</h3>
<p>Teamup allows for customized embedding through URL manipulation and iframes. The code used on this site is...</p>
<p><span style="background-color: #999999;">&lt;iframe src="https://teamup.com/ksibd8hjseukqomw2y?view=w&amp;amp;showHeader=0&amp;amp;showSidepanel=0" width="100%" height="500"&gt;&lt;/iframe&gt;</span></p>
<p>This code sets the calendar to a 6-day view, hides the header, and hides the side panel, making it more suited for embedding. Full doucmentation about available embed codes is available at&nbsp;<a href="https://calendar.teamup.com/kb/calendar-link-parameters/">https://calendar.teamup.com/kb/calendar-link-parameters/</a></p>
<p>Note that the ID used here is for read-only access to the calendar.</p>
<h3>Generating subscribe links</h3>
<p>Single-tag subscription links are easy. For a link that allows subscription to multiple calendars (NINJA hours + Professor hours), use the "Sharing" tab in settings to make a new view-only link with access to those calendars, then using that link, get the webcal subscription feed from there.</p>
