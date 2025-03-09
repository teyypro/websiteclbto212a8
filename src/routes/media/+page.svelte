
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
        <img src = 'images/logoclb/media.jpg'>
        Câu Lạc Bộ Truyền Thông - THPT Nguyễn Trân
    </div>

    <div class="nav">
        <a href="#gioithieu">Giới Thiệu</a>
        <a href="#hoatdong">Hoạt Động</a>
        <a href="#hinhanh">Hình Ảnh</a>
        <a href="#tintuc">Tin Tức</a>
        <a href="#lienhe">Liên Hệ</a>
    </div>

    <div class="container">
        <!-- Giới Thiệu -->
        <div class="section" id="gioithieu">
            <h2>Giới Thiệu</h2>
            <p>Câu lạc bộ Truyền thông Trường THPT Nguyễn Trân, thành lập ngày 4/9/2021, là cầu nối thông tin giữa học sinh, giáo viên và phụ huynh, mang đến tin tức hữu ích, lan tỏa tri thức và truyền cảm hứng qua từng sản phẩm truyền thông.
            </p>
        </div>

        <!-- Hoạt Động Chính -->
        <div class="section" id="hoatdong">
            <h2>Hoạt Động Chính</h2>
            <ul>
                <li>Quản lý Fanpage và các kênh truyền thông của trường.</li>
                <li>Sản xuất video, chụp ảnh cho các sự kiện và hoạt động của trường.</li>
                <li>Viết bài, thiết kế ấn phẩm truyền thông và quảng bá cho các chương trình.</li>
                <li>Hỗ trợ tổ chức các sự kiện ngoại khóa và cuộc thi của trường.</li>
              </ul>
              
        </div>

        <!-- Hình Ảnh Hoạt Động -->
        <div class="section" id="hinhanh">
            <h2>Hình Ảnh Hoạt Động</h2>
            <div class="gallery">
                <div class="image-item">
                    <img src="images/media/anh1.jpg" alt="Hoạt động 1">
                    <p class="caption">Chương trình khoá xinh ngày xuân</p>
                </div>
                <div class="image-item">
                    <img src="images/media/anh2.jpg" alt="Hoạt động 2">
                    <p class="caption">Vui trung thu</p>
                </div>
                <div class="image-item">
                    <img src="images/media/anh3.jpg" alt="Hoạt động 3">
                    <p class="caption">Tiếp sức mùa thi</p>
                </div>
            </div>
            
        </div>

        <!-- Tin Tức -->
        <div class="section" id="tintuc">
            <h2>Tin Tức & Sự Kiện</h2>
            <p>Chúng tôi thường xuyên cập nhật những tin tức mới nhất về các hoạt động của CLB và trường. Hãy theo dõi để không bỏ lỡ những sự kiện hấp dẫn!</p>
            <ul>
                <li><a href = {`${address}/media/hd1`}>KHÓA XINH NGÀY XUÂN" - TRAO YÊU THƯƠNG - NHẬN NỤ CƯỜI</a></li>
                <li><a href = {`${address}/media/hd2`}>BÁO TƯỜNG GENZ NGÀN LỜI TRI ÂN</a></li>
                <li><a href = {`${address}/media/hd3`}>20/11 TRI ÂN NHỮNG NGƯỜI LÁI ĐÒ TẬN TỤY</a></li>
            </ul>
        </div>

        <!-- Liên Hệ Tham Gia -->
        <div class="section" id="lienhe">
            <h2>Tham Gia Cùng Chúng Tôi</h2>
            <p>Nếu bạn muốn trở thành một phần của Câu Lạc Bộ Truyền Thông, hãy liên hệ với chúng tôi qua các kênh sau:</p>
            <p>Facebook: <a href="https://www.facebook.com/ntsmediaclub" class="highlight">@clbtruyenthongnguyentran</a></p>
            <p>Gmail: <a href="mailto:ntsmediaclub@gmail.com" class="highlight">ntsmediaclub@gmail.com</a></p>
            <p>Instagram: <a href="https://www.instagram.com/ntsmediaclub" class="highlight">@ntsmediaclub</a></p>
        </div>
        
    </div>

    <div class="footer">
        © 2025 Câu Lạc Bộ Truyền Thông - THPT Nguyễn Trân | Thiết kế bởi CLB Truyền Thông
    </div>


