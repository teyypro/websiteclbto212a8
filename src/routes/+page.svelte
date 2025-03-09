<script>
    import { address } from "../store";
   
</script>

<style>

        h1 {
            font-size: 2.5rem;
    text-align: center;
        }
        p {
            font-size: 1.2rem;
    color: #555;
    margin: auto;
    line-height: 1.4;
        }
    
        .footer {
            margin-top: 40px;
            font-size: 16px;
            color: #555;
        }
        .highlight {
            font-weight: bold;
    color: #e74c3c;
    width: 100%;
    border-top: 1px solid #eeeeee;
    padding-top: 8px;
    margin-top: 10px;
        }
     

        #background_header{
        
    background-size: cover;
    background-repeat: none;
    background-position: center center;
    position: absolute;
    width: 100%;
    height: 100%;
    top: 0;
    left: 0;
        }
        header{
            height: 65vh;
    top: 0rem;
    position: relative;
    text-align: center;
    display: flex
;
    align-items: center;
    justify-content: center;
}
        header p{
            font-size: 3rem;
    z-index:1;
    font-weight: bold;
    color: #ffffff;
        }
        #overlay{
            position: absolute;
    width: 100%;
    height: 100%;
    background-color: rgba(0, 0, 0, 0.6); /* 0.5 = 50% tối */
        }

        main{
            position: relative;
    padding-block: 12vh;
    padding-inline: 6vw;
        }
        .findmore{
            height: 3rem;
    padding-inline: 2rem;
    background-color: #e0e1dd;
    font-size: 1.4rem;
    margin-top: 1rem;
    border-radius: 1rem;
    color: #415a77;
    font-weight:bold;
        }
        .findmore:hover{
            background-color: #778da9;
            color:white;
            
        }

        @media screen and (max-width: 768px) {
            #logo p {
                display: none;
            }
            
        }
        @media screen and (max-width: 480px) {
       
        }
        a{
            text-decoration: none;
            color: #415a77;
        }

        .club-container {
            display: flex
;
    flex-wrap: wrap;
    justify-content: center;
    gap: 20px;
    margin-top: 5vh;
    margin-right: -3vw;
    margin-left: -3vw;
    }
    .club-card:nth-child(3){
        border: 5px solid #FDB5D7;
    }
 .club-card:nth-child(1){
        border: 5px solid #5CE1E6;
    }
    .club-card:nth-child(2){
        border: 5px solid #9996E7;
    }
    
    .club-card {
        flex: 1 1 300px;
        max-width: 400px;
        padding: 20px;
        border: 1px solid #ddd;
        border-radius: 15px;
        text-align: center;
    }

  
    </style>


        <header>
            <div id = "background_header" style={`background-image: url('${address}/images/ntscloub.jpg');`}></div>
            <div id = "overlay"></div>
           <p>CÁC CÂU LẠC BỘ<br>TRƯỜNG THPT NGUYỄN TRÂN</p>
        </header>

        <main>
    <h1>🎓 Giới Thiệu Câu Lạc Bộ - THPT Nguyễn Trân</h1>
    <p>
        Câu lạc bộ tại Trường THPT Nguyễn Trân đóng vai trò quan trọng trong việc giúp học sinh rèn luyện tư duy, phát triển kỹ năng sống, tinh thần đồng đội và giao tiếp. Nhà trường luôn chú trọng tổ chức các hoạt động ngoại khóa đa dạng, từ học thuật, nghệ thuật, thể thao đến công nghệ và hoạt động xã hội, tạo điều kiện để học sinh khám phá sở thích, trau dồi năng khiếu và phát triển bản thân. Tham gia câu lạc bộ không chỉ nâng cao kỹ năng chuyên môn mà còn rèn luyện khả năng làm việc nhóm, giải quyết vấn đề, mở rộng mối quan hệ và giảm căng thẳng sau giờ học. Nhờ đó, Trường THPT Nguyễn Trân không chỉ là nơi cung cấp tri thức mà còn giúp học sinh phát triển toàn diện về cả thể chất lẫn tinh thần. Dưới đây là ba câu lạc bộ tiêu biểu giúp bạn khám phá đam mê, trau dồi kỹ năng và kết nối với bạn bè. Hãy tham gia ngay để trải nghiệm những hoạt động thú vị!

    </p>

    <div class="club-container">
        <div class="club-card">
            <h2>💡 MEDIA CLUB</h2>
            <p>
                Câu lạc bộ Truyền thông (Media Club) là nơi dành cho những bạn trẻ yêu thích viết lách, nhiếp ảnh, thiết kế, quay phim và sáng tạo nội dung. Câu lạc bộ chuyên đưa tin về sự kiện trường, phỏng vấn, quay dựng video và quản lý kênh truyền thông. Đây là môi trường lý tưởng để rèn luyện kỹ năng báo chí, truyền thông, tư duy sáng tạo, làm việc nhóm và giao tiếp. Tham gia câu lạc bộ, học sinh có cơ hội thể hiện cá tính, học hỏi thực tế và lan tỏa những câu chuyện ý nghĩa trong cộng đồng trường học.
            </p>
            <p class="highlight">🕒 Thời gian sinh hoạt:</p>
            <p>📅 Mỗi Thứ 5, từ 15:30 - 17:30</p>
            <p>📍 Địa điểm: Phòng 1</p>
            <button class='findmore'><a href={`${address}/media`}>Find more!</a></button>
        </div>
        
        <div class="club-card">
            <h2>😎 S&B DANCE CLUB</h2>
            <p>
                CLB nhảy S&B là một CLB sôi động, náo nhiệt và tràn đầy năng lượng tích cực. Đây là các tiêu chí mà S&B CREW đặt ra để mang đến cho các bạn một không gian trải nghiệm nghệ thuật đầy thú vị. Dù "Tuổi đời" còn non trẻ nhưng S&B sẽ cố gắng chinh phục mục tiêu đề ra để đem đến một "món ăn" tinh thần không thể thiếu đối với mọi người theo dõi và yêu quý S&B.
            </p>
            <p class="highlight">🕒 Thời gian sinh hoạt:</p>
            <p>📅 Thứ 4 & Chủ Nhật, từ 17:00 - 19:00</p>
            <p>📍 Địa điểm: sân khấu trường</p>
            <button class='findmore'><a href={`${address}/sbcrew`}>Find more!</a></button>
        </div>
        
        <div class="club-card">
            <h2>🎤 FEMB CLUB</h2>
            <p>
                CLB hát FEMB của Trường THPT Nguyễn Trân là một môi trường năng động, nơi các bạn trẻ có chung niềm đam mê âm nhạc có thể gặp gỡ, học hỏi và cùng nhau sáng tạo. Khi tham gia câu lạc bộ, thành viên không chỉ được phát triển kỹ năng âm nhạc như ca hát, chơi nhạc cụ hay phong cách biểu diễn mà còn có cơ hội thể hiện tài năng trên sân khấu qua các sự kiện âm nhạc lớn nhỏ trong và ngoài trường. Bên cạnh đó, câu lạc bộ còn tổ chức nhiều hoạt động thú vị, giúp các thành viên mở rộng mối quan hệ và kết nối với những người có chung sở thích.
            </p>
            <p class="highlight">🕒 Thời gian sinh hoạt:</p>
            <p>📅 Mỗi Thứ 6, từ 16:00 - 18:00</p>
            <p>📍 Địa điểm: sân trường</p>
            <button class='findmore'><a href={`${address}/femb`}>Find more!</a></button>
        </div>
    </div>
    
    

        <div class="footer">
            📞 <b>Liên hệ:</b> 0123 456 789 | ✉ <b>Email:</b> clb@nguyentran.edu.vn<br>
            🌍 <b>Website:</b> <a href="#">www.nguyentran.edu.vn/clb</a><br>
            👨‍💻 <b>Creators:</b> Kiều Oanh, Tú Quyên, Vũ Luân, Kim Hân, Thiên Hương, Phi Quý, Công Huyền, Huỳnh Thi 12A4
        </div>
    </main>




