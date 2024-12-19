---
layout: default
---


<script>
  document.addEventListener("DOMContentLoaded", () => {
    const markdownUrl = "https://raw.githubusercontent.com/hangga/delvelin/refs/heads/main/README.md";
    const container = document.getElementById("markdown-content");

    fetch(markdownUrl)
      .then((response) => {
        if (!response.ok) {
          throw new Error("Network response was not ok " + response.statusText);
        }
        return response.text();
      })
      .then((markdown) => {
        container.innerHTML = marked(markdown);
      })
      .catch((error) => {
        console.error("Error fetching the Markdown file:", error);
        container.innerHTML = "<p>Unable to load content.</p>";
      });
  });
</script>
<div id="markdown-content"></div>
