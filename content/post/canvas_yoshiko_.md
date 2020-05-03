+++
date = "2017-01-08T16:42:10+09:00"
draft = false
title = ""

+++

<link rel="stylesheet" type="text/css" href="">
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.1/css/bootstrap.min.css">
<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.9.1/jquery.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/embed-js/4.2.1/embed.min.js"></script>

# 津島善子
<script>
// canvasを作ってHTMLに突っ込む。
const canvas = document.createElement('canvas');
const context1 = canvas.getContext('2d');
canvas.width = 500;
canvas.height = 500;
document.body.appendChild(canvas);

/*  津島善子 ここから  */
context1.fillStyle = '#adadad';
context1.strokeStyle = '#adadad';
context1.beginPath();
context1.arc(250, 250, 150,  0, (Math.PI*2), false);
context1.stroke();
context1.fill();

/* 顔 白枠 左半分 */
context1.fillStyle = '#fff';
context1.strokeStyle = '#fff';
context1.beginPath();
context1.moveTo(250, 180);
context1.lineTo(230, 180);
context1.lineTo(225, 150);
context1.arc(250, 250, 105,  (Math.PI*17)/12, (Math.PI*2)/2, true);
context1.lineTo(130, 245);
context1.lineTo(120, 300);
context1.lineTo(130, 290);
context1.arc(250, 250, 105,  (Math.PI*2)/3, (Math.PI*1)/2, true);
context1.stroke();
context1.fill();

/* 顔 白枠 右半分 */
context1.fillStyle = '#fff';
context1.strokeStyle = '#fff';
context1.beginPath();
context1.moveTo(250, 180);
context1.lineTo(270, 180);
context1.lineTo(275, 150);
context1.arc(250, 250, 105,  (Math.PI*19)/12, 0, false);
context1.lineTo(370, 245);
context1.lineTo(380, 300);
context1.lineTo(370, 290);
context1.arc(250, 250, 105,  (Math.PI*1)/3, (Math.PI*1)/2, false);
context1.stroke();
context1.fill();

/* 顔 内部 左半分 */
context1.fillStyle = '#adadad';
context1.strokeStyle = '#adadad';
context1.beginPath();
context1.moveTo(250, 200);
context1.lineTo(215, 200);
context1.lineTo(210, 165);
context1.arc(250, 250, 92,  (Math.PI*16)/12, (Math.PI*23)/24, true);
context1.lineTo(140, 255);
context1.lineTo(135, 285);
context1.lineTo(155, 280);
context1.arc(250, 250, 90,  (Math.PI*3)/4, (Math.PI*1)/2, true);
context1.stroke();
context1.fill();

/* 顔 内部 右半分 */
context1.fillStyle = '#adadad';
context1.strokeStyle = '#adadad';
context1.beginPath();
context1.moveTo(250, 200);
context1.lineTo(285, 200);
context1.lineTo(290, 165);
context1.arc(250, 250, 92,  (Math.PI*20)/12, (Math.PI*1)/24, false);
context1.lineTo(360, 255);
context1.lineTo(365, 285);
context1.lineTo(345, 280);
context1.arc(250, 250, 90,  (Math.PI*1)/4, (Math.PI*1)/2, false);
context1.stroke();
context1.fill();


/* 口 */
context1.fillStyle = '#fff';
context1.strokeStyle = '#fff';
context1.beginPath();
context1.moveTo(200, 280);
context1.lineTo(300, 280);
context1.ellipse(250, 280, 50, 35, 0, Math.PI, 0, true);
context1.stroke();
context1.fill();

/* 左キバ */
context1.fillStyle = '#adadad';
context1.strokeStyle = '#adadad';
context1.beginPath();
context1.moveTo(220, 279);
context1.lineTo(225, 290);
context1.lineTo(230, 279);
context1.stroke();
context1.fill();

/* 右キバ */
context1.fillStyle = '#adadad';
context1.strokeStyle = '#adadad';
context1.beginPath();
context1.moveTo(280, 279);
context1.lineTo(275, 290);
context1.lineTo(270, 279);
context1.stroke();
context1.fill();

/* 左眼 */
context1.fillStyle = '#fff';
context1.strokeStyle = '#fff';
context1.beginPath();
context1.ellipse(225, 230, 15, 18, Math.PI*1/6, Math.PI, 0, true);
context1.stroke();
context1.fill();

/* 右眼 */
context1.fillStyle = '#fff';
context1.strokeStyle = '#fff';
context1.beginPath();
context1.ellipse(275, 230, 15, 18, -Math.PI*1/6, Math.PI, 0, true);
context1.stroke();
context1.fill();

/*  ここまで  */
</script>