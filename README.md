# HCM-KS26-CNTT1_NhapMonCNTT_Session22_Ex01
# BÀI 1: TÌM KIẾM TÀI LIỆU HỌC TẬP CHÍNH THỐNG BẰNG GOOGLE

**Họ và tên:** Phạm Thành Đạo  
**Lớp:** HCM-KS26-CNTT1  
**Môn học:** IT-101 – Nhập môn Công nghệ thông tin  
**Bài tập:** Bài 1 – Tìm kiếm tài liệu học tập chính thống bằng Google

## 1. Mục tiêu

Sử dụng phối hợp các toán tử tìm kiếm nâng cao của Google để tìm kiếm tài liệu học tập chính thống, ưu tiên tài liệu PDF từ website của Học viện Công nghệ Bưu chính Viễn thông (PTIT), hạn chế các kết quả không liên quan và website không đáng tin cậy.

## 2. Xây dựng chuỗi truy vấn Google

### 2.1. Chuỗi truy vấn

```text
site:ptit.edu.vn filetype:pdf "Nhập môn Công nghệ Thông tin" -tailieu.vn -123doc.org
```

### 2.2. Giải thích các toán tử

| Toán tử | Chức năng | Mục đích |
|---|---|---|
| `site:ptit.edu.vn` | Giới hạn phạm vi website | Chỉ tìm kiếm trên tên miền PTIT |
| `filetype:pdf` | Lọc định dạng tệp | Tìm tài liệu PDF |
| `"Nhập môn Công nghệ Thông tin"` | Tìm kiếm cụm từ chính xác | Hạn chế kết quả sai chủ đề |
| `-tailieu.vn` | Loại trừ website | Loại bỏ kết quả từ Tailieu.vn |
| `-123doc.org` | Loại trừ website | Loại bỏ kết quả từ 123doc |

### 2.3. Lý do lựa chọn tên miền

PTIT là tên viết tắt của Học viện Công nghệ Bưu chính Viễn thông. Việc sử dụng toán tử `site:ptit.edu.vn` giúp giới hạn kết quả trong phạm vi website của Học viện, tăng khả năng tìm được tài liệu có nguồn gốc chính thống.

Ngoài ra, có thể tham khảo thư viện số của Học viện tại:

https://dlib.ptit.edu.vn/

## 3. Phân tích hiệu quả của toán tử filetype:

Khi tìm kiếm thông thường bằng từ khóa:

```text
tải sách Nhập môn Công nghệ Thông tin PDF
```

Google có thể trả về nhiều kết quả không phù hợp như:

- Các trang quảng cáo dịch vụ tải tài liệu.
- Các bài viết giới thiệu sách nhưng không cung cấp tệp PDF.
- Các website yêu cầu đăng ký tài khoản hoặc nạp tiền.
- Các trang chia sẻ tài liệu không rõ nguồn gốc.

Khi sử dụng toán tử `filetype:pdf`, Google sẽ lọc kết quả theo định dạng tệp PDF, giúp người dùng tập trung hơn vào loại tài liệu cần tìm.

Khi kết hợp với `site:` và dấu ngoặc kép, phạm vi tìm kiếm được thu hẹp hơn, giảm thời gian sàng lọc kết quả.

### Lợi ích

1. Tiết kiệm thời gian tìm kiếm tài liệu.
2. Hạn chế các kết quả không liên quan.
3. Tìm kiếm đúng định dạng tệp mong muốn.
4. Tăng khả năng tiếp cận nguồn tài liệu chính thống.
5. Hạn chế truy cập nhầm vào các website chia sẻ tài liệu không rõ nguồn gốc.

**Lưu ý:** Toán tử `filetype:pdf` không có chức năng kiểm tra virus. Người dùng vẫn cần kiểm tra nguồn tải và quét tệp trước khi mở.

## 4. Kết quả thực nghiệm và minh chứng

Truy cập Google bằng đường dẫn sau:

https://www.google.com/search?q=site%3Aptit.edu.vn+filetype%3Apdf+%22Nh%E1%BA%ADp+m%C3%B4n+C%C3%B4ng+ngh%E1%BB%87+Th%C3%B4ng+tin%22+-tailieu.vn+-123doc.org

Sau khi thực hiện tìm kiếm, tiến hành:

1. Quan sát các kết quả được Google trả về.
2. Kiểm tra tên miền của từng kết quả.
3. Xác định tiêu đề và nội dung tài liệu.
4. Chụp ảnh màn hình 3 kết quả đầu tiên.


## 5. Cấu trúc repository GitHub

Tên repository đề xuất:

```text
HCM-KS26-CNTT1_IT-101_Session-20_Bai-1
```

Cấu trúc thư mục:

```text
HCM-KS26-CNTT1_IT-101_Session-20_Bai-1/
│
├── README.md
│
└── images/
    └── google-search-results.png
```

Toàn bộ nội dung phân tích được lưu trong `README.md`, ảnh minh chứng được lưu trong thư mục `images`.

## 6. Kết luận

Thông qua bài tập, em đã tìm hiểu và vận dụng các toán tử tìm kiếm nâng cao của Google gồm `site:`, `filetype:`, dấu ngoặc kép và toán tử loại trừ `-`.

Việc kết hợp các toán tử này giúp quá trình tìm kiếm tài liệu có định hướng rõ ràng hơn, hạn chế kết quả không liên quan và tăng khả năng tiếp cận nguồn học liệu chính thống.

Đây là kỹ năng cần thiết đối với sinh viên Công nghệ thông tin khi tìm kiếm tài liệu phục vụ học tập, nghiên cứu và giải quyết các vấn đề kỹ thuật.

---
