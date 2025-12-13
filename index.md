---
layout: default
permalink: /
---
<script>
  'use strict';
(function () {
	function init() {
		var datum = new Date();
		document.getElementById('zeit')
			.innerHTML = datum;
	}
	document.addEventListener("DOMContentLoaded", function () {
		init();
	});
}());
</script>


<h1>Aktuelle Uhrzeit:</h1>
<time aria-current="date" id="zeit"></time>
<a href="">Neu laden</a>
<br>
<a href="/">Zurück zu viktor-chiarcos.github.io</a>
