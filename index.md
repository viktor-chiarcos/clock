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
<a href="/clock/apple/instruction">Auf iOS installieren</a><br>

[Docker image für Windows/Linux/Unix/Macs](https://hub.docker.com/r/viktorchiarcos/uhrzeitapp)
<br><a href="/">Zurück zu viktor-chiarcos.github.io</a>
