+++
date = "2017-01-08T16:42:10+09:00"
draft = false
title = ""

+++

<link rel="stylesheet" type="text/css" href="">
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.1/css/bootstrap.min.css">
<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.9.1/jquery.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/embed-js/4.2.1/embed.min.js"></script>

# 小原鞠莉
<script>
// canvasを作ってHTMLに突っ込む。
const canvas = document.createElement('canvas');
const context1 = canvas.getContext('2d');
canvas.width = 500;
canvas.height = 500;
document.body.appendChild(canvas);

/*  小原鞠莉 ここから  */
context1.fillStyle = '#b58dff';
context1.strokeStyle = '#b58dff';
context1.beginPath();
context1.arc(250, 250, 150,  0, (Math.PI*2), false);
context1.stroke();
context1.fill();

/**手裏剣の白枠*******************/

context1.fillStyle = '#fff';
context1.strokeStyle = '#fff';
context1.beginPath();
context1.ellipse(240, 250, 35, 130, 0, 0, (Math.PI*2), true);
context1.stroke();
context1.fill();

context1.fillStyle = '#fff';
context1.strokeStyle = '#fff';
context1.beginPath();
context1.ellipse(240, 250, 130, 35, 0, 0, (Math.PI*2), true);
context1.stroke();
context1.fill();

/***小さい白丸4つ******************/

context1.fillStyle = '#fff';
context1.strokeStyle = '#fff';
context1.beginPath();
context1.ellipse(190, 200, 30, 30, 0, 0, (Math.PI*2), true);
context1.stroke();
context1.fill();

context1.fillStyle = '#fff';
context1.strokeStyle = '#fff';
context1.beginPath();
context1.ellipse(190, 300, 30, 30, 0, 0, (Math.PI*2), true);
context1.stroke();
context1.fill();

context1.fillStyle = '#fff';
context1.strokeStyle = '#fff';
context1.beginPath();
context1.ellipse(290, 300, 30, 30, 0, 0, (Math.PI*2), true);
context1.stroke();
context1.fill();

context1.fillStyle = '#fff';
context1.strokeStyle = '#fff';
context1.beginPath();
context1.ellipse(290, 200, 30, 30, 0, 0, (Math.PI*2), true);
context1.stroke();
context1.fill();

/***小さい手裏剣の白枠******************/

context1.fillStyle = '#fff';
context1.strokeStyle = '#fff';
context1.beginPath();
context1.ellipse(320, 320, 18, 35, 0, 0, (Math.PI*2), true);
context1.stroke();
context1.fill();

context1.fillStyle = '#fff';
context1.strokeStyle = '#fff';
context1.beginPath();
context1.ellipse(320, 320, 35, 18, 0, 0, (Math.PI*2), true);
context1.stroke();
context1.fill();

/***大きい方の手裏剣******************/

context1.fillStyle = '#b58dff';
context1.strokeStyle = '#b58dff';
context1.beginPath();
context1.ellipse(240, 250, 20, 120, 0, 0, (Math.PI*2), true);
context1.stroke();
context1.fill();

context1.fillStyle = '#b58dff';
context1.strokeStyle = '#b58dff';
context1.beginPath();
context1.ellipse(240, 250, 120, 20, 0, 0, (Math.PI*2), true);
context1.stroke();
context1.fill();

/***小さい方の手裏剣******************/

context1.fillStyle = '#b58dff';
context1.strokeStyle = '#b58dff';
context1.beginPath();
context1.ellipse(320, 320, 5, 30, 0, 0, (Math.PI*2), true);
context1.stroke();
context1.fill();

context1.fillStyle = '#b58dff';
context1.strokeStyle = '#b58dff';
context1.beginPath();
context1.ellipse(320, 320, 30, 5, 0, 0, (Math.PI*2), true);
context1.stroke();
context1.fill();

/***4つのキラキラ******************/

context1.fillStyle = '#b58dff';
context1.strokeStyle = '#b58dff';
context1.beginPath();
context1.moveTo(190, 190);
context1.lineTo(180, 200);
context1.lineTo(200, 215);
context1.lineTo(202, 213);
context1.stroke();
context1.fill();

