# CLAUDE.md - tuanminhhole

Bối cảnh gốc MonkeyTech: `~/SecondBrain/CONTEXT.md`. Bộ chuẩn dự án (hành văn, cấu trúc, bí mật, khung): `~/Project/chuan/master/README.md`.

- Repo làm gì: repo trang profile GitHub `tuanminhhole`: `README.md` là sản phẩm duy nhất (hiển thị trên trang cá nhân), `.github/workflows/snake.yml` sinh ảnh rắn đóng góp. Không có TASKS.md / CHANGELOG.md vì không có việc hay bản phát hành.
- Deploy: không deploy; GitHub tự hiển thị README khi đẩy lên `main`.
- Bí mật: biến trong `.env` (mẫu `.env.example`), tệp khoá trong `secrets/`; cả hai gitignore, không commit.
- Luật cứng: không deploy khi Kent chưa duyệt, không `git push --force`, cấm dấu gạch dài (chỉ dùng `-`), commit không kèm Co-Authored-By. Chỉ leader gộp vào nhánh chính; việc dở ghi ở khối "Đang dở" của `TASKS.md`.
