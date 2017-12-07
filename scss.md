# Guidelines

A quick reminder on how to share your project with Seniormedia team when working with Scss/Sass projects

* Line break after calling an html element (tag, class ...)
```scss
false
.parent-bloc {
  .child-bloc {
    font-size: 9px;
  }
}

true
.parent-bloc {

  .child-bloc {
    font-size: 9px;
  }
}
```

* No call identifier, use a class for style (id reserved for javascript)
```scss
false
#id-bloc {
  font-size: 9px;
}

true
.id-bloc {
  font-size: 9px;
}
```

* respected the alphabetical order for the css values (font-family, color, cursor, background ...)
```scss
false
div {
  width: 100%;
  font-size: 9px;
  border-radius: 50%;
}

true
div {
  border-radius: 50%;
  font-size: 9px;
  width: 100%;
}
```
* 3 nests maximum (except for exceptions see linter conf)
```scss
false
.parent-bloc {

  .child-bloc {
    
    .child-bloc {
      
      &:before {
        width: 30px;
      }
    }
  }
}

true
.parent-bloc {

  .child-bloc {
    
    &:before {
      width: 30px;
    }
  }
}
```

* Do not use the all keyword during transitions and other animation effects
```scss
false
div {
 transition: all 4s, color 1s;
}

true
div {
 transition: margin-right 4s, color 1s;
}
```
* Only use color variables
```scss
false
div {
  background-color: #fff;
}

true
div {
  background-color: $white;
}
```
