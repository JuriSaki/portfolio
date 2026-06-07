# Hướng dẫn đăng Portfolio lên web (lấy URL miễn phí)

Bạn có **3 cách**. Chọn 1 trong 2 cách đầu để **giữ nguyên 100% thiết kế** (nhanh, đẹp); cách 3 dành cho khi thầy/cô **bắt buộc dùng Google Sites**.

---

## ⭐ CÁCH 1 — Netlify Drop (nhanh nhất, ~2 phút, giữ nguyên thiết kế)

1. Mở trình duyệt, vào **https://app.netlify.com/drop**
2. Mở thư mục `Portfolio_PhamMinhDung_2026` trên máy.
3. **Kéo–thả cả thư mục** `Portfolio_PhamMinhDung_2026` vào ô “Drag and drop your site folder here”.
   - Lưu ý: kéo nguyên thư mục (bên trong đã có `index.html`, `styles.css`, `fonts/`, `images/`, `reports/`).
4. Đợi vài giây → Netlify cấp một URL dạng `https://ten-ngau-nhien.netlify.app`.
5. (Tuỳ chọn) Đăng nhập (Google/GitHub) để giữ site vĩnh viễn và đổi tên miền phụ: **Site settings → Change site name** → ví dụ `portfolio-phamminhdung`.
6. **Dán URL này vào bài nộp** và vào ô “URL website” ở chân trang Giới thiệu.

> Ưu điểm: giữ y nguyên font Lora/Be Vietnam Pro, màu teal, ảnh, bảng, nút tải PDF. Không cần tài khoản để thử nhanh.

---

## CÁCH 2 — GitHub Pages (miễn phí, ổn định lâu dài, giữ nguyên thiết kế)

1. Tạo tài khoản tại **https://github.com** (nếu chưa có).
2. Bấm **New repository** → đặt tên, ví dụ `portfolio` → chọn **Public** → **Create**.
3. Bấm **Add file → Upload files** → kéo **toàn bộ nội dung bên trong** thư mục `Portfolio_PhamMinhDung_2026` (file `index.html`, `du-an.html`, `tong-ket.html`, `styles.css`, và các thư mục `fonts/`, `images/`, `reports/`) → **Commit changes**.
4. Vào **Settings → Pages** → mục “Build and deployment”, **Source: Deploy from a branch** → chọn nhánh `main` và thư mục `/ (root)` → **Save**.
5. Đợi 1–2 phút, URL sẽ là `https://<tên-tài-khoản>.github.io/portfolio/`.
6. **Dán URL** vào bài nộp.

> Mẹo: trang chủ mặc định mở `index.html` (trang Giới thiệu) — đúng như mong muốn.

---

## CÁCH 3 — Google Sites (khi bắt buộc dùng Google Sites)

Google Sites **không nhập trực tiếp file HTML**, nên cần **dựng lại bằng tay** theo bản dàn sẵn dưới đây. Cứ tạo **3 trang** (Giới thiệu, Dự án, Tổng kết), rồi copy từng đoạn văn và chèn ảnh/bảng đúng vị trí.

### A. Các bước tạo & publish
1. Vào **https://sites.google.com** → **Blank / Trang trống**.
2. Đặt tiêu đề site: **Portfolio – Phạm Minh Dũng**.
3. Bên phải, tab **Pages (Trang)** → tạo 3 trang: `Giới thiệu`, `Dự án`, `Tổng kết`. Kéo để sắp thứ tự; đặt `Giới thiệu` làm trang chủ (Home).
4. Chọn **Theme (Chủ đề)** → chọn theme có tông xanh; trong phần màu, chọn **màu xanh ngọc/teal**; font tiêu đề chọn kiểu **serif (vd. Lora/“Playfair”)**, thân bài chọn **sans (vd. “Be Vietnam Pro”/“Roboto”)** để gần với thiết kế gốc.
5. Dùng nút **Insert (Chèn)** để thêm: *Text box* (đoạn văn), *Image* (ảnh), *Table* (bảng), *Button* (nút tải PDF), *Divider* (đường kẻ).
6. **Tải ảnh & PDF lên:** dùng Insert → Image (chọn ảnh trong thư mục `images/`); với báo cáo PDF, tải các file trong `reports/` lên **Google Drive**, đặt quyền “Bất kỳ ai có liên kết – Người xem”, rồi dùng Insert → Button/Link gắn link Drive.
7. Khi xong: bấm **Publish (Xuất bản)** ở góc phải → đặt đường dẫn web (vd. `portfolio-phamminhdung`) → **Publish**. Lấy URL công khai và **dán vào bài nộp**.

### B. Bản dàn sẵn để dán (copy đúng theo từng section)

> Quy ước: **[Tiêu đề]** = đặt làm Heading; “…” = đoạn văn dán vào Text box; **[Ảnh: …]** = vị trí chèn ảnh; **[Bảng …]** = chèn Table với số cột tương ứng.

---

#### TRANG 1 — GIỚI THIỆU

