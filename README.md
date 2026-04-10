1. Cài đặt SQL Server 2025 Developer
<img width="1919" height="1077" alt="image" src="https://github.com/user-attachments/assets/02f4fbe0-6869-4358-908d-942ff4ee1f69" />
2. Cấu hình cổng động: Port: 36037
<img width="1918" height="1078" alt="image" src="https://github.com/user-attachments/assets/732a5c16-169c-44ca-bdfd-14977bf65d05" />
<img width="1918" height="1075" alt="image" src="https://github.com/user-attachments/assets/16ab97f0-d398-4874-9140-cbf6b6981c48" />
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/2122bcdb-4846-4830-b355-f9e4da7381e4" />
3. Kiểm tra cổng động và hoạt động đúng
<img width="1917" height="1078" alt="image" src="https://github.com/user-attachments/assets/88d3f9c5-c3ec-407a-baf0-b0f75f175a93" />
4. Cài đặt SQL Server Management Studio
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/21f785c5-dbee-4be2-a9eb-cebda2ae5009" />
5. Đăng nhập vào SQL Server bằng 2 cách là: Windows Authentication và SQL Server Authentication
<img width="1918" height="1077" alt="image" src="https://github.com/user-attachments/assets/28c09def-d713-48dc-a2d5-60fdb8b0edfa" />
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/9f8e49ee-ab2c-4f8c-8380-800889997ee1" />
6. Tạo CSDL mới
<img width="1919" height="1077" alt="image" src="https://github.com/user-attachments/assets/4d3d3c7d-fea6-4d57-931b-c59c41018198" />
<img width="1919" height="1077" alt="image" src="https://github.com/user-attachments/assets/6e133de8-acf0-42e6-b670-7a7283167459" />
7. Tạo bảng
<img width="1918" height="1075" alt="image" src="https://github.com/user-attachments/assets/c250e4ed-ff3a-446d-b152-a44566e8b9e8" />
8. Nhập dữ liệu
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/7c3a70f8-209a-47fd-910a-bf68d63e595b" />
9. Mở cửa sổ mới để nhập lệnh trong SSMS: Lệnh kiểm tra xem số dòng của dữ liệu bảng sau khi nhập
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/9df2f54d-7182-4dc1-8ec3-c5b9ea88a22a" />
10. Trong cửa sổ mới để gõ lệnh: Gõ lệnh để thêm (insert) 1 row vào bảng, với dữ liệu là thông tin cá nhân của sv
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/3d908cd6-3aa4-42a1-8495-b2a773393995" />
11. Trong cửa sổ mới để gõ lệnh: Gõ lệnh để cập nhật(update) trường noisinh thành 'Sao Hoả' cho những dòng có noisinh và diachi đều là NULL.
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/2b8a84fe-c5c0-4adc-a83b-91d8eb355e1d" />
12. Sử dụng giao diện đồ hoạ của ssms: Tạo bảng SaoHoa gồm những sinh viên có nơi sinh ở 'Sao Hoả', keyword gợi ý: sử dụng 1 câu lệnh: SELECT + INTO
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/1ccf38e0-75e1-4554-b62a-4db2277020c9" />
13. Trong cửa sổ mới để gõ lệnh: Gõ lệnh xoá (delete) trong bảng SaoHoa những sinh viên cùng họ với em, vd em họ nguyễn thì xoá những sv họ nguyễn.
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/c29673d7-5fe5-4306-b840-2e93f6d867c0" />
14. Sử dụng giao diện đồ hoạ của ssms: Xuất toàn bộ kết quả của các bước 6,7,8,9,10,11,12,13 ra file dulieu.sql , keyword gợi ý: sử dụng tính năng GEN SCRIPT struct+data cho database
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/7da1025c-c042-4cac-a379-32c4d41c471d" />
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/0a0ebe1b-a72e-423c-948e-3a1dbe5c9999" />
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/8e39e7cc-72e0-44a4-a4ff-aebd58ac2229" />
<img width="1909" height="1079" alt="image" src="https://github.com/user-attachments/assets/33b175cd-fcec-4346-b56e-ca37cae3e919" />
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/933dc52c-0b26-4711-980e-47645baf7c4d" />
15. Sử dụng giao diện đồ hoạ của ssms: Xoá csdl đã tạo, sau khi xoá thành công, kiểm tra tại path (path chọn ở bước 6) xem còn tồn tại 2 file của bước 6 không?
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/b5070fb3-c780-45cd-a2f9-1272fbc504e8" />
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/eebe087c-8fc7-4afb-8243-d57155b7d9fc" />
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/e68d20bf-0c9a-4ff5-b667-5ccaf1174e75" />



 





