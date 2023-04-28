# EthanWebsitebuilder.github.io
<!DOCTYPE html>
<html>
<head>
  <title>Redirect Page</title>
</head>
<body>
  <div style="position:absolute; top:50%; left:50%; transform:translate(-50%,-50%);">
    <input type="text" id="urlInput" placeholder="Enter a URL">
    <button onclick="redirectToUrl()">Go</button>
  </div>

  <script>
    function redirectToUrl() {
      var url = document.getElementById("urlInput").value;
      window.location.href = url;
    }
  </script>
</body>
</html>
