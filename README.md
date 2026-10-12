# AI IN ACTION · TRACK 1 · KHÓA 4
## BÀI TẬP CS9 (NGÀY 24): KINH TẾ SẢN PHẨM AI (AI PRODUCT ECONOMICS)

---

### I. THÔNG TIN NHÓM & PHÂN VAI THÀNH VIÊN
* **Tên nhóm:** `tung tung tung sahur`
* **Đề bài lựa chọn:** **Đề bài 2 · ChấmNhanh** (*Trợ lý chấm bài viết tiếng Anh cho trung tâm ngoại ngữ, bán qua đối tác phân phối*).
* **Danh sách thành viên & Phân công vai trò:**
  1. **Nguyễn Thị Minh Khánh** – *Điều phối*: Quản lý tiến độ, điều phối thảo luận và kiểm soát thời gian.
  2. **Lại Bá Quân** – *Tính số*: Lập mô hình tài chính, nhập số liệu các ô màu vàng, theo dõi các ô kiểm tra (`Đạt`).
  3. **Đỗ Lê Việt Anh** – *Phản biện*: Sử dụng câu lệnh prompt hỏi AI, kiểm thử kịch bản xấu và tìm lỗ hổng rủi ro.
  4. **Nguyễn Quang Huy** – *Ghi chép*: Điền cột nguồn/lý do, hoàn thiện 5 câu ghi chú quyết định và chuẩn bị nội dung thuyết trình.

---

### II. CÁC TÀI LIỆU TRONG REPOSITORY
1. **`DAY24_Track1_2A202602546_NguyenThiMinhKhanh.xlsx`**: File Excel bài làm hoàn chỉnh, đầy đủ công thức và giá trị đã được tính toán, kiểm thử đạt chuẩn 100% trên toàn bộ các sheet:
   * `0_Đầu vào`: Thông tin nhóm và đánh dấu đầu vào.
   * `A_Tài chính căn bản`: 3 báo cáo tài chính cân và khớp 100%, trả lời 4 câu hỏi nhận định, bài toán đầu tư máy chủ (mua vs thuê).
   * `1_Chi phí mỗi việc`: Tính toán chi phí phục vụ 1 việc (Job Unit Economics) với mô hình Claude Sonnet và quy trình Human-in-the-loop.
   * `2_Định giá`: Mô hình định giá kết hợp (Phí cố định + Phí vượt hạn mức), vượt qua 3 phép thử giá (neo lương, chi phí AI/doanh thu, biên sau chia đối tác).
   * `3_Giả định`: 3 kịch bản (Lạc quan, Cơ sở, Xấu với cú sốc rời bỏ và CAC $\ge 1,5 \times$ cơ sở).
   * `4_Chỉ số mỗi khách`: LTV trên lợi nhuận gộp, LTV/CAC, Thời gian hoàn vốn chi phí có khách.
   * `5_Dòng tiền & hiệu quả`: Dự phóng dòng tiền 24 tháng, NPV 24 tháng, Bảng độ nhạy và Ngưỡng cảnh báo tự tính.
   * `7_Quyết định`: 5 câu ghi chú quyết định hoàn chỉnh, luật xử lý theo khuôn `NẾU - TRONG - THÌ - KHÔNG THÌ`.

---

### III. TÓM TẮT CHỈ SỐ KINH TẾ & TÀI CHÍNH (ĐỀ BÀI 2 - CHẤM NHANH)

#### 1. Chi phí mỗi việc (Unit Economics)
* **Mô tả 1 việc:** 1 bài viết tiếng Anh (250–300 từ) được chấm theo 4 tiêu chí rubric và viết nhận xét chi tiết.
* **Chi phí gọi AI (Claude Sonnet):** 769,40 đ/bài.
* **Chi phí giáo viên kiểm tra (10% số bài, 3 phút/bài, 120k/h):** 600,00 đ/bài.
* **Hạ tầng, đánh giá định kỳ, bảo mật:** 250,00 đ/bài.
* **Tổng chi phí phục vụ mỗi việc:** **1.619,40 đ/bài**.
* **Tỷ lệ phần chìm ngoài AI:** **110,48%** ($\ge 30\%$ $\rightarrow$ Đạt).
* **Giá sàn mỗi việc ($3 \times$ Chi phí):** **4.858,19 đ/bài**.

