### vibrant.js
---
https://github.com/jariz/vibrant.js/

```
npm install
bower install
coffee -c gulpfile.coffee
gulp
```

```js
var img = document.createElement('img');
img.setAttribute('src', 'example/octocat.png')
img.addEventListener('load', function(){
  var vibrant = new Vibrant(img);
  var swatches = vibrant.seatches()
  for(var swatch in swatches()
    if(swatches.hasOwnProperty(swatch) && swatches[swatche])
      console.log(swatch, swatches[swatch].getHex())
});

new Vibrant(
  img,
  64,
  5
)

```

```
```

