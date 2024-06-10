# TWC Icons

A place to store icons (e.g. social media icons for e-mail signatures), linkable via free CDN ([jsDelivr](https://www.jsdelivr.com)). Current round icon set provided by [Tom](http://tomswebspace.com).

### Usage Example

Example linking to Twitter icon via jsDelivr:

```html
<a href="https://twitter.com/thewandcompany/">
  <img src="https://cdn.jsdelivr.net/gh/thewandcompany/icons/round/35px/twitter.png" alt="Twitter" title="Twitter" width="25" height="25" />
</a>
```

Replace the [icon name](https://github.com/thewandcompany/icons/tree/master/icons/round/50px/) and social media link as desired.

Please **DO NOT** link to the file directly on GitHub. Please use a CDN, as shown above.

This was based on https://github.com/dmhendricks/signature-social-icons 

Example Zendesk email footer:
```html
<div style="color: #aaaaaa; margin: 10px 0 14px 0; padding-top: 10px; border-top: 1px solid #eeeeee;">
This email was sent to you by The Wand Company<br>
<div>
  <a href="https://www.facebook.com/thewandcompany"><img src="https://cdn.jsdelivr.net/gh/thewandcompany/icons/round/35px/facebook.png" width="20" height="20" style="padding-right:5px; position:relative; top:5px" />Like</a> <a href="https://twitter.com/thewandcompany"><img src="https://cdn.jsdelivr.net/gh/thewandcompany/icons/round/35px/twitter.png" width="20" height="20" style="padding-left:15px; padding-right:5px; position:relative; top:5px" />Follow</a> <a href="https://www.youtube.com/thewandcompanyltd"><img src="https://cdn.jsdelivr.net/gh/thewandcompany/icons/round/35px/youtube.png" width="20" height="20" style="padding-left:15px; padding-right:5px; position:relative; top:5px" />Watch</a>
</div>
</div>
```

Can also use FontAwesome icons like this (but note that the CSS styles don't work reliably in email clients)

```html
<head>
  <link rel="stylesheet" href=
  "https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css" />

  <style>  
    .fa {
      color: #FFF;
      background-color: #222;
      font-size: 18px;
      line-height: 30px;
      width: 30px;
      height: 30px;
      border-radius: 30px;
      text-decoration: none;
      margin: 5px;
    } 
    .fa:hover {
      opacity: 0.6;
    }
  </style>
</head>

<body>
  <center> 
    <a href="#" class="fa fa-facebook"></a>
    <a href="#" class="fa fa-twitter"></a>
    <a href="#" class="fa fa-youtube-play"></a>
  </center>
</body>
```