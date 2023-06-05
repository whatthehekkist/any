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


# HTML/CSS text in background image 
```html
<!DOCTYPE html>
<html>

<head>
<style>
  body {
    background-image: url('https://github.com/whatthehekkist/any/assets/131659910/8efae30b-4f52-436a-b952-5510328bdf6c');
    background-repeat: no-repeat;
    background-attachment: fixed;
    background-size: cover;
  }
  div { background-color: grey; text-align: center;}
  </style>
</head>

<body>

  <div>
    <h1>some text</h1>
  </div>

</body>
</html>
```
![image](https://github.com/whatthehekkist/any/assets/131659910/df2448aa-7266-42ed-bf2c-fbef582ee287)
