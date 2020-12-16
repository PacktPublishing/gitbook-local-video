## $5 Tech Unlocked 2021!
[Buy and download this product for only $5 on PacktPub.com](https://www.packtpub.com/)
-----
*The $5 campaign         runs from __December 15th 2020__ to __January 13th 2021.__*

Gitbook Plugin for [Video.js](http://videojs.com)
==============

Intentionally kept simple; just include the plugin in book.json:

```
{
    "plugins": [ "local-video" ]
}
```

Run `gitbook install`, and then include the Video.js markup where you want it using raw GitBook tags

```
{% raw %}
  <video id="my-video" class="video-js" controls preload="auto" width="640" height="264"
  poster="MY_VIDEO_POSTER.jpg" data-setup="{}">
  <source src="MY_VIDEO.mp4" type='video/mp4'>
  <source src="MY_VIDEO.webm" type='video/webm'>
  <p class="vjs-no-js">
    To view this video please enable JavaScript, and consider upgrading to a web browser that
    <a href="http://videojs.com/html5-video-support/" target="_blank">supports HTML5 video</a>
  </p>
  </video>
{% endraw %}
```

Lazy, but it should work.
