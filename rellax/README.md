# RELLAX

Rellax is a buttery smooth, super lightweight (1021bytes gzipped), vanilla javascript parallax library. **Update:** Rellax now works on mobile (v1.0.0). 

* [Demo Website](https://dixonandmoe.com/rellax/)

Have any suggestions or feedback? Reach out [@dixonandmoe](https://twitter.com/dixonandmoe)

## Getting Started
`npm install rellax --save` or if you're old school like us download and insert `rellax.min.js`

```html
<div class="rellax">
  I’m that default chill speed of "-2"
</div>
<div class="rellax" data-rellax-speed="7">
  I’m super fast!!
</div>
<div class="rellax" data-rellax-speed="-4">
  I’m extra slow and smooth
</div>

<script src="rellax.min.js"></script>
<script>
  // Accepts any class name
  var rellax = new Rellax('.rellax');
</script>
```
```html
<script>
  // Also can pass in optional settings block
  var rellax = new Rellax('.rellax');
</script>
```
## Features

### Centering
After some fantastic work from [@p-realinho](https://github.com/p-realinho), we just released the ability to center 
## Development
In the spirit of lightweight javascript, the build processes (thus far) is lightweight also.

1. Open demo.html
2. Make code changes and refresh browser
3. Once feature is finished or bug fixed, use [jshint](http://jshint.com/) to lint code
4. Fix lint issues then use [Google Closure Compiler](https://closure-compiler.appspot.com/home) to minify
5. 🍻

