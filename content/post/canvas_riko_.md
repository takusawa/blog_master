+++
date = "2017-01-08T16:42:10+09:00"
draft = false
title = ""

+++

<link rel="stylesheet" type="text/css" href="">
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.1/css/bootstrap.min.css">
<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.9.1/jquery.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/embed-js/4.2.1/embed.min.js"></script>

# 桜内梨子
<script>
// canvasを作ってHTMLに突っ込む。
const canvas = document.createElement('canvas');
const context1 = canvas.getContext('2d');
canvas.width = 500;
canvas.height = 500;
document.body.appendChild(canvas);

/*  桜内梨子 ここから  */
context1.fillStyle = '#f76876';
context1.strokeStyle = '#f76876';
context1.beginPath();
context1.arc(250, 250, 150,  0, (Math.PI*2), false);
context1.stroke();
context1.fill();

/****ピアノ白枠*****************/

context1.fillStyle = '#fff';
context1.strokeStyle = '#fff';
context1.beginPath();
context1.moveTo(270, 150);
context1.lineTo(150, 210);
context1.lineTo(150, 250);
context1.lineTo(160, 280);
context1.lineTo(305, 313);
context1.lineTo(310, 200);
context1.stroke();
context1.fill();

context1.fillStyle = '#fff';
context1.strokeStyle = '#fff';
context1.beginPath();
context1.ellipse(160, 260, 20, 20, 0, 0, (Math.PI*2), true);
context1.stroke();
context1.fill();

context1.fillStyle = '#fff';
context1.strokeStyle = '#fff';
context1.beginPath();
context1.ellipse(180, 280, 20, 20, 0, 0, (Math.PI*2), true);
context1.stroke();
context1.fill();

context1.fillStyle = '#fff';
context1.strokeStyle = '#fff';
context1.beginPath();
context1.ellipse(255, 315, 25, 25, 0, 0, (Math.PI*2), true);
context1.stroke();
context1.fill();

context1.fillStyle = '#fff';
context1.strokeStyle = '#fff';
context1.beginPath();
context1.ellipse(290, 300, 25, 25, 0, 0, (Math.PI*2), true);
context1.stroke();
context1.fill();

context1.fillStyle = '#fff';
context1.strokeStyle = '#fff';
context1.beginPath();
context1.ellipse(290, 205, 64, 57, 0, 0, (Math.PI*2), true);
context1.stroke();
context1.fill();

/***ピアノ ピンク枠******************/

/***ピアノ 鍵盤上部分******************/
context1.fillStyle = '#f76876';
context1.strokeStyle = '#f76876';
context1.beginPath();
context1.moveTo(260, 170);
context1.lineTo(175, 215);
context1.lineTo(265, 240);
context1.lineTo(300, 222);
context1.stroke();
context1.fill();

/***ピアノ 鍵盤譜面台部分******************/
context1.fillStyle = '#f76876';
context1.strokeStyle = '#f76876';
context1.beginPath();
context1.moveTo(175, 225);
context1.lineTo(175, 240);
context1.lineTo(265, 265);
context1.lineTo(265, 250);
context1.stroke();
context1.fill();

/***ピアノ 鍵盤部分******************/
context1.fillStyle = '#f76876';
context1.strokeStyle = '#f76876';
context1.beginPath();
context1.moveTo(160, 250);
context1.lineTo(160, 262);
context1.lineTo(260, 290);
context1.lineTo(260, 278);
context1.stroke();
context1.fill();

/***ピアノ 側面******************/
context1.fillStyle = '#f76876';
context1.strokeStyle = '#f76876';
context1.beginPath();
context1.moveTo(265, 265);
context1.lineTo(265, 250);
context1.lineTo(295, 235);
context1.lineTo(295, 305);
context1.lineTo(285, 305);
context1.lineTo(285, 280);
context1.stroke();
context1.fill();

/***ピアノ 右前足******************/
context1.fillStyle = '#f76876';
context1.strokeStyle = '#f76876';
context1.beginPath();
context1.moveTo(260, 285);
context1.lineTo(260, 320);
context1.lineTo(250, 320);
context1.lineTo(250, 285);
context1.stroke();
context1.fill();

/***ピアノ 左足******************/
context1.fillStyle = '#f76876';
context1.strokeStyle = '#f76876';
context1.beginPath();
context1.moveTo(185, 265);
context1.lineTo(185, 285);
context1.lineTo(175, 285);
context1.lineTo(175, 265);
context1.stroke();
context1.fill();

/***ピアノ 鍵盤斜め線******************/
context1.fillStyle = '#f76876';
context1.strokeStyle = '#f76876';
context1.beginPath();
context1.moveTo(260, 290);
context1.lineTo(275, 275);
context1.lineTo(275, 260);
context1.lineTo(250, 290);
context1.stroke();
context1.fill();

/***ピアノ 鍵盤上部******************/
context1.fillStyle = '#f76876';
context1.strokeStyle = '#f76876';
context1.beginPath();
context1.moveTo(175, 225);
context1.lineTo(175, 240);
context1.lineTo(265, 265);
context1.lineTo(265, 250);
context1.stroke();
context1.fill();

/***ピアノ 丸い部分******************/
context1.fillStyle = '#f76876';
context1.strokeStyle = '#f76876';
context1.beginPath();
context1.ellipse(285, 187, 35, 25, 0, 0, (Math.PI*2), true);
context1.stroke();
context1.fill();

/***ピアノ 白枠で******************/
context1.fillStyle = '#fff';
context1.strokeStyle = '#fff';
context1.beginPath();
context1.ellipse(300, 220, 25, 12, 0, 0, (Math.PI*2), true);
context1.stroke();
context1.fill();

/***ピアノ 曲線に見せるための苦肉の策******************/
context1.fillStyle = '#fff';
context1.strokeStyle = '#fff';
context1.beginPath();
context1.moveTo(320, 200);
context1.lineTo(300, 208);
context1.lineTo(310, 213);
context1.stroke();
context1.fill();

/***ピアノ ピンク 小さいティアドロップ******************/
context1.fillStyle = '#f76876';
context1.strokeStyle = '#f76876';
context1.beginPath();
context1.arc(290, 200, 35,  (Math.PI*1)/3, 0, true);
context1.lineTo(308, 215);
context1.arc(308, 222, 7,  (Math.PI*4)/2, 0, true);
context1.stroke();
context1.fill();

/*********************/
</script>