# HƯỚNG DẪN CHUNG KHI SỬ DỤNG UIPATH
### 1. Phím tắt dừng chương trình UiPath **F12**  
### 3. Tắt các ứng dụng không cần thiết  
### 4. Tắt các file mà UiPath sẽ tương tác khi chạy(.xlsx, .txt, ...)  
  
# HƯỚNG DẪN CHUẨN BỊ TRƯỚC KHI CHẠY CÁC CHƯƠNG TRÌNH **"UA-GiayBaoCo", "UA-GiayBaoNo", "UA-PhieuChiTienMat"**  

> ## Hướng dẫn cung cấp dữ liệu đầu vào  
**Bước 1:** Vào thư mục chứa chương trình và mở file **Data\Config.xlsx**  
  
![image](https://github.com/ismphi/UiPath-Learning/blob/master/libary/config.jpg)  
  
**Bước 2:** Xem hướng dẫn trong sheet **“General”**  
  
![image](https://github.com/ismphi/UiPath-Learning/blob/master/libary/tmtgtv/general.jpg)  
  
**Bước 3:** Tạo 1 file excel mới đúng theo form nhập dữ liệu theo hướng dẫn trong sheet **“General”**  
  
**Bước 4:** kéo file excel vừa tạo vào thư mục **Data\Input** và đổi tên file trong sheet **“Settings”** hoặt lưu file nơi bất kỳ đâu và nhập đường dẫn trong sheet **“Settings”**(Hướng dẫn cấu hình file Config bên dưới)  
  
![image](https://github.com/ismphi/UiPath-Learning/blob/master/libary/tmtgtv/input.png)  
  

> ## Hướng dẫn Cấu hình chi tiết  
**Bước 1:** Vào thư mục chứa chương trình và mở file **Data\Config.xlsx**  
  
**Bước 2:** Cấu hình các thông số như hướng dẫn trong sheet **“Setting”**  
  
![image](https://github.com/ismphi/UiPath-Learning/blob/master/libary/tmtgtv/setting.png)  
  
> ## Chạy chương trình  
>   
**Bước 1:** Mở Uipath và chọn chương trình cần chạy hoặt vào thư mục chứa chương trình mở file **Main.xaml**  
  
![image](https://github.com/ismphi/UiPath-Learning/blob/master/libary/tmtgtv/main.png)  
  
hoặt  
  
![image](https://github.com/ismphi/UiPath-Learning/blob/master/libary/tmtgtv/uipath.png)  
  
**Bước 2:** Mở **FAST** và vào đúng màn hình thêm mới dữ liệu  
  
![image](https://github.com/ismphi/UiPath-Learning/blob/master/libary/tmtgtv/new.png)  
  
**Bước 3:** Click **“mũi tên”** phía dưới Debug File để lựa chọn chức năng và chọn **“Run”**  
  
![image](https://github.com/ismphi/UiPath-Learning/blob/master/libary/tmtgtv/run.png)  
> ## Hướng dẫn kiểm tra email  
Sau khi thực hiện xong chương trình sẽ gửi 1 tin nhắn đến các địa chỉ mail được cấu hình trong sheet "Settings"  
![image](https://github.com/ismphi/UiPath-Learning/blob/master/libary/tmtgtv/email.png)  
- STARTUP: chế độ chương trình đang chạy(test hoặt production)  
- USER: user chạy chương trình  
- AMOUNT: Số dòng người dùng cấu hình  
- Report Content: Nội dung report của chương trình  
> ## Hướng dẫn sửa một số lỗi cơ bản thường gặp  
**Lỗi 1: ** do phản hồi từ chương trình FAST  
Cách sửa:  đóng cửa sổ FAST đang chạy và mở lại cửa sổ mới  
![image](https://github.com/ismphi/UiPath-Learning/blob/master/libary/tmtgtv/error1.png)  
  

