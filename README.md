Phạm Tiến Vinh - 23810310085

<img width="2048" height="1280" alt="image" src="https://github.com/user-attachments/assets/922f3633-7697-4792-ac64-6b4e8d2b14ce" />
<img width="2048" height="1280" alt="image" src="https://github.com/user-attachments/assets/1a0eb887-2828-44ee-98b9-e2e158252486" />
<img width="2048" height="1280" alt="image" src="https://github.com/user-attachments/assets/d6cf315f-5972-4ac3-9305-844bd792943c" />
<img width="2048" height="1280" alt="image" src="https://github.com/user-attachments/assets/fda46009-88d9-475f-bf4f-72fc85bf63ca" />
<img width="2048" height="1280" alt="image" src="https://github.com/user-attachments/assets/3c701df5-f2ee-4985-a096-5ff0f7c47e01" />

So sánh lưu lượng dữ liệu:
Dùng REST API khi lấy tất cả trường của sản phẩm sẽ trả về toàn bộ dữ liệu, bao gồm nhiều trường không cần thiết, dẫn đến payload lớn hơn và tốn băng thông. Trong khi đó, GraphQL cho phép chỉ định trường cần lấy, nên payload nhỏ hơn, tối ưu tốc độ và băng thông.

Thay đổi giá sản phẩm qua Headless API:
Em sẽ sử dụng Mutation, vì Mutation trong GraphQL được thiết kế để thay đổi dữ liệu trên server (tạo, cập nhật, xóa). Query chỉ dùng để truy xuất dữ liệu, không gây thay đổi trạng thái server.
