# sass
Sass is a CSS pre-processor.  Sass reduces repetition of CSS and therefore saves time. Sass is the most mature, stable, and powerful professional grade CSS extension language in the world.
### use extension Scss live compiler and click on watch scss. 
- It will getnerate css.map and .css file
- link your html file with generated css file not scss

### Superpowers:
1. Operators
    -  sass provides some standard math operators i.e. +, -, *, /, and %.
    eg: `font-size: 2rem+3rem;`
2. Variables
    - you can create variable
```
// Variables
$bg-color:#2e86de;
```
```
.main_header{
    background-color:$bg-color;
 ```

3. nesting
```
.main_header{
   width: 100vw;
    height: 100vh;
    background-color: #2e86de;
        h1 {
            color: red;
            font-size: 2rem + 2rem;
           }
}
```
4. mixin
    - If you are finding common properties, store that properties into a variable and you can use that variable through include 
```
//@mixin
@mixin flexprob{
    display: grid;
    justify-content: center;
    align-items: center;
    flex-direction: column;
}
 ```
 ```
 .main_header{
    @include flexprob;
 ```
5. Parameters
```
@mixin flexprob($space) {
    display: grid;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    letter-spacing: $space;
}
```
6. partials
    - _ is mandatory
    - create separate files for variables, mixins etc
    - use `@import 'var';` to import the file
    - No need to write `_var.scss`. use 'var'.
### References
- https://www.javatpoint.com/sass-tutorial
- https://sass-lang.com/documentation/
- https://www.youtube.com/watch?v=tEQOdFgUXI4

### Live link : [SCSS](https://rupachandram.github.io/sass/)
### Happy Learning !!!