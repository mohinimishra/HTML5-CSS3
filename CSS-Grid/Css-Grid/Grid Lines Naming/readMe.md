# Grid Lines Naming -

##  row naming :
```css
grid-templet-row : [header-start] 100px [header-end menu-start] 50px [menu-end]
```
```css
.header {
    grid-row : header-start / header-end
    /* it will create header, 50px height from header-start to header-end (ex-1 / 2) */
}
```

```css
grid-templet-column : repeat(3, [col-start] 10px [col-end])

