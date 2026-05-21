# Felix Phan · Portfolio 2026

Personal portfolio site for Felix Phan — Story Architect.
Built as a single static HTML file with the QNH Huế Treatment as the featured deep-dive.

**Live site (after setup):** https://fzzzzzlix.github.io/felixphan.portfolio2026/

---

## 📁 File Structure

```
felixphan.portfolio2026/
├── index.html                       ← Main portfolio page (THIS IS THE HOMEPAGE)
├── README.md                        ← This file
├── projects/
│   └── qnh-hue-treatment.html       ← QNH Treatment (featured work)
├── files/
│   ├── Felix_Phan_CV.pdf            ← Generic CV for download
│   ├── Felix_Phan_Yeah1_CV.pdf      ← Yeah1-tailored CV
│   └── Felix_Phan_Yeah1_Cover_Letter.pdf
└── images/
    ├── hero-portrait.jpg            ← All placeholder images
    ├── qnh-cover.jpg                  (REPLACE THESE WITH REAL ONES)
    ├── tvc-buv.jpg
    ├── ... (see full list below)
```

---

## 🚀 Part 1 — Putting It Onto GitHub Pages (10 phút)

> Felix, bạn không cần biết code. Làm theo từng bước này qua giao diện web của GitHub là đủ.

### Bước 1. Upload tất cả files lên repo

1. Mở repo: **https://github.com/fzzzzzlix/felixphan.portfolio2026**
2. Bấm nút **"Add file"** → **"Upload files"** (góc phải, gần thanh xanh "Code")
3. Kéo thả **toàn bộ** thư mục portfolio này vào — bao gồm:
   - `index.html`
   - `README.md`
   - `projects/` (cả thư mục)
   - `files/` (cả thư mục)
   - `images/` (cả thư mục)
4. Cuộn xuống cuối trang. Trong ô "Commit changes":
   - Tiêu đề: `Initial portfolio upload`
5. Bấm **"Commit changes"** (nút xanh).

> ⚠️ **Lưu ý:** GitHub web upload đôi khi không giữ cấu trúc thư mục con nếu bạn chỉ kéo từng file một. Cách an toàn nhất: kéo cả thư mục `portfolio/` vào cửa sổ upload — GitHub sẽ tự động giữ nguyên tree.

### Bước 2. Bật GitHub Pages

1. Trong repo, bấm tab **"Settings"** (góc phải trên cùng).
2. Cuộn xuống menu trái → bấm **"Pages"**.
3. Trong phần "Build and deployment":
   - **Source:** chọn `Deploy from a branch`
   - **Branch:** chọn `main` (hoặc `master`), folder `/ (root)`
   - Bấm **Save**
4. Đợi 1–3 phút.
5. Quay lại trang Pages — sẽ thấy dòng:
   > ✅ Your site is live at `https://fzzzzzlix.github.io/felixphan.portfolio2026/`

### Bước 3. Test thử

- Mở URL trên — sẽ thấy portfolio
- Bấm vào "Bếp Haha Gặp Bếp Cung Đình" (Featured Work) — sẽ mở QNH treatment ở tab mới
- Bấm "Download PDF" ở cuối trang — sẽ tải CV

✅ Done! Bây giờ có thể chia sẻ URL.

---

## 🖼️ Part 2 — Thay Ảnh Placeholder Bằng Ảnh Thật

Tất cả ảnh hiện đang là **placeholder** (cream + chữ đỏ ghi tên file). Khi nhìn vào portfolio, mỗi vị trí cần ảnh thật đang hiện ra một placeholder ghi rõ "REPLACE THIS PLACEHOLDER" và tên file cần thay.

### Cách thay (cực dễ):

1. Vào repo → mở thư mục `images/`
2. Bấm vào ảnh placeholder muốn thay (vd: `hero-portrait.jpg`)
3. Bấm nút **bút chì** (✎) hoặc nút **"Delete"** rồi upload lại với cùng tên
4. **Tên file phải giống hệt** — kể cả `.jpg` (không phải `.jpeg`, không phải `.JPG`)

**Cách dễ nhất:**
- Trên máy, chuẩn bị ảnh thật có tên giống placeholder (ví dụ: bạn có 1 ảnh portrait — đổi tên thành `hero-portrait.jpg`)
- Vào `images/` trên GitHub
- Bấm "Add file" → "Upload files"
- Kéo ảnh mới vào — nó sẽ tự **ghi đè** lên placeholder cũ
- Commit changes

### 📋 Bảng tham chiếu ảnh

