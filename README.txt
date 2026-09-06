MYTHICAL OVERLAY – TIKTOK STUDIO

1. Upload toàn bộ thư mục này lên một static hosting (GitHub Pages, Netlify, Cloudflare Pages...).
2. Link điều khiển: /control.html
3. Link overlay để dán vào TikTok Studio: /index.html
4. Mở control.html trên cùng máy/trình duyệt và bật/tắt thẻ.

LƯU Ý: Bản này dùng localStorage + BroadcastChannel để điều khiển không cần server. Nếu TikTok Studio dùng một storage partition riêng khiến trạng thái không đồng bộ, cần bản có backend/WebSocket; khi đó phải deploy thêm server.
