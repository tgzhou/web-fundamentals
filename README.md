# Web Fundamentals

## HTML

- Anchor tag and `href` attribute
``` html
<a href="https://codenation.org">Code Nation</a>
```

<a href="https://codenation.org">Code Nation</a>

- Image tag and `src` attribute

``` html
<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRnkntY6ZfhKPx8fKD5-va0utgWqXkcdbssOQ&usqp=CAU">
```

<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRnkntY6ZfhKPx8fKD5-va0utgWqXkcdbssOQ&usqp=CAU">


## CSS

```
body {
    background-color: purple;
    color: aqua;
}

p {
  color: blue;
  font-family: cursive;
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

## jQuery / JavaScript

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

### Reading and displaying input

```
$(".ask").click(function() {
    let question = $(".speech").val(); 
    $(".speech-bubble").text(question);
});
```


#### Using `.append()`

``` js
$(".add").click(function(){
    let newMessage = $("input").val();
    $(".messages").append("<p>" + newMessage + "</p>");
});
```


### CSS Actions

```
$(".change").click(function)() {
    $("body").css("color", "aqua");
});
```

## Unit 7.4

### Guided Practice

``` js
$(".ask").click(function() {
    let question = $(".speech").val();
    $(".speech-bubble").text(question);
    // Add your code below:
    $(".history").append("<p>"+question);
});
```

### Independent Lab

``` js
$(".to-pack-button").click(function(){
    let packingItem = $(".to-pack-input").val();
    console.log(packingItem);
    $(".packing-list").append("<li>" + "I'm going to pack item " + packingItem + "</li>");
    $("img").attr("src",  "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRnkntY6ZfhKPx8fKD5-va0utgWqXkcdbssOQ&usqp=CAU");
});

$(".to-class-button").click(function(){
    let courseItem = $(".to-class-input").val();
    console.log(courseItem);
    $(".course-list").append("<li>" + courseItem + "</li>");
});

```
