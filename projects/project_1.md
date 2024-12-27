### Project 1: Interactive Web Pages with JavaScript

#### Objectives
- Use JavaScript to interact with HTML and CSS.

#### Code Example
```html
<!DOCTYPE html>
<html>
  <body>
    <button id="colorButton">Change Background Color</button>

    <script>
      document.getElementById("colorButton").addEventListener("click", function () {
        document.body.style.backgroundColor = "lightblue";
      });
    </script>
  </body>
</html>
```