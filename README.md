# klikEvents
This addon propose a simple event showing some data. 

####Sidebox()
To use it, you need to call the sideBox() method on the layer of your choice (if it's not a graphic Layer).

```javascript
yourLayer.sideBox();
```
When you are using this event, you need/can pass this following data in the element object of your polygone:

```javascript
element:{
  'price': Number,
  'title': String,
  'description': String
}
```
