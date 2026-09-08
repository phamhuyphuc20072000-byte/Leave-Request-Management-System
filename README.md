# 🏢 Leave Request Management System (LRMS)
> **IT Business Analysis Portfolio Project**  
> *End-to-end requirement analysis, process modeling, business rule matrix, and interactive multi-role prototype.*

---

##  1. Project Overview & Business Context
Hệ thống **Quản lý Đơn xin Nghỉ phép Tự động** được thiết kế nhằm giải quyết bài toán quản lý nghỉ phép thủ công (email/giấy tờ), giảm thiểu sai sót chấm công, và tối ưu hóa thời gian phê duyệt trong doanh nghiệp.

* **Target Audience:** Nhân viên (Employee), Trưởng phòng (Manager), Nhân sự (HR/Admin).
* **Key Achievements:**
  * **Giảm ~65%** thời gian xử lý và phê duyệt đơn nghỉ phép.
  *  **Đảm bảo 100%** tính chính xác trong tính toán số dư phép năm và quy tắc trừ phép.
  *  **Giảm ~25%** thời gian làm lại (rework) giữa BA và đội ngũ Development thông qua Interactive Prototype.

---

## 👥 2. User Roles & Permissions

| Role | Key Responsibilities |
| :--- | :--- |
| ** Nhân viên (Employee)** | Tạo đơn nghỉ phép, chọn loại phép, xem số dư phép theo thời gian thực, hủy đơn khi chưa duyệt. |
| ** Trưởng phòng (Manager)** | Nhận thông báo, duyệt/từ chối đơn cấp 1 (áp dụng cho mọi đơn từ phòng ban quản lý). |
| ** HR / Quản trị viên (Admin)** | Phê duyệt cấp 2 (đối với các đơn nghỉ **> 3 ngày**), quản lý quỹ phép năm, thiết lập ngày lễ và chốt phép thừa. |
| ** Hệ thống (System)** | Tự động kiểm tra số dư phép, phân luồng phê duyệt theo ma trận luật, đồng bộ lịch công tác & gửi email thông báo. |

---



