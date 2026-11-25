# BÀI LÀM PHA 2 

- **Họ tên:**
- **Lớp:**
- **Link repository Pha2:**
- **Công cụ AI đã dùng (ChatGPT/Claude/Gemini):**

> Pha 2 (20 phút cuối). Mỗi mục: mở cuộc trò chuyện mới, gửi nguyên văn prompt đã viết trong bai_lam_pha1.md, dán câu trả lời và link chia sẻ vào đây. Xong, kéo thả file này vào repository Pha2.

## 4.2. Trích xuất tin nhắn đặt vé ra JSON

**KET QUA AI**

```text
[\
&#x20; {\
&#x20;   "ma_goi": null,\
&#x20;   "ngay_su_kien": "2026-12-20",\
&#x20;   "nguoi_lon": 2,\
&#x20;   "tre_em": 1,\
&#x20;   "loai_ve": "thuong",\
&#x20;   "ghi_chu": null\
&#x20; },\
&#x20; {\
&#x20;   "ma_goi": "FZ",\
&#x20;   "ngay_su_kien": "2027-01-05",\
&#x20;   "nguoi_lon": 3,\
&#x20;   "tre_em": 0,\
&#x20;   "loai_ve": "thuong",\
&#x20;   "ghi_chu": "hỗ trợ xe lăn"\
&#x20; },\
&#x20; {\
&#x20;   "ma_goi": null,\
&#x20;   "ngay_su_kien": null,\
&#x20;   "nguoi_lon": 4,\
&#x20;   "tre_em": 0,\
&#x20;   "loai_ve": "vip",\
&#x20;   "ghi_chu": "hỗ trợ tìm chỗ ngồi cho người khiếm thị"\
&#x20; }\
]
```

**Link trò chuyện:https://chatgpt.com/share/6b063805-c670-83ec-a042-2412558fa13b**


## 4.3. Báo giá vé bằng Chain-of-Thought

**KET QUA AI**

```text
## **BÁO GIÁ VÉ – TRẬN BÁN KẾT CÚP SAO VÀNG**

### **Bước 1: Tính tiền vé người lớn**

- Số lượng: 5 người lớn.
- Gói vé SVT: 1.200.000 đồng/người.

Phép tính:

\\[ 5 \times 1.200.000 = 6.000.000 \\]

**Tiền vé người lớn: 6.000.000 đồng.**

### **Bước 2: Tính tiền vé trẻ em**

Theo quy định:

- Trẻ 8 tuổi: 70% giá vé người lớn.
- Trẻ 10 tuổi: 70% giá vé người lớn.
- Trẻ 3 tuổi: Miễn phí.

Giá vé mỗi trẻ từ 5–11 tuổi:

\\[ 1.200.000 \times 70\\% = 840.000 \\]

Tiền vé 2 trẻ em:

\\[ 2 \times 840.000 = 1.680.000 \\]

Tiền vé trẻ 3 tuổi:

\\[ 1 \times 0 = 0 \\]

**Tiền vé trẻ em: 1.680.000 đồng.**

### **Bước 3: Tính tổng tiền vé trước giảm giá**

\\[ 6.000.000 + 1.680.000 = 7.680.000 \\]

**Tổng tiền vé trước giảm giá: 7.680.000 đồng.**

### **Bước 4: Tính giảm giá nhóm**

Nhóm có 5 người lớn nên đủ điều kiện giảm 5%.

Tiền được giảm:

\\[ 7.680.000 \times 5\\% = 384.000 \\]

Tiền vé sau giảm:

\\[ 7.680.000 - 384.000 = 7.296.000 \\]

**Tổng tiền vé sau giảm: 7.296.000 đồng.**

### **Bước 5: Tính phụ thu khu ghế ưu tiên**

Có 1 người lớn chọn khu ghế ưu tiên.

Phụ thu:

\\[ 1 \times 300.000 = 300.000 \\]

**Tổng phụ thu: 300.000 đồng.**

### **Bước 6: Tính tổng tiền thanh toán**

Theo quy định:

\\[ \text{Tổng tiền} = \text{Tiền vé sau giảm} + \text{Phụ thu} \\]

Thay số:

\\[ 7.296.000 + 300.000 = 7.596.000 \\]

### **Kết quả báo giá**

- Người lớn: 5 người.
- Trẻ em: 3 bé (2 bé tính phí, 1 bé miễn phí).
- Gói vé: SVT – Sân Vận Động.
- Giảm giá nhóm: 384.000 đồng.
- Phụ thu ghế ưu tiên: 300.000 đồng.

**[RESULT: 7.596.000 đồng]**
```

