The original code uses audio files contained in the sounds folder as a source, which works well on Opera, Chrome and Safari, while with Internet Explorer and Mozilla the audio does not start in autoplay, but I could not fix it with the html5 tag.
I had tried to embed directly youtube videos and then hide them with the tag hidden = "true", but since the audio files I used are the originals, and therefore protected by copyright, they were blocked directly by youtube, thus causing the failure audio autoplay; (
But I managed to find a nice remix with a creative commons license of Super Mario Bros, this time it obviously worked and the audio part in autoplay on all the browsers.

Find the file indexwithsoundfix.html, replace it with the original and you're done ...

<img src="https://i.imgur.com/SAPU3LH.gif" 
alt="Mario is Alive!" width="600" height="450" border="100" />

you can try a demo here:
https://codepen.io/JonnyBanana/pen/paQyKo

<a href="https://codepen.io/JonnyBanana/pen/paQyKo
" target="_blank"><img src="https://i.imgur.com/z7PMR46.jpg" 
alt="Mario is Alive!" width="600" height="450" border="100" /></a> 

