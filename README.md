# SESSION 20 – QUY TRÌNH GỠ LỖI

## PHẦN 1 – GOOGLING

**1.** Câu hỏi dài, nhiều từ thừa nên Google khó xác định từ khóa chính.

**2. Bóc tách lỗi:**
- Phần mềm / Hệ điều hành: Node.js / Windows 11.
- Mã lỗi: `npm is not recognized...`
- Thao tác: Gõ `npm -v` trong VS Code.

**3. Ba câu tìm kiếm:**
- `site:stackoverflow.com npm not recognized Windows 11`
- `"npm is not recognized as an internal or external command"`
- `npm not recognized Windows -windows-xp`

## PHẦN 2 – STACKOVERFLOW

**1. So sánh:**

| Tiêu chí | A | B |
|---|---|---|
| Vote | +186, có tích xanh | +2, không tích xanh |
| Thời gian | 2 năm | 9 năm |
| Tags | Windows, npm | Windows XP |

**2.** Chọn A vì uy tín và phù hợp Windows 11. B là bẫy vì hướng dẫn cho Windows XP.

**3.** Thứ tự đọc lướt: Tiêu đề -> Tags -> Vote -> Tích xanh -> Nội dung.

## PHẦN 3 – HỎI AI

**1. Prompt:**

Tôi dùng Node.js trên Windows 11, chạy `npm -v` trong VS Code nhưng gặp lỗi:

`npm is not recognized as an internal or external command.`

Tôi đã thêm PATH và mở Terminal mới nhưng vẫn lỗi. Hãy giải thích nguyên nhân và hướng dẫn cách sửa an toàn.

**2.** Không chạy lệnh AI đề xuất vì có thể xóa tệp hệ thống và làm hỏng Windows.

**3.** Hỏi AI: "Có cách nào kiểm tra và sửa PATH an toàn hơn không? Vì sao cần xóa System32?"

## PHẦN 4 – BUG REPORT

**1. Tin nhắn kém:**

"Thầy ơi, máy em bị lỗi npm, thầy giúp em với!"

**2. Tin nhắn chuẩn:**

| Mảnh ghép | Nội dung |
|---|---|
| Context | Dùng Node.js trên Windows 11, VS Code. |
| Expected | `npm -v` hiển thị phiên bản npm. |
| Actual | Báo lỗi `npm is not recognized...` dù đã thêm PATH. |
| Log & Screenshot | Gửi ảnh chụp màn hình lỗi. |

**3.**
- Phím tắt: `Windows + Shift + S`.
- Bảo mật: Che mật khẩu và API Key trước khi gửi ảnh.
