jquery.w8n
==========

jQuery plugin that imitates the windows 8 notifications


Use
---
<pre><code>// Display a simple notification
$('#btnSample1').click(function(){
  $.w8n('Default notification', 'Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod.');
});

// Display a notification a set the tiemout to 1000ms
$('#btnSample2').click(function(){
  $.w8n('Timeout set to 1000', 'Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod.',
    {timeout: 1000});
});

// Display a stickynotification
$('#btnSample3').click(function(){
  $.w8n('Sticky notification', 'Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod.', 
    {timeout: 0});
});   
</code></pre>

Options
-------
* timeout (added in version 0.0.1): Number of milliseconds that the notification will be visible. For sticky notifications use 0. [default value is 1000]

Tested browsers
---------------
* Google Chrome 31.0.1650.57 m
* Internet Explorer 10.0.9200.16736

Demo
----
Someday... :-)

Version
-------
0.0.1 (Release date: 2013/11/22)
* Display notification in one color (lime).
* You can set the title and the message of the notifiacation.
* You can configure the time that the notification will be visitble.
* You can display sticky notifications (set timeout to 0)
* You can hide (destroy) the notification clicking in it.

In future
---------
