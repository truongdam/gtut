# Project title
Hướng dẫn việc sử dụng git basic

## Prerequisites
Đã cài đặt git command line

## Step by step
Clone 1 project 
```
git clone https://github.com/TruongDam/gtut.git
```
Sau khi clone, check branch của source
```
git branch
```
=> Check branch hiệnn tại là master
Sau khi tạo edit, add các file
```
git status
git add --all 
or
git add index.js/ *.js/ folder
git commit -m "commit file"
```
Sau đó check lại sự thay đổi từ repository

```
git pull origin master
```
Chỉnh sửa nếu có conflict. Thực hiện thao tác git add, git commit, git pull lại lần nữa
Sau khi check không có conflict, thực hiện
```
git push origin master
```

Hướng dẫn này được sử dụng cho branch master
