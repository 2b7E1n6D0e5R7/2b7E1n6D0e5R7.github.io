---
layout: default
title: Поддержать
permalink: /donate/
---
<p>Поддержите проект</p>

<script src="https://ajax.googleapis.com/ajax/libs/jquery/2.1.1/jquery.min.js"></script>

### Bitcoin:
<div id ="text">
```html
348dcb6f-3a73-48a8-86dc-4383b1b08942
```
</div>
<br>
<button id="copy">Копировать текст</button>

<script>
	$('#copy').click(function() {
	    var $temp = $("<input>");
	    $("body").append($temp);
	    $temp.val($('#text').text()).select();
	    document.execCommand("copy");
	    $temp.remove();

  $(this).text('Тест скопирован!');
  });
</script>

<style>@import url("//portal.fondy.eu/mportal/static/css/button.css");</style>
<a href="https://api.fondy.eu/s/sYxcaFx2" data-button="" class="f-p-b" style="--fpb-background:#dfdfdf; --fpb-color:#000000; --fpb-border-color:#000000; --fpb-border-width:1px; --fpb-font-weight:700; --fpb-font-size:17px; --fpb-border-radius:22px;">
<i data-text="name">Поддержать</i>
<i data-text="amount">500 RUB</i>
</a>