| File name | Nên là gì | Kích thước đề xuất |
|---|---|---|
| `hero-portrait.jpg` | Ảnh chân dung của bạn trên trang Cover | 800×1000 (portrait 4:5) |
| `qnh-cover.jpg` | Cover image cho QNH treatment — có thể là screenshot trang cover của treatment, hoặc 1 ảnh thuyền rồng Huế đẹp | 1600×900 (landscape 16:9) |
| `tvc-buv.jpg` | Khung hình hoặc storyboard của TVC BUV | 800×500 |
| `tvc-hapacol.jpg` | Khung hình hoặc storyboard của TVC Hapacol | 800×500 |
| `tvc-maggi.jpg` | Khung hình hoặc mood TVC MAGGI Tết 2026 | 800×500 |
| `tvc-boardgame.jpg` | Khung hình hoặc storyboard Boardgame Tết 2025 | 800×500 |
| `film-yenhoa.jpg` | Still từ phim ngắn Yên Hòa | 800×500 |
| `film-pnj.jpg` | Still từ phim PNJ Wedding | 800×500 |
| `podcast-energy.jpg` | Artwork podcast Sustainable Energy | 800×500 |
| `concept-google.jpg` | Visual cho dự án Google art direction | 800×500 |
| `concept-ikea.jpg` | Visual cho big idea IKEA | 800×500 |
| `concept-fanta.jpg` | Visual cho big idea Fanta | 800×500 |
| `concept-lume.jpg` | Visual cho big idea Lume | 800×500 |
| `magazine-gender.jpg` | Spread của tạp chí gender equality | 800×500 |
| `photoshoots.jpg` | Composite hoặc shot tiêu biểu của 3 photoshoots | 800×500 |
| `production-vinfast.jpg` | BTS của dự án VinFast × Kim Joo Yung | 800×500 |
| `production-onset.jpg` | BTS on-set TH true Milk hoặc Mộc Châu Milk | 800×500 |
| `rmit-social.jpg` | Screenshot TikTok hoặc IG của RMIT SC | 800×500 |
| `empacts.jpg` | Ảnh team EMPACTS hoặc triển lãm Mental Wellness | 800×500 |

> 💡 **Mẹo:** Nếu chưa có ảnh thật, có thể chụp lại screenshot của storyboard/script trong Google Drive portfolio cũ (folder `1V2B8GdUd8n1Ow4qBCJbamX6onqHldVvm`) — crop về đúng tỷ lệ và lưu với tên file tương ứng.

---

## 🔗 Part 3 — Cập Nhật Link Google Drive Cho Từng Project

Tất cả 17 thumbnail trong các Pillar đều là **link bấm được** — hover vào sẽ thấy 1 mũi tên ↗ ở góc phải ảnh. Khi click, nó mở Google Drive ở tab mới.

Hiện tại tất cả đều trỏ về **folder portfolio master** (`1V2B8GdUd8n1Ow4qBCJbamX6onqHldVvm`). Để mỗi project link tới folder/file riêng của nó:

### Bước 1. Lấy URL của project trên Drive

1. Mở Google Drive
2. Tìm folder/file của project (vd: `01 Script Writing/1.1 TVC/BUV`)
3. Bấm chuột phải → **"Get link"** → đổi sang **"Anyone with the link"** (để Yeah1 xem được)
4. Copy URL

### Bước 2. Paste URL vào portfolio

1. Mở file `index.html` (qua GitHub web hoặc VS Code)
2. **Ctrl+F** tìm: `DRIVE LINK: Replace href below`
3. Bạn sẽ thấy 17 chỗ — mỗi chỗ là một project (thứ tự giống thứ tự trong portfolio)
4. Ngay dưới mỗi comment, có dòng:
   ```html
   <a class="work reveal" href="https://drive.google.com/drive/folders/1V2B8GdUd8n1Ow4qBCJbamX6onqHldVvm" target="_blank" rel="noopener">
   ```
5. Chỉ đổi phần `href="..."` — paste URL mới vào giữa 2 dấu nháy kép
6. Commit changes

### 🗺️ Thứ tự 17 links cần update

Trong file `index.html`, thứ tự xuất hiện từ trên xuống:

| # | Project | Folder Drive đề xuất |
|---|---|---|
| 1 | TVC BUV | 01 Script Writing → 1.1 TVC → BUV |
| 2 | TVC Hapacol | 01 Script Writing → 1.1 TVC → Hapacol |
| 3 | TVC MAGGI Tết 2026 | 01 Script Writing → 1.1 TVC → MAGGI |
| 4 | Boardgame Tết 2025 | 01 Script Writing → 1.1 TVC → Boardgame |
| 5 | Yên Hòa Short Film | 01 Script Writing → 1.2 Short Film → Yên Hòa |
| 6 | PNJ Wedding | 01 Script Writing → 1.2 Short Film → PNJ |
| 7 | Podcast Sustainable Energy | 01 Script Writing → 1.3 Podcast |
| 8 | Google Art Direction | 04 Concept Planning → Google |
| 9 | IKEA Big Idea | 04 Concept Planning → IKEA |
| 10 | Fanta Big Idea | 04 Concept Planning → Fanta |
| 11 | Lume Big Idea | 04 Concept Planning → Lume |
| 12 | Gender Equality Magazine | 04 Concept Planning → Magazine |
| 13 | Photoshoots Series | 04 Concept Planning → Photoshoots |
| 14 | VinFast × Kim Joo Yung | 02 Short Video Creation → VinFast |
| 15 | TH true Milk · Mộc Châu Milk · VinFast On-set | 02 Short Video Creation hoặc 03 Project Management |
| 16 | RMIT SC TikTok · IG | 02 Short Video Creation → RMIT SC |
| 17 | Mental Wellness Exhibition · EMPACTS | 03 Project Management |

