# HTML căn bản – Ví dụ và khái niệm

Trong chương này, chúng ta sẽ cùng **lướt qua một số ví dụ HTML căn bản**. Đừng lo lắng nếu bạn bắt gặp những thẻ mà mình chưa được học nhé, chúng ta sẽ **dần dần làm quen** với chúng ngay thôi.

---

## Tài liệu HTML (HTML Documents)

Để một tài liệu HTML hoạt động đúng chuẩn, bạn cần nhớ các quy tắc sau:

- Mọi tài liệu phải bắt đầu bằng lời khai báo kiểu: `<!DOCTYPE html>`.
- Toàn bộ nội dung tài liệu bắt đầu bằng thẻ `<html>` và kết thúc bằng thẻ `</html>`.
- Phần nội dung hiển thị cho người xem nằm gói gọn giữa cặp thẻ `<body>` và `</body>`.

### Ví dụ minh họa

```html
<!DOCTYPE html>
<html>
  <body>
    <h1>Tiêu đề đầu tiên của tôi</h1>
    <p>Đoạn văn đầu tiên của tôi.</p>
  </body>
</html>
```

---

## Khai báo `<!DOCTYPE>`

Khai báo `<!DOCTYPE>` đại diện cho **kiểu tài liệu**, giúp trình duyệt hiểu và hiển thị trang web một cách chính xác.

- Chỉ xuất hiện **một lần duy nhất** ở dòng trên cùng của trang.
- Luôn đứng **trước bất kỳ thẻ HTML nào**.
- Không phân biệt chữ hoa hay chữ thường.

### Khai báo trong HTML5

```html
<!DOCTYPE html>
```

---

## Các tiêu đề trong HTML (Headings)

Các tiêu đề được định nghĩa bằng các thẻ từ `<h1>` đến `<h6>`:

- `<h1>`: Tiêu đề **quan trọng nhất** (lớn nhất)
- `<h6>`: Tiêu đề **ít quan trọng nhất** (nhỏ nhất)

### Ví dụ

```html
<h1>Đây là tiêu đề cấp 1</h1>
<h2>Đây là tiêu đề cấp 2</h2>
<h3>Đây là tiêu đề cấp 3</h3>
```

---

## Đoạn văn trong HTML (Paragraphs)

Để tạo một đoạn văn bản, chúng ta sử dụng thẻ `<p>`.

### Ví dụ

```html
<p>Đây là một đoạn văn.</p>
<p>Đây là một đoạn văn khác.</p>
```

---

## Liên kết trong HTML (Links)

Các liên kết được định nghĩa bằng thẻ `<a>`. Điểm đến của liên kết được quy định trong thuộc tính `href`.

### Ví dụ

```html
<a href="https://www.w3schools.com">Đây là một liên kết</a>
```

> **Lưu ý:** Thuộc tính (_attributes_) được dùng để cung cấp thêm thông tin cho các phần tử HTML. Bạn sẽ được tìm hiểu kỹ hơn về chúng ở chương sau.

---

## Hình ảnh trong HTML (Images)

Hình ảnh được định nghĩa bằng thẻ `<img>`. Các thông tin như:

- `src`: đường dẫn tới file ảnh
- `alt`: văn bản thay thế
- `width`: chiều rộng
- `height`: chiều cao

được cung cấp dưới dạng **thuộc tính**.

### Ví dụ

```html
<img src="w3schools.jpg" alt="W3Schools.com" width="104" height="142" />
```

---

## Cách xem mã nguồn HTML

Bạn đã bao giờ tự hỏi: _"Sao họ làm được trang web đẹp thế nhỉ?"_
Tin vui là bạn hoàn toàn có thể **xem và học hỏi từ mã nguồn của bất kỳ trang web nào**.

### 1. Xem mã nguồn trang (View Page Source)

- Nhấn **CTRL + U** trên trang web bất kỳ
- Hoặc nhấp chuột phải và chọn **View Page Source** (Xem nguồn trang)

-> Một tab mới sẽ mở ra chứa **toàn bộ mã HTML** của trang.

### 2. Kiểm tra phần tử (Inspect Element)

- Nhấp chuột phải vào một phần tử (hoặc vùng trống)
- Chọn **Inspect** (Kiểm tra)

Cách này cho phép bạn:

- Xem cấu trúc HTML
- Xem và chỉnh sửa CSS
- Thử thay đổi trực tiếp và **thấy kết quả ngay lập tức**
