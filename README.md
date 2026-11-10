# 🎂 Chúc Mừng Sinh Nhật Như Ý

Thiệp sinh nhật 3D tương tác — một file HTML duy nhất.

## Tuỳ biến không cần sửa code

Thêm tham số vào URL:

```
index.html?name=Như%20Ý&to=Khai&msg=Lời%20chúc...
```

| Param | Ý nghĩa |
|---|---|
| `name` | Tên người nhận |
| `to` | Tên người gửi (hiện trong modal quà) |
| `msg` | Nội dung lời chúc |

## Chạy local

```bash
python3 -m http.server 8000
# mở http://localhost:8000
```

## Công nghệ

Three.js r128 · GSAP 3 · canvas-confetti · Web Audio API (nhạc synth, không cần file mp3)