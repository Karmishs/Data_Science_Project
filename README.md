# ĐỒ ÁN KHOA HỌC DỮ LIỆU

---
1. **Thành viên**: 

|STT|MSSV|HỌ VÀ TÊN|
|---|----|---------|
|1  |20127485|Phạm Đức Duy|
|2  |20127571|Bùi Văn Nghĩa|
|3  |20127676|Nguyễn Vũ Khôi|

2. **Chủ đề đồ án**: 
- Chủ đề: Game TFT (Đánh giá đội hình trong tựa game TFT).
- Vậy TFT là gì? Định nghĩa: https://vi.wikipedia.org/wiki/%C4%90%E1%BA%A5u_Tr%C6%B0%E1%BB%9Dng_Ch%C3%A2n_L%C3%BD?fbclid=IwAR3Dx6YW19EgQ_GklIE5Fat20FZQBknlmcjZ3vjNO0IF58Y8T-NKyx59Ufk
- Nguồn dữ liệu: API từ Riot Games và crawl từ web https://tftactics.gg/ và https://blitz.gg/tft

3. **Phân tích**:
- Để có một đội hình mạnh chúng ta cần các vị tướng trong đội hình phải có sự kết hợp tốt, giá trị của các đơn vị phải cao, trang bị phù hợp,....
- Ta cần phải thu thập dữ liệu của các vị tướng, các hệ tộc trong game (dữ liệu có thể bao gồm giá trị quân cờ, tộc hệ nó có thể kích hoạt, trang bị cần thiết, tỉ lệ thắng, ...) và dữ liệu các trận đấu của các người chơi ở 2 server KR và NA.
- Xử lí dữ liệu để có đưa ra các thông số:
+ Tỉ lệ chọn các lõi nâng cấp, tỉ lệ thắng của lõi nâng cấp
+ Vị trí trung bình, tỉ lệ top 1, 4 của các vị tướng.
+ Các trang bị thường được dùng.

4. **Ứng dụng**:
- Tìm những những combo tướng đi với nhau mạnh để dễ dàng tạo đội hình mạnh.
- Xác định những nhóm tướng trong game (bao gồm tướng tank, dame, phép, đa dụng) để có thể đặt tướng vào các vị trí thích hợp và có lối lên đồ hợp lí.

link trello: https://trello.com/b/xM1M6ZRa/tft-project
