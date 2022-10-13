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
br {
  display: block;
  content: " ";
  margin-top: 2em;
}
.title-box { 
  display: flex;
  align-items: center;
}
.image-container {
  width: 12em;
  min-width: 12em;
  padding-right: 2em;
}
.intro-flair {
  color: #d1ca02;
  font-size: 2em;
}
.title-container {
  width: fit-content;
}
.review-container {
  line-height: 1.5em;
}
.emphasis-flair {
  color: #d1ca02;
  font-weight: bold;
}
.title-container #title {
  color: #d1ca02;
  font-size: 4em;
  font-weight: bold;
  line-height: .8em;
  text-transform: uppercase;
  margin-top: .2em;
}
.title-container #subtitle {
  font-size: 2em;
  line-height: 1em;
  text-transform: uppercase;
}
.title-container #rating {
  font-size: 2em;
  font-weight: bold;
  line-height: 2em;
  text-transform: uppercase;
}
#rating-text {
  font-size: 1.5em;
  font-weight: bold;
  color: #d1ca02;
}
</style>
<div class="title-box">
	<div class="image-container">
		<!-- add image to folder named after game -->
		{% asset_img REPLACEME.jpg %}
	</div>
	<div class="title-container">
		<div id="title">{{ title }}</div>
		<div id="subtitle">{{ subtitle }}</div>
		<div id="rating">{{ rating }}</div>
	</div>
</div>
<hr>
<div class="review-container">
	<span class="intro-flair"></span><span class="emphasis-flair"></span>
  </br>
</div>
