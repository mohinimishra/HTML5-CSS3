# Grid Rows & Columns Properties :

## grid-template-coloumns Property -

* Grid-template-columns property is used to define a coloumn

* Use as pixel values -: 
```css
grid-template-columns: 150px 150px 150px;  
 /* this will create 3 columns, width of 150px. 
```
```css
grid-template-columns: 150px 150px;    
/*this will create 2 columns, width of 150px 
```
```css
grid-template-columns: 150px 150px;    
/* this will create 2 columns, width of 150px
```
```css
grid-template-columns: 150px 150px;    
/*this will create 2 columns, width of 150px
```
```css
grid-template-columns: 150px 150px;    
/*this will create 2 columns, width of 150px
```
 ```css
 grid-template-columns: 150px 250px auto;  
 /*this will create 3 columns, 1 will be width of 150px, 2 will be 250px width and 3 will be cover the rest width.
 ```
 * Use as repeate() function -: 
```css
grid-template-columns: repeat(2, 50%) 
/*this will create 2 column width of 50, 50 %
```
```css
grid-template-columns: 150px, repeat(2, 30%);  /*this will create 1 column of 150px & 2 columns of 30-30% width.
```
*  Use as fraction values -:
```css
grid-template-columns: 3fr 3fr 3fr;
```

## grid-template-rows Property -                  

* grid-template-columns is used to define rows 
```css
grid-template-rows: 150px 150px 150px;
```