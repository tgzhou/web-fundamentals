# Web Fundamentals

## CSS

```
p {
  color: blue;
}

body {
    background-color: purple;
    color: aqua;
}

```

### Box model

``` css
.caption {
  padding: 10px;
  border: 5px solid blue;
  margin: 5px;
  background-color: blue;
}
```

### FlexBox

``` css
.parent {
   display: flex;
   justify-content: center;  // flex-start, flex-end, space-between, space-around
}


```

## jQuery


There are many types of events jQuery recognizes.  Here are a few:
- click
- dblclick
- mouseenter
- mouseleave
- hover


```
$(".button").click(function() {
   $(".pic").hide();   // show()
   $(".feedback").text("This is a Title");
});
```

### Aminations

```
$("div").show()
$("div").hide()
$("div").toggle()

$("div").slideDown()
$("div").slideUp()
$("div").slideToggle()

$("div").fadeIn()
$("div").fadeOut()
$("div").fadeToggle()
```

### CSS Actions

```
$(".change").click(function)() {
	$("body").css("color", "aqua");
});
```
