# background-parallax
A small parallax utility Javascript function for background images

### Dependencies
- None

### Usage


```javascript
elements = document.querySelectorAll(".parallax");
window.addEventListener("scroll", function() {
	Array.prototype.forEach.call(elements, function(el, i){
		background_parallax(el, 2.5)
	});
});
```

