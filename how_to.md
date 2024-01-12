#This is a way to get rid of the input number buttons

```html
<input type="number" name="age" class="age" autocomplete="off">
```
**and then add the properties @ CSS:**
```css
.age::-webkit-outer-spin-button {
  display:none;
}
.age::-webkit-inner-spin-button {
  display:none;
}
```
