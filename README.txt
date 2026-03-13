═══════════════════════════════════════
        AI ASSISTANCE - HƯỚNG DẪN
═══════════════════════════════════════

CÁCH CHẠY:
----------
1. Mở Terminal
2. cd vào folder này:
   cd "đường-dẫn/AI Assistance"

3. Chạy local server:
   python3 -m http.server 3000

4. Mở trình duyệt vào:
   http://localhost:3000

═══════════════════════════════════════

NẾU DÙNG VS CODE:
-----------------
- Cài extension "Live Server"
- Chuột phải index.html → "Open with Live Server"

═══════════════════════════════════════

ĐỔI API KEY (nếu cần):
----------------------
- Mở file index.html
- Tìm dòng: const API_KEY = '...'
- Thay bằng key mới từ console.anthropic.com

⚠️  QUAN TRỌNG: Revoke key cũ tại:
    console.anthropic.com → API Keys → Revoke
