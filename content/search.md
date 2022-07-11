---
title: "Search"
layout: "search"
priority : 0.1
menu: "main"
weight: 5
---

<script src="https://cdn.jsdelivr.net/npm/fuse.js@6.6.2"></script>
<script src="/js/search.js"></script>
<section id="search-input">
  <input style="display: center" id="search-content" placeholder="Search text" type="search" oninput="executeSearch()"> 🔍
</section>
<hr>
<section id="search-results">
  <h3>Please input some keywords to search</h3>
</section>