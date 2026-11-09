# CNTT1-nh-p-m-n-c-ng-ngh-th-ng-tin-Session22_Ex03
### BÁO CÁO PHÂN TÍCH (IPO)

* **Input:** Câu lệnh Terminal từ AI để sửa lỗi "Path not found" khi cài Python.
* **Process:**
1. Phân tích xem lệnh có dùng quyền quản trị , xóa dữ liệu hay ghi đè hệ thống không.
2. Tra cứu bằng toán tử tìm kiếm: site:stackoverflow.com "Path not found" python hoặc site:docs.python.org.
3. So sánh lệnh của AI với hướng dẫn chuẩn để phát hiện AI Hallucination.


* **Output:** Xác nhận lệnh **Không an toàn** $\rightarrow$ Không chạy lệnh, chuyển sang sửa lỗi theo tài liệu chuẩn.

---

### PROMPT HỎI NGƯỢC LAỊ AI

"Trước khi tôi chạy lệnh này, hãy giải thích:
 1. Từng từ khóa trong lệnh tác động chính xác đến thư mục/tệp nào?
 2. Lệnh này dành cho Hệ điều hành nào (Windows/macOS/Linux)?
 3. Cung cấp link/tài liệu từ docs.python.org hoặc Stack Overflow chứng minh lệnh này an toàn và không gây lỗi hệ thống."
