---
layout: post
title: "How to completely delete a software on OSX"
date:   2015-12-16 09:00:00 +0100
categories: osx
---

First, remove the *.app file in the Applications directory as usual. This will remove the app from the computer. However, some files related to the freshly deleted app remains. Check the following repertories and delete the relevant files in there:

{% highlight bash %}
Library/Application Support
Library/Caches/
Library/Preferences/
Library/Saved Application Sate/
Library/LaunchAgents
Library/LaunchDaemons
Library/Logs
{% endhighlight %}