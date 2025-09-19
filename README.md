# clock.js

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

---

表示形式：`YYYY/MM/DD HH:MM:SS`の形式で表示されます（デフォルトの場合で、変更できます）

---

個人利用はOKです。
このコードを使って公開する場合は、**必ず**このリポジトリのURLを見えるところに記載してください。
また個人・法人（団体など）問わず商用に利用するときは必ず「issue」内で相談して、私の許可を受けてからにしてください。
