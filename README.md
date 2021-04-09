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

### Evert types

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

### Reading input

```
$(".ask").click(function() {
    let question = $(".speech").val(); 
    $(".speech-bubble").text(question);
});
```


### Using `.append()`

``` js
$(".add").click(function(){
    let newMessage = $("input").val();
    $(".messages").append("<p>" + newMessage + "</p>");
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

## Guided Practice

### 7.4

``` js
$(".ask").click(function() {
    let question = $(".speech").val();
    $(".speech-bubble").text(question);
    // Add your code below:
    $(".history").append("<p>"+question);
});
```
