# Bài tập CSS selector

---

### Bài 1:

Cho đoạn mã HTML sau:

```html
<div>
  <h1>Chung kết không tìm được Hoa khôi Du lịch</h1>
  <p>Đại diện lãnh đạo tỉnh Đắk Nông cho rằng...</p>
</div>
```

> Câu hỏi : Để CSS cho thẻ p thì những selectors nào sau đây sử dụng được?

![Bài 1](./asset/image/005.png 'Bài 1')

- [ ] #p
- [ ] p
- [ ] .p
- [ ] div>p

### Bài 2:

Cho đoạn mã HTML sau:

```html
<div>
  <p class="paragraph p1">Đại diện lãnh đạo tỉnh Đắk Nông cho rằng</p>
  <p class="paragraph p2">Đại diện lãnh đạo tỉnh Đắk Nông cho rằng</p>
  <p class="paragraph p3">Đại diện lãnh đạo tỉnh Đắk Nông cho rằng</p>
</div>
```

> Câu hỏi : Để CSS riêng cho thẻ p nằm giữa (vị trí số 2) thì những selectors nào sau đây có thể dùng được?

![Bài 2](./asset/image/006.png 'Bài 2')

- [ ] .paragraph.p2
- [ ] p.p2
- [ ] div paragraph
- [ ] p2
- [ ] div>p

### Bài 3:

Để CSS cho thẻ có class box thì những CSS selectors nào sau đây sử dụng được?

```html
<div>
  <div class="container">
    <div>
      <div class="box">A box</div>
    </div>
  </div>
</div>
```

> Câu hỏi : Trong thực tế cứ cái nào đơn giản, hiệu quả thì ta dùng. Luyện cái khó để sau này gặp trường hợp khó còn biết cách giải quyết.

- [ ] .box
- [ ] div .box
- [ ] .container > .box
- [ ] .container div div

## _**II. Giải Bài Tập:**_

### Bài 1:

- [ ] #p
- [x] p
- [ ] .p
- [x] div>p
- [x] div p

### Bài 2:

- [x] div .p2
- [x] .p2
- [x] .paragraph.p2
- [x] p.p2
- [ ] div paragraph
- [ ] p2
- [ ] div>p

### Bài 3:

- [x] .box
- [x] div.box
- [x] div .box
- [x] .container .box
- [ ] .container > .box
- [x] .container div div
