<!DOCTYPE html>
<html>
<head>
	<title></title>
	<meta charset="utf-8">
	<link rel="stylesheet" type="text/css" href="style.css">
	<style>
		  html, body {
			  margin:0;
			  padding:40px;
			  background: #ffffff;
			  color: #666666;
			  line-height: 1.25em;
		  }
		  #outer {
			  position: absolute;
			  top: 50%;
			  left: 50%;
			  width: 1px;
			  height: 1px;
			  overflow: visible;
		  }
		  #canvasContainer {
			  position: absolute;
			  width: 1000px;
			  height: 560px;
			  top: -280px;
			  left: -500px;
		  }
		  canvas {
			  border: 1px solid #333333;
		  }
		  a {
		  	  margin: 
			  color: #cb0000;
			  text-decoration: none;
			  font-weight: bold;
		  }
		  a:hover {
			  color: #FFFFFF;
		  }
		  #output {
			  font-family: Arial, Helvetica, sans-serif;
			  font-size: 0.75em;
			  margin-top: 4px;
		  }
		  /*#more-experiments{
			color: #666666;
			  font-weight: normal;
		  }*/

		  @media screen and (max-width: 650px){
	</style>
</head>
<body>
	<header>
		<div class="logo">
			<img src="http://pisee.vn/wp-content/uploads/2016/11/thiet-ke-logo-cho-game-thu-doc-nhat-vo-nhi-1.png">
			<div class="logo-text"><b>LMHT</b></div>
		</div>
		<nav class="menu">
			<ul>
				<li><a href="https://lienminh.garena.vn/game-info" title="Giới Thiệu">Giới Thiệu</a></li>
				<li><a href="https://lienminh.garena.vn/news" title="Tin Tức">Tin Tức</a></li>
				<li><a href="https://lienminh.garena.vn/competition" title="Giải Đấu">Giải Đấu</a></li>
				<li><a href="https://lienminh.garena.vn/community" title="Cộng Đồng">Cộng Đồng</a></li>
				<li><a href="http://diendan.garena.vn/" title="Diễn Đàn">Diễn Đàn</a></li>
				<li><a href="https://hotro.garena.vn/" title="Support">Support</a></li>
			</ul>
		</nav>
	</header>
	<section>
		<div class="slogan">
			"Liên Minh Mẫu Mực"
			<div><a href="http://dl.garenanow.com/games/lolvn/patcher/VN_patch_20170826to20170914_2.zip">
				Tải Game
			</a>	
			<a href="https://sso.garena.com/ui/register?locale=vi-VN&redirect_uri=https%3A%2F%2Fsso.garena.com%2Fui%2Flogin%3Flocale%3Dvi-VN%26redirect_uri%3Dhttp%253A%252F%252Fplatform.garena.vn%252F%26app_id%3D10000%26display%3Dpage&display=page">
				Đăng Kí
			</a>	
			</div>
		</div>
		<div class="cuc-bai-viet">
			<h2><a href="https://lienminh.garena.vn/game-info/get-started">Khởi đầu trong Liên Minh Huyền Thoại</a></h2>
			<p>Có rất nhiều điều để tạo nên một trận đấu thành công trên Chiến Trường Công Lý. Trong mục hướng dẫn người chơi mới, bạn sẽ được học cách điều khiển các vị tướng của mình, những kiến trúc bạn sẽ gặp trên chiến trường và chơi qua quá trình Hướng dẫn.</p>
		</div>
		<div class="cuc-bai-viet">
			<h2><a href="https://lienminh.garena.vn/game-info/champions">Các tướng và trang bị</a></h2>
			<p>Liên Minh Huyền Thoại cho người chơi sự lựa chọn rộng rãi với các tướng, với mỗi tướng một thiết kế và phong cách chơi điển hình. Tại đây người chơi có thể xem toàn bộ đội hình các tướng và tìm hiểu nhân vật mình hứng thú.</p>
		</div>
		<div class="cuc-bai-viet">
			<h2><a href="https://lienminh.garena.vn/game-info/summoner/spells">Tùy chỉnh Anh Hùng</a></h2>
			<p>Là một Anh Hùng, người chơi sử dụng các công cụ để hỗ trợ vị tướng của mình trên chiến trường. Ngọc bổ trợ, bảng bổ trợ và phép bổ trợ cho phép người chơi tùy chỉnh vị tướng của mình phù hợp với phong cách chơi của bản thân. Ngoại trừ để có được một số lợi thế từ nó? Nhưng ai có quyền tìm ra lỗi lầm với một người đàn ông thích vui chơi mà không có hậu quả gây phiền nhiễu, hoặc người tránh được nỗi đau không tạo ra niềm vui nào cả</p>
		</div>
		<div class="cuc-bai-viet">
			<h2><a href="https://lienminh.garena.vn/game-info/game-mode/summoners-rift">Các chế độ chơi</a></h2>
			<p>Là một Anh Hùng, người chơi sử dụng các công cụ để hỗ trợ vị tướng của mình trên chiến trường. Ngọc bổ trợ, bảng bổ trợ và phép bổ trợ cho phép người chơi tùy chỉnh vị tướng của mình phù hợp với phong cách chơi của bản thân. Xem thêm</p>
		</div>
		<div class="cuc-bai-viet">
			<h2><a href="http://lmht.giaidau.vn/gcafe-cup/gioi-thieu">Thi đấu chuyên nghiệp Liên Minh Huyền Thoại</a></h2>
			<p>Gcafe Cup là giải đấu dành cho các đội tuyển nghiệp dư. Đây là nơi để các bạn game thủ có thể giao lưu cũng như học hỏi kinh nghiệm, làm tiền đề để bước lên chuyên nghiệp.</p>
		</div>
		<div class="cuc-bai-viet">
			<h2><a href="https://lienminh.garena.vn/game-info/summoner/spells">Phép Bổ Trợ</a></h2>
			<p>Những phép này cho phép người chơi tiến xa hơn về mặt tùy chỉnh những kỹ năng của vị tướng để phù hợp với lối chơi. Người chơi có thể chọn hai Phép bổ trợ khi bắt đầu trận đấu.Phép thiên về tấn côngNhững phép này tập trung vào việc gây sát thương lên địch và đuổi đối phương. Người chơi có thể cải thiện những phép này nhờ điểm bổ trợ Cuồng Nộ.Phép thiên về phòng thủNhững phép này ngăn cản sát thương hay xóa những hiệu ứng xấu lên người chơi. Người chơi có thể cải thiện những phép này nhờ điểm bổ trợ Quyết Tâm.Phép thiên về đa dụngNhững phép này gia tăng sự cơ động cũng như bao quát bản đồ. Người chơi có thể cải thiện những phép này nhờ điểm bổ trợ Sáng Suốt
			</p>
		</div>
	</section>
	<div class="clear-both"></div>	
	<footer>
		Hiển thị thông tin về bản quyển
	</footer>
</body>
</html>
