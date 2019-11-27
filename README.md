# ng5-slider

when tick is selected, keep orginal color.

```javascript
// if (tick.selected && !ValueHelper.isNullOrUndefined(this.viewOptions.getSelectionBarColor)) {
//   tick.style['background-color'] = this.getSelectionBarColor();
// }
// let tick color won't covered by default selectd color #0db9f0

if (tick.selected && !ValueHelper.isNullOrUndefined(this.viewOptions.getTickColor)) {
  tick.style['background-color'] = this.getTickColor(value);
}
```



## License

The project is licensed under the MIT license.
