# baitapso5
Thân Nhân Thành K225480105049
A. Trình bày lại đầu bài của đồ án PT&TKHT:
1. Mô tả bài toán của đồ án PT&TKHT, 
   đưa ra yêu cầu của bài toán đó
2. Cơ sở dữ liệu của Đồ án PT&TKHT :
   Có database với các bảng dữ liệu cần thiết (3nf),
   Các bảng này đã có PK, FK, CK cần thiết
B. Nội dung Bài tập 05:
1. Dựa trên cơ sở là csdl của Đồ án
2. Tìm cách bổ xung thêm 1 (hoặc vài) trường phi chuẩn
   (là trường tính toán đc, nhưng thêm vào thì ok hơn,
    ok hơn theo 1 logic nào đó, vd ok hơn về speed)
   => Nêu rõ logic này!
3. Viết trigger cho 1 bảng nào đó, 
   mà có sử dụng trường phi chuẩn này,
   nhằm đạt được 1 vài mục tiêu nào đó.
   => Nêu rõ các mục tiêu 
4. Nhập dữ liệu có kiểm soát, 
   nhằm để test sự hiệu quả của việc trigger auto run.
5. Kết luận về Trigger đã giúp gì cho đồ án của em.
## A  Trình bày lại đầu bài của đồ án PT&TKHT:
1. Yêu cầu của dồ án: Phân tích thiết kế Hệ thống hỗ trợ học trực tuyến trường đại học Công Nghiệp Thái Nguyên
2. Cơ sở dữ liệu của Đồ án PT&TKHT :Có database với các bảng dữ liệu cần thiết (3nf), các bảng này đã có PK, FK, CK cần thiết
Cơ sở dữ liệu quản lý thông tin học tập trực tuyến gồm các bảng chính phục vụ việc:

- Quản lý người dùng (Admin, giảng viên, sinh viên)
- Tổ chức khóa học
- Đăng ký học
- Bài giảng – bài tập – bài nộp
- Tin nhắn hỗ trợ
- Theo dõi lịch sử nộp/chấm điểm
### Bảng dữ liệu cần thiết, bảng này đã có PK, FK, CK cần thiết
![image](https://github.com/user-attachments/assets/7c2fab75-61f1-4f14-b418-0087a7fd8062)
### Bảng liên kết hệ thống 
![image](https://github.com/user-attachments/assets/9d6815b5-074c-4175-a1f3-452ee918eb7c)
## trigger cho bảng LichSuNopBai
![image](https://github.com/user-attachments/assets/cab16a18-1754-4273-a766-73fcbe9fa5af)
![image](https://github.com/user-attachments/assets/abc23a6f-ba7b-4fe5-8e24-2aeea8ddb756)
![image](https://github.com/user-attachments/assets/9d65243f-8842-48ab-93fb-534bf54cb385)
![image](https://github.com/user-attachments/assets/fac43039-869c-4034-8fc9-8cf4d844987c)
## kết quả
![image](https://github.com/user-attachments/assets/a378cc74-b090-4ba7-8e75-3d11f6630c25)
## Trigger đã giúp gì cho đồ án của em
trigger giúp cho em tự động hóa việc ghi lại lịch sử hành động của sinh viên → Giúp hệ thống hỗ trợ học tập trở nên đầy đủ, đáng tin cậy và dễ theo dõi


