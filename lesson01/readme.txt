Nội dung kiến thức học:
- Giới thiệu qua về web & các môn học liên quan
	- hosting/server -> đăng ky thử 1 hosting/server -> 000webhost, heroku, .v.v
	- domain/dns -> đăng ký thử 1 tên miền free
	- kết nối hosting/server & domain/dns
- Cài đặt môi trường
	- Phạm vi học: HTML/CSS/JS -> bien dich voi browser (chrome, cốc cốc, ie, safari, .v.v.)
	- Môi trường:
		- IDE: Visual Studio, Webstorm, Jetbrain, ..., sublime text 4
		- Sublime text: https://www.sublimetext.com/download
- Một số lưu ý khi phát triển website:
	- Mỗi 1 project -> tạo 1 folder
		- Phân cấp bài học -> thành các folder con (Giống C)
		- Nguyên tắc khi làm việc với web
			- Tất cả file hình ảnh, source code, .v.v -> để trong folder dự án
			- Đặt tên folder + tên file -> tiếng ánh/tiếng việt ko dấu -> ko có khoảng cách -> sử dụng dấu - hoặc _ => tạo folder/file
			- Viết chức thường (ko sử dụng chữ hoa trong phát triển web)
- Phát triển dự án web cơ bản
	- Tìm hiểu hiểu HTML
	- Phương pháp học:
		- Ghi nhớ nhiều -> qua thực hành
	- Tài liệu học:
		- EN: https://www.w3schools.com/html/default.asp
		- VN: https://gokisoft.com/hoc-html5-css3.htm
		- Slide Aptech -> dùng thi lý thuyết
	- Học cách tạo 1 website cơ bản:
- Deploy (phát hành) dự án -> đẩy lên git/github & public website
	B1. Tạo tài khoản trên github: https://github.com/
	B2. Cài đặt phầm mềm: https://git-scm.com/
	B3. Đẩy code từ máy tính lên github
		B3.1 -> TH: chưa đẩy code lên lần nào
			git init
			git add -A
			git commit -m 'first commit'
			git remote add origin https://github.com/tranvandiep/C2110I.git
			git push origin master
			