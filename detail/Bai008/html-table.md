# Thẻ TABLE

## Giới thiệu

Bố cục hiển thị dạng bảng rất phổ biến trên các website. Về cơ bản thì bảng được cấu tạo từ hai thành phần chính là `Hàng` và `Cột`. Tuy nhiên trong `HTML` thì bảng sẽ được chia thành các thành phần chi tiết hơn. Xem [video](https://youtu.be/AzmdwZ6e_aM?t=4).

## Các thành phần

Các thành phần của bảng trong HTML bao gồm:

- Thẻ `table` có nhiệm vụ khai báo khi sử dụng bảng.
- Thẻ `thead` chứa phần tiêu đề bảng. Thẻ `thead` luôn là con của thẻ `table`.
  > VD như thời khóa biểu thì tiêu đề là Thứ hai, Thứ ba.
- Thẻ `tbody` chứa phần thân của bảng. Thẻ `tbody` luôn là con của thẻ `table` và đứng ngang hàng với thẻ `thead`.
  > VD như thời khóa biểu thì phần này sẽ chứa tiết học và tên các môn học.
- Thẻ `tr` định nghĩa một dòng. Thẻ `tr` luôn là con của thẻ `thead` hoặc `tbody`.
- Thẻ `th` định nghĩa một cột tiêu đề. Thẻ `th` luôn là con của thẻ `tr` nằm trong thẻ `thead`.
- Thẻ `td` định nghĩa một cột nội dung. Thẻ `td` luôn là con của thẻ `tr` nằm trong thẻ `tbody`.

Khi viết thiếu thẻ `thead`, `tbody`, `tr` thì các trình duyệt hiện đại sẽ tự thêm các thành phần này vào website của bạn. Không vì lý do đó và chúng ta bỏ bớt các thành phần này, tốt nhất chúng ta luôn tuân thủ đúng cấu trúc `table` khi sử dụng nó.

> Trong video mình đã thiếu xót không nói về thẻ tr nằm trong thẻ thead. Xin lỗi các bạn!

## Cú pháp

Từ lý thuyết trên ta sẽ xây dựng một thời khóa biểu như sau:

```html
<!-- Thẻ table để tạo layout dạng bảng -->
<table>
  <!-- Thẻ thead chứa phần tiêu đề bảng (table head) -->
  <thead>
    <!-- Thẻ tr là một dòng (table row) -->
    <tr>
      <!-- Thẻ th chứa cột tiêu đề (table heading) -->
      <th>#</th>
      <th>Thứ hai</th>
      <th>Thứ ba</th>
    </tr>
  </thead>

  <!-- Thẻ tbody chứa phần thân bảng (table body) -->
  <tbody>
    <!-- Nội dung dòng 1 -->
    <tr>
      <!-- Thẻ td chứa cột nội dung (table data) -->
      <td>Tiết 1</td>
      <td>Chào cờ</td>
      <!-- Tiết 1 thứ hai -->
      <td>Toán</td>
      <!-- Tiết 1 thứ ba -->
    </tr>

    <!-- Nội dung dòng 2 -->
    <tr>
      <td>Tiết 2</td>
      <td>Văn</td>
      <!-- Tiết 2 thứ hai -->
      <td>Sử</td>
      <!-- Tiết 2 thứ ba -->
    </tr>

    <!-- Nội dung dòng n -->
    ...
  </tbody>
</table>
```

| #      | Thứ hai | Thứ ba |
| ------ | ------- | ------ |
| Tiết 1 | Chào cờ | Toán   |
| Tiết 2 | Văn     | Sử     |
| Tiết n | ...     | ...    |
