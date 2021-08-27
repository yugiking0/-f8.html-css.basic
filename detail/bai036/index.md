# Tạo Project Base

Tạo các thẻ div html

- header
- slider
- content
- footer
  Cần 1 thẻ div lớn chứa toàn bộ Website bao gồm các thẻ trên
- Cần nghĩ đến tên của class sẽ đặt tên trước khi tạo.
- Với các thành phần chính của trang web thì cần tạo bằng ID thay vì tạo class.
  - Tạo thẻ div id = wrapper hoặc main hoặc app
- Trong thẻ div main sẽ bao gồm các thẻ điv id là:
  - header
  - slider
  - content
  - footer
- Ngoài ra sẽ có 1 thẻ div là container mục đích sẽ chứa thẻ content vì đôi khi 1 trang web có nhiều content khác nhau, nên cần 1 thẻ div container chứa toàn bộ các content này.

```html
<body>
  <div id="wrapper">
    <div id="header"></div>

    <div id="slider"></div>

    <div id="container">
      <div class="content"></div>

      <div class="content"></div>
    </div>

    <div id="footer"></div>
  </div>
</body>
```

- Vì nhiều content có cấu trúc giống nhau nên sẽ không đặt ID mà chuyển thành class để đồng nhất và không bị trùng khi gọi vào.
