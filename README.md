# N3 Cấp Tốc

Web app ôn JLPT N3 cấp tốc bằng trình duyệt.

## Nội dung

App tải dữ liệu trực tiếp từ repo gốc `ngocbabby/n3-jlpt-app`:

- `VOCAB_DB` từ `vocab.html`
- `KANJI_DB` từ `kanji.html`
- `LESSONS` từ `n3-grammarnew.html`

Sau khi tải, app hiển thị kiểm kê:

- `V001-V...` cho từ vựng
- `K001-K...` cho Kanji / từ ghép Kanji
- `G001-G...` cho ngữ pháp

## Chức năng

- Story Sprint theo chương
- 3-trong-1: 1 từ + 1 Kanji + 1 ngữ pháp
- Từ vựng kèm câu ngắn
- Kanji Hán Việt
- Ngữ pháp có ví dụ và giải thích ngắn
- Quiz 5 phút
- Ôn lỗi sai/chậm
- Nút loa đọc tiếng Nhật bằng TTS của trình duyệt

## Cách chạy

Mở `index.html` bằng Chrome / Safari / Edge.

Để dùng bằng link công khai, bật GitHub Pages trong Settings của repo:

`Settings → Pages → Deploy from branch → main → /root → Save`

Sau đó truy cập:

`https://ngocbabby.github.io/n3-cap-toc/`

## Lưu ý

Đây là web app hỗ trợ nhận diện nhanh từ vựng / Kanji / ngữ pháp. App không thay thế luyện nghe JLPT bằng audio đề thật.
