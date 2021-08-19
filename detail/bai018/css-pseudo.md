# Pseudo

Bao gồm các mục:

- **_`Pseudo Classes - Lớp Giả`_**
  - :root
  - :hover
  - :active
  - :first-child
  - :last-child
- **_`Pseudo Elements - Phần Tử Giả`_**
  - ::before
  - ::after
  - ::first-letter
  - ::first-line
  - ::selection

---

## I. Pseudo Classes - Lớp Giả

Sẽ có dấu `:` đầu tiên, những **`Pseudo Classes`** hay sử dụng là:

- :root
- :hover
- :active
- :first-child
- :last-child

Xem thêm ở [w3schools css Pseudo Classes](https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-classes)

---

### :root

- Xem lại mục [CSS Variable](../bai014/css-variable.md) và [CSS Functions](../bai016/css-function.md)

- `:root` lớp giả này sẽ tham chiếu đến phần tử gốc của file html là cặp thẻ `<html> </html>`
- Sẽ dùng khai báo biến `Global Variable`.

![Pseudo Classes :root](./images/03-002.png "Pseudo Classes :root")

![Pseudo Classes :root](./images/12-001.png "Pseudo Classes :root")
![Pseudo Classes :root](./images/12-002.png "Pseudo Classes :root")

Xem thêm ở [w3schools css Pseudo :root](https://developer.mozilla.org/en-US/docs/Web/CSS/:root)

---

### :hover

- Thuộc tính khi chuyển con trỏ chạm vào đối tượng sẽ xảy ra sự kiện này.

![Pseudo Classes :hover](./images/12-003.png "Pseudo Classes :hover")
![Pseudo Classes :hover](./images/12-004.png "Pseudo Classes :hover")
![Pseudo Classes :hover](./images/12-005.png "Pseudo Classes :hover")

Xem thêm ở [w3schools css Pseudo :hover](https://developer.mozilla.org/en-US/docs/Web/CSS/:hover)

---

### :active

- Thuộc tính khi chuyển con trỏ click vào đối tượng và bấm giữ nguyên sẽ xảy ra sự kiện này. (`Click & hold`)

![Pseudo Classes :hover](./images/12-003.png "Pseudo Classes :hover")
![Pseudo Classes :hover](./images/12-004.png "Pseudo Classes :hover")
![Pseudo Classes :hover](./images/12-005.png "Pseudo Classes :hover")

Xem thêm ở [w3schools css Pseudo :hover](https://developer.mozilla.org/en-US/docs/Web/CSS/:hover)

---

### :first-child & :last-child

- Sử dụng cho 1 nhóm đối tượng, và sẽ lấy đối tượng đầu tiên hoặc đối tượng cuối cùng -> Thường áp dụng cho 1 list danh sách để lấy đối tượng.

![Pseudo Classes :first-child](./images/12-006.png "Pseudo Classes :first-child")

Xem thêm ở [w3schools css Pseudo :first-child](https://developer.mozilla.org/en-US/docs/Web/CSS/:first-child)

---

## II. Pseudo Elements - Phần Tử Giả

- ::before
- ::after
- ::first-letter
- ::first-line
- ::selection

Xem thêm ở [w3schools css Pseudo Elements](https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-elements)

---

### ::before

- Sử dụng để tạo 1 đối tượng giả đứng trước đối tượng cần thêm.

![Pseudo Elements ::before](./images/13-001.png "Pseudo Elements ::before 01")
![Pseudo Elements ::before](./images/13-002.png "Pseudo Elements ::before 02")
![Pseudo Elements ::before](./images/13-003.png "Pseudo Elements ::before 03")

> Syntax : Muốn thêm 1 khối màu thì phải có Content = "" và Display : block.

<img src="./images/13/13-000.png" alt="CSS Pseudo Elements ::before" width="300px"/>

![Pseudo Elements ::before](./images/13-004.png "Pseudo Elements ::before 04")

Xem thêm ở [w3schools css Pseudo ::before](https://developer.mozilla.org/en-US/docs/Web/CSS/::before)

---

### ::after

- Sử dụng để tạo 1 đối tượng giả đứng sau đối tượng cần thêm.
- Xem lại mục [CSS Function Attr()](../detail/css-function.md) có sử dụng điều chỉnh `Content`
- Tiếp theo mục `::before`, bây giờ sẽ thêm 1 block `::after` và kiểm tra vị trí `elements box` trên `Dev Tool`.

![Pseudo Elements ::after](./images/13-005.png "Pseudo Elements ::after 01")
![Pseudo Elements ::after](./images/13-006.png "Pseudo Elements ::after 02")
![Pseudo Elements ::after](./images/13-007.png "Pseudo Elements ::after 03")

Xem thêm ở [w3schools css Pseudo ::after](https://developer.mozilla.org/en-US/docs/Web/CSS/::after)

---

### ::first-letter

- Lấy ký tự đầu của 1 đối tượng text.
- Thường sẽ lấy chữ cái viết hoa.

![Pseudo Elements ::first-letter](./images/14-001.png "Pseudo Elements ::first-letter 01")
<img src="./images/14-002.png" alt="CSS Pseudo Elements ::first-letter" width="300px"/>

---

### ::first-line

- Sử dụng lấy dòng đầu tiên của Paragraph, khi co giãn vẫn lấy dòng đầu tiên hiển thị.

![Pseudo Elements ::first-line](./images/14-003.png "Pseudo Elements ::first-line 01")
![Pseudo Elements ::first-line](./images/14-004.png "Pseudo Elements ::first-line 02")

---

### ::selection

- Thuộc tính khi chọn hay bôi đen 1 đoạn, đối tượng nào đó.

![Pseudo Elements ::selection](./images/14-005.png "Pseudo Elements ::selection 01")
![Pseudo Elements ::selection](./images/14-006.png "Pseudo Elements ::selection 02")

---
