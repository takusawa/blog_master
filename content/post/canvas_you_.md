+++
date = "2017-01-08T16:42:10+09:00"
draft = false
title = ""

+++

<link rel="stylesheet" type="text/css" href="">
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.1/css/bootstrap.min.css">
<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.9.1/jquery.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/embed-js/4.2.1/embed.min.js"></script>

# 渡辺曜
<script>
// canvasを作ってHTMLに突っ込む。
const canvas = document.createElement('canvas');
const context1 = canvas.getContext('2d');
canvas.width = 500;
canvas.height = 500;
document.body.appendChild(canvas);

/*  渡辺曜 ここから  */
context1.fillStyle = '#00dcff';
context1.strokeStyle = '#00dcff';
context1.beginPath();
context1.arc(250, 250, 150,  0, (Math.PI*2), false);
context1.stroke();
context1.fill();

/****白枠*****************/

context1.fillStyle = '#fff';
context1.strokeStyle = '#fff';
context1.beginPath();
context1.ellipse(265, 140, 20, 30, 0, 0, (Math.PI*2), true);
context1.stroke();
context1.fill();

context1.fillStyle = '#fff';
context1.strokeStyle = '#fff';
context1.beginPath();
context1.ellipse(300, 150, 30, 20, 0, 0, (Math.PI*2), true);
context1.stroke();
context1.fill();

context1.fillStyle = '#fff';
context1.strokeStyle = '#fff';
context1.beginPath();
context1.ellipse(280, 185, 30, 24, 0, 0, (Math.PI*2), true);
context1.stroke();
context1.fill();

/***曲線に見せるための苦肉の策******************/
context1.fillStyle = '#fff';
context1.strokeStyle = '#fff';
context1.beginPath();
context1.moveTo(275, 124);
context1.lineTo(280, 160);
context1.lineTo(295, 131);
context1.stroke();
context1.fill();

context1.fillStyle = '#fff';
context1.strokeStyle = '#fff';
context1.beginPath();
context1.ellipse(260, 220, 100, 80, 0, (Math.PI*3)/2, (Math.PI*1)/2, true);
context1.stroke();
context1.fill();

context1.fillStyle = '#fff';
context1.strokeStyle = '#fff';
context1.beginPath();
context1.moveTo(310, 180);
context1.lineTo(360, 300);
context1.lineTo(250, 300);
context1.lineTo(250, 180);
context1.stroke();
context1.fill();

context1.fillStyle = '#fff';
context1.strokeStyle = '#fff';
context1.beginPath();
context1.ellipse(310, 310, 54, 24, 0, 0, (Math.PI*2), true);
context1.stroke();
context1.fill();

context1.fillStyle = '#fff';
context1.strokeStyle = '#fff';
context1.beginPath();
context1.ellipse(230, 305, 40, 30, 0, 0, (Math.PI*2), true);
context1.stroke();
context1.fill();

context1.fillStyle = '#fff';
context1.strokeStyle = '#fff';
context1.beginPath();
context1.ellipse(180, 280, 20, 24, 0, 0, (Math.PI*2), true);
context1.stroke();
context1.fill();

/****船描画*****************/

/****船 旗*****************/
context1.fillStyle = '#00dcff';
context1.strokeStyle = '#00dcff';
context1.beginPath();
context1.arc(295, 105, 40,  (Math.PI*5)/6, (Math.PI*5)/12, true);
context1.lineTo(260, 155);
context1.lineTo(260, 125);
context1.stroke();
context1.fill();

/****船 柱*****************/
context1.fillStyle = '#00dcff';
context1.strokeStyle = '#00dcff';
context1.beginPath();
context1.lineTo(260, 160);
context1.lineTo(275, 160);
context1.lineTo(275, 280);
context1.lineTo(260, 280);
context1.lineTo(260, 160);
context1.stroke();
context1.fill();

/****船 右三角*****************/

context1.fillStyle = '#00dcff';
context1.strokeStyle = '#00dcff';
context1.beginPath();
context1.ellipse(310, 222, 50, 6, (Math.PI*4)/3, 0, (Math.PI), true);
context1.lineTo(285, 270);
context1.lineTo(285, 180);
context1.stroke();
context1.fill();

/****船 土台*****************/
context1.fillStyle = '#00dcff';
context1.strokeStyle = '#00dcff';
context1.beginPath();
context1.moveTo(190, 275);
context1.lineTo(195, 285);
context1.lineTo(175, 290);
context1.lineTo(175, 270);
context1.lineTo(340, 285);
context1.lineTo(340, 305);
context1.ellipse(310, 310, 30, 12, 0, 0, (Math.PI), false);
context1.ellipse(230, 300, 54, 9, (Math.PI*1)/12, 0, (Math.PI), true);
context1.stroke();
context1.fill();

/****船 帆*****************/
context1.fillStyle = '#00dcff';
context1.strokeStyle = '#00dcff';
context1.beginPath();
context1.moveTo(190, 203);
context1.lineTo(250, 155);
context1.lineTo(250, 265);
context1.lineTo(200, 260);
context1.ellipse(200, 230, 24, 30, 0, (Math.PI*1)/2, (Math.PI*3)/2, false);
context1.stroke();
context1.fill();


/****船 底 水玉*****************/
context1.fillStyle = '#00dcff';
context1.strokeStyle = '#00dcff';
context1.beginPath();
context1.ellipse(210, 305, 10, 10, 0, 0, (Math.PI*2), false);
context1.stroke();
context1.fill();

context1.fillStyle = '#00dcff';
context1.strokeStyle = '#00dcff';
context1.beginPath();
context1.ellipse(230, 310, 5, 5, 0, 0, (Math.PI*2), false);
context1.stroke();
context1.fill();

/*********************/
</script>