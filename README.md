# 📥 X Downloader

Công cụ tải video cho Windows 10/11. Đọc 3 bước dưới đây là dùng được ngay.

### ⬇️ [Tải bộ cài X Downloader](https://github.com/trgiangvp3/x-downloader-releases/releases/latest/download/x-downloader-win-Setup.exe)

Chỉ cần cài một lần. Sau đó chương trình **tự cập nhật** mỗi lần mở, không phải tải lại.

---

## 1. Cài Cloudflare WARP (chỉ nếu bạn ở Việt Nam)

Trang web bị chặn ở Việt Nam, nên cần WARP để vào được. Làm một lần duy nhất:

1. Vào <https://1.1.1.1/> → tải **Cloudflare WARP** cho Windows.
2. Cài đặt, mở ứng dụng lên một lần (bật/tắt thế nào cũng được).

> ✅ X Downloader tự bật chế độ proxy của WARP khi chạy, bạn không phải chỉnh gì trong WARP.
>
> 🌍 Ở nước ngoài / mạng không bị chặn? Bỏ qua bước này.

## 2. Cài và chạy

1. Chạy file **x-downloader-win-Setup.exe** vừa tải.
2. Windows có thể hiện bảng **"Windows protected your PC"**: bấm **More info** → **Run anyway**.
   (Bình thường, vì file không mua chứng chỉ ký số.)
3. Cài xong có shortcut **X Downloader** trên Desktop và Start Menu.

Khi chạy, chương trình nằm ở **khay đồng hồ** (góc phải dưới, có thể nằm trong mũi tên ^),
biểu tượng 3 thanh màu cam. Chuột phải vào biểu tượng:

- **Mở giao diện**: mở lại trang điều khiển
- **Xem log**: xem chương trình đang làm gì / báo lỗi gì
- **Thoát**: tắt hẳn chương trình

> ⏳ Lần đầu chương trình tự tải ~200MB trình duyệt, chờ vài phút. Chỉ tải một lần.

## 3. Tải video

Trình duyệt tự mở trang `localhost:4321`. Trên trang đó:

1. Bấm **🌐 Lựa phim (proxy)** → một cửa sổ trình duyệt mở ra trang web. Tìm video bạn muốn, copy đường link.
2. Dán link vào ô **URLs** (mỗi link một dòng).
3. Chọn thư mục lưu (nút **Browse…**).
4. Bấm **Download All**. Theo dõi tiến độ ở bảng **Download Queue**.

Góc trên phải có chấm **WARP: connected** màu xanh là đã vượt chặn thành công, sẵn sàng tải.

## 💡 Mẹo & xử lý sự cố

| Tình huống | Cách xử lý |
|---|---|
| Không vào được trang web | Kiểm tra đã cài WARP chưa, và chấm WARP góc phải có xanh không. Chưa cài thì làm lại Bước 1. |
| Bấm play mãi không ra link | Công cụ đã tự chặn quảng cáo và thử lại nhiều lần. Cứ chờ, hoặc bấm lại **Download All**. |
| Tải chậm | Để mặc định (tải trực tiếp) là nhanh nhất. Đừng bật "Download via proxy" trừ khi cần. |
| Đóng mất trang điều khiển | Chuột phải biểu tượng ở khay → **Mở giao diện** (hoặc mở lại shortcut trên Desktop). |
| Chương trình báo dừng bất ngờ | Chọn mở log, chụp màn hình gửi người đưa bạn tool. |
| Muốn gỡ bỏ | **Settings → Apps → X Downloader → Uninstall**. |

> 🔒 Công cụ dùng cho mục đích cá nhân. Không đăng lại / chia sẻ công khai.
