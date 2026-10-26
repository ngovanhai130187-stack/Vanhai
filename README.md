# AI Ảnh Thẻ Studio V1.2

Web app tĩnh dùng HTML/CSS/JavaScript, có tải nhiều ảnh, chọn nền, điều chỉnh sáng/tương phản, thử tách nền bằng MediaPipe, phát hiện khuôn mặt nếu trình duyệt hỗ trợ, xuất PNG/JPG/ZIP và bố trí ảnh để in.

## GitHub Pages
Repository: https://github.com/ngovanhai130187-stack/Vanhai
Vào Settings → Pages → Build and deployment → Deploy from a branch → Branch: main → Folder: /(root) → Save.

## Lưu ý
- Cần Internet để tải thư viện MediaPipe và JSZip từ CDN.
- Tách nền có thể chưa hoàn hảo ở tóc, tai, vai; kiểm tra trước khi dùng.
- FaceDetector không được hỗ trợ trên mọi trình duyệt.
- Bản in A4 là bố trí ảnh xem trước; khổ ảnh vật lý phụ thuộc cài đặt in. Không bảo đảm đáp ứng tiêu chuẩn hộ chiếu hoặc giấy tờ của mọi cơ quan.
- Ảnh xử lý trong trình duyệt, không gửi ảnh lên máy chủ ứng dụng.
