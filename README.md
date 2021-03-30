# Web Fundamentals

## CSS

```
body {
    background-color: purple;
    color: aqua;
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