#### 2. Định giá & 3 Phép thử
* **Gói giá đề xuất:** Phí cố định **3.900.000 đ/tháng/trung tâm** (gồm 600 bài), phí vượt hạn mức **5.500 đ/bài** ($\ge$ giá sàn 4.858 đ).
* **Cơ cấu khách hàng:** 75% trung tâm nhỏ (chưa vượt hạn mức, doanh thu 3,9tr/tháng), 25% trung tâm lớn (chấm 2.500 bài, doanh thu 14,35tr/tháng).
* **Doanh thu bình quân:** 6.512.500 đ/khách/tháng.
* **Khách trả so với lương giáo viên thay thế (25 triệu/tháng):** Khách nhỏ 15,6% lương; Khách lớn 57,4% lương (nằm trong vùng 50–70% chuẩn).
* **Biên gộp sau chia 20% cho đối tác:** **55,13%** ($> 50\%$ $\rightarrow$ Ổn).

#### 3. Bảng chỉ số trên từng khách hàng (3 Kịch bản)
* **Kịch bản Cơ sở:**
  * Doanh thu bình quân sau chia đối tác (ARPU): **5.210.000 đ/tháng**.
  * Lợi nhuận gộp/khách/tháng: **3.590.602 đ** (Biên gộp **68,92%**).
  * Vòng đời khách hàng (Lifespan): **22,2 tháng** (Rời bỏ 4,5%/tháng).
  * Giá trị trọn đời (LTV): **79.791.156 đ**.
  * Chi phí có một khách (CAC): **7.000.000 đ**.
  * **LTV / CAC:** **11,40 lần** ($> 3$ lần $\rightarrow$ Khỏe).
  * **Thời gian hoàn vốn CAC:** **1,95 tháng** ($< 12$ tháng $\rightarrow$ Khỏe).
* **Dòng tiền 24 tháng & Đầu tư:**
  * **NPV 24 tháng (Cơ sở):** **+3.513 triệu đồng (+3,51 tỷ đồng)**.
  * **Tháng hoàn vốn đầu tư ban đầu:** Tháng 15. Không cạn tiền mặt trong 24 tháng.
  * **Kịch bản Xấu:** Hết tiền ở tháng 17 ($\ge 12$ tháng $\rightarrow$ Đạt).

#### 4. Phân tích độ nhạy & Luật xử lý
* **Biến nguy hiểm nhất:** **Doanh thu bình quân giảm 20%** (Làm NPV tụt -2,91 tỷ đồng, mất 83% giá trị dự án).
* **Luật xử lý khủng hoảng:**
  > **NẾU** doanh thu bình quân dưới 3.950.000 đ/trung tâm (sau chia đối tác) **TRONG** 2 tháng liên tiếp trên ít nhất 15 trung tâm, **THÌ** dừng mở rộng đại lý, đóng gói thêm tính năng phân tích phổ điểm và phát hiện lỗi ngữ pháp định kỳ để kích thích dùng vượt hạn mức. **KHÔNG THÌ** không giảm giá gói cơ bản xuống dưới 3.500.000 đ và không hạ phí vượt hạn mức xuống dưới giá sàn 4.858 đ.

---

### IV. NỘI DUNG 3 SLIDE THUYẾT TRÌNH (3 PHÚT)
* **Slide 1 - Kết luận:** Đề xuất Thử nghiệm nhỏ 4 tháng với 20 trung tâm ngoại ngữ; Gói kết hợp 3,9 triệu đồng/tháng (600 bài) + 5.500 đ/bài vượt hạn mức; Lý do: LTV/CAC đạt 11,4 lần, hoàn vốn 1,95 tháng, NPV +3,51 tỷ đồng.
* **Slide 2 - Bằng chứng:** Chi phí mỗi việc 1.619 đ, biên gộp sau chia đối tác 55,1%, dòng tiền 24 tháng an toàn và hoàn vốn tháng 15.
* **Slide 3 - Rủi ro & Ứng phó:** Biến nguy hiểm nhất là Doanh thu bình quân giảm (phụ thuộc 55% nguồn thu vào nhóm 25% trung tâm lớn); Kích hoạt luật xử lý và kế hoạch cắt giảm (Batch API giảm 50% chi phí AI) khi chạm ngưỡng cảnh báo.
