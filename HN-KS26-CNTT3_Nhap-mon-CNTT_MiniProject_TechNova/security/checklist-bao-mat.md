1. Tạo tài khoản Bitwarden, đặt Master Password dạng Passphrase dài trên 20 ký tự.

2. Dùng công cụ Generator sinh mật khẩu ngẫu nhiên 16–32 ký tự cho từng tài khoản riêng biệt.

3. Vào [github.com/settings/security](http://github.com/settings/security), bật Two-factor authentication, quét mã QR bằng Authenticator App.

4. Tải và lưu 10 Backup Codes vào Bitwarden để dự phòng khi mất điện thoại.

5. Tạo tệp .env chứa biến cấu hình dạng TEN_BIEN=GIA_TRI, tuyệt đối không hardcode trực tiếp trong mã nguồn.

6. Tạo tệp .gitignore khai báo dòng .env; kiểm tra tab Source Control để xác nhận .env không xuất hiện trong danh sách chuẩn bị push.

7. Tạo tệp .env.example (xóa giá trị thật) để đồng đội biết cần khai báo biến gì.

**Lưu ý / Bẫy**

- Không dùng SMS OTP làm 2FA chính; ưu tiên tuyệt đối Authenticator App (TOTP).

- Không cài phần mềm Crack/Keygen và không tắt Antivirus theo lời dụ dỗ của trang tải Crack.

- Trước khi push code, luôn rà soát mã nguồn để chắc chắn không có API Key hay mật khẩu thô bị gõ trực tiếp.