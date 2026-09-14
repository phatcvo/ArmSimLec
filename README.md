# ArmSimLec — Mô phỏng động học cánh tay robot

Mô phỏng tương tác dùng cho bài giảng động học robot, gói gọn trong **một file HTML**: không cần server, không cần mạng, mở bằng trình duyệt là chạy.

**Chạy trực tuyến:** https://phatcvo.github.io/ArmSimLec/

*Interactive robot-arm kinematics simulator for teaching (Vietnamese UI). Single self-contained HTML file.*

## Robot

- **2R / 3R phẳng**
- **ELBOW 6 khâu (3D)**: toàn khớp quay, cổ tay cầu
- **Stanford 6 khâu (3D)**: khớp 3 tịnh tiến

## Chế độ

| Tab | Nội dung |
|---|---|
| Động học thuận | Bảng thông số D–H (sửa trực tiếp) → ma trận Aᵢ → T; đối chiếu công thức đóng với tích ma trận |
| Động học nghịch | Giải từng bước từ bảng D–H, các nhánh nghiệm, trường hợp vô nghiệm; bước cuối kiểm tra ngược bằng động học thuận |
| Quỹ đạo | Bàn tay bám đường thẳng, đường tròn hoặc viết chữ trong không gian Đề-các |
| Jacobian · lặp số | Jacobian giải tích / hình học, lặp Δq = α·J⁻¹·e, giả nghịch đảo tắt dần (DLS) gần điểm kỳ dị |

## Chạy trên máy

Tải `index.html` rồi mở bằng trình duyệt.

## License

[MIT](LICENSE)
