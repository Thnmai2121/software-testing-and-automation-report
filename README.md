# Software Testing & Test Automation Project

> **Academic Project** - Faculty of Information Technology, Ho Chi Minh City Open University  
> **Course:** Software Testing (Kiểm thử phần mềm)  
> **Documentation:** [📄 Click Here to View Full Report (PDF)](./51_Bao_55_Mai_N2_DoAnKTPM.pdf)

---

## Project Overview
Báo cáo kiểm thử phần mềm toàn diện bao gồm thiết kế kịch bản test, phân tích lỗi và thực thi tự động trên 3 phân hệ:

1. **Unit Testing & Data-Driven Testing**: 
   * Kiểm thử đơn vị module tính tiền điện bậc thang sử dụng **MSTest / C# .NET**.
   * Áp dụng kỹ thuật phân vùng tương đương (Equivalence Partitioning) và phân tích giá trị biên (Boundary Value Analysis).
   * Thực hiện **Data-Driven Testing** tự động nạp dữ liệu kiểm thử từ file bên ngoài (`.csv` và `.xls`).

2. **Web Automation Testing (Selenium WebDriver)**: 
   * Tự động hóa kiểm thử luồng End-to-End trên website thương mại điện tử thực tế (`rubies.vn`).
   * Các luồng kiểm thử: Tìm kiếm sản phẩm, Giỏ hàng (Thêm/Sửa số lượng/Xóa nhiều sản phẩm), Kiểm tra Validation Form chăm sóc khách hàng.
   * Xử lý định vị element động qua XPath, CSS Selector và `IJavaScriptExecutor`.

3. **RESTful API Testing (Postman & Mock Server)**: 
   * Xây dựng mock server cục bộ với Node.js & `json-server`.
   * Thiết kế và tự động hóa bộ test script cho toàn bộ phương thức CRUD (`GET`, `POST`, `PUT`, `PATCH`, `DELETE`).
   * Viết assertions kiểm tra Status Code, Response Time, Header, Body JSON schema và quản lý các biến môi trường (`pm.environment`, `pm.globals`).

---

## 👥 Contributors
* **Đặng Hoàng Thanh Mai** (Tester / QA)
* **Nguyễn Minh Gia Bảo** (Tester/QA)
