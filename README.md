# devops12repo
#Bài 3: Tìm hiểu và chỉ ra sự khác biệt giữa mạng bridge mặc định và mạng bridge do người dùng tự tạo

* Mạng bridge do người dùng tự tạo cung cấp tính năng DNS
<br>\- Các container trên mạng default bridge chỉ có thể  truy cập qua nhau bằng địa chỉ IP
<br>\- Các container trên mạng user-defined bridge chỉ có thể  truy cập qua nhau bằng địa chỉ IP, tên hoặc bí danh (alias)

* User-defined bridges cung cấp môi trường mạng tách biệt tốt hơn
<br>\- Các container không chỉ định flag --network mặc định sẽ được gán vào mạng default bridge.
<br>\- Mạng user-defined bridge chỉ cung cấp truy cập cho các container phạm vị thuộc mạng đó