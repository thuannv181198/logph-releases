# Log(P)-h — bản cài đặt cho Windows

Chương trình vẽ đồ thị log(p)-h của môi chất lạnh và đồ thị không khí ẩm (I-d, t-d), tính chu
trình lạnh, trạng thái không khí và tra cứu tính chất nhiệt vật lý của 136 chất. Tính chất nhiệt
động lấy từ CoolProp.

Kho này chỉ chứa **bản cài đặt**. Mã nguồn không nằm ở đây.

## Tải về

Mở mục **[Releases](../../releases/latest)** và tải **một** file:

| File | Dùng khi |
|---|---|
| `Log.P.-h.Pro_<phiên bản>_x64-setup.exe` | Máy có Internet (gần như mọi máy) |
| `Log.P.-h.Pro_<phiên bản>_x64-offline-setup.exe` | Máy **không có Internet**: file này có sẵn WebView2 (khoảng 210 MB) |

**Chỉ một chương trình cho mọi người.**

- Chưa có licence code: chương trình chạy ở chế độ miễn phí, gồm đồ thị log(p)-h của R290, R32,
  R600a, R410A, R12, R22, NH3 và R11, cùng đồ thị không khí ẩm. Các chức năng Pro vẫn hiện trên
  màn hình nhưng bị làm mờ và có chữ **PRO**.
- Có licence code (do tác giả cấp): mở đầy đủ mọi chức năng, không cần cài lại.

Các file `logph-*.exe` và `latest-*.json` là để chương trình **tự cập nhật**. Bạn không cần tải
các file này.

## Cài đặt

Bản cài đặt chưa được ký số, nên lần đầu mở Windows có thể báo *"Windows protected your PC"*. Khi
đó bấm **More info**, rồi **Run anyway**.

Cài bản mới đè lên bản cũ không làm mất thiết lập, các điểm trạng thái hay giấy phép Pro.

Nếu máy đang có **Log(P)-h Free** (bản 0.1.1 hoặc 0.1.2), hãy cài chương trình ở trên rồi gỡ
Log(P)-h Free trong *Settings → Apps*. Bản Free không còn được phát hành riêng.

## Cập nhật

Chương trình tự kiểm tra bản mới mỗi lần khởi động. Khi có bản mới, nút **Update to …** hiện ở
góc trên bên phải; bấm nút đó là chương trình tự tải và cài. Mỗi bản cập nhật đều được kiểm tra
chữ ký trước khi cài.

---

*English:* Windows installers of Log(P)-h (refrigerant log(p)-h charts, humid-air charts, cycles,
a property lookup of 136 fluids). Download one file from the latest release: the setup, or the
offline setup (with WebView2 included). Without a licence code the program runs in its free mode
(the Pro functions shown dimmed); a licence code from the author unlocks everything. The
`logph-*.exe` and `latest-*.json` files are for the programs' automatic updates.
