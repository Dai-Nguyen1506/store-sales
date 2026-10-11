TUẦN 5 — MÔ HÌNH DỮ LIỆU VỚI POWER BI
Bộ dữ liệu: Doanh số bán hàng của cửa hàng Corporación Favorita
Link: https://www.kaggle.com/competitions/store-sales-time-series-forecasting/data

Tệp tin
-----
train.csv: Quan sát doanh số bán hàng theo ngày, cửa hàng và nhóm sản phẩm.

stores.csv: Các thuộc tính của cửa hàng như thành phố, tiểu bang, loại và cụm.

transactions.csv: Số lượng giao dịch hàng ngày theo cửa hàng.

oil.csv: Quan sát giá dầu hàng ngày.

holidays_events.csv: Các bản ghi về ngày lễ/sự kiện quốc gia, khu vực và địa phương.

Trước khi xây dựng các mối quan hệ
----------------------------- 
1. Kiểm tra chi tiết từng bảng: một hàng đại diện cho điều gì?

2. Phân tích các cột chính và các thuộc tính quan trọng.

3. Kiểm tra tính duy nhất ở phía "1" dự định của các mối quan hệ.

4. Giải quyết các vấn đề về chất lượng dữ liệu có thể làm sai lệch các danh mục, tổng hoặc mối quan hệ.

5. Không hợp nhất các bảng chỉ vì chúng có chung tên cột.

6. Xác thực tổng sau khi mô hình được xây dựng.

Các vai trò phân tích cốt lõi
---------------------
- Quản lý vận hành bán hàng

Quan trọng
---------
- Phiên bản giảng dạy này giữ nguyên toàn bộ phạm vi lịch sử của bộ dữ liệu gốc.

- Một số vấn đề về chất lượng dữ liệu đã được kiểm soát để phục vụ việc thực hành trong lớp học.

- Không nên cho rằng mọi giá trị bất thường đều tự động là lỗi: hãy kiểm tra và biện minh cho từng quyết định.