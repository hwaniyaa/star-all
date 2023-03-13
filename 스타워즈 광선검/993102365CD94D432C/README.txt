A Pen created at CodePen.io. You can find this one at https://codepen.io/chasebank/pen/eyOOmW.

 Just a little thing to bide the time until I see the movie.

I'm using a neat technique inspired by [@shshaw](https://codepen.io/shshaw/full/LVKEdv), of turning transparent PNGs into normalized masked JPGs (with an SVG mask).  Converting the images into base64 seems to help with browser compatibility, but the resulting strings in this case were getting a little too astronomically long. So, I'm only using base64 on the mask and the rest are normal images. If things look wrong, this is likely the cause.

An interesting benefit of composing images inside SVG (aside from the mask) is it makes positioning much easier. The images can be positioned on an x y coordinate without any care of viewport size or px vs rem vs xyz. The image will scale perfectly inside that viewbox and maintain it's appropriate position.

This is my first foray into particles and TweenMax. At first I tried appending each particle to the same timeline, but was having a rough time. So, I just created a new timeline for each particle. There's no way this is a good thing... So...

*CPU temperatures and turbine speeds may very with use.

May The Force be with you.