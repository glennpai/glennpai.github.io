---
title: {{ title }}
subtitle: 
date: {{ date }}
rating: 
categories:
  - gaming
  - review
tags: 
---
<style>
.title-box { 
  display: flex;
  align-items: center;
}
.image-container {
  width: 12em;
  min-width: 12em;
  padding-right: 2em;
}
.text-flair {
  color: #d1ca02;
  font-size: 2em;
}
#title {
  color: #d1ca02;
  font-size: 4em;
  font-weight: bold;
  line-height: .8em;
  text-transform: uppercase;
  margin-top: .2em;
}
#subtitle {
  font-size: 2em;
  line-height: 1em;
  text-transform: uppercase;
}
#rating {
  font-size: 2em;
  font-weight: bold;
  line-height: 2em;
  text-transform: uppercase;
}
</style>
<div class="title-box">
	<div class="image-container">
		<!-- add image to folder named after game -->
		{% asset_img REPLACEME.jpg %}
	</div>
	<div class="text-container">
		<div id="title">{{ title }}</div>
		<div id="subtitle">{{ subtitle }}</div>
		<div id="rating">{{ rating }}</div>
	</div>
</div>
<hr>
<div class="text-container">
	<span class="text-flair"></span>
</div>
