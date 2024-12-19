---
layout: default
---
<script>
  fetch('https://raw.githubusercontent.com/hangga/delvelin/refs/heads/main/README.md')
    .then(response => response.text())
    .then(data => {
      document.getElementById('readme-content').innerHTML = marked(data);
    });
</script>
<div id="readme-content"></div>
