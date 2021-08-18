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

<img src="./images/05/05-000.png" alt="Position Relative 000" width="300px"/>

<!-- ![Position Relative](./images/05-000.png "Position Relative 000") -->

![Position Relative](./images/05/05-001.png "Position Relative 001")

> Yêu cầu: Di chuyển Position(h1) đè lên hình vuông Box.

- Nếu thay đổi margin thì sẽ bị đẩy cả cụm xuống dưới.

![Position Relative](./images/05/05-002.png "Position Relative")

- Lúc này ta sử dụng `Position Relative` để không ảnh hưởng đến các `elements` khác.

![Position Relative](./images/05/05-003.png "Position Relative 003")
![Position Relative](./images/05/05-004.png "Position Relative 004")
![Position Relative](./images/05/05-005.png "Position Relative 005")
![Position Relative](./images/05/05-006.png "Position Relative 006")

<img src="./images/05/05-007.png" alt="Position Relative 007" width="300px"/>

<!-- ![Position Relative](./images/05-007.png "Position Relative 007") -->

> Lưu ý: Nếu không có thuộc tính position thì sẽ không dùng được các thuộc tính (top, bottom, left, right).

## 2. Position Absolute

- Khi nhìn layout thấy 1 đối tượng là con `child` của 1 đối tượng khác.
- Muốn di chuyển đối tượng vị trí đối tượng con xung quanh đối tượng cha.
- Di chuyển đối tượng cha nhưng không làm thay đổi vị trí của đối tượng con trong cha thì dùng chức năng `Absolute`.
- Đối tượng con có thể tự do di chuyển trong đối tượng cha.
- Khi đối tượng được khai báo `Absolute` sẽ tìm cấp cao hơn chứa thuộc tính `position` để làm trục tọa độ để sử dụng (top,bottom, left, right). Nếu không thấy sẽ căn cứ vào trình duyệt.

![Position Absolute](./images/06/06-001.png "Absolute Absolute 001")
![Position Absolute](./images/06/06-002.png "Absolute Absolute 002")
![Position Absolute](./images/06/06-003.png "Absolute Absolute 003")
![Position Absolute](./images/06/06-004.png "Absolute Absolute 004")
![Position Absolute](./images/06/06-005.png "Absolute Absolute 005")
![Position Absolute](./images/06/06-006.png "Absolute Absolute 006")
![Position Absolute](./images/06/06-007.png "Absolute Absolute 007")
![Position Absolute](./images/06/06-008.png "Absolute Absolute 008")
![Position Absolute](./images/06/06-009.png "Absolute Absolute 009")

- Thẻ con có position `Absolute` sẽ tìm theo từng cấp thẻ cha bên ngoài bao bọc thẻ con đó xem có thẻ nào có thuộc tính position để làm góc tọa độ.

- Ứng dụng: Tạo lớp layout overlay phủ lên toàn bộ trang.

![Position Absolute](./images/06/06-010.png "Absolute Absolute 010")
![Position Absolute](./images/06/06-011.png "Absolute Absolute 011")
![Position Absolute](./images/06/06-012.png "Absolute Absolute 012")
![Position Absolute](./images/06/06-013.png "Absolute Absolute 013")

## 3. Position Fixed

- Thuộc tính này giúp cố định đối tượng 1 vị trí nào đó, ghim(pin) đổi tượng.
- Ứng dụng cho các Header kéo xuống vẫn giữ nguyên ở đầu.

![Position Fixed](./images/07/07-001.png "Absolute Fixed 001")
![Position Fixed](./images/07/07-002.png "Absolute Fixed 002")
![Position Fixed](./images/07/07-003.png "Absolute Fixed 003")
![Position Fixed](./images/07/07-004.png "Absolute Fixed 004")
