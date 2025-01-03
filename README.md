# README: Comprehensive Logistics Data Analysis and Visualization with Tableau

## 1. Tổng quan Dự án

Dự án này tập trung vào phân tích và trực quan hóa dữ liệu logistics nhằm nâng cao hiệu suất quản lý chuỗi cung ứng và hỗ trợ ra quyết định chiến lược. Sử dụng bộ dữ liệu **DataCo Supply Chain**, nhóm đã xây dựng năm bảng điều khiển (dashboard) trên nền tảng Tableau, cung cấp các thông tin chi tiết về hiệu quả hoạt động logistics, hành vi khách hàng, và hiệu suất bán hàng.

---

## 2. Nội dung Chính

### 2.1 Mục tiêu Dự án

- **Mục tiêu chung**: Xây dựng hệ thống dashboard toàn diện để hỗ trợ quản lý hiệu suất kinh doanh, cải thiện hiệu quả logistics, và tối ưu hóa lợi nhuận.
- **Mục tiêu cụ thể**:
  - Tạo dashboard tổng quan để cung cấp cái nhìn toàn diện về hoạt động kinh doanh.
  - Phân tích hiệu suất logistics, bao gồm tỷ lệ giao hàng đúng hạn và thời gian giao hàng trung bình.
  - Hiểu rõ hành vi khách hàng thông qua phân khúc và giá trị vòng đời.
  - Đánh giá doanh thu và lợi nhuận theo sản phẩm, khu vực, và phương thức vận chuyển.

### 2.2 Các bảng điều khiển

1. **Dashboard Tổng quan**:
   - Cung cấp các chỉ số chính: Doanh thu, lợi nhuận, số lượng đơn hàng, thời gian giao hàng trung bình.
   - Phân tích khách hàng theo khu vực địa lý và phân khúc.
   - So sánh doanh thu và lợi nhuận trên bản đồ.

2. **Dashboard Bán hàng**:
   - Phân tích xu hướng doanh thu và lợi nhuận theo thời gian.
   - Đánh giá doanh thu theo danh mục sản phẩm và khu vực.

3. **Dashboard Logistics**:
   - Đánh giá hiệu suất giao hàng (tỷ lệ giao hàng trễ, thời gian giao hàng trung bình).
   - So sánh lợi nhuận theo phương thức vận chuyển và khu vực.

4. **Dashboard Khách hàng**:
   - Phân tích giá trị vòng đời khách hàng, tỷ lệ khách hàng quay lại.
   - Hiểu rõ xu hướng mua sắm và phương thức thanh toán ưa thích.

5. **Dashboard Quản lý đơn hàng**:
   - Đánh giá hiệu suất bán hàng theo danh mục sản phẩm.
   - Phân tích tỷ lệ hoàn trả sản phẩm và lợi nhuận trung bình mỗi đơn hàng.

---

## 3. Các bước Thực hiện

### 3.1 Chuẩn bị Dữ liệu

- Sử dụng Tableau Prep để tiền xử lý dữ liệu, bao gồm:
  - Làm sạch dữ liệu: Xử lý giá trị null và trùng lặp.
  - Chuyển đổi định dạng dữ liệu phù hợp (e.g., định dạng ngày tháng).
  - Loại bỏ các cột không cần thiết.

### 3.2 Mô hình hóa Dữ liệu

- Thiết kế schema cơ sở dữ liệu với các bảng:
  - `Order Items`, `Products`, `Orders`, `Departments`, `Customers`, `OrderDate`, và `ShippingDate`.
- Tạo mối liên kết giữa các bảng thông qua khóa chính và khóa ngoại.

### 3.3 Xây dựng Dashboard

- Chọn các biểu đồ phù hợp (biểu đồ cột, biểu đồ đường, bản đồ) để trình bày thông tin trực quan.
- Sử dụng bộ lọc để tùy chỉnh dữ liệu theo năm (2015-2018).

---

## 4. Công cụ và Công nghệ Sử dụng

- **Tableau Prep**: Làm sạch và chuẩn bị dữ liệu.
- **Tableau Desktop**: Tạo các dashboard trực quan.
- **Microsoft Excel**: Kiểm tra và xử lý dữ liệu ban đầu.

---

## 5. Kết quả Dự án

- **Dashboard trực quan**: Cung cấp thông tin chi tiết về doanh thu, lợi nhuận, hiệu suất giao hàng, và hành vi khách hàng.
- **Phân tích nâng cao**: Hỗ trợ đưa ra quyết định chiến lược, tối ưu hóa chuỗi cung ứng, và cải thiện hài lòng khách hàng.

---

## 6. Hạn chế và Định hướng Tương lai

### 6.1 Hạn chế

- Dữ liệu giới hạn trong giai đoạn 2015-2018.
- Một số dữ liệu bị thiếu hoặc không chính xác.

### 6.2 Định hướng Tương lai

- Tích hợp dữ liệu mới và sử dụng các kỹ thuật phân tích nâng cao (AI/ML).
- Tự động hóa quy trình làm mới dữ liệu và báo cáo.
- Đào tạo người dùng để tận dụng tối đa các dashboard.
