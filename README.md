<html>
<head>
<meta charset="UTF-8">
<title>Kỷ niệm 26/3</title>

<style>

body{
    margin:0;
    
    background:#f6e27a;
}

/* bố cục toàn trang */
.layout{
    width:100%;
}

/* khung chính */
.container{
    max-width:1100px;
    width:90%;
    margin:40px auto;
    padding:40px;

    border:4px solid red;
    border-radius:10px;
    background:#fff8c6;
    box-shadow:0 0 15px rgba(0,0,0,0.2);
}

/* box bên phải */
.sidebar{
    width:300px;
    border:3px solid red;
    border-radius:10px;
    background:#fff8c6;
    padding:15px;
    box-shadow:0 0 10px rgba(0,0,0,0.3);

    position:fixed;
    bottom:20px;
    right:20px;
    font-weight:bold;
}

.sidebar h3{
    text-align:center;
    color:red;
}

.sidebar p{
    font-size:16px;
    margin:10px 0;
}

/* logo */
.im{
    text-align:center;
}

.im img{
    max-width:750px;
    width:100%;
}

/* chữ chạy */
.marquee{
    width:100%;
    overflow:hidden;
    border:1px solid #ccc;
    background:#f6e27a;
    margin-top:10px;
}

.marquee p{
    display:inline-block;
    white-space:nowrap;
    animation:chaychu 12s linear infinite;
    font-size:18px;
    font-weight:bold;
    color:red;
}

@keyframes chaychu{
    from{transform:translateX(100%);}
    to{transform:translateX(-100%);}
}

/* phần đầu */
.header{
    display:flex;
    align-items:center;
    margin-top:20px;
}

.left{
    width:40%;
}

.left img{
    width:100%;
}

.right{
    width:60%;
    text-align:center;
}

/* tiêu đề */
.title{
    color:red;
    font-size:28px;
    font-weight:bold;
    text-align:center;
}

.date{
    color:blue;
    font-size:20px;
    margin-top:5px;
    font-weight:bold;
    text-align:center;
}
@import url('https://fonts.googleapis.com/css2?family=Dancing+Script:wght@700&display=swap');
.text{ 
    margin-top:20px;
    font-size:18px;
    color:#c0392b;
    line-height:1.6;
    font-weight:bold;
    font-family: 'Dancing Script', cursive !important;
}

.l{
    font-weight:bold;
    text-align:center;
    font-size:18px;
    color:#c0392b;
    line-height:1.6;
    font-family: 'Dancing Script', cursive !important;

}
.im{
    display:flex;
    justify-content:center;
    gap:10px;
}

.im img{
    width:48%;
}

.video{
    text-align:center;
    margin-top:20px;
}
.t{
    margin-top:10px;
    font-size:20px;
    color:#c0392b;
    line-height:0.4;
    font-weight:bold;
}

/* nút đóng */
.close-btn{
    position:absolute;
    top:5px;
    right:8px;
    border:none;
    background:red;
    color:white;
    font-weight:bold;
    cursor:pointer;
}
/* nút mở */
.open-btn{
    position:fixed;
    bottom:20px;
    right:20px;
    padding:10px 15px;
    background:red;
    color:white;
    border:none;
    border-radius:6px;
    cursor:pointer;
    display:none;
}
</style>
</head>
<body>
<script>
function dongBox(){
    document.getElementById("sidebar").style.display="none";
    document.getElementById("openBtn").style.display="block";
}

function moBox(){
    document.getElementById("sidebar").style.display="block";
    document.getElementById("openBtn").style.display="none";
}
</script>
<div style="width: 100%; margin: 0; padding: 0; overflow: hidden;">
    <img src="https://toplist.vn/images/800px/tu-hao-doan-thanh-nien-127778.jpg" alt="Banner Đoàn" style="width: 100%; height: auto; display: block;">
</div>
<div class="marquee">
<p>CHÀO MỪNG NGÀY THÀNH LẬP ĐOÀN THANH NIÊN CỘNG SẢN HỒ CHÍ MINH 26/03</p>
</div>
<div class="layout">
<div class="container">
<div class="header">
<div class="left">
<img src="https://cdn.thuvienphapluat.vn/phap-luat/2022-2/QB/180324/DOAN-TNCS.jpg" alt="Đoàn TNCS Hồ Chí Minh thành lập khi nào? Người đoàn viên Đoàn TNCS Hồ Chí Minh đầu tiên là ai?" data-adbro-processed="true">
</div>
<div class="right">
<div class="title">
KỶ NIỆM 95 NĂM NGÀY THÀNH LẬP<br>
ĐOÀN TNCS HỒ CHÍ MINH
</div>
<div class="date">
(26/3/1931 - 26/3/2026)
</div>
<div class="text">
Ngày 26/3 hằng năm là dịp để tuổi trẻ Việt Nam cùng nhau ôn lại truyền thống vẻ vang của Đoàn Thanh niên Cộng sản Hồ Chí Minh – tổ chức được thành lập vào ngày 26/3/1931. Đây là nơi tập hợp, giáo dục và định hướng lý tưởng cho thế hệ thanh niên Việt Nam.
</div>
<br>
<div class="l">
    Trong suốt chặng đường lịch sử của dân tộc, thanh niên luôn là lực lượng xung kích trong học tập, lao động và bảo vệ Tổ quốc. Biết bao thế hệ đoàn viên đã cống hiến sức trẻ, lòng nhiệt huyết để góp phần xây dựng và phát triển đất nước.

