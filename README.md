# clock.js

---

htmlに読み込んで、時計を表示させるJavascriptです。
まずclock.jsを`<script src="clock.js"></script>`のように読み込ませ、
```
<div id="clock"></div>
```
などの時計を表示させる場所をhtmlに配置しておきます。

また、サイトの動作に一番使う`script.js`など、またはhtmlの`<script>`の中に、
```
let timesp = document.getElementById('time'); //時計表示用

window.setInterval(showdt ,1000);
```
のコードも置いてください。


表示形式：`YYYY/MM/DD HH:MM:SS`の形式で表示されます（デフォルトの場合で、変更できます）
