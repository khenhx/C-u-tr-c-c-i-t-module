## Cấu trúc để cài đặt module
```php
## {Tạo một trang web}.
vào thư mục project gõ <cmd> => enter
## Tải drupal với lệnh 
composer create-project drupal/recommended-project tên_dự_án
xong vào Wampserver64 tới virtualHost để thêm virtualHost.

## Cài drush với cú pháp :
composer require drush/drush

sau đó cài tên và password :
thienhx@DESKTOP-J3BPUAG MINGW64 /c/wamp64/www/project/blog (master)
$ vendor/bin/drush si

 Database name [drupal]:
 > blog

 Database driver [mysql]:
 >

 Database username [drupal]:
 > root

 Database password [drupal]:
 > root

 Database host [127.0.0.1]:
 >

 Database port [3306]:
 => nếu có hỏi Do you want to continue? (yes/no) [yes]: thì chọn yes nhé


## Một số lện :.. 
vendor/bin/drush cex    xuất config 
vendor/bin/drush cr     xóa ccche
vendor/bin/drush cim    nhập config vào



## Tải module về bằng composer:
composer require drupal/ten_module

## bật module bằng drush:
vendor/bin/drush en ten_module

## tắt module bằng drush:
vendor/bin/drush pmu ten_module

## Các bước để tạo một theme:
vào thư mục theme => tạo custom bên trong theme =>tạo một thư mục theme với tên của theme
=> tạo info.ymk vd: tên theme.info.yml
=> tạo libraries.yml vd: tên theme.libraries.yml
=> tạo thư mục css rồi lấy fai ở thư mục mẫu
=> tạo thư mục js rồi lấy fai ở thư mục mẫu
=> Tạo vùng và hiển thị tới page.html.twig: lấy cốt ở body trong thư mục mẫu rồi exit lại.

## Tạo MENU và List  link:

-Tạo menu vào Structure => Menus => Add menu.
-Sau khi tạo menu thì Add link

## TẠO VIEW HOME:
Vào Structure=>views=>add view=>Điền các mục cần thiết còn lại để mặc định
Add view mode=>content=>


## Gits:
-git init (khởi tạo thư mục git)
-git status (cho biết trạng thái của lệnh)
-git add (ẹt fai, thêm pom)
-git commit (thêm ripo trong máy)
-git clone (lấy code ở trên mạng về)
-git pull (lôi code từ trên mạng về)
-git push (đẩy code lên)
-git branch (sâu branck)
-git checkout -b tên nhánh (tạo nhánh)
```
