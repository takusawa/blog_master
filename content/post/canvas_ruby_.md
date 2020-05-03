+++
date = "2017-01-08T16:42:10+09:00"
draft = false
title = ""

+++

<link rel="stylesheet" type="text/css" href="">
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.1/css/bootstrap.min.css">
<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.9.1/jquery.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/embed-js/4.2.1/embed.min.js"></script>

# 黒澤ルビィ
<script>
// canvasを作ってHTMLに突っ込む。
const canvas = document.createElement('canvas');
const context1 = canvas.getContext('2d');
canvas.width = 500;
canvas.height = 500;
document.body.appendChild(canvas);

/*  黒澤ルビィ ここから  */
context1.fillStyle = '#f94a9a';
context1.strokeStyle = '#f94a9a';
context1.beginPath();
context1.arc(250, 250, 150,  0, (Math.PI*2), false);
context1.stroke();
context1.fill();


/* 飴 白枠 */
context1.fillStyle = '#fff';
context1.strokeStyle = '#fff';
context1.beginPath();
context1.arc(230, 200, 90,  0, (Math.PI*2), false);
context1.stroke();
context1.fill();

/* 飴 ピンク */
context1.fillStyle = '#f94a9a';
context1.strokeStyle = '#f94a9a';
context1.beginPath();
context1.arc(230, 200, 75,  0, (Math.PI*2), false);
context1.stroke();
context1.fill();

/* 飴 白 */
context1.fillStyle = '#fff';
context1.strokeStyle = '#fff';
context1.beginPath();
context1.arc(230, 200, 60,  0, (Math.PI*2), false);
context1.stroke();
context1.fill();


/* 取っ手 白枠 */
context1.fillStyle = '#fff';
context1.strokeStyle = '#fff';
context1.beginPath();
context1.moveTo(285, 260);
context1.lineTo(260, 285);
context1.lineTo(311, 380);
context1.lineTo(345, 359);
context1.stroke();
context1.fill();

context1.fillStyle = '#fff';
context1.strokeStyle = '#fff';
context1.beginPath();
context1.ellipse(326, 367, 12, 20, Math.PI/3, 0, Math.PI*2, false);
context1.stroke();
context1.fill();

/* 取っ手 ピンク */
context1.fillStyle = '#f94a9a';
context1.strokeStyle = '#f94a9a';
context1.beginPath();
context1.moveTo(275, 260);
context1.lineTo(260, 266);
context1.lineTo(315, 365);
context1.lineTo(330, 355);
context1.stroke();
context1.fill();

context1.fillStyle = '#f94a9a';
context1.strokeStyle = '#f94a9a';
context1.beginPath();
context1.ellipse(324, 363, 9, 9, Math.PI/3, 0, Math.PI*2, false);
context1.stroke();
context1.fill();

/*  ここから飴部分  */

context1.fillStyle = '#f94a9a';
context1.strokeStyle = '#f94a9a';
context1.beginPath();
context1.ellipse(190, 135, 75, 75, 0, 0, (Math.PI*1)/3, false);
context1.ellipse(162, 170, 75, 75, -(Math.PI*1)/5, (Math.PI*1)/3, 0, true);
context1.stroke();
context1.fill();

context1.fillStyle = '#f94a9a';
context1.strokeStyle = '#f94a9a';
context1.beginPath();
context1.ellipse(158, 215, 75, 75, -(Math.PI*2)/5, 0, (Math.PI*1)/3, false);
context1.ellipse(180, 255, 75, 75, -(Math.PI*3)/5, (Math.PI*1)/3, 0, true);
context1.stroke();
context1.fill();

context1.fillStyle = '#f94a9a';
context1.strokeStyle = '#f94a9a';
context1.beginPath();
context1.ellipse(220, 272, 75, 75, -(Math.PI*4)/5, 0, (Math.PI*1)/3, false);
context1.ellipse(262, 262, 75, 75, -(Math.PI*5)/5, (Math.PI*1)/3, 0, true);
context1.stroke();
context1.fill();

context1.fillStyle = '#f94a9a';
context1.strokeStyle = '#f94a9a';
context1.beginPath();
context1.ellipse(298, 229, 75, 75, (Math.PI*4)/5, 0, (Math.PI*1)/3, false);
context1.ellipse(302, 186, 75, 75, (Math.PI*3)/5, (Math.PI*1)/3, 0, true);
context1.stroke();
context1.fill();

context1.fillStyle = '#f94a9a';
context1.strokeStyle = '#f94a9a';
context1.beginPath();
context1.ellipse(280, 145, 75, 75, (Math.PI*2)/5, 0, (Math.PI*1)/3, false);
context1.ellipse(238, 125, 75, 75, (Math.PI*1)/5, (Math.PI*1)/3, 0, true);
context1.stroke();
context1.fill();

/* 飴 ピンク */
context1.fillStyle = '#f94a9a';
context1.strokeStyle = '#f94a9a';
context1.beginPath();
context1.arc(230, 200, 3,  0, (Math.PI*2), false);
context1.stroke();
context1.fill();


/*  ここまで  */
</script>