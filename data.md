---
title: Data
subtitle: Data
layout: page
show_sidebar: false
---

<pre id="jekyll-debug"></pre>
<script>
  var obj = JSON.parse(decodeURIComponent("{{ site | jsonify | uri_escape }}"));
  var prettyJson = JSON.stringify(obj, null, 4);  // Pretty-printed JSON (indented 4 spaces).
  document.getElementById("jekyll-debug").textContent = prettyJson;
</script>
