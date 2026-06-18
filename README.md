# Web 8/3 ❤️

Một trang web nhỏ chúc mừng Ngày Quốc tế Phụ nữ **8/3**, làm tặng các bạn nữ lớp **K70I-IT5**.

Trang gồm hiệu ứng lá rơi, một thẻ trái tim 3D nghiêng theo chuột (tilt), và một nút bấm để mở lời chúc.

## Tính năng

- 🍃 Hiệu ứng lá rơi nền (falling leaves).
- 💗 Thẻ trái tim với hiệu ứng nghiêng 3D + ánh sáng (glare) bằng [Vanilla Tilt](https://micku7zu.github.io/vanilla-tilt.js/).
- 🔘 Nút **"Nhấn vào đây"** để hiện lời chúc, và nút ✖ để đóng lại.
- 📱 Responsive cơ bản (có thẻ `viewport`).

## Công nghệ

- HTML
- CSS
- JavaScript (thuần)
- [vanilla-tilt.js](https://micku7zu.github.io/vanilla-tilt.js/) cho hiệu ứng nghiêng
- [Font Awesome](https://fontawesome.com/) cho icon

## Cấu trúc thư mục

```
Web-83/
├── index.html        # Trang chính
├── style.css         # Toàn bộ style & animation
├── vanilla-tilt.js   # Thư viện hiệu ứng nghiêng 3D
├── leaf.png          # Ảnh lá rơi
├── heart.png         # Ảnh trái tim
└── bgrMail.jpg       # Ảnh nền
```

## Cách chạy

Không cần build hay cài đặt gì cả, chỉ là web tĩnh:

1. Tải / clone repo về máy.
2. Mở file `index.html` bằng trình duyệt.

Hoặc chạy một server tĩnh đơn giản:

```bash
# Python 3
python3 -m http.server 8000
```

Rồi mở `http://localhost:8000` trên trình duyệt.

---

> Chúc các bạn nữ K70I-IT5 ngày 8/3 thật vui vẻ, luôn xinh đẹp, tự tin, code mượt và bug ngày càng ít! 🎉
