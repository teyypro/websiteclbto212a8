
<script>
    import { address } from "../../store";
</script>
<style>

    /* Header */
    .header {
        background-color: #0D47A1;
color: white;
padding: 20px;
font-size: 2.5em;
font-weight: bold;
text-align: left;
display: flex
;
align-items: flex-end;
gap: 1rem;
    }
    /* Navigation Menu */
    .nav {
        background-color: #1976D2;
        overflow: hidden;
    }
    .nav a {
        float: left;
        display: block;
        color: #f4f4f4;
        text-align: center;
        padding: 14px 16px;
        text-decoration: none;
    }
    .nav a:hover {
        background-color: #1565C0;
    }
    /* Main Content */
    .container {
        max-width: 1200px;
        margin: 20px auto;
        background: white;
        padding: 30px;
        border-radius: 5px;
        box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    }
    .section {
        margin-bottom: 40px;
    }
    .section h2 {
        color: #0D47A1;
        margin-bottom: 20px;
    }
    .section p, .section ul {
        line-height: 1.6;
        font-size: 16px;
        text-align: justify;
    }
    .highlight {
        color: #0D47A1;
        font-weight: bold;
    }
    /* Image Gallery */
    .gallery {
display: flex;
flex-wrap: wrap;
gap: 15px;
}

.image-item {
width: calc(33.333% - 10px);
text-align: center;
min-width: 200px;
}

.image-item img {
width: 100%;
border-radius: 5px;
min-width: 200px;
}

.caption {
margin-top: 8px;
font-size: 14px;
color: #555;
}
    /* Footer */
    .footer {
        background-color: #0D47A1;
        color: white;
        padding: 15px;
        font-size: 14px;
        text-align: center;
    }

    /* Responsive */
    @media screen and (max-width: 768px) {
        .gallery img {
            width: calc(50% - 10px);
        }
    }
    @media screen and (max-width: 480px) {
        .nav a {
            float: none;
            width: 100%;
        }
        .gallery img {
            width: 100%;
        }
    }
    .header img{
        border-radius: 100%;
height: 12rem;
    }
</style>


<div class="header">
    <img src='images/logoclb/crew.jpg'>
    Câu Lạc Bộ S&B Crew - THPT Nguyễn Trân
</div>

<div class="nav">
    <a href="#gioithieu">Giới Thiệu</a>
    <a href="#hoatdong">Hoạt Động</a>
    <a href="#hinhanh">Hình Ảnh</a>
    <a href="#tintuc">Tin Tức</a>
    <a href="#lienhe">Liên Hệ</a>
</div>

<div class="container">
    <div class="section" id="gioithieu">
        <h2>Giới Thiệu</h2>
        <p>CLB Nhảy S&B được thành lập vào ngày 8/4/2021 do một số bạn có niềm đam mê với nhảy. CLB là nơi các bạn học sinh yêu thích vũ đạo có thể học hỏi và luyện tập các thể loại nhảy hiện đại như Hip-hop, Kpop, street dance.</p>
    </div>

    <div class="section" id="hoatdong">
        <h2>Hoạt Động Chính</h2>
        <p>Nhảy, múa cho các sự kiện trong và ngoài trường,hoạt động theo sự quản lý của nhà trường mang đến niềm vui và giải trí cho mọi người.
        </p>
    </div>

    <div class="section" id="hinhanh">
        <h2>Hình Ảnh Hoạt Động</h2>
        <div class="gallery">
            <div class="image-item">
                <img src="images/sbcrew/1.jpg" alt="Biểu diễn sân khấu">
                <p class="caption"></p>
            </div>
            <div class="image-item">
                <img src="images/sbcrew/2.jpg" alt="Luyện tập nhóm">
                <p class="caption"></p>
            </div>
            <div class="image-item">
                <img src="images/sbcrew/3.jpg" alt="Cuộc thi vũ đạo">
                <p class="caption"></p>
            </div>
        </div>
    </div>

    <div class="section" id="tintuc">
        <h2>Tin Tức & Sự Kiện</h2>
        <p>Cập nhật những hoạt động mới nhất của CLB!</p>
        <ul>
            <li><a href = {`${address}/sbcrew/hd1`}>S&B CREW TUYỂN QUÂN – THIẾU BẠN LÀ THIẾU TẤT CẢ!</a></li>
            <li><a href = {`${address}/sbcrew/hd2`}>MÓN QUÀ TRI ÂN ĐẶC BIỆT TỪ S&B Crew!</a></li>
            <li><a href = {`${address}/sbcrew/hd3`}>TRUNG THU 2024 CỦA NTS-ER CÓ GÌ?</a> </li>
        </ul>
    </div>

    <div class="section" id="lienhe">
        <h2>Tham Gia Cùng Chúng Tôi</h2>
        <p>Bạn có đam mê nhảy múa và muốn tỏa sáng? Hãy tham gia ngay!</p>
        <p>Email: <a href="mailto:sbcrew@nguyentran.edu.vn" class="highlight">sbcrew@nguyentran.edu.vn</a></p>
        <p>Facebook: <a href="https://www.facebook.com/sbcrewnguyentran" class="highlight">@sbcrewnguyentran</a></p>
        <p>Hoặc đăng ký trực tiếp tại văn phòng Đoàn trường.</p>
    </div>
</div>

<div class="footer">
    © 2025 Câu Lạc Bộ S&B Crew - THPT Nguyễn Trân | Thiết kế bởi CLB S&B Crew
</div>


