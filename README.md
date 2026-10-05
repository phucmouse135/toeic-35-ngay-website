# TOEIC - Lộ trình 35 ngày

Trang web tĩnh lộ trình TOEIC 35 ngày, sẵn sàng deploy lên Vercel.

## Lưu dữ liệu (localStorage)

Trang tự động lưu tiến độ bằng `localStorage` dưới key `toeic35_v1`: bạn đã làm xong ngày nào, điểm từng bài, từ đã biết, sổ lỗi sai, tốc độ nghe, điểm các đề thi thử. Dữ liệu nằm ngay trên trình duyệt, không cần server, mở lại là còn nguyên.

## Deploy lên Vercel

### Cách 1: Vercel CLI
```bash
cd toeic-35-ngay-website
vercel --prod
```

### Cách 2: GitHub
1. Push project lên GitHub.
2. Vào [vercel.com](https://vercel.com) → Add New Project → chọn repo → Deploy.

- **Framework Preset:** Other
- **Build:** không cần (`vercel.json` chỉ bật `cleanUrls`)