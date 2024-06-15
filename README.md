# Trợ lý Ảo Sun
Đây là dự án về trợ lý ảo Sun, có thể thực hiện nhiều chức năng khác nhau như chuyển đổi văn bản thành âm thanh, mở ứng dụng, xem thời tiết, và nhiều hơn nữa. Dưới đây là hướng dẫn chi tiết và mã nguồn của dự án.

##**Cài đặt:**
Yêu cầu hệ thống
Python 3.x
Các thư viện cần thiết: os, gtts, playsound, speech_recognition, time, datetime, random, re, webbrowser, requests, json, selenium, tkinter, PIL, youtube_search, youtubesearchpython

# Cài đặt các thư viện cần thiết
Sử dụng lệnh sau để cài đặt các thư viện cần thiết
```
pip install gtts playsound SpeechRecognition selenium webdriver_manager youtube-search-python pillow
```
# Cách sử dụng
**Tiếp đến là các khối câu lệnh trong "main.py" để khởi chạy các chức năng của trợ lý ảo:**

**1. Chào hỏi:** Trợ lý ảo sẽ chào và hỏi xem người dùng có cần trợ giúp gì không.

Bạn có thể nói "xin chào" hoặc "hello", để trợ lý ảo bắt đầu chức năng.

**2. Hiển thị giờ và ngày:** Trợ lý có thể cho biết thời gian và ngày hiện tại.

Bạn có thể nói "ngày mấy", "mấy giờ" hoặc "Thứ mấy", để trợ lý ảo bắt đầu chức năng.

**3. Mở ứng dụng:** Trợ lý có thể mở một số ứng dụng nhất định như Google Chrome, Microsoft Word, Garena, và Steam.
Bạn có thể nói ""mở ứng dụng" hoặc "mở phần mềm" + [tên ứng dụng], để trợ lý ảo bắt đầu chức năng.

**4. Thời tiết:** Trợ lý có thể cung cấp thông tin về thời tiết hiện tại tại một địa điểm cụ thể.
Bạn có thể nói ... + "thời tiết" + ..., để bắt đầu chức năng.

**5. Mở website:** Trợ lý có thể mở các trang web theo yêu cầu của người dùng.
Bạn có thể nói "Mở website" + [tên web muốn mở], để trợ lý ảo bắt đầu chức năng.

**6. Tìm kiếm trên Google:** Trợ lý có thể thực hiện tìm kiếm trên Google và hiển thị kết quả.
Bạn có thể nói "Mở google và tìm kiếm" + [nội dung muốn tìm kiếm], để trợ lý ảo bắt đầu chức năng.

**7. Đổi màu nền, đổi màu chữ:** 
Bạn có thể nói "đổi hình nền" và "đổi màu chữ": để thực hiện chức năng

**8. Dừng chương trình:**
Bạn nói "dừng lại", để kết thức chương trình.

# Lưu ý
Để chức năng dự báo thời tiết và đọc báo hoạt động, bạn cần có API key từ các dịch vụ tương ứng (OpenWeatherMap, NewsAPI).
Cập nhật đường dẫn cài đặt ứng dụng cho phù hợp với hệ thống của bạn.

