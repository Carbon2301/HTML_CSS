## CSS Flexbox

Flexbox cung cấp một cách bố trí linh hoạt cho các phần tử con trong một container. Dưới đây là một số thuộc tính chính của Flexbox:

- **display**: Điều khiển container là một hộp flex hoặc inline-flex.
  - Giá trị: `flex | inline-flex`

- **flex-direction**: Xác định hướng của các phần tử flex trong container.
  - Giá trị: `row | column`

- **flex-wrap**: Điều khiển các phần tử có được xếp thành nhiều dòng (container).
  - Giá trị: `nowrap | wrap | wrap-reverse`

- **justify-content**: Căn chỉnh các phần tử dọc theo trục chính (container).
  - Giá trị: `flex-start | flex-end | center | space-between | space-around`

- **align-content**: Căn chỉnh các dòng flex khi chúng chiếm nhiều hơn một dòng theo trục chéo (container).
  - Giá trị: `flex-start | flex-end | center`

- **align-items**: Căn chỉnh tất cả các phần tử dọc theo trục chéo (container).
  - Giá trị: `flex-start | flex-end | center`

- **flex-basis**: Đặt kích thước chiều ngang hoặc chiều dọc "main size" theo trục main axis (item).
  - Giá trị: `<length>`

- **justify-self**: Căn chỉnh một phần tử con flex item theo trục chính  (item).
  - Giá trị: `flex-start | flex-end | center`

- **align-self**: Căn chỉnh một phần tử con flex item dọc theo trục chéo (item).
  - Giá trị: `flex-start | flex-end | center`

- **flex-grow**: Xác định khả năng mở rộng của một phần tử trong không gian còn lại của container (main size).
  - Giá trị: `<number>`

- **flex-shrink**: Xác định khả năng thu nhỏ của một phần tử khi không gian container bị thiếu.
  - Giá trị: `<number>`

- **flex**: Cung cấp một cách viết tắt cho các thuộc tính `flex-grow`, `flex-shrink` và `flex-basis`.
  - Giá trị: `<number>`

- **flex-flow**: Thuộc tính viết tắt kết hợp **flex-direction** và **flex-wrap**.
  - Giá trị: `row nowrap | column wrap | ...`

- **order**: Xác định thứ tự hiển thị của các phần tử trong container flex.
  - Giá trị: `<number>`


### Snapshot
![Flexbox Model Overview](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Flexbox/flex_terms.png "Flexbox Model")