context1.fillStyle = '#b58dff';
context1.strokeStyle = '#b58dff';
context1.beginPath();
context1.moveTo(190, 310);
context1.lineTo(180, 300);
context1.lineTo(200, 285);
context1.lineTo(202, 287);
context1.stroke();
context1.fill();

context1.fillStyle = '#b58dff';
context1.strokeStyle = '#b58dff';
context1.beginPath();
context1.moveTo(290, 190);
context1.lineTo(300, 200);
context1.lineTo(280, 215);
context1.lineTo(278, 213);
context1.stroke();
context1.fill();

context1.fillStyle = '#b58dff';
context1.strokeStyle = '#b58dff';
context1.beginPath();
context1.moveTo(290, 310);
context1.lineTo(300, 300);
context1.lineTo(280, 285);
context1.lineTo(278, 287);
context1.stroke();
context1.fill();

/****無理矢理手裏剣ぽくする************************/

context1.fillStyle = '#b58dff';
context1.strokeStyle = '#b58dff';
context1.beginPath();
context1.moveTo(225, 170);
context1.lineTo(220, 190);
context1.lineTo(217, 203);
context1.lineTo(211, 214);
context1.lineTo(208, 220);
context1.lineTo(200, 228);
context1.lineTo(190, 230);
context1.lineTo(175, 235);
context1.lineTo(225, 235);
context1.stroke();
context1.fill();

context1.fillStyle = '#b58dff';
context1.strokeStyle = '#b58dff';
context1.beginPath();
context1.moveTo(255, 170);
context1.lineTo(260, 190);
context1.lineTo(263, 203);
context1.lineTo(269, 214);
context1.lineTo(272, 220);
context1.lineTo(280, 228);
context1.lineTo(290, 230);
context1.lineTo(305, 235);
context1.lineTo(255, 235);
context1.stroke();
context1.fill();

context1.fillStyle = '#b58dff';
context1.strokeStyle = '#b58dff';
context1.beginPath();
context1.moveTo(225, 267);
context1.lineTo(175, 267);
context1.lineTo(190, 270);
context1.lineTo(195, 272);
context1.lineTo(205, 275);
context1.lineTo(210, 280);
context1.lineTo(216, 290);
context1.lineTo(220, 300);
context1.lineTo(224, 320);
context1.stroke();
context1.fill();

context1.fillStyle = '#b58dff';
context1.strokeStyle = '#b58dff';
context1.beginPath();
context1.moveTo(255, 267);
context1.lineTo(305, 267);
context1.lineTo(290, 270);
context1.lineTo(285, 272);
context1.lineTo(275, 275);
context1.lineTo(270, 280);
context1.lineTo(262, 290);
context1.lineTo(260, 300);
context1.lineTo(256, 320);
context1.stroke();
context1.fill();

/****無理矢理手裏剣ぽくする************************/

context1.fillStyle = '#b58dff';
context1.strokeStyle = '#b58dff';
context1.beginPath();
context1.ellipse(320, 320, 10, 10, 0, 0, (Math.PI*2), true);
context1.stroke();
context1.fill();

context1.fillStyle = '#b58dff';
context1.strokeStyle = '#b58dff';
context1.beginPath();
context1.ellipse(320, 315, 8, 8, 0, 0, (Math.PI*2), true);
context1.stroke();
context1.fill();

context1.fillStyle = '#b58dff';
context1.strokeStyle = '#b58dff';
context1.beginPath();
context1.ellipse(320, 325, 8, 8, 0, 0, (Math.PI*2), true);
context1.stroke();
context1.fill();

context1.fillStyle = '#b58dff';
context1.strokeStyle = '#b58dff';
context1.beginPath();
context1.ellipse(315, 320, 8, 8, 0, 0, (Math.PI*2), true);
context1.stroke();
context1.fill();

context1.fillStyle = '#b58dff';
context1.strokeStyle = '#b58dff';
context1.beginPath();
context1.ellipse(325, 320, 8, 8, 0, 0, (Math.PI*2), true);
context1.stroke();
context1.fill();

/*  ここまで  */

</script>