Ngày nay, thanh niên tiếp tục phát huy tinh thần năng động, sáng tạo thông qua nhiều phong trào ý nghĩa như học tập tốt, tham gia hoạt động tình nguyện và rèn luyện bản thân. Những hoạt động đó giúp tuổi trẻ trưởng thành và đóng góp tích cực cho xã hội.
</div>
</div>
</div>
<hr>
<div style="text-align: center;">
    <h2 style="color: #d32f2f; font-family: Dancing Script; margin-bottom: 20px;">MỘT SỐ BỨC ẢNH TIÊU BIỂU </h2>
</div>
<div class="im">
<img src="https://daknong.1cdn.vn/2024/03/20/storage-vnportal.vnpt.vn-ndh-ubnd-4930-tn1882022-_ngay-thanh-lap-doan-9.jpg">
<img src="https://daknong.1cdn.vn/2024/03/22/phuong3.tayninh.gov.vn-uploads-news-2022_11-_pano-co-dong-ngay-30-2.jpg">
</div>
<hr>
<div class="video" style="text-align: center; margin: 30px 0;">
    <h2 style="color: #d32f2f; font-family: Dancing Script; margin-bottom: 20px;">VIDEO TUYÊN TRUYỀN VỀ NGÀY THÀNH LẬP ĐOÀN </h2>
    <div style="position: relative; display: inline-block; width: 700px; max-width: 95%;">
        <a href="https://www.youtube.com/watch?v=XUaAevUdIxw" target="_blank" style="text-decoration: none;">
            <img src="thumb_video.jpg" 
                 alt="Video Đoàn Thanh Niên" 
                 style="width: 100%; border-radius: 12px; box-shadow: 0 10px 20px rgba(0,0,0,0.2); display: block; border: 2px solid #ddd;">
            <div style="position: absolute; top: 50%; left: 50%; transform: translate(-50%, -50%); filter: drop-shadow(0 2px 5px rgba(0,0,0,0.5));">
                <svg height="80" width="80" viewBox="0 0 68 48">
                    <path d="M66.52,7.74c-0.78-2.93-2.49-5.41-5.42-6.19C55.79,0.13,34,0.13,34,0.13s-21.79,0-27.1,1.42C3.97,2.33,2.27,4.81,1.48,7.74C0.06,13.05,0,24,0,24s0.06,10.95,1.48,16.26c0.78,2.93,2.49,5.41,5.42,6.19C12.21,47.87,34,47.87,34,47.87s21.79,0,27.1-1.42c2.93-0.78,4.64-3.26,5.42-6.19C67.94,34.95,68,24,68,24S67.94,13.05,66.52,7.74z" fill="#f00"></path>
                    <path d="M 45,24 27,14 27,34" fill="#fff"></path>
                </svg>
            </div>
            <p style="margin-top: 15px; color: #d32f2f; font-weight: bold; font-family: sans-serif;">
                ▶ Xem video trên YouTube
            </p>
        </a>
    </div>
</div>
<hr>
<div class="t">
    <p>THPT Ea Súp</p>
    <p>Chi đoàn 12A1</p>
    <p>Nhóm 1</p>
    <p>Người làm: Đức Phong</p>
</div>
<div class="sidebar" id="sidebar">
    <button class="close-btn" onclick="dongBox()">✖</button>
<h3>Một Số thông Tin cơ bản</h3>
<p>Ngày thành lập</p>
<p>26/03/1931</p>
<p>Ý nghĩa</p>
<p>- Giáo dục và phát triển thanh niên Việt Nam</p>
<p>Hoạt động</p>
<p>• Văn nghệ</p>
<p>• Thể thao</p>
<p>• Sinh hoạt đoàn</p>
<p>Kết quả</p>
<p>• Ngày 26/03 hằng năm là dịp để thanh niên cả nước ôn lại truyền thống vẻ vang của Đoàn Thanh niên Cộng sản Hồ Chí Minh.
Thông qua các hoạt động kỷ niệm, phong trào thanh niên ngày càng phát triển mạnh mẽ và thu hút nhiều đoàn viên tham gia.
</p>
</div>
<button class="open-btn" id="openBtn" onclick="moBox()">Mở</button>
</div>
</div>
