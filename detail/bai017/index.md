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
