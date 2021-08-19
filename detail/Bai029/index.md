# Phần 07: Thuộc tính vị trí (Position)

Các khai báo về vị trí `Position`:

- Relative
- Absolute
- Fixed
- Sticky

---

## 1. Position Relative

- Vị trí tương đối của đối tượng.
- Nếu ta có vị trí bố trí như sau:

<img src="./images/05-000.png" alt="Position Relative 000" width="300px"/>

<!-- ![Position Relative](./images/05-000.png "Position Relative 000") -->

![Position Relative](./images/05-001.png "Position Relative 001")

> Yêu cầu: Di chuyển Position(h1) đè lên hình vuông Box.

- Nếu thay đổi margin thì sẽ bị đẩy cả cụm xuống dưới.

![Position Relative](./images/05-002.png "Position Relative")

- Lúc này ta sử dụng `Position Relative` để không ảnh hưởng đến các `elements` khác.

![Position Relative](./images/05-003.png "Position Relative 003")
![Position Relative](./images/05-004.png "Position Relative 004")
![Position Relative](./images/05-005.png "Position Relative 005")
![Position Relative](./images/05-006.png "Position Relative 006")

<img src="./images/05-007.png" alt="Position Relative 007" width="300px"/>

<!-- ![Position Relative](./images/05-007.png "Position Relative 007") -->

> Lưu ý: Nếu không có thuộc tính position thì sẽ không dùng được các thuộc tính (top, bottom, left, right).
