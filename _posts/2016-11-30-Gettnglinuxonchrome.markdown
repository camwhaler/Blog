---
layout: page
title: 'Emulators on chromebooks [Tutorial]'
published: true
---
In this tutorial I will provide instructions on how to get linux (or rather access it) on your chromebook and get acess to various linux programs such as emulators, which is what I will be focusing on in this tutorial.

<div class="alert alert-dismissible alert-warning">
  <button type="button" class="close" data-dismiss="alert">&times;</button>
  <h4>Warning!</h4>
  <p>This tutorial involves enabling developer mode on your chromebook and modifying key part of the chromebook's software. Software may crash and other issues could occur. Make a <a href="https://support.google.com/chromebook/answer/6002417?hl=en" class="btn btn-link">recovery flash drive</a>if you want a way to recover your chromebook software if something goes wrong (even though it's unlikely). Also be aware that you may be violating the "chromebook agreement" if the chromebook it's yours. As long you disable developer mode before you return it there shouldn't be any issues.<a href="#" class="alert-link">Continue at your own risk. I am not responsible for your actions.</a></p>
</div>
<h1>Enabling devloper mode and installing linux</h1>

<div class="alert alert-dismissible alert-warning">
  <button type="button" class="close" data-dismiss="alert">&times;</button>
  <h4>Note</h4>
  <p>If your chromebook doesn't have an intel sticker on it, don't bother with this tutorial. Your chromebook isn't powerful enough. (If you have a lenovo chromebook you should be good).<a href="#" class="alert-link"></a></p>
</div>

To make this simpler for me, go [here](http://www.howtogeek.com/162120/how-to-install-ubuntu-linux-on-your-chromebook-with-crouton/){: target="_blank"} and follow step one to get into developer mode. Follow step two to the where they want you to copy and paste a command in the shell (the black page with white text). Insted of using their command use mine insted: 
{% highlight bash %}
sudo sh ~/Downloads/crouton -r trusty -t gnome
{% endhighlight %}
Also insted of typing sudo startxfce4, type this insted:
{% highlight bash %}
sudo startgnome
{% endhighlight %}
You will have to run this command upon every reboot.
If you press the wrong keys while switching desktops you may end up on a screen that looks like this: ![Gatok Jekyll Theme](http://yoosee.net/d/objects/2012/12/img2012122700204-chromedevconsole.jpg) just press Ctrl+Alt+Back.
