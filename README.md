# Subway Dash — Bản cập nhật v9.18.2

- File game chính: `index.html`
- **Xe lửa có đường lên (`obs.type === 8`)**: Có đường dốc màu vàng-cam (`#f59e0b`), viền sáng, các vạch bậc ngang và chữ `▲ DỐC LÊN` ở phần đuôi tàu. Chạy đúng làn vào dốc sẽ leo thẳng lên nóc tàu (`TRAIN_ROOF_ALT = 92`).
- **Xe lửa thường (`obs.type === 2`)**: Không có đường dốc ở phần đuôi tàu; cần đổi làn hoặc dùng **Giày nhảy cao** để nhảy lên nóc.

### Cập nhật Mô-tô bá khí & Xe tăng bá khí
- **Mô-tô bá khí (`moto`)**: Khi bấm phím Nhảy (`W` / `↑` / `Space` / vuốt lên), xe không nhảy bay lên không trung mà **bốc đầu nghiêng cao** quanh trục bánh sau, thân xe và tư thế nhân vật (thân, đầu, tay, chân) ngả cân đối theo độ bốc đầu để cán nát vật cản trực tiếp.
- **Xe tăng bá khí (`tank`)**: Giữ xe tăng bám sát mặt đường/ray (không nhảy bay ảo); khi bấm phím Nhảy sẽ kích hoạt xung lực tăng cường tia laser, giật nhẹ nòng pháo và rung gầm xích uy lực.
