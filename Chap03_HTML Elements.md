# Các phần tử HTML (HTML Elements)

Một **phần tử HTML** thường được định nghĩa bởi **thẻ mở**, **nội dung** và **thẻ đóng**.

## Cấu trúc chung

```html
<tên_thẻ> Nội dung nằm ở đây... </tên_thẻ>
```

---

## Ví dụ về một số phần tử HTML

```html
<h1>Tiêu đề chính của tôi</h1>
<p>Đoạn văn đầu tiên của tôi.</p>
```

---

## Bảng phân tích thành phần

| Thẻ mở | Nội dung phần tử          | Thẻ đóng |
| ------ | ------------------------- | -------- |
| `<h1>` | Tiêu đề chính của tôi     | `</h1>`  |
| `<p>`  | Đoạn văn đầu tiên của tôi | `</p>`   |
| `<br>` | Không có                  | Không có |

> **Lưu ý:** Một số phần tử HTML không có nội dung (như thẻ ngắt dòng `<br>`). Chúng được gọi là **phần tử rỗng (empty elements)** và **không có thẻ đóng**.

---

## Các phần tử HTML lồng nhau (Nested HTML Elements)

Các phần tử HTML có thể được **lồng vào nhau**, nghĩa là phần tử này có thể chứa phần tử khác bên trong nó.

Thực tế, **tất cả tài liệu HTML** đều bao gồm các phần tử lồng nhau, giống như **những chiếc hộp xếp chồng lên nhau**.

### Ví dụ

Đoạn mã dưới đây chứa **4 phần tử**: `<html>`, `<body>`, `<h1>` và `<p>`.

```html
<!DOCTYPE html>
<html>
  <body>
    <h1>Tiêu đề chính của tôi</h1>
    <p>Đoạn văn đầu tiên của tôi.</p>
  </body>
</html>
```

---

## Giải thích chi tiết

- **Phần tử `<html>`**:
  - Là phần tử gốc (_root element_)
  - Bao trùm toàn bộ tài liệu HTML
  - Có thẻ mở `<html>` và thẻ đóng `</html>`

- **Phần tử `<body>`**:
  - Nằm bên trong `<html>`
  - Định nghĩa phần thân của tài liệu
  - Có thẻ mở `<body>` và thẻ đóng `</body>`

- **Phần tử `<h1>` và `<p>`**:
  - Nằm bên trong `<body>`
  - `<h1>`: Định nghĩa một tiêu đề
  - `<p>`: Định nghĩa một đoạn văn

---

## Đừng bao giờ bỏ quên thẻ đóng

Một số phần tử HTML **vẫn có thể hiển thị** ngay cả khi bạn quên viết thẻ đóng.

### Ví dụ (không khuyến khích)

```html
<html>
  <body>
    <p>Đây là một đoạn văn</p>
    <p>Đây là một đoạn văn</p>
  </body>
</html>
```

Lưu ý: **Tuy nhiên, đừng bao giờ ỷ lại vào điều này!**
Việc quên thẻ đóng có thể dẫn đến:

- Hiển thị sai lệch
- Lỗi bố cục
- Hành vi không mong muốn trên các trình duyệt khác nhau

-> **Luôn viết code đầy đủ và cẩn thận.**

---

## Phần tử HTML rỗng (Empty HTML Elements)

Như đã đề cập, **phần tử rỗng** là các phần tử **không có nội dung**.

- Ví dụ điển hình: `<br>` – dùng để **ngắt dòng**
- Không cần thẻ đóng

### Ví dụ

```html
<p>
  Đây là một <br />
  đoạn văn có ngắt dòng.
</p>
```

---

## HTML không phân biệt chữ hoa – chữ thường

Các thẻ HTML **không phân biệt hoa – thường**:

- `<P>` và `<p>` có tác dụng như nhau

Tuy nhiên:

- Tiêu chuẩn HTML **không bắt buộc**, nhưng
- **W3C khuyến khích dùng chữ thường**
- Các chuẩn nghiêm ngặt như **XHTML bắt buộc viết thường**

### Lời khuyên

> Trong môi trường lập trình chuyên nghiệp (và tại W3Schools), **luôn sử dụng tên thẻ viết thường** để mã nguồn gọn gàng, dễ đọc và chuẩn mực.
