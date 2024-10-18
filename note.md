# Terms (Danh từ)

Repository (Repo): THư mục, dự án
Branch: Cành và cành mặc định lúc nào cũng là master
Conflict: xung đột
Local: tất cả cái gì trên máy tính là local
Remote: dữ liệu ko nằm trên máy tính mà nằm trên server

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
- git branch : xem nhánh
- git checkout -b {branch name} : tạo ra branch mới
- git merge {branch name} : tổng hợp các branch
- git branch -d {branch name} : xóa đi một branch
- git push : Giúp đẩy lên local repo của mình trên remote repo

Lấy từ remote repo về local

- Git clone 'link'
- Code .: mở vscode
- Git push -u origin dev: đẩy branch dev lên remote repo

add branch từ remote repo về local
git fetch origin
git checkout -b staging origin/staging
git publl: keo ve pull branch

git remote add origin {repo URL}
