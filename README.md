# Telegram-Member-Adder
This tool can scrap and add Telegram members from any group to your group. It has many more useful files like "filter by last seen", "private-public", "addauto", "ban filter" etc.


Basic requirement to run this tool Download :

Notepad++ : https://notepad-plus-plus.org/downloads/
Python : https://www.python.org/downloads/
Module Required : Open PowerShell in Administrator Mode and Type "pip install telethon" & "pip install Licensing" 

------------------------------------------------------------------------------------

Bước 1. Mở Tệp Phone.csv trong Notepad ++ và sau đó Nhập số Telegram của bạn

Bước 2. Bây giờ hãy mở tệp api.csv trong Notepad ++ và nhập id api & băm cho các số đó (Để lấy Api & ID băm, hãy sử dụng bot của chúng tôi: https; // t.me/Apiextractor_bot)

Bước 3. Mở tệp Config.ini trong Notepad ++ và nhập Số điện thoại chính (chọn bất kỳ số nào từ phone.csv)
        cũng nhập tên người dùng Nhóm mục tiêu trong
        "from_channel" và đặt tên người dùng nhóm của bạn vào "to_channel"

Bước 4. Tạo một thư mục trống với tên "phiên". Bây giờ chạy tệp đăng nhập và nhập OTP và sau đó phiên đăng nhập sẽ được lưu trong thư mục phiên

Bước 5. Chạy tệp Export và loại bỏ các thành viên mà các thành viên đó sẽ được lưu trong un.csv

Bước 6. Bây giờ hãy chạy Filter.py và FilterByLastSeen.py tương ứng các tệp này sẽ lọc dữ liệu từ un.csv và sẽ lưu chúng trong data.csv

Bước 7. Bây giờ hãy chỉnh sửa tệp memory.csv, theo mặc định của nó là 1,1,50 có nghĩa là trình thêm tự động (autoadd.py) sẽ chọn số điện thoại di động đầu tiên từ phone.csv và nó sẽ bắt đầu thêm từ tên người dùng đầu tiên đến tên người dùng thứ 50 từ dữ liệu tập tin. (Không cần chỉnh sửa mỗi lần, nó sẽ tự động được chỉnh sửa khi bạn chạy lại tệp đó và giá trị tệp bộ nhớ sẽ là 2,51,100)

Bước 8. Bây giờ mở thư mục ManualSelect Script và chạy tệp addauto.py sẽ bắt đầu thêm thành viên

--------------------------------------------------------------------------------------

2nd line, Text now and many more applications are freely available by which you can create unlimited Telegram accounts to add members.
