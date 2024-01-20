![image](https://github.com/thel6trial/ECommerceShopAPI/assets/101937836/d20002c6-11a4-4f22-8708-9baf3f968526)# ECommerceShopAPI

Phần mềm phát triển dựa trên kiến trúc MVC và restfulAPI kế thừa của Java SpringBoot, kết hợp gửi API từ Back-end đến hệ thống Front-end được xử lý bởi React. Mẫu kiến trúc MVC là phương pháp chia nhỏ các thành phần dữ liệu, trình bày và dữ liệu nhập từ người dùng thành những thành phần riêng biệt.
Từ sơ đồ kiến trúc MVC và restfulAPI chung, nhóm đã xây dựng và phát triển phần mềm dựa trên khung của sơ đồ kiến trúc này. Cụ thể, thành phần Model trong phần mềm là bao gồm gói model và service, model định nghĩa và khởi tạo ra các đối tượng cần thiết phù họp với những dữ liệu trong cơ sở dữ liệu, service cung cấp các thao tác trực tiếp tới cơ sở dữ liệu để có thể dễ dàng thêm, xóa, sửa dễ hơn trên cơ sở dữ liệu. Thành phần controller trong package Controller bao gồm OrderController, UserController, ProductController được sử dụng để xử lý yêu cầu request từ phía server người dùng, tương tác với Model và Cơ sở dữ liệu để trả về kết quả. Kết quả sau đó được gửi qua API tới hệ thống front-end của React, được React xử lý và hiển thị ra với người dùng thông qua HTML, CSS, JS.