> 💡 **Tip:** Nếu chưa có folder riêng cho từng project, **để tạm link master folder** là OK — Yeah1 vẫn xem được toàn bộ portfolio. Khi có thời gian thì split ra từng folder con sau.

---

## ✏️ Part 4 — Sửa Text Trong Portfolio

Toàn bộ text nằm trong file **`index.html`**. Có 2 cách sửa:

### Cách A — Sửa trực tiếp trên GitHub (dễ nhất, không cần app)

1. Mở repo → bấm vào file `index.html`
2. Bấm nút **bút chì** (✎) góc phải trên
3. Trang sẽ chuyển sang chế độ edit (như Google Docs)
4. Dùng **Ctrl+F** (Cmd+F trên Mac) để tìm chữ cần sửa
5. Sửa xong, cuộn xuống cuối → "Commit changes"

### Cách B — Sửa local bằng VS Code (nếu muốn xem trước)

1. Cài [VS Code](https://code.visualstudio.com/) (miễn phí)
2. Cài extension **"Live Server"** (Ritwick Dey)
3. Mở thư mục portfolio
4. Click chuột phải vào `index.html` → "Open with Live Server"
5. Sửa file → save → trình duyệt tự reload

### 📝 Những chỗ cần sửa text

Tìm chữ **`[EDIT]`** trong file — đó là những chỗ mình để placeholder text. Cụ thể:

**Pillar 01 — Story Architecture:**
- Mỗi TVC (BUV, Hapacol, MAGGI, Boardgame) đang có mô tả "[EDIT]" — viết 2–3 dòng mô tả thực tế dự án
- Yên Hòa film mô tả "[EDIT]" — viết về phim
- PNJ Wedding mô tả "[EDIT]"
- Podcast Sustainable Energy mô tả "[EDIT]"

**Pillar 02 — Cultural Intelligence:**
- Google, IKEA, Fanta, Lume — mô tả "[EDIT]"
- Gender Equality Magazine "[EDIT]"
- Photoshoots Series "[EDIT]"

**Pillar 03 — Production Fluency:**
- RMIT Social mô tả "[EDIT]"

### Sửa thông tin liên hệ

Trong `index.html`, tìm:

```
felixphan.contact@gmail.com
+84 936 647 704
linkedin.com/in/felixphan
```

Đổi nếu cần. Có 3 chỗ xuất hiện (đầu trang masthead, ẩn; cuối trang trong section Contact).

### Sửa tagline/positioning

Tìm dòng `Story Architect` (xuất hiện 2 lần) — đó là tagline chính.
Tìm "Tôi thiết kế những tình huống" (Hero premise) để sửa câu định vị nhỏ phía dưới tên.

---

## 🔄 Part 5 — Cập Nhật Sau Này

Mỗi lần cần update (thêm project mới, đổi ảnh, sửa text):

1. Edit qua GitHub web → Commit changes
2. GitHub Pages **tự động deploy** trong vòng 1–3 phút
3. Refresh URL portfolio để thấy thay đổi

Không cần làm gì khác. Không cần build, không cần deploy command.

---

## 🎨 Design Notes (cho người tò mò)

- **Hệ font:** Playfair Display (display) + DM Sans (body) — cùng hệ với QNH treatment để cả 2 file feel like one creative universe
- **Palette:** Paper cream `#f7f3ec` + Ink dark `#1a1410` + **Dark Red signature** `#7a1c1c` + Gold accent `#b8922a`
- **Cấu trúc:** Hero → Index/TOC → About → Featured (QNH) → Pillar I → Quote → Pillar II → Quote → Pillar III → Personal → Contact
- **Animations:** Reveal-on-scroll dùng IntersectionObserver, không phải scroll-jacking. Hiệu năng tốt, không ảnh hưởng SEO.
- **Responsive:** Mobile-first breakpoints ở 900px và 600px. Side nav ẩn trên mobile.

---

## 🆘 Khi Gặp Vấn Đề

**"Trang trắng / 404 sau khi setup Pages"**
→ Đợi thêm 5 phút. Lần đầu deploy mất lâu hơn các lần sau.
→ Check tab Settings → Pages có hiện "Your site is live at..." chưa.

**"Ảnh không hiện"**
→ Tên file phải giống hệt placeholder, kể cả phần đuôi `.jpg`. Không phải `.JPG`, không phải `.jpeg`.
→ Check folder `images/` trong repo có file đó không.

**"Bấm vào QNH treatment lỗi 404"**
→ Check folder `projects/` có file `qnh-hue-treatment.html` không.
→ Tên file phải đúng cả dấu gạch ngang.

**"Mình sửa text rồi nhưng nó không thay đổi trên web"**
→ Refresh hard: Ctrl+Shift+R (Cmd+Shift+R trên Mac). Browser đôi khi cache.
→ Đợi thêm 1 phút nữa.

---

*Portfolio code & design foundation: Claude · May 2026*
*Built for Felix Phan's Yeah1 application & beyond.*