**[Banner/Heading lớn]** Phạm Minh Dũng — Sinh viên Khoa học Máy tính
*Phụ đề:* Portfolio Kỹ thuật số · Lớp K70I-CS4 · Trường ĐH Công nghệ – ĐHQGHN · Học phần: Nhập môn Công nghệ số & Ứng dụng Trí tuệ nhân tạo
**[Ảnh: ảnh chân dung — cần bổ sung; nếu chưa có, tạm bỏ trống]**

**[Heading] Thông tin sinh viên** — chèn **[Bảng 2 cột]**:
| Mục | Thông tin |
|---|---|
| Họ và tên | Phạm Minh Dũng |
| Ngày sinh | (cần bổ sung) |
| Quê quán | Hà Nội |
| Mã sinh viên | (cần bổ sung) |
| Lớp | K70I-CS4 |
| Trường | Trường Đại học Công nghệ – ĐHQGHN |
| Ngành | Khoa học Máy tính |
| Học phần | Nhập môn Công nghệ số & Ứng dụng Trí tuệ nhân tạo |

**[Heading] Đôi nét bản thân**
“Tôi là sinh viên ngành Khoa học Máy tính tại Trường ĐH Công nghệ – ĐHQGHN, hứng thú với lập trình hướng đối tượng (OOP), thiết kế hệ thống và ứng dụng AI vào học tập một cách có trách nhiệm. Trong các dự án nhóm, tôi thường đảm nhận phần logic (backend) và xây dựng cấu trúc lớp theo OOP.” *(Có thể bổ sung sở thích/thành tích cá nhân.)*

**[Heading] Mục tiêu học tập & Mục tiêu Portfolio**
“Nắm vững nền tảng Khoa học Máy tính và làm chủ công cụ số/AI như một cộng sự. Portfolio tập hợp, trình bày minh bạch sáu nhiệm vụ trong học phần kèm minh chứng thật, thể hiện quá trình tư duy và năng lực tự đánh giá.”

---

#### TRANG 2 — DỰ ÁN (6 nhiệm vụ)

> Mỗi nhiệm vụ trình bày theo mạch: **Mục tiêu → Quá trình → Sản phẩm/Minh chứng (ảnh + bảng) → Phân tích → Nút tải PDF**.

**[Heading] Nhiệm vụ 1 — Quản lý tệp & thư mục**
- *Mục tiêu:* “Thành thạo thao tác cơ bản với tệp/thư mục trên Windows và xây dựng quy tắc đặt tên, tổ chức dữ liệu khoa học.”
- *Quá trình:* “Thực hiện trọn vòng đời một tệp trong thư mục ThucHanh_PhamMinhDung trên ổ D:, gồm 13 bước có ảnh minh chứng.”
- **[Ảnh: bai1_01.png → bai1_13.png]** (chèn theo thứ tự; chú thích B1…B13 như trong website).
- *Phân tích:* “Quy tắc đặt tên PascalCase, tổ chức thư mục phân cấp; phân biệt Delete / Shift+Delete / Restore.”
- **[Nút] Tải báo cáo Bài 1 (PDF)** → link `reports/Bai1_QuanLyTepVaThuMuc.pdf` (trên Drive).

