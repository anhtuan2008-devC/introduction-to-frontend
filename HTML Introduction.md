# HTML là gì?

**HTML** (viết tắt của _Hyper Text Markup Language_) là **ngôn ngữ đánh dấu siêu văn bản**. Đây là ngôn ngữ tiêu chuẩn để tạo nên các trang web.

Bạn có thể hình dung HTML giống như **bộ khung xương của một ngôi nhà**:

- Nó mô tả **cấu trúc** của trang web.
- Nó bao gồm một loạt các **phần tử (elements)**.
- Các phần tử này sẽ _"hướng dẫn"_ trình duyệt cách hiển thị nội dung, chẳng hạn như:
  - đây là tiêu đề
  - đây là đoạn văn
  - đây là một liên kết

---

## Ví dụ về một tài liệu HTML đơn giản

Dưới đây là cấu trúc cơ bản nhất của một trang web:

```html
<!DOCTYPE html>
<html>
  <head>
    <title>Tiêu đề trang</title>
  </head>
  <body>
    <h1>Tiêu đề chính của tôi</h1>
    <p>Đoạn văn đầu tiên của tôi.</p>
  </body>
</html>
```

---

## Giải thích ý nghĩa các thành phần

- `<!DOCTYPE html>`: Lời khai báo giúp trình duyệt hiểu rằng đây là tài liệu chuẩn **HTML5**.
- `<html>`: Phần tử gốc (_root element_) bao trùm toàn bộ trang web.
- `<head>`: Chứa các thông tin **meta** về trang (không hiển thị trực tiếp).
- `<title>`: Tiêu đề của trang (xuất hiện trên tab hoặc thanh tiêu đề trình duyệt).
- `<body>`: Phần thân tài liệu, chứa **toàn bộ nội dung hiển thị** cho người xem.
- `<h1>`: Định nghĩa một **tiêu đề lớn** (_Heading_).
- `<p>`: Định nghĩa một **đoạn văn bản** (_Paragraph_).

---

## Phần tử HTML (HTML Element) là gì?

Một **phần tử HTML** thường bao gồm:

- Thẻ mở
- Nội dung
- Thẻ đóng

### Cấu trúc chung

```html
<tên_thẻ> Nội dung nằm ở đây... </tên_thẻ>
```

### Ví dụ

```html
<h1>Tiêu đề chính của tôi</h1>
<p>Đoạn văn đầu tiên của tôi.</p>
```

### Lưu ý quan trọng

- Một số phần tử HTML **không có nội dung**, ví dụ: `<br>`.
- Chúng được gọi là **phần tử rỗng (empty elements)** và **không có thẻ đóng**.

---

## Trình duyệt Web (Web Browsers)

Mục đích chính của các trình duyệt (Chrome, Edge, Firefox, Safari, ...) là:

- Đọc tài liệu HTML
- Hiển thị nội dung một cách chính xác cho người dùng

Lưu ý: Trình duyệt **không hiển thị các thẻ HTML**, mà sử dụng chúng như **quy tắc trình bày nội dung**.

---

## Cấu trúc trang HTML

Cấu trúc cây của một trang HTML:

```
<html>
 ├── <head>
 │    └── <title> Tên trang
 └── <body>
      ├── <h1> Đây là tiêu đề
      ├── <p> Đây là một đoạn văn
      └── <p> Đây là một đoạn văn khác
```

**Ghi chú:**

- Chỉ nội dung nằm trong `<body>` mới hiển thị trên trình duyệt.
- Nội dung trong `<title>` chỉ hiển thị trên **tab/thanh tiêu đề**.

---

## Lịch sử phát triển HTML

| Năm  | Phiên bản / Sự kiện                             |
| ---- | ----------------------------------------------- |
| 1989 | Tim Berners-Lee phát minh ra WWW                |
| 1991 | Tim Berners-Lee phát minh ra HTML               |
| 1993 | Dave Raggett soạn thảo HTML+                    |
| 1995 | HTML Working Group định nghĩa HTML 2.0          |
| 1997 | Khuyến nghị của W3C: HTML 3.2                   |
| 1999 | Khuyến nghị của W3C: HTML 4.01                  |
| 2000 | Khuyến nghị của W3C: XHTML 1.0                  |
| 2008 | WHATWG ra mắt bản nháp đầu tiên của HTML5       |
| 2012 | WHATWG công bố HTML5 Living Standard            |
| 2014 | Khuyến nghị của W3C: HTML5                      |
| 2016 | Ứng viên khuyến nghị của W3C: HTML 5.1          |
| 2017 | Khuyến nghị của W3C: HTML5.1 (Lần 2) và HTML5.2 |

---

**Hướng dẫn này tuân theo tiêu chuẩn HTML5 mới nhất.**
