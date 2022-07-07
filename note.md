# terms :danh từ
Repository (Repo)   (Thư mục:git-github)
Branch : nhánh
conflict: xung đột
local: địa phương 
remote:xa xôi

# commands :Lệnh
- git init : biến repo của chúng ta thành 1 git hay để sử dụng git ta sử dụng init cho repo
-git status: cho phép chúng ta thấy được trạng thái của dự án và sự thay đổi của trạng thái ấy
- git add : cho phép chúng ta chuẩn bị lưu lại thời điểm hiện tại của dự án
-git add . : lưu tất cả file trong dự án
-git reset : hủy lưu flie dự án ( hủy add)
-git commit:chính thức lưu dữ liệu vào hệ thống
 <!--đây là 1 lệnh đặc biệt cần ghi chú trước khi lưu. Ghi chú này để xem quá trình trên dự án đang ở đâu hay đang làm gì  
 git commit -m 'initial commit'
 :initial commit là tên ghi chú và hay được đặt với nội dung thời điểm ban đầu của dự án
  -->
-git log: dùng để coi những thời điểm mà chúng ta đã lưu
-git log --oneline: ngăn gọn hơn git log
-git checkout{id commit; branch name} :id trở lại 1 thời điểm của commit-- branch trở lại thời điểm hiện tại
-git branch: xem tên của branch
<!-- 1 dự án có thể có nhiều nhánh và nhánh mặc định sẽ là name branch của bạn là master -->
-git checkout -b {branch name}:tạo ra 1 branch mới
-git merge {name branch}: tổng hợp lại branch 
-git branch -d {name branch}:xóa đi 1 branch

-git push: đẩy code lên github
<!-- git push link repo master -->
-git remote add origin link repo
<!-- biến đường dẫn thành biến origin (tùy đặt tên của origin) -->
-git push origin master: đẩy code tiện hơn khi đỡ phải gán link
