**Bài 1 : Xử lý cảnh báo đăng nhập giả mạo GitHub** 

**3\. Yêu cầu đầu ra**

-Chỉ ra ký tự lạ trong URL:
+ xuất hiện ký tự ú thay vì u tên gốc Github.com
-Giải thích vì sao lại đánh lừa được người dùng:
+ Do người dùng chỉ nhìn lướt qua hoặc vội vã bấm vào mà không để ý tên miền có ký tự lạ githúb.com
+ Do tên miền sử dụng các ký tự Unicode có định dạng chữ giống như trong tên miền gốc (github.com)


-Đề xuất quy trình kiểm tra URL nhanh bằng mắt thường và công cụ hỗ trợ trước khi nhập Master Password.  
- Kiểm tra bằng mắt:  xem có bị sai chính tả không,xem có chữ Hoa không,các ký tự đặc biệt (-,',!), hoặc phần mở rộng ( .com, .net): ví dụ GlThub.com , Git-hub.net
- Công cụ bảo mật:
- Sử dụng Authenticator như 1Password, Bitwarden có chức năng Autofill để xem tên miền có khớp không ,nếu một liên kết tên miền lạ thì  Autofill sẽ không cho vào
+ Sử dụng VirusTotal: Dán URL vào để kiểm tra hệ thống bảo mật có đánh dấu trang web này có virus độc hại,phishing không.
  


