# Website Bán điện thoại đi động bằng Django

Một ứng dụng giúp quản lý đơn hàng và sản phẩm cho cửa hàng điện thoại di động.

## Tính năng chính

- Quản lý sản phẩm (thêm/sửa/xóa)
- Giỏ hàng và đặt hàng online
- Quản lý đơn hàng
- Đăng nhập và phân quyền người dùng

## Cài đặt môi trường

- Python 3.12.1
- pip 32.x
- virtualenv (khuyến khích sử dụng)

# Cấu hình

- Tạo superuser và khởi chạy project

- "python manage.py migrate
  python manage.py createsuperuser
- user: 'huukhoa29@gmail.com'
- password: '290401'
  python manage.py runserver"

## Cấu trúc thư mục

- `accounts/` – Quản lý người dùng (đăng nhập, đăng ký, phân quyền)
- `carts/` – Xử lý giỏ hàng và đặt hàng
- `category/` – Danh mục sản phẩm
- `orders/` – Quản lý đơn hàng
- `photos/` – Hình ảnh sản phẩm
- `store/` – Quản lý sản phẩm và chi tiết
- `templates/` – Giao diện người dùng (HTML sử dụng Django Template)
- `static/` – Static files như CSS, JS, hình ảnh
- `tphone/` – Cấu hình gốc của dự án Django (settings, urls, wsgi)
- manage.py – Tập tin điều khiển và chạy dự án

## Công nghệ sử dụng

Backend:

- Python 3.12.1
- Django 4.x là Framwork web theo kiến trúc MTV (Model-Templates-View)
- SQLite3: Sử dụng SQLite được tích hợp sẵn trong Django làm cơ sở dữ liệu
  Frontend:
- HTML, CSS, JavaScript
- Bootstrap v4.3.1

## Tài khoản admin

huukhoa29@gmail.com
290401

## Create by

002 - 3120219080 - Nguyễn Hữu Khoa
