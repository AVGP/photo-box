<photo-box>
===========

Component that allows the user to take a screenshot and download it

Usage
-----
* Import the photo-box.html into your application
* Insert a `<photo-box>` tag

Example:

```html
<!doctype html>
<html>
<head>
  <link rel="import" href="http://components.geekonaut.de/photo-box/photo-box.html">
</head>
<body>
  <h1>Examples for a photo box</h1>

  <article>
    <h2>Simple</h2>
    <p><button onclick="document.getElementById('simple').startCapture()">Start camera</button></p>
    <photo-box id="simple"></photo-box>
  </article>

  <article>
    <h2>Customized the displayed texts</h2>
    <p><button onclick="document.getElementById('custom').startCapture()">Start camera</button></p>
    <photo-box id="custom">
      <label for="snapshotButton">Cheese</label>
      <label for="saveButton">Get yours</label>
      <label for="retakeButton">Nah, again</label>
      <div class="error">Yikes &gt;-&lt;</div>
      <div class="nosupport">Your browser just can't...</div>
    </photo-box>
  </article>

  <article>
    <h2>Automatically start capturing</h2>
    <photo-box autostart="true"></photo-box>
  </article>

</body>
</html>
```
