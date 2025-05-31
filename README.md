# CompNet Laboratory
## Install Git
- Step 1: Tải và cài đặt Git: https://git-scm.com/downloads
- Step 2: Đăng ký tài khoản trên github.com
- Step 3: Gửi địa chỉ mail đăng ký github.com cho giảng viên để được mời làm cộng tác viên trên kho CompNet
- Step 4: Truy cập kho CompNet để theo dõi nộp bài thực hành: https://github.com/dzokha1010/CompNet
## Clone and Push to CompNet
- Step 1: Mở Command Prompt hoặc CMD trên Windows
- Step 2: Thực hiện câu lệnh clone CompNet
  ```
  git clone https://github.com/dzokha1010/CompNet.git
  ```
- Step 2: Di chuyển vào thư mục CompNet
  ```
  cd CompNet
  ```
- Step 3: Tạo tập tin Word đặt tên là MSSV lưu trong thư mục CompNet, tập tin này sẻ lưu trữ kết quả mỗi buổi thực hành.
- Step 4: Chụp hình kết quả thực hành từng bài tập và dán vào tập tin Word
- Step 5: Nộp tập tin Word sau buổi thực hành lên kho CompNet bằng các câu lệnh
  ```
  git add .  
  git commit -m "<ghi chú>"  
  git push -u origin <name_branch>
  ```
- Lưu ý: Nên tạo Token thay thế mật khẩu để thuận tiện mỗi khi thực hiện câu lệnh Push
  - Link để tạo Token: https://github.com/settings/tokens
