# Altura-dinamica-para-sliders-videos-e-iframes


```html
<div class="wrap">
    <div class="container">
        <video id="video" controls="controls">
            <source type="video/mp4"
                    src="http://clips.vorwaerts-gmbh.de/big_buck_bunny.mp4" />
        </video>
    </div>           
</div>
```

```css
video {
    max-width: 100%;
    height: auto;
}

.container {
    background: red;
    position: relative;
    padding-bottom: 56.25%;
    height: 0;
    overflow: hidden;
}

.container iframe,  
.container object,  
.container embed,
.container video{
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
}
```

Fuente: https://stackoverflow.com/questions/13555061/dynamic-parent-div-width-and-height-based-on-html5-video-resolution
