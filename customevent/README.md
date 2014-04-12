##Usage:
add an appropriate event listener  
```javascript
obj.addEventListener("cat", function(e) { process(e.detail) });
```
create and dispatch the event  
```javascript
var event = new CustomEvent("cat", {"detail":{"hazcheeseburger":true}});  
obj.dispatchEvent(event);  
```

