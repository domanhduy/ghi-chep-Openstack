# Một số ghi chép về lý thuyết trong OPenstack

## Các mục chính cần tìm hiểu

### 1, Tổng quan

- Cloud computing là gì?

- Mô hình 5-4-3 trong Cloud Computing

- Openstack là gi? Kiến trúc

### 2, Keystone

- Tìm hiểu các khái niệm về project, user, domain, role

- Vai trò của keystone

- Các thành phần, kiến trúc

- Luồng làm việc cơ bản của Keystone

- Một số các command hay sử dụng

- Tìm hiểu các option trong file cấu hình của keystone

- File log của Keystone

- Hai khái niệm endpoint và catalog

- Tìm hiểu các loại token, đặc điểm mỗi loại

- Tìm hiểu Fernet token, tại sao lại dùng Fernet

- Cách sử dụng token để giải mã và mã hóa

- Tìm file cấu hình policy dạng json

- Tìm hiểu API, sử dụng CURL hoặc Python để gọi tới API

### 3, Glance

- Khái niệm, kiến trúc

- Một số các định dạng image được hỗ trợ

- Các trạng thái và luồng hoạt động của Imgae trong Glance

- File cấu hình của Glance

- File log của Glance

- Một số command thường dùng

- Metadata của image

### 4, Nova

- Khái niệm, các thành phần, kiến trúc, mối quan hệ giữa các thành phần trong nova

- Tìm hiểu file cấu hình nova

- Tìm hiểu quá trình khởi tạo máy ảo

- Tìm hiểu cloud-init (giới thiệu, các module, ví dụ,...)

- Các lệnh thường dùng với Nova

- File log của Nova

- Tìm hiểu về luồng khởi tạo và quản lí vnc trong nova

- Tìm hiểu về nova placement và nova conductor, tại sao lại cần 2 service này

- Tìm hiểu và phân biệt 2 khái niệm host aggreate vs availability zone trong nova

- Tìm hiểu cơ chế schedule vs filter trong nova

- Tìm hiểu khái niệm cold vs live migrate, resize, rescue, evacuate và luồng hoạt động của nó trong ops

### 5, Cinder

- Tổng quan về cinder, các thành phần trong cinder, một số backend thông dụng

- Cinder workflow

- File cấu hình cinder

- Các câu lệnh thường dùng

- Cinder scheduler vs cinder backup

- Cài đặt cinder với backend là lvm (theo docs)

- Thực hiện cấu hình cinder backup với backend là nfs

- Thực hiện cài đặt multi backend cinder với backend là nfs vs LVM

- Thực hiện schedule volume theo từng backend

- Log của Cinder

- Lab các tính năng migrate, evacuate với máy ảo boot từ volume

### 6, Neutron

- Khái niệm, các thành phần của Neutron

- Tìm hiểu các loại mạng trong Neutron và mô hình của chúng, phân biệt provider và self-service

- Tìm hiểu file cấu hình của Neutron

- Một số các câu lệnh thường dùng với Neutron

- Tìm hiểu đường đi của gói tin trong mô hình sử dụng với Linux bridge theo hai chiều đông tây và bắc nam

- Tìm hiểu về namespace trong neutron

- Tìm hiểu về security group

- Tìm hiểu về các đường network trong mô hình OPS 3 node

- Tìm hiểu VXLAN

- Tìm hiểu Qos

### 7, Nâng cao

- Cài đặt OPS Multi Region

- Cài đặt OPS HA 

- Làm việc với API của Openstack


### Tham khảo

https://github.com/danghai1996/OpenStack

https://github.com/thaonguyenvan/openstack-notes




