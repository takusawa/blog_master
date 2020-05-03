+++
date = "2017-01-08T16:42:10+09:00"
draft = false
title = ""

+++

<link rel="stylesheet" type="text/css" href="">
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.1/css/bootstrap.min.css">
<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.9.1/jquery.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/embed-js/4.2.1/embed.min.js"></script>

# 松浦果南
<script>
// canvasを作ってHTMLに突っ込む。
const canvas = document.createElement('canvas');
const context1 = canvas.getContext('2d');
canvas.width = 500;
canvas.height = 500;
document.body.appendChild(canvas);

/*  松浦果南 ここから  */
context1.fillStyle = '#36d6a7';
context1.strokeStyle = '#36d6a7';
context1.beginPath();
context1.arc(250, 250, 150,  0, (Math.PI*2), false);
context1.stroke();
context1.fill();

/****白枠*****************/

context1.fillStyle = '#fff';
context1.strokeStyle = '#fff';
context1.beginPath();
context1.ellipse(250, 240, 100, 100, (Math.PI*1)/4, 0, (Math.PI), true);
context1.stroke();
context1.fill();


context1.fillStyle = '#fff';
context1.strokeStyle = '#fff';
context1.beginPath();
context1.ellipse(300, 160, 30, 20, 0, 0, (Math.PI*2), true);
context1.stroke();
context1.fill();


context1.fillStyle = '#fff';
context1.strokeStyle = '#fff';
context1.beginPath();
context1.ellipse(310, 315, 15, 25, 0, 0, (Math.PI*2), true);
context1.stroke();
context1.fill();

context1.fillStyle = '#fff';
context1.strokeStyle = '#fff';
context1.beginPath();
context1.ellipse(280, 315, 15, 25, 0, 0, (Math.PI*2), true);
context1.stroke();
context1.fill();

context1.fillStyle = '#fff';
context1.strokeStyle = '#fff';
context1.beginPath();
context1.ellipse(195, 175, 30, 20, 0, 0, (Math.PI*2), true);
context1.stroke();
context1.fill();

context1.fillStyle = '#fff';
context1.strokeStyle = '#fff';
context1.beginPath();
context1.ellipse(203, 205, 35, 20, 0, 0, (Math.PI*2), true);
context1.stroke();
context1.fill();

context1.fillStyle = '#fff';
context1.strokeStyle = '#fff';
context1.beginPath();
context1.ellipse(210, 270, 60, 60, (Math.PI*1)/3, (Math.PI), 0, true);
context1.stroke();
context1.fill();

context1.fillStyle = '#fff';
context1.strokeStyle = '#fff';
context1.beginPath();
context1.ellipse(220, 308, 30, 20, 0, 0, (Math.PI*2), true);
context1.stroke();
context1.fill();

context1.fillStyle = '#fff';
context1.strokeStyle = '#fff';
context1.beginPath();
context1.ellipse(250, 290, 20, 20, 0, 0, (Math.PI*2), true);
context1.stroke();
context1.fill();

context1.fillStyle = '#fff';
context1.strokeStyle = '#fff';
context1.beginPath();
context1.moveTo(180, 220);
context1.lineTo(180, 310);
context1.lineTo(250, 290);
context1.lineTo(310, 320);
context1.lineTo(310, 220);
context1.stroke();
context1.fill();


/****イルカ 右*****************/

context1.fillStyle = '#36d6a7';
context1.strokeStyle = '#36d6a7';
context1.beginPath();
context1.ellipse(245, 175, 60, 15, 0, 0, (Math.PI*2), true);
context1.stroke();
context1.fill();

context1.fillStyle = '#36d6a7';
context1.strokeStyle = '#36d6a7';
context1.beginPath();
context1.ellipse(225, 195, 30, 9, 0, 0, (Math.PI*2), true);
context1.stroke();
context1.fill();

context1.fillStyle = '#36d6a7';
context1.strokeStyle = '#36d6a7';
context1.beginPath();
context1.ellipse(252, 243, 55, 12, (Math.PI*1)/4, 0, (Math.PI*1), true);
context1.lineTo(300, 170);
context1.lineTo(300, 280);
context1.lineTo(290, 290);
context1.stroke();
context1.fill();

context1.fillStyle = '#36d6a7';
context1.strokeStyle = '#36d6a7';
context1.beginPath();
context1.ellipse(285, 170, 30, 12, -(Math.PI*1)/12, 0, (Math.PI*2), true);
context1.stroke();
context1.fill();

context1.fillStyle = '#36d6a7';
context1.strokeStyle = '#36d6a7';
context1.beginPath();
context1.ellipse(300, 235, 30, 60, 0, (Math.PI*1)/2, (Math.PI*3)/2, true);
context1.stroke();
context1.fill();

context1.fillStyle = '#36d6a7';
context1.strokeStyle = '#36d6a7';
context1.beginPath();
context1.ellipse(305, 300, 8, 20, -(Math.PI*1)/12, 0, (Math.PI*2), true);
context1.stroke();
context1.fill();

context1.fillStyle = '#36d6a7';
context1.strokeStyle = '#36d6a7';
context1.beginPath();
context1.ellipse(290, 300, 8, 20, (Math.PI*1)/12, 0, (Math.PI*2), true);
context1.stroke();
context1.fill();

/****イルカ 左*****************/

context1.fillStyle = '#36d6a7';
context1.strokeStyle = '#36d6a7';
context1.beginPath();
context1.ellipse(205, 270, 45, 45, 0, (Math.PI*4)/3, (Math.PI*1)/3, true);
context1.ellipse(225, 305, 5, 5, 0, (Math.PI*1)/3, (Math.PI*4)/3, true);
context1.ellipse(215, 287, 15, 15, 0, (Math.PI*1)/3, (Math.PI*4)/3, false);
context1.ellipse(206, 272, 2, 2, 0, (Math.PI*1)/3, (Math.PI*4)/3, true);
context1.ellipse(208, 300, 30, 30, 0, (Math.PI*9)/6, (Math.PI*7)/6, true);
context1.ellipse(195, 255, 20, 20, 0, (Math.PI*1)/3, (Math.PI*4)/3, false);
context1.ellipse(183, 234, 3, 3, 0, (Math.PI*1)/3, (Math.PI*4)/3, true);
context1.stroke();
context1.fill();

/****ボール*****************/

context1.fillStyle = '#36d6a7';
context1.strokeStyle = '#36d6a7';
context1.beginPath();
context1.ellipse(225, 275, 10, 10, 0, 0, (Math.PI*2), true);
context1.stroke();
context1.fill();

context1.fillStyle = '#36d6a7';
context1.strokeStyle = '#36d6a7';
context1.beginPath();
context1.ellipse(245, 255, 5, 5, 0, 0, (Math.PI*2), true);
context1.stroke();
context1.fill();
</script>