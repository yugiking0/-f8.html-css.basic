# Priority - Ưu tiên CSS

Cấp độ ưu tiên trong CSS khi gán Style:

- Internal, External ?
- tag - 1
- .class - 10
- #id - 100
- Inline - 1000
- Equal specificity
- Universal selector or inherited

---

## Nội dung

Phần này sẽ liên quan đến việc CSS gán style cho các thẻ, đối tượng elements trong html dựa trên các mức độ ưu tiên nếu cùng 1 đối tượng được khai báo cùng lúc bằng nhiều cách.

---

### 1. Internal, External (Khai báo trong hay khai báo file ngoài)

- `Internal` : Khi sử dụng khai báo CSS bằng style trong file html.

![Internal](./images/02-001.png "Internal")

- `External` : Khi sử dụng khai báo CSS thông qua 1 file style link từ bên ngoài vào file html.

![External](./images/02-002.png "External")

> file style.css được khai báo ở ngoài file index.html và được link vào.

<img src="./images/02-000.png" alt="style.css" width="300px"/>

```css
h1 {
  color: red;
}
```

- Vậy việc ưu tiên khai báo nào sẽ được ưu tiên hơn giữa `Internal` - Khai báo ngay ở trong file và `External`- Khai báo liên kết từ file ngoài ???

- Vị trí ưu tiên cùng 1 đối tượng `element` sẽ được ưu tiên dựa trên vị trí đặt của `Internal` hay `External` theo thứ tự sắp xếp, khai báo được gọi sau cùng sẽ được ưu tiên hơn.

![Internal, External](./images/02-003.png "Internal, External")
![Internal, External](./images/02-004.png "Internal, External")
![Internal, External](./images/02-005.png "Internal, External")

> Thẻ h1 được khai báo ở vị trí 3 cuối cùng sẽ được ưu tiên.

### 2. Tag (Khai báo theo thẻ)

- Nếu khai báo cùng 1 đối tượng element nằm sau cùng sẽ được ưu tiên hơn.

![tag](./images/02-007.png "tag")

### 3. Class (Khai báo lớp .class)

- Nếu cùng một đối tượng được khai báo, mức độ ưu tiên sẽ theo thứ tự sắp xếp của điểm số tăng dần như sau:
  - tag - 1
  - .class - 10
  - #id - 100
  - Inline - 1000

> Nếu đối tượng h1 được khai báo thẻ h1 và được khai báo theo lớp .class thì lớp class sẽ được ưu tiên hơn mặc dù khai báo .class nằm ở trên.

![tag](./images/02-006.png "tag")

### 4. ID (Khai báo theo id)

- Khai báo bằng ID sẽ được ưu tiên hơn so với khai báo bằng Class và Tag theo thứ tự: `ID > Class > Tag`

> **_Ví dụ :_**
> Nếu đối tượng `Priority` có thẻ `h1`. Có `class` = "heading-class" và có `ID` = "heading-id". Thì khai báo ID sẽ được ưu tiên hơn mặc dù vị trí khai báo ở đầu tiên.

![Ưu tiên id](./images/02-009.png "Ưu tiên id")

### 5. Inline (Khai báo style bên trong đối tượng)

- Khai báo Inline bên trong đối tượng sẽ được ưu tiên hơn so với các khai báo khác theo thứ tự như sau: `Inline > ID > Class > Tag`

> **_Ví dụ :_**
> Nếu đối tượng `Priority` có thẻ `h1`. Có `class` = "heading-class" và có `ID` = "heading-id". Và có thêm khai báo Inline ở trong. Thì sẽ dựa trên khai báo Inline.

![Ưu tiên id](./images/02-010.png "Ưu tiên id")

### 6. Equal specificity (Cộng gộp các khai báo)

- Khi một khai báo được xác định bởi nhiều thành phần liên tục nhau thì sẽ được ưu tiên hơn so với đối tượng cùng cấp (Có thể đặt trước hoặc sau không cần theo thứ tự, và có thể được khai báo ở trên)
- Cộng gộp các khai báo mô tả cho cùng một đối tượng.

![1](./images/02-011.png "Ưu tiên Equal specificity")
![2](./images/02-012.png "Ưu tiên Equal specificity")
![3](./images/02-013.png "Ưu tiên Equal specificity")

![Ưu tiên Equal specificity](./images/02-014.png "Ưu tiên Equal specificity")

> Khi xem F12 Dev Tool theo thẻ Style của đối tượng Element Priority sẽ thấy các style được áp dụng cho đối tượng, những style nào hết hiệu lực sẽ bị gạch ngang.

### 6. Universal selector or inherited (Khai báo theo \* hoặc thẻ html)

- `Universal selector` và `inherited` có giá trị ưu tiên thấp nhất trong khai báo.
- Khai báo `inherited`: Là khai báo theo thẻ `html`

![Inherited](./images/02-016.png "Ưu tiên Inherited")

- Khai báo `Universal selector`: là khai báo `select *`

![Universal selector](./images/02-015.png "Ưu tiên Universal selector")

![Universal selector](./images/02-017.png "Ưu tiên Universal selector")

![F12 Dev Tool](./images/02-018.png "F12 Dev Tool")

### 7. Important (Có cụm từ )

- Nếu khai báo có cụm từ `! important` thì khai báo đó sẽ được ưu tiên hơn so với các khai báo nếu không có cụm từ đó.

> Mặc dù ở h1 đã có khai báo Inline nhưng do có khai báo ! important nên độ ưu tiên sẽ cao hơn.

![Sử dụng ! important](./images/02-019.png "! Important")

- Không có tác dụng nếu dùng cho `inherited`.

![Sử dụng ! important](./images/02-020.png "! Important")
![Sử dụng ! important](./images/02-021.png "! Important")

---
