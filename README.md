
# ĐỒ ÁN CUỐI KÌ NHẬP MÔN KHOA HỌC DỮ LIỆU 
- **Giảng viê**n: TS Nguyễn Ngọc Thảo. 
- **Trợ giảng**: Lê Nhựt Nam.
- **Trợ giảng**: Kiều Vũ Minh Đức.

---
1. **Thành viên**: 

|STT|MSSV|HỌ VÀ TÊN|
|---|----|---------|
|1  |20127485|Phạm Đức Duy|
|2  |20127571|Bùi Văn Nghĩa|
|3  |20127676|Nguyễn Vũ Khôi|

2. **Chủ đề đồ án**: 
- Chủ đề: Game (Đánh giá đội hình trong tựa game TFT).
- Vậy TFT là gì? Định nghĩa: https://vi.wikipedia.org/wiki/%C4%90%E1%BA%A5u_Tr%C6%B0%E1%BB%9Dng_Ch%C3%A2n_L%C3%BD?fbclid=IwAR3Dx6YW19EgQ_GklIE5Fat20FZQBknlmcjZ3vjNO0IF58Y8T-NKyx59Ufk
- Nguồn dữ liệu: API từ Riot Games hoặc crawl từ web https://tftactics.gg/ (hiện tại chúng em đang nghiên cứu về thu thập dữ liệu qua API nếu không làm được sẽ chuyển qua crawl từ web).

3. **Phân tích**:
- Để có một đội hình mạnh chúng ta cần các vị tướng trong đội hình phải có sự kết hợp tốt, giá trị của các đơn vị phải cao, trang bị phù hợp,....
- Ta cần phải thu thập dữ liệu của các vị tướng, các hệ tộc trong game (dữ liệu có thể bao gồm giá trị quân cờ, tộc hệ nó có thể kích hoạt, trang bị cần thiết, tỉ lệ thắng, ...).
- Xử lí dữ liệu để có đưa ra các thông số:
+ Tỉ lệ chọn các lõi nâng cấp, tỉ lệ thắng của lõi nâng cấp
+ Vị trí trung bình, tỉ lệ top1, 4 của các vị tướng.
+ Các trang bị thường được dùng.

4. **Dự đoán**:
- Dự đoán được 1 đội hình mạnh hay không.
- Dự đoán sực mạnh của 1 đơn vị tướng khi mang các trang bị tương ứng.
- Dự đoán sức mạnh của đội hình nếu bỏ(thêm, thay thế) một con tướng.
- Từ tướng và trang bị -> tìm kiếm tỉ lệ người chơi lựa chọn lối xây dựng đội hình phù hợp.
