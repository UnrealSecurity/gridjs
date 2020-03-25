# Grid.js
Canvas drawing but for text... or something like that...

## To-do
- Fix strange behavior with autosize option (disabled by default)

## Simple example
```javascript
let grid = new Grid();

let ti = grid.textInfo('Hello\n     beautiful\n               world');
grid.create(ti.width+2, ti.height+2);
grid.write(1, 1, ti.text, true)

console.log(grid.toString());
```
```md
┌────────────────────┐
│Hello               │
│     beautiful      │
│               world│
└────────────────────┘
```
