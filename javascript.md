# Objects

* Count object size

Full code
```javascript
objectSize = funcion(object){
	var size = 0;
	for (var key in obj) {
        if (obj.hasOwnProperty(key)) size++;
	return size;
}
```

Minified
```javascript
objectSize = funcion(o){var s=0;for(var k in o){if(o.hasOwnProperty(k))s++;}return s;}
```
