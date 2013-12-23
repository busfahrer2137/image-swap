<script type="text/javascript">
imgs=Array("img1.jpg","pic2.jpg","another.jpg","whee.gif","whatever.png");
var x=0;

function change() {
document.getElementById("bob").src=imgs[++x];

if (x==5) {
x=0;
}
}
</script>

<img src="img1.jpg" id="bob" alt="" onmousedown="change()">
