# JS write() method
```html
<!DOCTYPE html>
<html>
<body>

<script>
  document.write("<p>Hello World!</p>");
</script>

</body>
</html>
```
```
Hello World!
```

# internal CSS & JS
```html
<!DOCTYPE html>
<html>
<head>
 <style> div { color: red; } </style>
</head>
<body>
  <div id="myId"></div>
  <script>
    let example = "lorem itsum";
    document.getElementById("myId").innerHTML = example;
  </script>

</body>
</html>
```
![image](https://github.com/whatthehekkist/any/assets/131659910/2353b279-0ef5-4838-9f3d-28f261502eed)