**Link trò chuyện: https://chatgpt.com/share/6b0638d0-3608-83ec-9a78-45028280981d**

### b) Kiểm tra kết quả AI

Đúng

## 4.4. Dây chuyền xử lý khiếu nại – kết quả Trạm 1

**KET QUA AI**

```text
{\
&#x20; "loai_su_co": "sai_khu_vuc",\
&#x20; "so_khach": 2,\
&#x20; "so_hiep_bi_anh_huong": 2,\
&#x20; "tom_tat": "Hai khán giả bị xếp vào khu không mái che trong 2 hiệp đầu, ảnh hưởng quyền lợi đã cam kết."\
}
```

**Link trò chuyện:https://chatgpt.com/share/6b0639b0-323c-83ec-92f4-e4ef029a055f**

## 4.5. Prompt chấm bài theo Rubric

**KET QUA AI**

```text
| Tiêu chí             | Điểm     | Minh chứng                                                                                                                                                                                                                                                     | Đề xuất sửa                                                                                                                            |
| -------------------- | -------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------- |
| Đúng thông tin (50%) | 0/5      | **Câu bị lỗi:** "Vé Sân Vận Động bên em giá 1.000.000đ/người". **Lý do:** Giá chuẩn là 1.200.000đ/người, báo sai 200.000đ. **Câu bị lỗi:** "Anh huỷ trước 3 ngày thì được hoàn tiền đầy đủ nha anh." **Lý do:** Chưa có dữ liệu xác nhận chính sách hoàn tiền. | "Vé Sân Vận Động có giá 1.200.000đ/người. Về chính sách hủy vé, em xin phép kiểm tra quy định chính thức để tư vấn chính xác cho anh." |
| Đầy đủ (30%)         | 0/3      | **Câu bị lỗi:** "Anh cần gì cứ nhắn em nhé!" **Lý do:** Chưa chủ động mời khách cung cấp ngày trận đấu và số lượng vé để đặt.                                                                                                                                  | "Anh vui lòng cho em biết ngày diễn ra trận đấu và số lượng vé cần đặt để em hỗ trợ kiểm tra và tư vấn cụ thể ạ."                      |
| Giọng điệu (20%)     | 1/2      | **Câu bị lỗi:** "xem rất đã luôn ạ", "nha anh". **Lý do:** Cách diễn đạt hơi suồng sã, chưa phù hợp với phong cách tư vấn chuyên nghiệp.                                                                                                                       | Sử dụng ngôn ngữ lịch sự, chuyên nghiệp: "Trận đấu hứa hẹn mang đến trải nghiệm hấp dẫn. Em luôn sẵn sàng hỗ trợ anh ạ."               |
| **Tổng điểm**        | **1/10** | Bài trả lời sai giá vé, đưa ra chính sách hủy chưa được xác minh và thiếu thông tin cần thiết để đặt vé.                                                                                                                                                       | Cần kiểm tra thông tin chuẩn, trả lời đầy đủ và sử dụng ngôn ngữ chuyên nghiệp.                                                        |
```

**Link trò chuyện:https://chatgpt.com/share/6b063a25-5134-83ec-9901-d021e8ebf6ef**
