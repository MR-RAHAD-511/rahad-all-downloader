
<h3 align="center">

  <p align="center"><img src="https://img.shields.io/badge/WLCM%20TO -RAHAD All DOWNLOADER-green?colorA=%23ff0000&colorB=%23017e40&style=flat-square">  

</h3>

[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Neuton&size=25&color=30FF40&background=000000&center=true&vCenter=true&width=360&height=60&lines=Hello+World%2C+I'm+Mohammad-Rahad+Here+🤙;𝙸𝚃'𝚜+𝙽𝙾𝚃+𝙰+𝙹𝚄𝚂𝚃+𝙽𝙰𝙼𝙴+𝙱𝚁𝙾+🥱;𝙸𝚃'𝚜+𝙰+𝙱𝚁𝙰𝙽𝙳+🔥;Respect+Mohammad-Rahad+🥀;Thanks+My+All+Friend+🤙+🥰)](https://git.io/typing-svg)


<a href="https://www.npmjs.com/package/rahad-all-downloader"><img alt="npm version" src="https://img.shields.io/npm/v/rahad-all-downloader.svg?style=flat-square"></a>
<img alt="version" src="https://img.shields.io/github/package-json/v/MR-RAHAD-511/rahad-all-downloader?label=github&style=flat-square">
<a href="https://www.npmjs.com/package/rahad-all-downloader"><img src="https://img.shields.io/npm/dm/rahad-all-downloader.svg?style=flat-square" alt="npm downloads"></a><br>
[![Socket Badge](https://socket.dev/api/badge/npm/package/rahad-all-downloader)](https://socket.dev/npm/package/rahad-all-downloader) 
[![js dilvr](https://data.jsdelivr.com/v1/package/npm/rahad-all-downloader/badge)](https://www.jsdelivr.com/package/npm/rahad-all-downloader)

## Instalation :
```bash
> npm i rahad-all-downloader
```

## Example (all downloader request)
```js
const { alldl } = require('rahad-all-downloader');

const videoUrl = ''; // Insert a supported URL from YouTube, Facebook, TikTok, Instagram, Twitter, Google Drive, or Capcut.

async function downloadVideo(url) {
  try {
    const result = await alldl(url);
    console.log(result);// all response same
  } catch (error) {
    console.error('Error:', error.message);
  }
}

downloadVideo(videoUrl);
```
## Output Example 
```
{
  "metadata": {
    "Author": "Mohammad Rahad",
    "message": "any problem please contact me",
    "Facebook": "https://www.facebook.com/md.rahad.hosain18"
  },
  "data": {
    "title": "ভালোবাসার মাঝে  দুঃখ কষ্ট তো থাকবেই  \nতার পরও শেষ টা সুন্দর হলেই হলো।",
    "videoUrl": "https://video-ord5-2.xx.fbcdn.net/o1/v/t2/f2/m69/An-LG-mxljb9dfsGidTTV1zUJhcS4gRhTpsW9Vt6QkMswkLmCnvPdnJR9LaHWFkw3ggQdk1R5Tl1vl2Su8awWLIU.mp4?efg=eyJ2ZW5jb2RlX3RhZyI6Im9lcF9oZCJ9&_nc_ht=video-ord5-2.xx.fbcdn.net&_nc_cat=108&strext=1&vs=30fddadf5b346217&_nc_vs=HBksFQIYOnBhc3N0aHJvdWdoX2V2ZXJzdG9yZS9HR2hWcXhwTFE1ZzM1N1FIQUg3VXFOYkZrS1J1Ym1kakFBQUYVAALIAQAVAhg6cGFzc3Rocm91Z2hfZXZlcnN0b3JlL0dLcGpzeHJXamdkTEdSd0JBSnlqc0V5S19RTXFickZxQUFBRhUCAsgBAEsHiBJwcm9ncmVzc2l2ZV9yZWNpcGUBMQ1zdWJzYW1wbGVfZnBzABB2bWFmX2VuYWJsZV9uc3ViACBtZWFzdXJlX29yaWdpbmFsX3Jlc29sdXRpb25fc3NpbQAoY29tcHV0ZV9zc2ltX29ubHlfYXRfb3JpZ2luYWxfcmVzb2x1dGlvbgAddXNlX2xhbmN6b3NfZm9yX3ZxbV91cHNjYWxpbmcAEWRpc2FibGVfcG9zdF9wdnFzABUAJQAcjBdAAAAAAAAAABERAAAAJoLrzPuMyK8BFQIoAkMzGAt2dHNfcHJldmlldxwXQGxUQYk3S8cYGWRhc2hfaDI2NC1iYXNpYy1nZW4yXzcyMHASABgYdmlkZW9zLnZ0cy5jYWxsYmFjay5wcm9kOBJWSURFT19WSUVXX1JFUVVFU1QbCogVb2VtX3RhcmdldF9lbmNvZGVfdGFnBm9lcF9oZBNvZW1fcmVxdWVzdF90aW1lX21zATAMb2VtX2NmZ19ydWxlB3VubXV0ZWQTb2VtX3JvaV9yZWFjaF9jb3VudAUxMzQzMRFvZW1faXNfZXhwZXJpbWVudAAMb2VtX3ZpZGVvX2lkEDIxMzkyNzUyMjMyMTQ1OTcSb2VtX3ZpZGVvX2Fzc2V0X2lkDzk0OTk2MTE0MDIxMjY2NBVvZW1fdmlkZW9fcmVzb3VyY2VfaWQPMzg2MDY3NzYwNTE5ODczHG9lbV9zb3VyY2VfdmlkZW9fZW5jb2RpbmdfaWQPMzk3Nzg0ODk5ODkzOTA3DnZ0c19yZXF1ZXN0X2lkACUCHAAlxAEbB4gBcwQzODY0AmNkCjIwMjQtMDYtMDYDcmNiBTEzNDAwA2FwcBlQYWdlcyBNYW5hZ2VyIGZvciBBbmRyb2lkAmN0GUNPTlRBSU5FRF9QT1NUX0FUVEFDSE1FTlQTb3JpZ2luYWxfZHVyYXRpb25fcwoyMjYuNjI2NzM1AnRzFXByb2dyZXNzaXZlX2VuY29kaW5ncwA%3D&ccb=9-4&oh=00_AYDdP1hZLgFCS72QD-myiakXvrd0wnre0gCfiGYqOztiTw&oe=6665CA75&_nc_sid=1d576d&_nc_rid=438836236495732&_nc_store_type=1"
  }
}
```
# Installation

## You can install `rahad-all-downloader` using npm:

```bash
npm install rahad-all-downloader
```

------

## coming Soon

This package is under development, and many exciting features are planned for future releases. Stay tuned for updates and enhancements!

## Contributing

We welcome contributions! If you find any issues or have suggestions for improvement, feel free to open an issue or submit a pull request. If you want to contact me, check my [GitHub profile](https://github.com/MR-RAHAD-511).

# developer information 
#### 𝗡𝗮𝗺𝗲         : 𝗠𝗼𝗵𝗮𝗺𝗺𝗮𝗱 𝗥𝗮𝗵𝗮𝗱
#### 𝗥𝗲𝗹𝗶𝗴𝗶𝗼𝗻    : (𝗜𝘀𝗹𝗮𝗺)
#### 𝗣𝗲𝗿𝗺𝗮𝗻𝗲𝗻𝘁 𝗔𝗱𝗱𝗿𝗲𝘀𝘀 : (𝗗𝗵𝗮𝗸𝗮)
#### 𝗖𝘂𝗿𝗿𝗲𝗻𝘁 𝗔𝗱𝗱𝗿𝗲𝘀𝘀 :𝗦𝗵𝗮𝗵𝗿𝗮𝘀𝘁𝗶 𝗖𝗵𝗮𝗻𝗱𝗽𝘂𝗿
#### 𝗚𝗲𝗻𝗱𝗲𝗿     : (𝗠𝗮𝗹𝗲)
#### 𝗔𝗴𝗲            :  (𝟮𝟬)
#### 𝗥𝗲𝗹𝗮𝘁𝗶𝗼𝗻𝘀𝗵𝗶𝗽 : (𝗦𝗶𝗻𝗴𝗹𝗲)
#### 𝗚𝗺𝗮𝗶𝗹        :  mdrahadhossain00@gmail.com
#### 𝗧𝗲𝗹𝗲𝗴𝗿𝗮𝗺  : t.me/rabbyhosainRahad
### [Facebook](https://www.facebook.com/md.rahad.hosain18)
 
Copyright © 2024 Mohammad Rahad
