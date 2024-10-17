# Terms (Danh từ)

Repository (Repo): THư mục, dự án
Branch: Cành và cành mặc định lúc nào cũng là master

# Commands

- git init : làm một dự án hoặc Repository trở thành một Git Repository tr

- git status : cho thấy được trạng thái của mình tất cả thay đổi gì chúng ta sẽ thấy được

- git add : chuẩn bị lưu lại thời điểm hiện tại của dự án và chúng ta có thể gõ git add folder

* muốn lưu lại tất cả file: git add .

- git reset : lấy ra folder chuẩn bị lưu

- git commit : chính thức lưu

* ghi chú lại một chi tiết trước khi lưu cho biết quá trình trên dự án đang ở đâu
* git commit -m 'initial commit'
* initial commit: cam kết ban đầu

- git log : coi thời điểm đã lưu
  thoát git log nhấn phím q

* git log --oneline
  Muốn trở lại một thời điểm ban đầu thì sao ?

- git checkout {branch name}[id]: trở lại thời điểm mong muốn
- git checkout master : trở về hiện tại
- git branch :
- git checkout -b {branch name} : tạo ra branch mới
- git merge {branch name} : tổng hợp các branch
- git branch -d {branch name} : xóa đi một branch
