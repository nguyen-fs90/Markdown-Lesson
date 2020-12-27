# Ký pháp Markdown

## Code

Dùng khi trích dẫn source code

`javascript` `java` `python` `php` `c++` `...`

```javascript
    ``` + tên language
    code
    code
    code
    ```
```

## Format Text

### Headers

- `#` tương đương với tag H1
- `##` tương đương với tag H2
- `###` tương đương với tag H3
- `####` tương đương với tag H4
- `#####` tương đương với tag H5

### Emphasis

- `*in nghiêng*`: *in nghiêng*
- `**in đậm**`: **in đậm**

### Strike through

- `~~chữ bị gạch ngang~~`: ~~bị gạnh ngang~~

### Details

Đóng mở nội dung
<details>
<summary>Click me!</summary>
Nội dung. Nội dung. Nội dung. Nội dung. Nội dung. Nội dung. Nội dung. Nội dung. Nội dung. Nội dung. Nội dung. Nội dung. Nội dung. Nội dung. Nội dung. Nội dung. 
</details>

### List

#### Kiểu Disc

Dùng 1 trong 3 ký tự sau để tạo list kiểu disc `*` `+` `-`

#### Kiểu Decimal

Viết số + dấu `.` để tạo list kiểu decimal (vd: `1.` `2.` `...`)

#### Kiểu Definition

Dùng thẻ `<dl>` để tạo list kiểu definition

```html
<dl>
    <dt>ô tô</dt>
    <dd>VinFast</dd>
    <dd>Honda</dd>
    <dt>Xe máy</dt>
    <dd>Yamaha</dd>
    <dd>Honda</dd>
</dl>
```

Kết quả:
<dl>
    <dt>ô tô</dt>
    <dd>VinFast</dd>
    <dd>Honda</dd>
    <dt>Xe máy</dt>
    <dd>Yamaha</dd>
    <dd>Honda</dd>
</dl>

#### Kiểu Checkbox

```html
- [ ] Task 1
- [x] Task 2
```

Kết quả:

- [ ] Task 1
- [x] Task 2

### Blockquotes

>Sử dụng ký tự `>` để tạo blockquote

### Horizontal rules

Sử dụng các ký tự sau để tạo horizotal rules
> `* * *` <br>
> `***` <br>
> `*****` <br>
> `- - -` <br>
> `---------------------------------------` <br>

Kết quả:
***

### Links

Cú pháp: <br>
`[link text](url)`
`![img text](img url)`

[Google](https://google.com.vn) <br>
[YouTube](https://youtube.com) <br>
![Deno logo](https://deno.land/logo.svg)