**[Heading] Nhiệm vụ 2 — Tìm kiếm & đánh giá thông tin học thuật**
- *Mục tiêu:* “Tìm kiếm có hệ thống và đánh giá nguồn theo 5 tiêu chí (tác giả, nơi xuất bản, phương pháp, trích dẫn, cập nhật).”
- *Quá trình:* “Báo cáo A: 10 nguồn về AI & phát triển phần mềm (chấm 1–5). Báo cáo B: 5 bài báo về vi nhựa qua công cụ Consensus. Toán tử dùng: \"…\", AND/OR, site:, filetype:.”
- **[Bảng 5 cột]** (10 nguồn: #, Loại, Tiêu đề & Tác giả, Nhận xét 5 tiêu chí, Hạng) — copy số liệu từ website/báo cáo Word.
- **[Bảng 5 cột]** (5 bài báo vi nhựa: #, Bài báo, Phương pháp, Đối tượng, Kết quả).
- *Phân tích:* “Ưu tiên ACM/IEEE & tạp chí SCIE; thận trọng với preprint/blog; tính cập nhật là then chốt.”
- **[Nút] Tải PDF** → `reports/Bai2_TimKiem_AI-SoftwareDev.pdf` và `reports/Bai2b_TimKiem_ViNhua-BienHoc.pdf`.

**[Heading] Nhiệm vụ 3 — Viết Prompt hiệu quả**
- *Mục tiêu & Quá trình:* “So sánh prompt 3 cấp độ (Cơ bản/Cải tiến/Nâng cao) trên 3 tác vụ: tóm tắt, giải thích OOP, tạo câu hỏi ôn tập.”
- **[Bảng 4 cột]** (Tác vụ / Cơ bản / Cải tiến / Nâng cao).
- *Phân tích:* “Prompt nâng cao tốt nhất nhờ role prompting, chain-of-thought, few-shot. Công thức: Vai trò + Bối cảnh + Nhiệm vụ + Định dạng + Ràng buộc.”
- **[Nút] Tải PDF** → `reports/Bai3_VietPromptHieuQua.pdf`.

**[Heading] Nhiệm vụ 4 — Hợp tác trực tuyến**
- *Mục tiêu & Quá trình:* “Vai trò backend/OOP; dùng Discord (giao tiếp), Google Docs (soạn thảo, >20 lượt sửa), Google Drive (lưu trữ, cấu trúc thư mục Dự_án_OOP).”
- **[Ảnh: bai4_01.png → bai4_05.png]** (Drive, Google Docs, thư mục Drive, cấu trúc thư mục, Discord).
- *Thách thức & giải pháp:* “Xung đột sửa Docs → tag trước khi sửa; lệch giờ → kênh Urgent; khó giải thích code → họp voice + share screen.”
- **[Nút] Tải PDF** → `reports/Bai4_HopTacTrucTuyen.pdf`.

**[Heading] Nhiệm vụ 5 — Sáng tạo nội dung với AI**
- *Mục tiêu:* “Làm Infographic về OOP & AI, phối hợp ≥3 công cụ AI.”
- **[Bảng 3 cột]** (Phân loại / Công cụ / Mục đích): Văn bản–Gemini & ChatGPT-4; Hình ảnh–Midjourney v6; Thiết kế–Canva AI.
- **[Ảnh: bai5_01.png, bai5_02.png, bai5_03.png]** (Text AI, Midjourney, Canva).
- *Tỉ lệ AI/cá nhân:* “~60% AI / ~40% cá nhân (điều phối, biên tập, kiểm chứng).” *(điều chỉnh theo cảm nhận thật)*
- *Phân tích:* “Ưu điểm tốc độ; hạn chế ‘ảo giác’ → kiểm chứng chéo với giáo trình.”
- **[Nút] Tải PDF** → `reports/Bai5_SangTaoNoiDung_AI.pdf`.

**[Heading] Nhiệm vụ 6 — AI có trách nhiệm & liêm chính học thuật**
- *Mục tiêu & Quá trình:* “Phân tích chính sách dùng AI; thực hành bài Dijkstra/A* có AI, phát hiện & sửa lỗi AI; trích dẫn APA.”
- **[Bảng 3 cột]** (Tiêu chí / Nội dung chính sách / Chế tài).
- **[Ảnh: bai6_01.png]** (Infographic “Sử dụng AI có trách nhiệm”).
- *Bộ 6 nguyên tắc* (dạng danh sách): Chủ thể duy nhất; Hoài nghi lành mạnh; Minh bạch tuyệt đối; Truy vết nguồn gốc; Bảo mật thông tin; Phát triển năng lực làm gốc.
- **[Nút] Tải PDF** → `reports/Bai6_AICoTrachNhiem.pdf`.

---

#### TRANG 3 — TỔNG KẾT

**[Heading] Trải nghiệm tổng thể**
“Sau sáu nhiệm vụ, tôi nhận ra kỹ năng số thật sự nằm ở quy trình và tư duy phản biện: tổ chức dữ liệu, đánh giá nguồn, viết prompt có chủ đích, cộng tác minh bạch, dùng AI như cộng sự được kiểm soát.”

**[Heading] Kiến thức & kỹ năng quan trọng** — danh sách 6 mục (Tổ chức dữ liệu, Năng lực thông tin, Prompt Engineering, Cộng tác số, Sáng tạo với AI, AI có trách nhiệm).

**[Heading] Điểm tâm đắc & Thách thức**
“Tâm đắc: tự phát hiện & sửa lỗi AI ở bài Dijkstra/A*. Thách thức đã vượt: xung đột nhóm từ xa, lọc ‘ảo giác’ AI, giữ kỷ luật không lạm dụng AI.”

**[Heading] Tự đánh giá theo 8 tiêu chí** — chèn **[Bảng 3–4 cột]** (#, Tiêu chí, Minh chứng) — copy từ website/báo cáo.

**[Heading] Định hướng tương lai**
“Học thêm Git, prompt engineering nâng cao và quy trình phát triển phần mềm có AI hỗ trợ một cách có trách nhiệm.”

---

## Việc cần làm trước khi nộp (checklist)
- [ ] Điền **ngày sinh** và **mã sinh viên** (đang để “cần bổ sung”).
- [ ] Thêm **ảnh chân dung** (`images/avatar.jpg`) nếu muốn — đã có chỗ trong `index.html`.
- [ ] Rà 3 ghi chú đỏ trong website/báo cáo: tên ví dụ “NguyenVanA”, “YenLinh”, và tỉ lệ AI 60/40.
- [ ] Publish (Cách 1/2/3) → lấy **URL** → dán vào ô “URL website” ở chân trang Giới thiệu và vào bài nộp.
- [ ] Nộp kèm **file PDF báo cáo** (`BaoCao_Portfolio_PhamMinhDung.pdf`) theo yêu cầu mục “Hình thức nộp bài”.
