# Cài đặt SSL cho domain (domain sử dụng cho website wordpress)
#### Bước 1: Đăng nhập vào aaPanel Linux panel bằng tài khoản quản trị
![text](./Images/Man_hinh_chinh_aaPanel.png)
#### Bước 2: Vào tab `Website`, sau đó tại domain cần cài ssl chon `Not Set` 
![text](./Images/Not_Set_Domain.png)
#### Bước 3: Tại bảng `Site modification` chọn mục `SSL`. Sau đó chọn tab `Let’s Encrypt`, ở mục `Verification mode` chọn `File verification`
![text](./Images/Let'sEncrypt.png)
- Tại mục Domain chọn domain muốn cấp SSL và chọn `Apply` sau khi cấu hình xong.
####
![text](./Images/Man_hinh_setup.png)
- Tiếp theo sẽ hiện ra cửa sổ chứng thực cài đặt SSL vào website. 
- Khi quá trình hoàn tất Let’s Encrypt SSL, hệ thống sẽ hiển thị một thông báo chi tiết về thời hạn của chứng chỉ, cũng như cung cấp private key và chứng chỉ tương ứng.
- Tại đây mở `Force HTTPS` để website tự động chuyển đổi về giao thức HTTPS.\
####
![text](./Images/Ket_qua_cert.png)

---


